# Base

* Git Bash, Git GUI for wondows or linux
	* http://git-scm.com/downloads
* gitk (Git GUI)

## 開始 - 初次設定Git

* 設定識別資料
	* git config --global user.name "John Doe"
	* git config --global user.email "John@example.com"
* 指定編輯器 (default vi)
	* git config --global core.editor emacs
* git config --list

* 初始化
	* git init
* 加外來源
	* git remote add origin git@github.com:rockst/Git.git
	* git push origin master

## simple useing

* git add filename
	* git add . (此資料夾)
	* git add * (所有)
* git status (可省去)
* git commit -m 'message'


[參考](https://git-scm.com/book/zh-tw/v1/)