# Hello, World!

нажать правой клавишей мыши на нужную папку
нажать "новая вкладка терминала по адресу папки"
ввести в открывшемся терминале команду git init , тем самым создав из папки гит-репозиторий
чтобы удалить его, нужно включить показ скрытых файлов и папок, после чего из папки-репозитория удалить появившуюся скрытую папку .git
команда git status позволяет увидеть, какие файлы отслеживаются
чтобы добавить файл в отслеживаемые, необходимо ввести команду git add ИМЯФАЙЛА.расширение
чтобы создать коммит, нужна команда git commit
чтобы создать подписанный коммит, нужна команда git commit -m "ИМЯ" (например, "Initital commit")

PROVERIM

после внесения изменений в файл, при вызове команды git status появится напдпись красного цвета: modified: ИМЯФАЙЛА
после этого этот файл снова нужно добавить в отслеживаемые, после чего снова формируем коммит и подписываем его при помощи команды git commit -m "ДРУГОЕИМЯ"
чтобы посмотреть историю проекта, нужна команда git log --oneline