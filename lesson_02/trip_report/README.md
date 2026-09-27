Исмаилов Алишах Иса оглы РПО-26/1 

## Настройки окружения

- Python 3.12.x
- Путь до интерпретатора: `/home/user/trip-report/.venv/bin/python`
  (вывод команды `python -c "import sys; print(sys.executable)"`)

## Что где лежит в проекте

app/__init__.py      — пустой файл, чтобы папка считалась модулем
app/main.py          — главный скрипт, принимает данные и выводит готовый отчет
app/services/calculator.py — код для самих расчетов, в консоль ничего не выводит
app/utils/formatter.py     — делает красивую таблицу отчета через Rich
tests/test_calculator.py   — тесты для проверки калькулятора
requirements.txt     — нужные для работы библиотеки
README.md            — описание проекта, которое вы сейчас читаете

## Как запустить проект

### Инструкция для Windows

Разворачиваем окружение:
py -m venv .venv

Включаем его:
.venv\Scripts\activate

Ставим нужные библиотеки:
pip install -r requirements.txt

Запуск программы:
python -m app.main


### Инструкция для macOS

Создаем окружение:
python3 -m venv .venv

Активируем его:
source .venv/bin/activate

Переходим в нужную папку:
cd trip_report

Устанавливаем зависимости:
pip install -r requirements.txt

Запускаем главный файл:
python -m app.main


Примечание: Если PowerShell в Windows выдает ошибку и запрещает активацию, попробуйте перезапустить терминал от имени администратора. ..

























































































#Тёмный принц (Ыа-Ыа)