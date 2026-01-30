1. ГІТ-АЛГОРИТМ (щоразу після змін):
- git add .
- git commit -m "виконав завдання модуля 2"
- git push

2. РОБОТА НА ІНШОМУ ПК:
- Зайшов у папку -> git pull. Працюєш. В кінці -> git push.

3. Робота на новій машині (Windows або Linux)
Якщо ти сів за комп'ютер, де немає твоїх проектів:
Крок 1: Створити кореневу папку (опційно)
    • Linux: mkdir ~/projects && cd ~/projects
    • Windows: створи папку C:\projects і зайди в неї через термінал.
Крок 2: Завантажити все з GitHub
Для кожного репозиторію один раз виконай:
Bash
git clone https://github.com/lexx23021074/jr_learning.git
git clone https://github.com/lexx23021074/go_it_learning.git
git clone https://github.com/lexx23021074/goit-markup-hw-01.git

Крок 3: Якщо папки вже є, але старі
Зайди в кожну і онови:
Bash
cd jr_learning
git pull