# scrapy_parser_pep

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Scrapu](https://img.shields.io/badge/Scrapy-2.5.1-Aquamarine)


Задача проекта — создать парсер документов PEP на базе фреймворка Scrapy.


## Запуск парсера
Клонируйте репозиторий в рабочую директорию вашего компьютера, разверните и активируйте виртуальное окружение, установите зависимости из файла requirements.txt

```
$ git clone https://github.com/Filichkin/scrapy_parser_pep.git

```

```
$ python -m venv venv

```

```
$ source venv/bin/activate

```

```
$ pip install -r requirements.txt

```

Перейдите в директорию pep_parse и запустите парсер:

```
(venv) ...$ cd pep_parse
(venv) ...$ scrapy crawl pep 
```

Парсер должен сохранять данные в файлы .csv в директорию results/, она должна находиться в корне проекта, на одном уровне с pep_parse/ и tests/.