# LinkedInMathJAX
Enable mathJax in Linkedin groups

This script only loads MathJax on pages that contain TeX or MathML markup (it does a very simple test for that, which certainly could be made more sophisticated). 

Note that the default delimiters are \(...\) for in-line math and \[...\] or $$...$$ for displayed math. In particular, single-dollars aren't enable as math delimiters (since they occur too frequently in ordinary non-math text). If you wanted to enable single-dollar delimiters, you would need to edit the script to add a MathJax configuration script prior to loading MathJax.js itself.

The script is set to trigger on http://github.com/* and https://github.com/*. Not all the GreaseMonkey implementations provide for pattern matching in the host part of the URL, but if yours does, you can make it more sophisticated so that it will get subdomains of github as well.

Forked from 

http://stackoverflow.com/questions/11255900/mathjax-support-in-github-using-a-chrome-browser-plugin#11284227

It doesn't quiet work yet; I am working on it!
