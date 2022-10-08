# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list"
https://i.ibb.co/r4sDfGh/1-1.png
https://i.ibb.co/7K53cvk/1-2.png

# Отримуємо контакт по id
node index.js --action="get" --id=5
https://i.ibb.co/DVCSDWm/2.png

# Додаємо контакт
node index.js --action="add" --name="Mango" --email="mango@gmail.com" --phone="322-22-22"
https://i.ibb.co/bWhzkM6/4.png

# Видаляємо контакт
node index.js --action="remove" --id=3
https://i.ibb.co/G3TzC0c/4-1.png