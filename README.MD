## Описание

Блокнот для определения соотношения пользователей в группах VK

-   указавших свой возраст к общему числу пользователей в сообществе
-   имеющих человеческое лицо на фото к общему количеству пользователей, у которых есть фото

Для определения лица используется библиотека OpenCV.

## Установка

Для запуска необходим python 3.6 или выше. Также необходим ключ VK API.

```bash
$ git clone https://github.com/shekshuev/vk-users-age-stat.git
$ cd vk-users-age-stat
$ python3 -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
$ echo "VK_ACCESS_TOKEN=<ключ_vk_api>" > .env
$ jupyter notebook
```
