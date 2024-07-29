1. Использование команды cat в Linux

    1.1. Создать два текстовых файла: "Pets"(Домашние животные) и "Pack animals"(вьючные животные), используя команду `cat` в терминале Linux. В первом файле перечислить собак, кошек и хомяков. Во втором — лошадей, верблюдов и ослов.\
   `cat > Pets.txt`\
   ___Содержание файла:___\
   "Cooper dog\
   Charlie god\
   Max cat\
   Ginger cat\
   Alex hamster\
   Lily hamster"\
   `cat > PackAnimals.txt`\
   ___Содержание файла:___\
   "Agat horse\
   Jack horse\
   Koliko camel\
   Ren camel\
   Chypa donkey\
   Nelson donkey"\
   1.2. Объединить содержимое этих двух файлов в один и просмотреть его содержимое.\
   `cat Pets.txt PackAnimals.txt > Animal.txt`\
   `cat Aminal.txt`\
   ___Содержание файла:___\
   "Cooper dog\
   Charlie god\
   Max cat\
   Ginger cat\
   Alex hamster\
   Lily hamster\
   Agat horse\
   Jack horse\
   Koliko camel\
   Ren camel\
   Chypa donkey\
   Nelson donkey"\
   1.3. Переименовать получившийся файл в "Human Friends"  
   `mv Animal.txt HumanFriends.txt`

2. Работа с директориями в Linux  
   2.2. Создать новую директорию и переместить туда файл "Human Friends".
   `mkdir HumanFriends`\
   `mv HumanFriends.txt ./HumanFriends/`
3. Работа с MySQL в Linux. “Установить MySQL на вашу вычислительную машину ” 
   `sudo dpkg -i https://dev.mysql.com/get/mysql-apt-config_0.8.32-1_all.deb` 
4. Управление deb-пакетами  
   `sudo dpkg -i mysql-apt-config_0.8.32-1_all.deb`