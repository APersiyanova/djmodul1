**Что такое API / Хабр** https://habr.com/ru/post/464261/ 
**Краткая история Linux — база знаний Timeweb Community** https://timeweb.com/ru/community/articles/kratkaya-istoriya-linux-1 

урок 1.4. Инструкция по настройке WSL (windows system for linux) на официальном сайте Microsoft https://apps.microsoft.com/store/detail/ubuntu/9PDXGNCFSCZV?hl=ru-ru; 
скачать Ubuntu из магазина приложений Microsoft https://apps.microsoft.com/store/detail/ubuntu/9PDXGNCFSCZV?hl=ru-ru; 
про настройку работы с WSL в PyCharm (интерпретатор и терминал) https://www.jetbrains.com/help/pycharm/using-wsl-as-a-remote-interpreter.html; 
сайт VirtualBox https://www.virtualbox.org/wiki/Downloads;
Kubuntu https://kubuntu.org/getkubuntu/;
неполная инструкция по установке Linux с модуля Python Advanced

**Django documentation** https://docs.djangoproject.com/en/4.0/

python3 -V
python3 --version
pip --help
python3 -m pip --help
sudo apt -y python3-pip
pip install django
python3 -m django
python3 -m django startproject mysite
cd mysite
python3 manage.py runserver

Чтобы можно было воссоздать вашу виртуальную среду на любой машине, необходимо сгенерировать файл **requirements.txt** с описанием зависимостей проекта. Это делается командой pip freeze > requirements.txt. Файл должен находиться внутри проекта mysite, рядом с файлом manage.py. Подробнее — в статье «Как создать requirements.txt в Python, pip install, pip freeze» https://dvmn.org/encyclopedia/pip/pip_requirements_txt/. 

pip freeze > requirements.txt
pip install -r requirements.txt

**  ** 
