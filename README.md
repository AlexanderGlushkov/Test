# Hello, World!

нажать правой клавишей мыши на нужную папку
нажать "новая вкладка терминала по адресу папки"
ввести в открывшемся терминале команду git init , тем самым создав из папки гит-репозиторий
чтобы удалить его, нужно включить показ скрытых файлов и папок, после чего из папки-репозитория удалить появившуюся скрытую папку .git
команда git status позволяет увидеть, какие файлы отслеживаются
чтобы добавить файл в отслеживаемые, необходимо ввести команду git add ИМЯФАЙЛА.расширение
чтобы создать коммит, нужна команда git commit
чтобы создать подписанный коммит, нужна команда git commit -m "ИМЯ" (например, "Initital commit")
после внесения изменений в файл, при вызове команды git status появится напдпись красного цвета: modified: ИМЯФАЙЛА
после этого этот файл снова нужно добавить в отслеживаемые, после чего снова формируем коммит и подписываем его при помощи команды git commit -m "ДРУГОЕИМЯ"
чтобы посмотреть историю проекта, нужна команда git log --oneline
чтобы посмотреть историю проекта в несокращенном виду, нужна команда git log
чтобы исправить ошибку в подписи (названии) коммита, нужна команда git commit --amend -m "Правильнаяподпись"
чтобы добавить все файлы из папки в отслеживаемые, нужна команда git add -A
чтобы добавить новый файл в старый коммит, нужно использовать команду git commit --amend -m "Правильнаяподпись"
для перемещений по истории коммита, нужна команда git checkout КЭШКОММИТА
для перемещения к последней версии, нужна команда git checkout master
чтобы узнать, есть ли у папки связь с удаленными репозиториями, нужна команда git remote -v, если термина ничего не ответил, то такой связи нет
чтобы связать папку с удаленным репозиторием, нужна команда "git remote add origin SSH-ссылка на удаленный репозиторий".
для того, чтобы отправлять данные с локального репозитория на удаленный репозиторий, нужна команда git push -u origin main