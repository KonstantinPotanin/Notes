# Консольное приложение заметок на Python
Это консольное приложение на Python, которое позволяет вам создавать, просматривать, редактировать и удалять заметки. Вы также можете фильтровать заметки по дате.


## Использование

1. Запустите приложение через `NoteManager.py`:
2. Следуйте инструкциям в консоли для выполнения действий с заметками:
- Добавление заметки: введите "add".
- Просмотр списка заметок: введите "list".
- Просмотр списка заметок по дате: введите "list_by_date".
- Редактирование заметки: введите "edit".
- Удаление заметки: введите "delete".
- Чтение заметки: введите "read".
- Выход из приложения: введите "exit".

## Структура проекта

- `Note.py`: Определяет класс `Note`, представляющий заметку.
- `NoteSerializer.py`: Определяет класс `NoteSerializer`, который отвечает за сериализацию и десериализацию объектов заметок.
- `NoteManager.py`: Определяет класс `NoteManager`, который управляет заметками: загрузка, сохранение, добавление, удаление, фильтрация.
- `notes.json`: Файл для хранения заметок в формате JSON.
