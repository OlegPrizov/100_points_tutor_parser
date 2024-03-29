# Первый шаг
Скачиваем [архив](https://github.com/ev1nnn/100p_parser/raw/main/100p%20parser.zip) и распаковываем его в удобном месте

# Установка Python
Переходим по [ссылке](https://www.python.org/downloads/release/python-3110), листаем в самый низ и скачиваем Windows installer (64-bit) для **Windows** ![image](https://user-images.githubusercontent.com/45720190/204282646-d7c25bfa-e72c-4c60-bebe-7a9ff129a164.png)  и macOS 64-bit universal2 installer для **macOS** ![image](https://user-images.githubusercontent.com/45720190/204282808-39578003-f494-4208-93fe-1981230930bd.png)  
Запускаем скачанный файл. В открывшемся окне ставим обе галочки и жмем на "Customize installation". ![image](https://user-images.githubusercontent.com/45720190/204283070-d687db1c-e321-448c-8acf-c696fe9dd50d.png)  
Проверяем, что стоят ВСЕ галочки, и жмем "Next" ![image](https://user-images.githubusercontent.com/45720190/204283311-82907d35-8690-42e6-9bc9-0e45876c9eef.png)  
В новом окне ставим первые 5 галочек и нажимаем "Install" ![image](https://user-images.githubusercontent.com/45720190/204283465-bc762d1c-1969-4e24-8640-249eff794083.png)   
# Установка библиотек
**(Windows)** Запускаем файл setup.bat из скачанного архива и ждем, пока выполняются необходимые команды (Windows)  
**(macOS)** Открываем терминал и поочередно прописываем следующие команды:
1. python -m pip install --upgrade pip
2. pip install bs4
3. pip install requests
4. pip install fake_useragent  
Если во время выполнения действий этого шага возникли какие-то ошибки, пишите [мне](https://vk.com/mrgreyson), помогу их решить

# Запуск программы
Для запуска программы 2 раза кликаем по файлу parser.py  

# Важно
* Программа может выдвать нереалистичные результаты домашки (например, все 0) при возникновении ошибки доступа к сайту. Повторный запрос результатов выдаст верный ответ.
* Программа может функционировать некорректно после создания списка своей группы, нужно перезапустить программу после этого действия.
* Имена учеников в списке должны ПОЛНОСТЬЮ совпадать с именами на сайте. Если на платформе будет результат ученика, имя которого не совпадает ни с одним из вашего списка, то программа выведет его в самом конце ![image](https://user-images.githubusercontent.com/45720190/204288560-c6884929-038e-43ff-a0fc-c3c743152808.png)
