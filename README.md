# Домашнее задание к занятию «Helm»

Цель задания
В тестовой среде Kubernetes необходимо установить и обновить приложения с помощью Helm.


## Задание 1. Подготовить Helm-чарт для приложения

[Helm-чарт](https://github.com/vladmgb/kuber-2.4/tree/main/myapp)

Установка:

<img width="462" height="124" alt="image" src="https://github.com/user-attachments/assets/b2662de8-8c71-4722-822e-8b7ac3d193b9" />


<img width="645" height="628" alt="image" src="https://github.com/user-attachments/assets/0d5e257e-95ba-47e7-b09f-e0277738f9a0" />


<img width="429" height="217" alt="image" src="https://github.com/user-attachments/assets/4b2d5536-0032-4a07-964f-332700fa7863" />


Обновление версии:

<img width="547" height="286" alt="image" src="https://github.com/user-attachments/assets/f99eca84-8549-464a-8a7c-82cc437e9287" />



## Задание 2. Запустить две версии в разных неймспейсах
1. Подготовив чарт, необходимо его проверить. Запуститe несколько копий приложения.
2. Одну версию в namespace=app1, вторую версию в том же неймспейсе, третью версию в namespace=app2.
3. Продемонстрируйте результат.


Файл README.md должен содержать скриншоты вывода необходимых команд kubectl, helm, а также скриншоты результатов.
