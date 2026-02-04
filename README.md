1. открыть visual studio
2. Открыть файл, выбрать проект WpfDatabaseFirsDemo
3. Нажать F5
4. Ура.Все готово
P.S - Если необходимо установить EntytiesFramework и подключить бд с именем University1, с таблицей Students
Код SQL:
CREATE DATABASE University1;
USE University1;
CREATE TABLE Students (
    Id INT PRIMARY KEY IDENTITY(1,1),
    FirstName NVARCHAR(50) NOT NULL,
    LastName NVARCHAR(50) NOT NULL,
    BirthDate DATE
);
INSERT INTO Students (FirstName, LastName, BirthDate) VALUES
('Иван', 'Иванов', '2000-05-15'),
('Мария', 'Петрова', '2001-08-22');
