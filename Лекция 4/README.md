# Задание 1: Установлен CentOS 7 + Gnome HUD на системе HyperV
# Задание 2: 
echo "Artamonov Iaroslav" && echo "Lesson 4 07-07-2022" && cat /proc/version
# Задание 3:
mkdir Artamonov4 && ls -la` / `cd Artamonov4 && ls -la
# Задание 4:
mvdir Artamonov4 Artamonov4-07-07-2022 && cd Artamonov4-07-07-2022 && touch concept.1 && cat /proc/version > concept.1 && echo "Artamonov Iaroslav " >> concept.1 && tail -1 concept.1 && echo "Lesson 4" >> concept.1
# Задание 5:
cd Artamonov4-07-07-2022 && ln concept.1 hardlink && mv hardlink concept.1.old && rm concept.1 && cat concept.1.old
# Задание 6:
yum update -y
yum install mc vim-enhanced