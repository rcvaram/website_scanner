# The WOLF Scanner --> To Find Vulnerabilities in websites


<img src="https://github.com/rcvaram/website_scanner/blob/master/agence-olloweb-d9ILr-dbEdg-unsplash-scaled.jpg" height="64"/>




1. *You install following python packages using **pip**:*

```
$ pip install requests
```

```
$ pip install beautifulsoup4
```




2. *Clone the **wolf_scanner** github reposistory*

```
$ git clone https://github.com/rcvaram/wolf_scanner.git
```



3. *Then, you run **wolf_scanner.py** and follow the instructions:*

```
$ python wolf_scanner.py -t  target_web_address
```





When you give the target web address as t argument, this script scan all the pages of the website and listout the vulnerabilites that found.
Initally, I've implemented to find the **XSS vulnerability** only. So This script will list out the places where the XSS vulnerability is exist 
  




# Contributing Guidelines

Thanks for taking the time to contribute!

The following is a set of guidelines for contributing to website scanner. These are just guidelines, not rules, so use your best judgement and feel free to propose changes to this document in a pull request.


**First**: if you're unsure or afraid of anything, just ask or submit the issue or pull request anyways. You won't be yelled at for giving your best effort. The worst that can happen is that you'll be politely asked to change something. We appreciate any sort of contributions, and don't want a wall of rules to get in the way of that.

However, for those individuals who want a bit more guidance on the best way to contribute to the project, By addressing all the points we're looking for, it raises the chances we can quickly merge or address your contributions.

## Filing issues

If you have a question about the project or have a problem using it, please [file an
issue](https://github.com/rcvaram/website_scanner/issues/new).


1. Submit an issue describing your proposed change to the repo in question.
1. The repo owners will respond to your issue promptly.
1. Clone the repo, develop, and test your changes.
1. Submit a pull request.

