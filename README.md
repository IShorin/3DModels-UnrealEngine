# Версия Unreal Engine: 4.24.3
Просьба всех скачать именно ее для предотвращения возможных конфликтов.  
Последовательность действий разработчиков моделей:
1) Отписаться мне, за какую задачу вы беретесь (см. задания во вкладке issues).
2) Разработать выбранную модель.
3) Форкнуть к себе данный репозиторий и в соответствующей папке проекта разместить разработанную модель и ее компоненты.
4) Отправить pull request на слияние ветки master вашего репозитория с веткой master данного репозитория. В pull request'e написать "Closes #" и выбрать вашу задачу из выпавшего списка.
5) Дождаться подтверждения верного выполнения задания.
## Устройство проекта Unreal Engine:  
В корневой папке проекта будут лежать папки с именами каждого проекта, где будут использоваться 3D модели. В каждой из этих папок будут лежать папки с названием моделей, если их несполько на один проект. В каждой папке с моделями будет лежать игровая сцена, в которую нужно будет поместить настроенную модель, а также 3 папки - "Textures", "Materials" и "Meshes". Просьба распределить все составляющие своей модели по данным папкам и собрать готовую модель в соответствующей сцене.Также необходимо создать папку Sources рядом с тремя вышеуказанными. Папка Sources предназначена для хранения в ней таких исходников, как .max файл и .fbx файл, используемый в движке.
