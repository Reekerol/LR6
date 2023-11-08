# **Лабараторная работа 6**
## Цель работы:
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.
## Ход работы:
1. Аккаунт GitHub был создан до выполнения лабораторной работы ([ссылка])
2. Сделана копия в личное хранилище (Fork)
   
    ![1](https://github.com/Reekerol/LR6/blob/otchet/screenshots/1.png)
   
3. Git был установлен до выполнения лабораторной работы

    ```sh
    git --version
    ```
   
    ![2](https://github.com/Reekerol/LR6/blob/otchet/screenshots/2.png)
    
5. Настройка клиента git

    Изменено имя пользователя.
   
    ```sh
    git config --global user.name "Коскин Артём 4216"
    ```
    
    ![3](https://github.com/Reekerol/LR6/blob/otchet/screenshots/3.png)
    
    Изменен email.
   
    ```sh
    git config --global user.email "artm.koskin@list.ru"
    ```
    
   ![4](https://github.com/Reekerol/LR6/blob/otchet/screenshots/4.png)
   
7. Клонирован свой личный удалённый репозиторий на компьютер

    ```sh
    git clone https://github.com/Reekerol/LR6.git
    ```
   
    ![5](https://github.com/Reekerol/LR6/blob/otchet/screenshots/5.png)

    ![6](https://github.com/Reekerol/LR6/blob/otchet/screenshots/6.png)
    
9. Добавлен файл через интерфейс GitHub, подтянуты изменения в локальный репозиторий

   Добавлен файл через интерфейс GitHub.

   ![7](https://github.com/Reekerol/LR6/blob/otchet/screenshots/7.png)
    
    Подтянуты изменения в локальный репозиторий.
   
    ```sh
    git pull
    ```
    
    ![8](https://github.com/Reekerol/LR6/blob/otchet/screenshots/8.png)
    
11. Получена история операций для каждой из веток

    Для master
    
    ```sh
    git log
    ```
    
    ![9](https://github.com/Reekerol/LR6/blob/otchet/screenshots/9.png)
    
    Для branch1
    
    ```sh
    git log origin/branch1
    ```
    
    ![10](https://github.com/Reekerol/LR6/blob/otchet/screenshots/10.png)
    
13. Просмотрены последние изменения

    ```sh
    git status
    ```
    
    ![11](https://github.com/Reekerol/LR6/blob/otchet/screenshots/11.png)
    
15. Выполнено слияние в ветку master, разрешив конфликт

    Слияние веток.
    
    ```sh
    git merge branch1
    ```
    
    ![12](https://github.com/Reekerol/LR6/blob/otchet/screenshots/12.png)
    
    Конфликт решен с помощью графического интерфейса.
    
    ![13](https://github.com/Reekerol/LR6/blob/otchet/screenshots/13.png)
    
    Зафиксированы изменения.
    
     ```sh
     git add mergefile.txt
     ```

     ```sh
     git commit -m "Слияние веток и разрешение конфликтов"
     ```
    
    ![14](https://github.com/Reekerol/LR6/blob/otchet/screenshots/14.png)
    
11. Удалена побочная ветка после успешного слияния

    При слиянии ветка удалилась автоматически.

    ![15](https://github.com/Reekerol/LR6/blob/otchet/screenshots/15.png)

    Удаление ветки на GitHub
        
    ```sh
    git push origin -d branch1
    ```
    
    ![16](https://github.com/Reekerol/LR6/blob/otchet/screenshots/16.png)
    
11. Изменения сделаны и зафиксированы
    
    Первое изменене.

    ![17](https://github.com/Reekerol/LR6/blob/otchet/screenshots/17.png)

    Второе изменение.

    ![18](https://github.com/Reekerol/LR6/blob/otchet/screenshots/18.png)

    Третье изменение.

    ![19](https://github.com/Reekerol/LR6/blob/otchet/screenshots/19.png)
    
12. Сделан откат коммита
    
     ```sh
     git reset --hard HEAD~
     ```

    ![20](https://github.com/Reekerol/LR6/blob/otchet/screenshots/21.png)
     
    До отката:

    ![21](https://github.com/Reekerol/LR6/blob/otchet/screenshots/20.png)

    После отката:

    ![22](https://github.com/Reekerol/LR6/blob/otchet/screenshots/22.png)
    
13. Создана ветка для отчета

    ![23](https://github.com/Reekerol/LR6/blob/otchet/screenshots/23.png)

14. Получена история операций в форматированном виде
    
    ![24](https://github.com/Reekerol/LR6/blob/otchet/screenshots/24.png)


   [ссылка]: <https://github.com/Reekerol>

