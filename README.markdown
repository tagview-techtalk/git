Roteiro git
===========

O que todo controle de versão deve ter
--------------------------------------
* Repositório
* Metadata
* Histórico de modificações
* Tags


Por que usar um controle de versão
----------------------------------
* Histórico de modificações
* Trabalho em grupo


Versionando o código
--------------------
* "The Three Trees of Git"
* "The Working Directory"
* "The Index"
* "The HEAD"
* Adicionar ao Index
* Criar commit
* git remote add my-remote git://my-remote/project.git
* git fetch my-remote
* git remote prune my-remote


Branches & merges
-----------------
* git merge feature
* git pull
* git config [--global] push.default upstream


Verficando modificações
-----------------------
* git log --author=Daniel
* git log --decorate --graph --oneline
* git log -p Gemfile
* git diff
* git diff --cached
* git diff --word-diff master feature Gemfile
* git diff --name-only -Gfeature master app/


Tags
----
* git tag -a -m"Tag R1"


Misc.
-----
* contrib/completion/git-completion.bash
* git config [--global] help.autocorrect <deciseconds>
