# ansible
my ansible work
=======
Далее, если у вас уже есть локальный git репозиторий, и вы хотите его залить, выполните инструкции из раздела

…or push an existing repository from the command line
```
git remote add origin https://github.com/ИМЯ_ПОЛЬЗОВАТЕЛЯ/ИМЯ_ПРОЕКТА.git
git push -u origin master
```
Если у вас просто есть файлы, которые не были под Git, выполните инструкции из раздела

…or create a new repository on the command line

```
echo "# ИМЯ_ПРОЕКТА" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/ИМЯ_ПОЛЬЗОВАТЕЛЯ/ИМЯ_ПРОЕКТА.git
git push -u origin master
```

```
openssl req -x509 -nodes -days 3650 -newkey rsa:2048 \
    -subj /CN=localhost \
    -keyout files/nginx.key -out files/nginx.crt
```

