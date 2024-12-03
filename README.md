## Установка и запуск

### 1. Клонирование репозитория
```bash
git clone https://github.com/assami1337/OTRPO_lab9.git
cd OTRPO_lab9
```
### 2. Создание виртуального окружения
```bash
  python3 -m venv venv
```
Активируйте виртуальное окружение:
- Linux/macOS:
```bash
  source venv/bin/activate
```
- Windows:
```bash
  venv\Scripts\activate
```
### 3. Установка зависимостей
Убедитесь, что у вас установлен Python 3.7 или выше. Установите необходимые зависимости:
```bash
pip install -r requirements.txt
```
### 4. Запустите redis

### 5. Запуск сервера
```bash
python server.py
```
## Использование
1. Перейдите на `http://localhost:8888`.
2. Введите имя пользователя.
3. Чат доступен в режиме реального времени.
