# Config

> 列出所有設定

	git config -l
	
> Author and Email set in respo

	git config user.name 'author'
	git config user.email 'email'
	
> Author and email set in home directory

	git config --global user.name 'author'
	git config --global user.email 'email'
	
> Remove set

	git config --unset user.name
	
> 使用 Alias 來縮短指令

	git config alias.指令別名 '正確的指令'
	
	git config alias.con 'config -l'
	git con (使用方法)
	git config --unset alias.con (移除)

	git config alias.com 'commit'
	git config alias.pul 'pull origin master'
	git config alias.pus 'push origin master'
	git config alias.sta 'status'

> Editor

	git config --global core.editor notepad
	git config --global core.editor "'C:/xxxxxxxxx/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
	
> credentials

	git config --global credential.helper store
	git pull
	
	(Input username/password)
	
	git pull (For test)
	
	If you want to change the password
	
	.git-credentials file

