## GitHub. HW_2

1. На локальном репозитории сделать ветки для:
- Postman          === `git branch Postman`
- Jmeter           === `git branch Jmeter`
- CheckLists       === `git branch Check_lists`
- Bug Reports      ===` git branch Bug_Reports`
- SQL              === `git branch SQL`
- Charles          === `git branch Charles`
- Mobile testing   === `git branch Mobile_testing`

2. Запушить все ветки на внешний репозиторий
 === `git push -u origin Postman`
 
 === `git push -u origin Jmeter`
 
 === `git push -u origin Check_lists`
 
 === `git push -u origin Bug_Reports`
 
 === `git push -u origin SQL`
 
 === `git push -u origin Charles`
 
 === `git push -u origin Mobile_testing`

3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта
 === `git checkout Bug_Reports`
 
 === `vim bug_report.txt`

4. Запушить структуру багрепорта на внешний репозиторий
 === `git add .`
 
 === `git commit -m "Add bug_report.txt file"`
 
 === `git push`

5. Вмержить ветку Bug Reports в Main
 === `git checkout main`
 
 === `git merge Bug_Reports`

6. Запушить main на внешний репозиторий. === `git push`

7. В ветке CheckLists набросать структуру чек листа.
 === `vim check_list.txt`

8. Запушить структуру на внешний репозиторий
 === `git add .`
 
 === `git commit -m "Add check_list.txt file"`
 
 === `git push`

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
 === `кликнуть на кнопку Compare & Pull Request`
 
 === `нажать Create pull request`
 
 === `нажать Merge pull request`

10. Синхронизировать Внешнюю и Локальную ветки Main
 === `git pull (в ветке main локального репозитория)`
