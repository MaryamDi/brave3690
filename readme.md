## Работа с удаленным репозиторием

Копировать внешний репозиторий на свой ПК можно командой git clone.
Команда git clone составная: она не только загружает все изменения, но и пытается слить все ветки на локальном компьютере и в удаленном репозитории.
git pull
Эта команда позволяет скачать все 
из текущего репозитория и автоматически сделать merge с нашей версией
git push
Отправить свою версию репозитория во внешний репозиторий поможет команда git push. При первом её использовании нужна авторизация.Эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории.
pull request
➜ команда для предложения изменений
➜ запрос на вливание изменений в репозиторий
В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду pull request. Предлагать изменения на GitHub нужно в отдельной ветке. Сначала пользователь копирует репозиторий на свой компьютер, делает fork репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой push в свой аккаунт на GitHub и даёт команду pull request.