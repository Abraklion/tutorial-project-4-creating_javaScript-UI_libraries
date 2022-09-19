# Практический JavaScript (Продвинутый уровень)

Проект №4. Создаем свою JavaScript UI библиотеку

![уроки курса](https://thumbsnap.com/i/acJCLbhw.png)

### Настройки для сборки:

NODE v: 16.16.0

NPM v: 8.16.0

***

**Урок 2**: Сборка и архитектура проекта

В этом уроке мы разберем два главных вопроса: как собирать проект и какую архитектуру построить.

**core.js.js** - ядро библиотеки

**library.js** - расширяет ядро новыми методами

**main.js** - точка входа

*Модуль **core.js** подключаем в **library.js***

*Модуль **display.js** подключаем в **library.js***

*Модуль **library.js** подключаем в **main.js***

---

**Урок 3**: Работа с css-классами, атрибитами и обработчиками событий

В этом уроке мы добавим методы для работы с классами и обработчиками событий

*Модифицировал **core.js***

*Модуль **actions.js** подключаем в **library.js***

*Модуль **attribute.js** подключаем в **library.js***

*Модуль **classes.js** подключаем в **library.js***

---

**Урок 4**: Создаем методы для работы с элементами, часть 1

В этом уроке мы создадим несколько полезных методов для работы со страницей.

*Модуль **actions.js** переименовал в **handlers.js***

*Модуль **handlers.js** подключаем в **library.js***

---

**Урок 5**: Создаем методы для работы с элементами, часть 2

Это вторая часть урока по созданию полезных методов для работы с элементами на странице.

*Модифицировал **actions.js***

---