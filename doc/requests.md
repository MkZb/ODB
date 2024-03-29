# Запити зацікавлених осіб
***
## Зміст

1. [Вступ](https://github.com/MkZb/ODB/blob/master/doc/requests.md#1-%D0%B2%D1%81%D1%82%D1%83%D0%BF)

	1.1 [Цілі](https://github.com/MkZb/ODB/blob/master/doc/requests.md#11--%D1%86%D1%96%D0%BB%D1%96)
	
	1.2 [Контекст](https://github.com/MkZb/ODB/blob/master/doc/requests.md#12-%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%BA%D1%81%D1%82)
	
2. [Короткий огляд продукту](https://github.com/MkZb/ODB/blob/master/doc/requests.md#2-%D0%BA%D0%BE%D1%80%D0%BE%D1%82%D0%BA%D0%B8%D0%B9-%D0%BE%D0%BF%D0%B8%D1%81-%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D1%83)

3. [Сценарії](https://github.com/MkZb/ODB/blob/master/doc/requests.md#3-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D1%97)

	3.1 [Сценарій запрошення експертів](https://github.com/MkZb/ODB/blob/master/doc/requests.md#31-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%88%D0%B5%D0%BD%D0%BD%D1%8F-%D0%B5%D0%BA%D1%81%D0%BF%D0%B5%D1%80%D1%82%D1%96%D0%B2)
	
	3.2 [Сценарій збору результатів](https://github.com/MkZb/ODB/blob/master/doc/requests.md#32-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D0%B7%D0%B1%D0%BE%D1%80%D1%83-%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%96%D0%B2)
	
	3.3 [Сценарій створення опитування](https://github.com/MkZb/ODB/blob/master/doc/requests.md#33-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D1%81%D1%82%D0%B2%D0%BE%D1%80%D0%B5%D0%BD%D0%BD%D1%8F-%D0%BE%D0%BF%D0%B8%D1%82%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F)
	
	3.4 [Сценарій дослідження результатів опитування](https://github.com/MkZb/ODB/blob/master/doc/requests.md#34-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D0%B4%D0%BE%D1%81%D0%BB%D1%96%D0%B4%D0%B6%D0%B5%D0%BD%D0%BD%D1%8F-%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%96%D0%B2-%D0%BE%D0%BF%D0%B8%D1%82%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F)
	
	3.5 [Сценарій корректування результатів](https://github.com/MkZb/ODB/blob/master/doc/requests.md#35-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D0%BA%D0%BE%D1%80%D1%80%D0%B5%D0%BA%D1%82%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F-%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%96%D0%B2)
	
4. [Функціональність](https://github.com/MkZb/ODB/blob/master/doc/requests.md#4-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D1%96%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%96%D1%81%D1%82%D1%8C)

	4.1 [Можливості «Менеджер»](https://github.com/MkZb/ODB/blob/master/doc/requests.md#41-%D0%BC%D0%BE%D0%B6%D0%BB%D0%B8%D0%B2%D0%BE%D1%81%D1%82%D1%96-%D0%BC%D0%B5%D0%BD%D0%B5%D0%B4%D0%B6%D0%B5%D1%80)
	
	4.2 [Можливості «Користувач»](https://github.com/MkZb/ODB/blob/master/doc/requests.md#42-%D0%BC%D0%BE%D0%B6%D0%BB%D0%B8%D0%B2%D0%BE%D1%81%D1%82%D1%96-%D0%BA%D0%BE%D1%80%D0%B8%D1%81%D1%82%D1%83%D0%B2%D0%B0%D1%87)
	
	4.3 [Можливості «Експерт»](https://github.com/MkZb/ODB/blob/master/doc/requests.md#43-%D0%BC%D0%BE%D0%B6%D0%BB%D0%B8%D0%B2%D0%BE%D1%81%D1%82%D1%96-%D0%B5%D0%BA%D1%81%D0%BF%D0%B5%D1%80%D1%82)
	
	4.4 [Можливості «Аналітик»](https://github.com/MkZb/ODB/blob/master/doc/requests.md#44-%D0%BC%D0%BE%D0%B6%D0%BB%D0%B8%D0%B2%D0%BE%D1%81%D1%82%D1%96-%D0%B0%D0%BD%D0%B0%D0%BB%D1%96%D1%82%D0%B8%D0%BA)
	
	4.5 [Можливості «Адміністратор»](https://github.com/MkZb/ODB/blob/master/doc/requests.md#45-%D0%BC%D0%BE%D0%B6%D0%BB%D0%B8%D0%B2%D0%BE%D1%81%D1%82%D1%96-%D0%B0%D0%B4%D0%BC%D1%96%D0%BD%D1%96%D1%81%D1%82%D1%80%D0%B0%D1%82%D0%BE%D1%80)
	
	4.6 [Діаграма функціональності](https://github.com/MkZb/ODB/blob/master/doc/requests.md#46-%D0%B4%D1%96%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%B0-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D1%96%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D1%96)

5. [Практичність](https://github.com/MkZb/ODB/blob/master/doc/requests.md#5-%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%BD%D1%96%D1%81%D1%82%D1%8C)

	5.1 [Стандартизація](https://github.com/MkZb/ODB/blob/master/doc/requests.md#51-%D1%81%D1%82%D0%B0%D0%BD%D0%B4%D0%B0%D1%80%D1%82%D0%B8%D0%B7%D0%B0%D1%86%D1%96%D1%8F)
	
	5.2 [Локалізація](https://github.com/MkZb/ODB/blob/master/doc/requests.md#52-%D0%BB%D0%BE%D0%BA%D0%B0%D0%BB%D1%96%D0%B7%D0%B0%D1%86%D1%96%D1%8F)
	
6. [Надійність](https://github.com/MkZb/ODB/blob/master/doc/requests.md#6-%D0%BD%D0%B0%D0%B4%D1%96%D0%B9%D0%BD%D1%96%D1%81%D1%82%D1%8C)

	6.1. [Роботоздатність системи](https://github.com/MkZb/ODB/blob/master/doc/requests.md#61-%D1%80%D0%BE%D0%B1%D0%BE%D1%82%D0%BE%D0%B7%D0%B4%D0%B0%D1%82%D0%BD%D1%96%D1%81%D1%82%D1%8C-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B8)
  
	6.2. [Резервне копіювання і відновлення даних](https://github.com/MkZb/ODB/blob/master/doc/requests.md#62-%D1%80%D0%B5%D0%B7%D0%B5%D1%80%D0%B2%D0%BD%D0%B5-%D0%BA%D0%BE%D0%BF%D1%96%D1%8E%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F-%D1%96-%D0%B2%D1%96%D0%B4%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%BD%D1%8F-%D0%B4%D0%B0%D0%BD%D0%B8%D1%85)
  
7. [Технічні правила і обмеження](https://github.com/MkZb/ODB/blob/master/doc/requests.md#7-%D1%82%D0%B5%D1%85%D0%BD%D1%96%D1%87%D0%BD%D1%96-%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D0%B0-%D1%96-%D0%BE%D0%B1%D0%BC%D0%B5%D0%B6%D0%B5%D0%BD%D0%BD%D1%8F)

	7.1 [Базове програмне забезпечнення](https://github.com/MkZb/ODB/blob/master/doc/requests.md#71-%D0%B1%D0%B0%D0%B7%D0%BE%D0%B2%D0%B5-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BD%D0%B5-%D0%B7%D0%B0%D0%B1%D0%B5%D0%B7%D0%BF%D0%B5%D1%87%D0%BD%D0%B5%D0%BD%D0%BD%D1%8F)
	
	7.2 [Операційне середовище](https://github.com/MkZb/ODB/blob/master/doc/requests.md#72-%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D1%96%D0%B9%D0%BD%D0%B5-%D1%81%D0%B5%D1%80%D0%B5%D0%B4%D0%BE%D0%B2%D0%B8%D1%89%D0%B5)
	
	7.3 [Конфігурація програмного забепечення](https://github.com/MkZb/ODB/blob/master/doc/requests.md#73-%D0%BA%D0%BE%D0%BD%D1%84%D1%96%D0%B3%D1%83%D1%80%D0%B0%D1%86%D1%96%D1%8F-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE-%D0%B7%D0%B0%D0%B1%D0%B5%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%BD%D1%8F)

8. [Вимоги до комплектації](https://github.com/MkZb/ODB/blob/master/doc/requests.md#8-%D0%B2%D0%B8%D0%BC%D0%BE%D0%B3%D0%B8-%D0%B4%D0%BE-%D0%BA%D0%BE%D0%BC%D0%BB%D0%B5%D0%BA%D1%82%D0%B0%D1%86%D1%96%D1%97)

9. [Вимоги до документації](https://github.com/MkZb/ODB/blob/master/doc/requests.md#9-%D0%B2%D0%B8%D0%BC%D0%BE%D0%B3%D0%B8-%D0%B4%D0%BE-%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D1%96%D1%97)

	9.1 [Загальні положення.](https://github.com/MkZb/ODB/blob/master/doc/requests.md#91-%D0%B7%D0%B0%D0%B3%D0%B0%D0%BB%D1%8C%D0%BD%D1%96-%D0%BF%D0%BE%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%BD%D1%8F)
	
	9.2 [Експертні опитування "PollOchka". Запити зацікавлених осіб.](https://github.com/MkZb/ODB/blob/master/doc/requests.md#92-%D0%B5%D0%BA%D1%81%D0%BF%D0%B5%D1%80%D1%82%D0%BD%D1%96-%D0%BE%D0%BF%D0%B8%D1%82%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F-pollochka-%D0%B7%D0%B0%D0%BF%D0%B8%D1%82%D0%B8-%D0%B7%D0%B0%D1%86%D1%96%D0%BA%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%85-%D0%BE%D1%81%D1%96%D0%B1)

10. [Тривалість проекту](https://github.com/MkZb/ODB/blob/master/doc/requests.md#10-%D1%82%D1%80%D0%B8%D0%B2%D0%B0%D0%BB%D1%96%D1%81%D1%82%D1%8C-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%83)

***
## 1. Вступ

У цьому документі описуються запити зацікавлених осіб, в якості яких виступають представники компанії, по відношенню до проекту "PollOchka".

### 1.1  Цілі

Метою документа є визначення основних вимог до функціональності, продуктивності і експлуатаційної придатності, а також визначення бізнес-правил і технологічних обмежень, що пред'являються до предмету розробки.

### 1.2 Контекст

Перелік вимог, перерахованих в цьому документі, є основою технічного завдання на розробку проекту.

***
## 2. Короткий опис продукту
Проект "PollOchka" дозволяє визначити основні вимоги до функціональності, продуктивності і експлуатаційної придатності нашого проекту. Система представляє собою сайт з опитуваннями спрямованих на покращення проекту. Доступ до системи мають розробники та зацікавлені особи.

***
## 3. Сценарії

У даному розділі описані всі можливі взаємодії учасників у рамках проекту.

### 3.1 [Сценарій запрошення експертів](https://github.com/MkZb/ODB/blob/master/doc/business-usecases/invite.md)
### 3.2 [Сценарій збору результатів](https://github.com/MkZb/ODB/blob/master/doc/business-usecases/collect.md)
### 3.3 [Сценарій створення опитування](https://github.com/MkZb/ODB/blob/master/doc/business-usecases/createpoll.md)
### 3.4 [Сценарій дослідження результатів опитування](https://github.com/MkZb/ODB/blob/master/doc/business-usecases/analyse.md)
### 3.5 [Сценарій корректування результатів](https://github.com/MkZb/ODB/blob/master/doc/business-usecases/correct.md)

***
## 4. Функціональність
Основні вимоги до функціональності, що пред’являються зацікавленими
особами до предмета розробки, відносяться до чотирьох категорій:

- Менеджер
- Користувач  
- Аналітик 
- Експерт
- Адміністратор

###  4.1 Можливості «Менеджер»

- Запрошення експертів.
  
###  4.2 Можливості «Користувач»

- Реєстрація;

- Вхід.

###  4.3 Можливості «Експерт»

- Прийняття участі в опитуваннях.

###  4.4 Можливості «Аналітик»

- Створення опитування;

- Редагування опитування;

- Видалення опитування;

###  4.5 Можливості «Адміністратор»
- Запрошення експертів;

- Створення опитування;

- Редагування опитування;

- Видалення опитування;

- Прийняття участі в опитуваннях;

- Вхід. 

### 4.6 Діаграма функціональності
![Diagram](https://i.imgur.com/if9tHRR.png)

***
## 5. Практичність

### 5.1 Стандартизація

Cистема має підтримуватись всіма браузерами.

### 5.2 Локалізація

Программа повинна мати українську та англійську локалізацію.
***
## 6. Надійність

### 6.1. Роботоздатність системи
Роботоздатність не має порушуватися за відсутності синхронізації, за її ж відсутності має працювати в режимі накопичення інформації.

### 6.2. Резервне копіювання і відновлення даних
Резервне копіювання і відновлення даних має відбуватися незалежно засобами нашого сервісу.

***
## 7. Технічні правила і обмеження

### 7.1 Базове програмне забезпечнення
  1. MySQL/8.0.17

  2. Apache/4.1.6

### 7.2 Операційне середовище

ОС на базі Microsft Windows чи Linux

### 7.3 Конфігурація програмного забепечення

Конфігурація ПЗ на стороні замовника здійснюється розробником на етапі налагодження тільки в тій частині, яка безпосередньо відноситься до предмету розробки.

***
## 8. Вимоги до комлектації

Зацікавленим особам надають інформацію що містить все необхідне для установки і функціонування даного проекту, а також електронні чи друковані версії документації проекту.

***
## 9. Вимоги до документації
Вся документація проекту розроблюється спільно з зацікавленими особами і розробником.

### 9.1 [Загальні положення.](https://github.com/MkZb/ODB/blob/master/doc/documents.md)
Описує терміни та загальні положення, використані в документації.

### 9.2 [Експертні опитування "PollOchka". Запити зацікавлених осіб.](https://github.com/MkZb/ODB/blob/master/doc/requests.md)
Описує загальні вимоги зацікавлених осіб до предмету розробки.

***
## 10. Тривалість проекту

Тривалість проекту без урахування терміну остаточного налагодження програмного забезпечення становить 8 тижнів.
При зміні вимог до предмету розробки, які тягнуть за собою зміну трудомісткості робіт, тривалість проекту може переглядатися за погодженням зацікавлених осіб.
