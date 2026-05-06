# People Database

Простая база данных на SQL для хранения информации о пользователях.

##  реализовано:
- Создание таблицы (CREATE TABLE)
- Типы данных: INT, VARCHAR, TEXT, DATE
- PRIMARY KEY
- AUTO_INCREMENT

##  Файлы:
- `people.sql` — создание таблицы

##  Использовано:
- MySQL
-- INSERT
INSERT INTO people (name, email, bio, birth)
VALUES ('Misha', 'misha@mail.com', 'Video editor', '2005-01-01');

-- UPDATE
UPDATE people
SET bio = 'Pro video editor'
WHERE name = 'Misha';

-- SELECT с WHERE
SELECT * FROM people
WHERE name = 'Misha';
