# Revert-NeuroStartUp
## Задача №2 - Откат изменений
### Легенда
Команда из NeuroStartUp начала работать над сайтом в Git, но случилось непредвиденное: один из разработчиков допустил ряд ошибок и залил всё вместе с ошибками в репозиторий на GitHub. Вам нужно отменить его последний коммит и исправить ситуацию.

### Задача
1. Склонируйте Git-репозиторий [по ссылке](https://github.com/netology-code/git-homeworks-neuro);
2. Отмените один последний коммит в проекте при помощи команды `git revert`;
3. Создайте отдельный репозиторий на GitHub'е;
4. Свяжите ваш локальный репозиторий с только что созданным удалённым репозиторием. При связывании используйте *кодовое имя* `target` поскольку стандартное *кодовое имя* `origin` уже занято.
5. Отправьте сделанные вами изменения на GitHub.

*Примечание**: поскольку вы использовали операцию `git clone` в первом пункте, то в вашем репозитории уже существует `remote origin`. При попытке добавления второго такого, будет ошибка. Поэтому вместо `origin` пишем `target` и push тоже делаем в `target`. Посмотреть все связи локального репозитория можно командой `git remote -v`.
