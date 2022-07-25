# С чего начинать?
<img src="https://git-scm.com/images/logos/1color-orange-lightbg@2x.png" alt="drawing" width="550"/>

---

Для начала следует установить приложение [GIT](https://git-scm.com/downloads)

---

Далее следует привязать теминал к GIT HUB, это делается данной командой

```
 git config --global user.name "name"
 git config --global user.email "example@gmail.com"
```
Вместо "name" прописываем свое имя, а вместо "example@.gmail.com" прописываем имейл к которому привязан ваш GIT HUB

---

Далее нам требуется создать репозиторий, это делается на вашей странице в GIT HUB. Заходите в ваш профиль и сверху увидите вкладку **"repositories"** сверху справа будет зеленая надпись **"new"** нажимаете на неё, называете ваш репозиторий и в терминале VS Code прописываете данные команды

```
 git init

 git add README.md

 git commit -m "first commit"

 git branch -M main

 git remote add origin git@github.com:(ваш ник/название репозитория.git)

 git push -u origin main
```
 Всё, теперь вы подключили VS Code к GIT HUB.

[⇐назад](readme.md)