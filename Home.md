# User Agent Overrider

You also can custom the toolbar button menu item in preference panel.

One line one menu item. The format is a colon separate menu label and a user agent string, line starts with `#` is comment. Empty line, comment and other invalid format will be ignored.

    # Default
    Firefox 20/Linux: Mozilla/5.0 (X11; Linux x86_64; rv:20.0) Gecko/20100101 Firefox/20.0
    Firefox 20/Windows: Mozilla/5.0 (Windows NT 6.1; WOW64; rv:20.0) Gecko/20100101 Firefox/20.0
    Chrome 26/Linux: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.31 (KHTML, like Gecko) Chrome/26.0.1410.43 Safari/537.31
    Chrome 26/Windows: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.31 (KHTML, like Gecko) Chrome/26.0.1410.43 Safari/537.31

If you remove or rename the checked menuitem's label, the extension will deactivate automatically.

Useful sites to get and test user agent:

* http://user-agent-string.info/
* http://www.useragentstring.com/
* http://www.user-agents.org/