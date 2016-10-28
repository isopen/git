<h4>Скачать изменения себе</h4>
git pull
<h4>Выгрузить ветку в удаленный репозиторий</h4>
git push origin branch
<h4>Откатить коммит</h4>
git reset --soft HEAD^
<h4>Удалить коммит</h4>
git reset --hard HEAD^
<h4>Посмотреть автора изменений</h4>
git log -L 2484,2501:test/test.rb
<h4>Логирование до определенного уровня</h4>
git log -p -2
<h4>Список веток</h4>
git branch
<h4>Создать ветку</h4>
git checkout -b test
<h4>Выгрузить ветку из удаленного репозитория</h4>
git checkout -b test origin/test
<h4>Удалить ветку из удаленного репозитория</h4>
git push origin :test
<h4>Перенос коммитов из ветки в ветку</h4>
git cherry-pick 43b3445cdcd<br>
gt cherry-pick -n 43b3445cdcd
