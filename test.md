## Работа с удаленными репозиториями 

1.Чтобы скачать данные с сервера необходимо воспользоваться командой:  
**git pull** - по сути, это сочитание двух команд: **git fetch** (загружает коммиты, ссылки, файлы из удаленного репозитория в локальный) и **git merge** (объединяет несколько коммитов в один общий). 

2.Команда **git push** в ходе выполнения переносит все изменения, внесенные пользователем , в удаленный репозиторий (например, такой как GitHub):
> **Git push 'remote_name' 'branch_name'**

Чтобы отправить данные в **удаленный** репозиторий, нужно удостовериться, что все перемены зафиксированы в **локальном** репозитории. После того, как вы внесете изменения локально, вы сможете поделиться ими, но прежде чем отправлять какие-либо перемены в удаленную ветку, рекомендуется запустить команду **git pull**. Это обновит локальную ветвь.

3.Команда **git clone <ссылка на репозиторий> <название папки>** просит Git создать копию репозитория, который находится по ссылку (<ссылка на репозиторий>), и и можем указать название новой папки , в которую Git скопирует репозиторий (<название папки>). Если не указывать название папки, то папка будет называться также как и репозиторий. 