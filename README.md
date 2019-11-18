# smart-wait-example-tests
A sample test cases for using Smart Wait, a smart waiting function is introduced in Katalon Studio version 7. The Smart Wait will tell the WebDriver to wait for the web page to become static before any operations perform.

See more deatils at [WebUI - Smart Wait Function](https://docs.katalon.com/katalon-studio/docs/webui-smartwait.html)

** Apply Smart Wait to all elements in a project **
To enable the Smart Wait function for the whole project in Katalon Studio, navigate to Project > Settings > Execution> Select Enable in Default Smart Wait.

** Apply Smart Wait to specific elements in a script **
If you want to use Smart Wait function for certain test elements only, it's important that you disable Default Smart Wait in Project Settings. Navigate to Project > Settings > Execution> Select Disable in Default Smart Wait. Then use enableSmartWait and disableSmartWait keywords to enable and disable this function respectively.

** enableSmartWait **
Description: Enable the Smart Wait function when it's disabled by default in project settings.
Keyword name: enableSmartWait.

** disableSmartWait **
Description: Disable the Smart Wait function when it's enabled by using the above keyword.
Keyword name: disableSmartWait.
Example:

> Note: The Smart Wait function is only available in Chrome and Firefox.
