University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://ftmi.itmo.ru/)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/) 
Year: 2023/2024
Group: U4125
Author: Chumachenko Anastasia Alexandrovna
Lab: Lab1
Date of create: 19.04.2024
Date of finished: 

Был создан service account с ролью storage admin
![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/0789d777-1178-45da-bc75-6270c3c366bd)
Была создана виртуальная машина с machine type e2-micro в режиме spot. Был выбран  свой созданный ранее service account.
![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/62818358-3a51-47e8-b504-a41736bb1e83)
С помощью утилиты gsutils был найден бакет lab1-bucket-itmo и были скопированы 3 файла в локальную папку на виртуальную машину. 
![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/7bf4661c-632f-477a-973d-19a5d5e894ef)
Были изменены права доступа моего service account с Storage Admin на Compute Viewer
![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/82f674f3-4d95-4a36-94de-fe39171562b0)
Возникла ошибка при повторной попытке копирования файлов на виртуальную машину. Она связана с ограничением доступа. Роль Compute Viewer предоставляет только права на чтение ресурсов Compute Engine, но не предоставляет доступ к данным, хранящимся на этих ресурсах, в то время как роль Storage Admin предоставляет полный контроль над бакетами и объектами.
![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/d186b5e7-947c-407a-a69f-ae923098fb38)
