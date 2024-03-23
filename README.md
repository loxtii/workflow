# Работа над workflow
Настройка workflow для автоматического тестирования и публикации приложения в DockerHub. 

**Два jobs:🔖🔖**
- Первый будет проверять код на наличие ошибок и запускать тесты.
- Второй при добавлении тегов должен автоматически публиковать приложение в DockerHub.

**Cсылка на опубликованный образ:🔍**
https://hub.docker.com/repository/docker/mityad/workflow/general

**Успех:🎁**
- все jobs завершились успешно 
- образ скачивается с DockerHub и запускается

**Команды для скачивания и запуска:📞**
docker pull --platform linux/x86_64 mityad/workflow:pr-1
docker run --platform linux/x86_64 mityad/workflow:pr-1