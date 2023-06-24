# git-commads

git status
git add [files] - добавляет файлы в stage
git commit -m "comment"
git log / git log --oneline
git push [rep_link] [branch_name]
Полезное --

git remote -v посмотреть ссылку на гит
git remote add origin [rep_link] привязать пустой гид к папке
git reset [название файла] убрать из stage
git diff просмотр изменений, можно так же у отдельного файла
git reset --hard отменяет все изменения
git config --list посмотреть настройки гита
Работа с ветками

git branch посмотреть все ветки
git branch [название] создать новую ветку
git checkout [название] переключиться на другую ветку
git pull [rep_link] [branch_name] получить слияние веток с гита
git merge [branch_name] склеить ветки (обычно делают слияние находясь в мейн)
git branch -d [branch_name] удалить ветку (обычно после слияния удаляют)
git checkout -b [branch_name] переместиться в сразу созданную ветку
