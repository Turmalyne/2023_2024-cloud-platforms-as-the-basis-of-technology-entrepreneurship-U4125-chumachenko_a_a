University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://ftmi.itmo.ru/)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/) 
Year: 2023/2024
Group: U4125
Author: Chumachenko Anastasia Alexandrovna
Lab: Lab2
Date of create: 30.04.2024
Date of finished:

Используя draw.io, накидала схему инфраструктуры приложения
![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/d9d18b96-660f-49b2-a01f-9740ae3d5a4f)

**Начальное состояние**
1) VM: e2-micro 0.25-2 vCPU 1 GB memory — 7.11$
2) SQL Cloud: PostgreSQL 1 vCPU 0.6 GB memory — 9.5$

**Итого** 16.61$

В начальном состоянии, ожидается небольшое количество пользователей. Требований к  VM должно быть достаточно для этого этапа. Условий для SQL также должно быть достаточно для обработки данных от небольшого количества пользователей.

![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/5ba9cd08-f3ab-4ec4-b063-ce784472126a)
![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/420f0199-e11e-4bcb-bb39-e5bbb5ebe214)

**Тестирование партнёрами**
1) VM: e2-small 0.5-2 vCPU 2 GB memory — 13.23$
2) SQL Cloud: PostgreSQL 1 vCPU 1.7 GB memory — 28.98$

**Итого** 42.21$

На этом этапе, количество пользователей увеличится. Увеличение ресурсов VM обеспечит больше мощности для обработки дополнительного трафика, а увеличение ресурсов SQL обеспечит достаточно быстрый доступ к данным.

![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/c390cd2f-0616-431c-8956-0438f2a4f367)
![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/46f16bfb-53ca-4984-adcf-31b7a957bb65)

**Продовое решение**
1) VM: e2-medium 1-2 vCPU 4 GB memory — 25.46$
2) SQL Cloud: PostgreSQL 1 vCPU 3.75 GB memory — 66.5$

**Итого** 91.96$

После успешного тестирования, ожидается рост числа пользователей. Увеличение мощности VM обеспечит необходимую производительность для обработки большого количества запросов, а увеличение ресурсов базы данных SQL обеспечит высокую производительность и отказоустойчивость.

![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/805aa6bd-032e-4c13-9e06-78f680ed2746)
![image](https://github.com/Turmalyne/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-chumachenko_a_a/assets/164026253/50aa7aa9-70f5-432c-bb1a-80a1af6dbcca)

Было бы прекрасно, если бы оплата шла только за реальное использование ресурсов, для того чтобы уменьшить расходы в периоды простоя приложения
