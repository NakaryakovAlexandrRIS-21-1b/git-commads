# git-commads

1.git status\n
2.git add [files] - добавляет файлы в stage
3.git commit -m "comment"
4.git log / git log --oneline
5.git push [rep_link] [branch_name]

Полезное --

1.git remote -v посмотреть ссылку на гит
2.git remote add origin [rep_link] привязать пустой гид к папке
3.git reset [название файла] убрать из stage
4.git diff просмотр изменений, можно так же у отдельного файла
5.git reset --hard отменяет все изменения
6.git config --list посмотреть настройки гита

Работа с ветками

git branch посмотреть все ветки
git branch [название] создать новую ветку
git checkout [название] переключиться на другую ветку
git pull [rep_link] [branch_name] получить слияние веток с гита
git merge [branch_name] склеить ветки (обычно делают слияние находясь в мейн)
git branch -d [branch_name] удалить ветку (обычно после слияния удаляют)
git checkout -b [branch_name] переместиться в сразу созданную ветку
