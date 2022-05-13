# 1. На локальном репозитории сделать ветки для:
*- Postman 

*- Jmeter

*- CheckLists

*- Bag Reports

*- SQL

*- Charles

*- Mobile testing

       git branch "название ветки"

# 2. Запушить все ветки на внешний репозиторий 

        git push -u --all origin

# 3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта 

        vim structure.txt

# 4. Запушить структуру багрепорта на внешний репозиторий 
        
        git push 
        
# 5. Вмержить ветку Bag Reports в Main
    
        git merge Bag_Reports
    
# 6. Запушить main на внешний репозиторий.
        
        git push -u origin main
# 7. В ветке CheckLists набросать структуру чек листа. 
        
        vim structure2.txt
        
# 8. Запушить структуру на внешний репозиторий 
        
        git add git commit -m git push
        
# 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main перехожу на github /кнопка Pull Request / create Pull Request  / merge pull request

        
        перехожу на github /кнопка Pull Request / create Pull Request  / merge pull request
# 10. Синхронизировать Внешнюю и Локальную ветки Main 

        git fetch 
        git pull
