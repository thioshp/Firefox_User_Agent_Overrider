# User Agent Overrider

You also can custom the toolbar button menu item in preference panel.

One line one menu item. The format is a colon separate menu label and a user agent string, line starts with `#` is comment. Empty line, comment and other invalid format will be ignored.

    # Firefox
    Firefox 24/Linux: Mozilla/5.0 (X11; Linux x86_64; rv:24.0) Gecko/20100101 Firefox/24.0
    Firefox 24/Windows: Mozilla/5.0 (Windows NT 6.1; WOW64; rv:24.0) Gecko/20100101 Firefox/24.0
    Firefox 24/Android: Mozilla/5.0 (Android; Mobile; rv:24.0) Gecko/24.0 Firefox/24.0

    # Chrome
    Chrome 30/Linux: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/30.0.1599.101 Safari/537.36
    Chrome 30/Windows: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/30.0.1599.101 Safari/537.36
    Chrome 30/Android: Mozilla/5.0 (Linux; Android 4.3; Nexus 4 Build/JWR66Y) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/30.0.1599.92 Mobile Safari/537.36
    Chrome 30/iOS: Mozilla/5.0 (iPhone; CPU iPhone OS 7_0_3 like Mac OS X) AppleWebKit/537.51.1 (KHTML, like Gecko) CriOS/30.0.1599.16 Mobile/11B511 Safari/8536.25

    # IE
    IE 6/Windows: Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.1; SV1)
    IE 7/Windows: Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 5.1)
    IE 8/Windows: Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1; WOW64; Trident/4.0)
    IE 9/Windows: Mozilla/5.0 (compatible; MSIE 9.0; Windows NT 6.1; WOW64; Trident/5.0)
    IE 10/Windows: Mozilla/5.0 (compatible; MSIE 10.0; Windows NT 6.1; WOW64; Trident/6.0)

If you remove or rename the checked menuitem's label, the extension will deactivate automatically.

Useful sites to get and test user agent:

* http://user-agent-string.info/
* http://www.useragentstring.com/
* http://www.user-agents.org/