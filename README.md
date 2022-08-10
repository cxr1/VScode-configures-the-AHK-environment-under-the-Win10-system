# Win10系统下VScode配置AHK环境

本文默认已安装autohotkey。

1.下载vscode安装包

https://code.visualstudio.com/Download

![994650c61a21e8aaf_1_post](https://user-images.githubusercontent.com/56662006/183874426-11cd1d5d-9124-4d7c-a19b-70d80827a7f1.png)

2.开始安装

![9946a36561c069172_1_post](https://user-images.githubusercontent.com/56662006/183874577-957bcdef-6b68-42a5-924c-3da4dd6f59f5.png)

![9946107266c18f5a3_1_post](https://user-images.githubusercontent.com/56662006/183874652-ad12c73c-aca0-4f40-bd85-296a46a98743.png)

![9946f0a42c0962163_1_post](https://user-images.githubusercontent.com/56662006/183874701-2ef28ee5-bacf-4837-bba2-fd2ce3cb9079.png)

安装好之后打开是英文界面，先安装一个中文插件，安装好之后会提示重启ide，点击重启。

![9946cc1663725f22c_1_post](https://user-images.githubusercontent.com/56662006/183874801-ad2dffa1-ab4e-4ae6-9d0c-0794d43320ea.png)

接下来安装autohotkey插件，跟上面一样的操作。

![9946d618d69cb3426_1_post](https://user-images.githubusercontent.com/56662006/183874894-9d74f130-efd7-4212-a8bb-8397b0577ab7.png)

安装coderunner。

![99461f29464c6d1cb_1_post](https://user-images.githubusercontent.com/56662006/183875011-5c30c333-8c0a-4bd9-aa1a-0bddbc4fc7ef.png)

配置coderunner。

![99469226fd16e6c16_1_post](https://user-images.githubusercontent.com/56662006/183875094-1d771a72-2e44-490c-aded-5855ff628f67.png)

复制粘贴进去

{
 "code-runner.executorMap": {
 "ahk": "\"C:\\Program Files\\AutoHotkey\\AutoHotkey.exe\" /CP65001"
    },
 "code-runner.defaultLanguage": "ahk",
 "code-runner.executorMapByFileExtension": {
 ".ahk": "\"C:\\Program Files\\AutoHotkey\\AutoHotkey.exe\""
    }
}

![994623b7d41666cdb_1_post](https://user-images.githubusercontent.com/56662006/183875214-d391c1e4-ba28-4275-bb28-52d29578953b.png)

配置完成，测试一下

![994632171121eb66c_1_post](https://user-images.githubusercontent.com/56662006/183875320-15716956-243a-4744-992d-9474276f1b91.png)
