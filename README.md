# school21_jerikeny
jerikeny
carmelob

1 Git Bash - это эмулятор командной строки для Windows, который предоставляет доступ к инструментам командной строки Git. Он основан на MinGW (Minimalist GNU for Windows) и обеспечивает среду, аналогичную той, что доступна в Linux и macOS, позволяя использовать команды Git без необходимости установки Git для Windows.

2 Команда git pull в Git используется для обновления локального репозитория данными из удаленного репозитория. Она выполняет две операции:

git fetch: Загружает данные (ветки, коммиты, изменения) из удаленного репозитория в ваш локальный репозиторий.
git merge: Сливает измененные данные из загруженной ветки в вашу текущую ветку.
git push, наоборот, отправляет ваши локальные изменения в удаленный репозиторий. Она выполняет следующие действия:

git push origin <branch_name>: Отправляет изменения из вашей текущей ветки в удаленную ветку с тем же именем (например, main) в репозитории с именем origin.

3 Merge request (MR) - это запрос на слияние кода, который используется в системах управления версиями, таких как Git, для объединения изменений из одной ветки в другую. В основном, это способ предложить изменения, сделанные в одной ветке (часто в вашей собственной ветке разработки), для включения в другую ветку (часто в основную ветку, например, main).

4 Команды git status и git log обе предоставляют информацию о вашем репозитории Git, но они предоставляют разную информацию:

5 Git Submodule - это способ встроить другой Git-репозиторий в качестве подкаталога в ваш основной репозиторий. По сути, это позволяет вам включать внешний проект (например, библиотеку) в ваш проект, не копируя весь его код в ваш репозиторий.
