# curso_git
============================
GIT

--version

config
	--global
		user.name
			"Seu Nome"
		user.email
			"Seu Email"
		core.editor
			vscode
	--list
	user.name
	user.email
	core.editor

init

REDME.MD

status

add
	nome do arquivo
	-A

commit
	-m
		"Descrição"

reset
	--soft
		ID do commit
	--hard
		ID do commit

log

branch
	nome

checkout
	nome da branch

-am
	"Descrição"

=============================================

Site Git
################################################
…or create a new repository on the command line
=================================================
echo "# curso_git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Xeroga/curso_git.git
git push -u origin main

…or push an existing repository from the command line
========================================================
git remote add origin https://github.com/Xeroga/curso_git.git
git branch -M main
git push -u origin main
