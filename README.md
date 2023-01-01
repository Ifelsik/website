# mysite.ru
 My WSGI app
Предварительно клонируется репозиторий с приложением
`
git clone
`
Для установки предварительно создаётся виртуальная среда
`
python -m venv env
`
Для её запуска используется команда (Linux)
`
source env/bin/activate
`
Далее устанавливаются необходимые модули
`
pip install -r requirements.txt
`
Затем устанавливается переменная среды и запускается приложение, предварительно перйдя в директорию с приложением
`
cd mysite.ru
export FLASK_APP=app.py
flask run
`
