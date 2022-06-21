# GIT
GitHub. HW_2
1. На локальном репозитории сделать ветки для:
```git init
```git commit --allow-empty -m "root commit"

- Postman
```git branch postman

- Jmeter
git branch jmeter

- CheckLists
git branch CheckLists

- Bag Reports
git branch BagReports

- SQL
git branch SQL

- Charles
git branch Charles

- Mobile testing
git branch MobileTesting

2. Запушить все ветки на внешний репозиторий
git remote add origin git@github.com:bayusheva-lyudmila/GIT.git
git push -u origin --all 

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
git checkout BagReports
vim br_structure.txt
1. ID
2. Title
3. Project
4. Version
5. Environment
6. Severity
7. Priority
8. Steps to reproduse
9. Expected result
10. Actual result
ESC :wq

4. Запушить структуру багрепорта на внешний репозиторий
git add .
git commit -m "file create"
git push

5. Вмержить ветку Bag Reports в Main
git checkout master
git merge bagreports

6. Запушить main на внешний репозиторий.
git push

7. В ветке CheckLists набросать структуру чек листа.
git checkout checklists

vim check_lists.txt
1. Регистрация на сайте
1.1. Поддтверждение почты смс
1.2. Письмо о регистрации со ссылкой
1.3. Подтверждение по ссылке
2. Авторизация на сайте
3. Выбор товара
4. Отображение в корзине
5. Куплен товар
6. Оплата товара
ESC :wq

8. Запушить структуру на внешний репозиторий
git add .
git commit -m "file create"
git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Синхронизировать Внешнюю и Локальную ветки Main
git pull
