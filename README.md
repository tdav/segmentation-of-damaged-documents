# segmentation-of-damaged-documents

<h4>Задача очистки текста от зашумленности, распознавание текста на изображении и конвертации его в текстовый формат состоит из ряда подзадач:</h4>
1.	Выбор тестового изображения в любой папке на компьютере. Это происходит с помощью тестового графического интерфейса, реализованного для удобного пользования программой;<br>
2.	Процесс бинаризации изображения. Преобразования цветного изображения в черно-белое;<br>
3.	Очистка текста от зашумленности с помощью сверточной нейронной сети;<br>
4.	Очистка текста от зашумленности с помощью многослойного перцептрона;<br>
5.	Распознавание текста при помощи OCR Tesseract;<br>
6.	Конвертация  текста в текстовой формат для дальнейшей обработки.<br>

  Решив последовательно задачи, приведенные выше, из входных данных в виде зашумленного изображения с текстом, получаем выходные данные в виде текста в формате пригодном для его обработки.



<h2>Необходимые библиотеки:</h2>

1.	conda install keras;<br>
2.	conda install -c conda-forge opencv;<br> 
3.	pip install pytesseract;<br>
4.	conda install pyQt5; <br>
5.	Установить tesseract-ocr-setup-3.05.01;<br>
6.	Сделать привязку в файле pytesseract.py (находится в ...\Anaconda3\Lib\site-packages) на установленный tesseract.exe 
в файле pytesseract.py меняем старый tesseract_cmd на это tesseract_cmd = 'C:\\Program Files (x86)\\Tesseract-OCR\\';<br>
7.	Программа запускается с помощью файла main.py (остальные файлы должны быть в этой же папке).