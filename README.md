Screenshots of command execution

# Получаем и выводим весь список контактов в виде таблицы (console.table)
node index.js --action list
https://api.monosnap.com/file/download?id=nThJ5NZFJJlaR2hJ86ogXJZKjbI9l1

# Получаем контакт по id
node index.js --action get --id 5
https://api.monosnap.com/file/download?id=Ipmy2YzZBLfQN9pYHSWenJm9RRVi6z

# Добавялем контакт
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://api.monosnap.com/file/download?id=B9Q7WxT4auJcRgtIAaNdZBzL8USoeo

# Удаляем контакт
node index.js --action remove --id=3
https://api.monosnap.com/file/download?id=mCeVaKoVuE096KeAp7InDc8hYQRy4f