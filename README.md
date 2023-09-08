# Fzproxy
Finds and tests free proxies for Proxychains. Offers selections using fzf. 

## Purpose of Fzproxy
Free proxies are most often shortlived and unstable. This makes configuring lists of proxies for programs such as _proxychains_ a real hassle, because it requires frequent manual editing and lots of trials and errors.

_Fzproxy_ is a simple script that tries to help with that: it uses [fetch-some-proxies](https://github.com/stamparm/fetch-some-proxies) to find and test free proxies, and then offers selecting them in _fzf_ for automatic use in _proxychains_ with no  manual editing of the configuration file.

See the comments in the script to see how it works and how to use it, or check the quick demo below:

![](https://gist.github.com/Kabouik/ff6a41498fe4dc63488d2126c8ed8e2b/raw/e7d4bcb99a32284681a6ec3eabd803e5a86ee790/demo.svg)
