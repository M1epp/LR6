# LR6
Лабораторная работа №6
## Цель лабораторной работы: 
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.  

## Ход работы

### Операции
f3ac2f4 - 2023-11-15 - 4217 Mitrofanov D.S.: Research 2  
2268eeb - 2023-11-15 - 4217 Mitrofanov D.S.: Research 1  
f40e6c6 - 2023-11-15 - 4217 Mitrofanov D.S.: The file was changed  
e7da1bf - 2023-11-15 - 4217 Mitrofanov D.S.: Resolved the conflict  
e7347fe - 2023-11-15 - M1epp: add txt file  
921f53b - 2020-11-21 - Kurtyanik: Обновление информации  
0f9f50d - 2020-11-21 - Kurtyanik: Заполнил файл  
c08a654 - 2020-11-21 - Kurtyanik: Файл создан пустым  
3c6e913 - 2020-11-21 - Kurtyanik: Initial commit  

### Лог команд 
git clone https://github.com/M1epp/LR6  
cd LR6  
git pull  
git log  --all  
git log -n 1  
git merge origin/branch1  
git status  
cat mergefile.txt  
git add .  
git commit -m "Resolved the conflict"  
git push origin -d branch1  
git add .  
git commit -m "The file was changed"  
git add .  
git commit -m "The file was changed 2" 
git reset --hard HEAD^  
git checkout -b cool_branch  
git add .  
git commit -m "Research 1" 
git add .  
git commit -m "Research 2"  
git log --pretty=format:"%h - %ad - %an: %s" --date=short  
git add .  
git commit -m "Final"  
git push origin cool_branch

### Изображения
Изображение консоли  
![Первый скриншот](https://github.com/M1epp/LR6/blob/cool_branch/Screen/Screenshot_1.png)  

Изображения консоли  
![Второй скриншот](https://github.com/M1epp/LR6/blob/cool_branch/Screen/Screenshot_2.png)  

Изображения консоли    
![Третий скриншот](https://github.com/M1epp/LR6/blob/cool_branch/Screen/Screenshot_3.png)  

## Вывод: 
Я изучил базовые возможности системы управления версиями, получил опыт работы с Git Api и опыт работы с локальным и удаленным репозиторием.  