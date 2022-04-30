# curso_em_video_GIT_GITHUB
 repository for GIT & GITHUB course


**Git e Github**

**Aula#1 - O que eh Git e Github?**
	Git - gerenciamento de versoes (versionamento) na maquina
	Github - rede social de Programadores e repositorio remoto
	linear vs distribuido (Git eh distribuido e eh melhor)
	
**Aula#2 - Github**
	Funcoes:
		- repositorios ilimitados
		- hospedagem de codigo fonte
		- caracteristicas de rede social
		- Github Pages integrado
		- Colaboracao
		- Forks (divisao do trabalho em uma nova linha)
	Outras opcoes: gitlab, bitbucket, gogs, phabicator

**Aula#3 - Historia**
	CVS (1985) - centralizado, open source, mais popular na epoca, alguns problemas
	SVN (2000) - centralizado, open source, parecido com CVS, ainda eh ativo
	Bitkeeper (2000) - distribuido, proprietario, versao comunidade, diferente do CVS
	A TRETA: eng reversa (2004) -> bloqueio metadados (2005) -> criador do Linux cria o Git (2005)
	-> Guthub criado (2008) -> 3Musers (2013) -> Microsoft compra Github (2018)

**Aula#4 - Instalacoes e configuracoes**

**Aula#5 - O primeiro repositorio**
	Create repository
	Commity locally (from VS to local folder) -> on gitdesktop
	Commity to masteer (from local folder to github) -> on gitdesktop
	Edit file directly on github website

**Aula#6 - Gitdesktop on Linux**

**Aula#7 - Cloning**
	Cloning repository: code > open with > choose path

**Aula#8 - Old projects**
	Ignore file when commiting: rigth click and select ignore file > create gitignore file
	Company profile: have to type in the address bar
	Issue: requests opened by other, you can comment or close and comment.
	Link: can add a link to a commment with => [Clique aqui!](paste link here)

**Aula#9 - Issues**
	Search in issues on project repository to check if the problem was solved already
	Input issue: new issue > title > text details
	Start with "@" to reffer to someone
	LinK: add with link button > same as previous class
	Picture: drag to comment > upload
	Bold: use "**" before and after the text
	Close issue (solved) > lock conversation (stop comments)
	Pinned issues: this issues are placed at the top on issues list
	Standard reply: add standard text that can be used automatically

**Aula#10 - Markdown**
	Use in: README.md files, Issues and on Pull requests
	Bold: ** text** or __text__
	Italic: *text* or _text_
	Crossed: ~~text~~
	Title: # = lvl1 ; ## = lvl3 ; ### = lvl4
	Subline after title or divide area: --- or ***
	Can add fromats: __*text*__ (bold + italic)
	Number List: 1. (number + .) ; if add 3 spaces it is recognized as subitem
	Pin List: * or - before the item ; if add 3 spaces it is recognized as subitem
	Todo list: - [] before the item ; to check input "x" inside
	Image: drag and drop > upload (choose small images, change description inside [], format png or jpg)
	Link: [Text](link here)
	Table: 	Num | Nome | Nota
		---|---|---
		1 | Caio | 9,0
		2 | Marina | 10,0
	Command: `command here`
	Code: ```code here```
	Emojis: :starttyping (suggestions will appear) (gitub.com/ikatyang > repositories > emoji)
	Mention: @personname (suggestions will appear)
	Reply: click on "..." on target comment > quote reply or use ">"
	
**Aula#11 - Branches**
	branches are deviations from main version (think as a tree)
	master - master banch from local repository
	origin - master branch from remote repository
	each commit changes the master local repository
	merge - input all commits from branche to master
	push - send last commited master to origin
	avoid to commit everything on branch master - use side branches for new features
	if there is a conflict git warns you
	to merge has to be in master
	
**Aula#12 - Host on Github**
	Access repository > settings > git host > select repository root > get the link!