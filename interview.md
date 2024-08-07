# Вопросы и ответы для собеседования PHP developer

источник: [techrocks.ru](https://techrocks.ru/2021/04/18/250-php-job-interview-questions/)

### Junior

***1. Что такое ссылки?***

  Ссылки в PHP — это средство доступа к содержимому одной переменной под разными именами. В PHP имя переменной и её содержимое — это разные вещи,   поэтому одно содержимое может иметь разные имена.

  ![image](https://github.com/xmsi/interview/assets/59314275/6f941190-c959-4980-98fa-fa55559c6d5d)

***2. Каковы основные операции с использованием ссылок?***

  Есть три основных операции с использованием ссылок: присвоение по ссылке, передача по ссылке и возврат по ссылке.

  Читайте [документацию](https://www.php.net/manual/ru/language.references.whatdo.php#:~:text=%D0%95%D1%81%D1%82%D1%8C%20%D1%82%D1%80%D0%B8%20%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D1%8B%D1%85%20%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B8%20%D1%81,%D1%81%D1%81%D1%8B%D0%BB%D0%BA%D0%B5%20%D0%B8%20%D0%B2%D0%BE%D0%B7%D0%B2%D1%80%D0%B0%D1%82%20%D0%BF%D0%BE%20%D1%81%D1%81%D1%8B%D0%BB%D0%BA%D0%B5.)

***3. Назовите простые типы данных, поддерживаемые в РНР.***
   
  У каждого выражения в PHP один из следующих встроенных типов в зависимости от его значения:
  
  - null
  - bool
  - int
  - float (floating-point number)
  - string
  - array
  - object
  - callable
  - resource

  [из документации](https://www.php.net/manual/ru/language.types.intro.php)

***4. Нельзя делать логику в параметрах класса***\
``private $users = User::all()``\
``PHP Fatal error:  Constant expression contains invalid operations``

## References

- [My 10 “Clean” Code Principles](https://www.youtube.com/watch?v=wSDyiEjhp8k)
- [The 3 Laws of Writing Bug Free Code](https://www.youtube.com/watch?v=YMPlQCYp7xg)
- [Code optiomisation](https://www.youtube.com/watch?v=E7_gBwejLLw)
