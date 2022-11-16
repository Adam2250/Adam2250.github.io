# Welcome to Adam2250's Trash Can
It shouldn't be much here...<br>
information?<br>
ae7b8db6be4aeb36



WebAutomation.LaunchEdge.LaunchEdge Url: $'''https://www.bing.com''' WindowState: WebAutomation.BrowserWindowState.Normal ClearCache: False ClearCookies: False WaitForPageToLoadTimeout: 60 Timeout: 60 BrowserInstance=> Browser
LOOP LoopIndex FROM 0 TO 40 STEP 1
    Text.Random UseUpperCaseLetters: True UseLowerCaseLetters: True UseDigits: True UseSymbols: True MinimumLength: 6 MaximumLength: 30 RandomText=> RandomText
    WebAutomation.GoToWebPage.GoToWebPage BrowserInstance: Browser Url: $'''https://www.bing.com/search?PC=U523&q=%RandomText%''' WaitForPageToLoadTimeout: 60
END
