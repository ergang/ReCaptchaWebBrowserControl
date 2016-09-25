## Default setting of WPF Web Browser Control does not render Medium security preference setting of ReCaptcha 

To run the program on a Windows Machine

1. Down Executable from https://github.com/ergang/ReCaptchaWebBrowserControl/blob/master/ReCaptchaWebBrowserControl/bin/Release/ReCaptchaWebBrowserControl.exe
2. OR : Open Visual Studio 2015 and run the program.

##### Things to note:

* The low setting page is http://ergang.github.io/reCaptchaLow.html
* The med setting page is http://ergang.github.io/reCaptchaMedium.html
* The page is using latest render and JS engine on the machine with the meta tag `<meta http-equiv="X-UA-Compatible" content="IE=edge">`
* However the user agent is the default with IE 7

##### More Info about .NET WPF Web Browser Control:

https://blogs.msdn.microsoft.com/patricka/2015/01/12/controlling-webbrowser-control-compatibility/

##### Low Setting screen shot
![alt tag](https://raw.githubusercontent.com/ergang/ReCaptchaWebBrowserControl/master/LowSetting.png)

##### Medium Setting screen shot
![alt tag](https://raw.githubusercontent.com/ergang/ReCaptchaWebBrowserControl/master/MediumSetting.PNG)

##### Acid Test score for IE 7 user agent but with IE 11 document mode
![alt tag](https://raw.githubusercontent.com/ergang/ReCaptchaWebBrowserControl/master/AcidScore.png)
