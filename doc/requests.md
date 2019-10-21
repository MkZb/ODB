# Запити зацікавлених осіб
***
## Зміст

1. [Вступ](https://github.com/MkZb/ODB/blob/master/doc/requests.md#1-%D0%B2%D1%81%D1%82%D1%83%D0%BF)

	1.1 [Цілі](https://github.com/MkZb/ODB/blob/master/doc/requests.md#11--%D1%86%D1%96%D0%BB%D1%96)
	
	1.2 [Контекст](https://github.com/MkZb/ODB/blob/master/doc/requests.md#12-%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%BA%D1%81%D1%82)
	
2. [Короткий огляд продукту](https://github.com/MkZb/ODB/blob/master/doc/requests.md#2-%D0%BA%D0%BE%D1%80%D0%BE%D1%82%D0%BA%D0%B8%D0%B9-%D0%BE%D0%BF%D0%B8%D1%81-%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D1%83)

3. [Сценарії](https://github.com/MkZb/ODB/blob/master/doc/requests.md#3-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D1%97)

	3.1 [Сценарій реєстрації нового користувача](https://github.com/MkZb/ODB/blob/master/doc/requests.md#31-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D1%80%D0%B5%D1%94%D1%81%D1%82%D1%80%D0%B0%D1%86%D1%96%D1%97-%D0%BD%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE-%D0%BA%D0%BE%D1%80%D0%B8%D1%81%D1%82%D1%83%D0%B2%D0%B0%D1%87%D0%B0)
	
	3.2 [Сценарій входу користувача](https://github.com/MkZb/ODB/blob/master/doc/requests.md#33-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D0%B2%D1%85%D0%BE%D0%B4%D1%83-%D0%BA%D0%BE%D1%80%D0%B8%D1%81%D1%82%D1%83%D0%B2%D0%B0%D1%87%D0%B0)
	
	3.3 [Сценарій аутентифікації нового користувача](https://github.com/MkZb/ODB/blob/master/doc/requests.md#32-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D0%B0%D1%83%D1%82%D0%B5%D0%BD%D1%82%D0%B8%D1%84%D1%96%D0%BA%D0%B0%D1%86%D1%96%D1%97-%D0%BD%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE-%D0%BA%D0%BE%D1%80%D0%B8%D1%81%D1%82%D1%83%D0%B2%D0%B0%D1%87%D0%B0)
	
	3.4 [Сценарій створення нового опитування](https://github.com/MkZb/ODB/blob/master/doc/requests.md#34-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D1%81%D1%82%D0%B2%D0%BE%D1%80%D0%B5%D0%BD%D0%BD%D1%8F-%D0%BD%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE-%D0%BE%D0%BF%D0%B8%D1%82%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F)
	
	3.5 [Сценарій участі в опитуванні](https://github.com/MkZb/ODB/blob/master/doc/requests.md#35-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D1%83%D1%87%D0%B0%D1%81%D1%82%D1%96-%D0%B2-%D0%BE%D0%BF%D0%B8%D1%82%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%96)
	
	3.6 [Сценарій редагування існуючого опитування](https://github.com/MkZb/ODB/blob/master/doc/requests.md#36-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D1%80%D0%B5%D0%B4%D0%B0%D0%B3%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F-%D1%96%D1%81%D0%BD%D1%83%D1%8E%D1%87%D0%BE%D0%B3%D0%BE-%D0%BE%D0%BF%D0%B8%D1%82%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F)
	
	3.7 [Сценарій видалення існуючого опитування](https://github.com/MkZb/ODB/blob/master/doc/requests.md#37-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D0%B9-%D0%B2%D0%B8%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%BD%D1%8F-%D1%96%D1%81%D0%BD%D1%83%D1%8E%D1%87%D0%BE%D0%B3%D0%BE-%D0%BE%D0%BF%D0%B8%D1%82%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F)
	
	3.8 [Сценарій запрошення користувача для участі в опитуванні](https://github.com/MkZb/ODB/blob/master/doc/usecases/sending_invitation.md#%D0%B7%D0%B0%D0%B3%D0%B0%D0%BB%D1%8C%D0%BD%D0%B8%D0%B9-%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D1%96%D1%97%D0%B2)
	
4. [Функціональність](https://github.com/MkZb/ODB/blob/master/doc/requests.md#4-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D1%96%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%96%D1%81%D1%82%D1%8C)

	4.1 [Система](https://github.com/MkZb/ODB/blob/master/doc/requests.md#41-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0)
	
	4.2 [Користувач](https://github.com/MkZb/ODB/blob/master/doc/requests.md#42-%D0%BA%D0%BE%D1%80%D0%B8%D1%81%D1%82%D1%83%D0%B2%D0%B0%D1%87)

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

### 3.1 [Сценарій реєстрації нового користувача](https://github.com/MkZb/ODB/blob/master/doc/usecases/registration.md)
### 3.2 [Сценарій входу користувача](https://github.com/MkZb/ODB/blob/master/doc/usecases/login.md)
### 3.3 [Сценарій аутентифікації нового користувача](https://github.com/MkZb/ODB/blob/master/doc/usecases/authentification.md)
### 3.4 [Сценарій створення нового опитування](https://github.com/MkZb/ODB/blob/master/doc/usecases/pollcreation.md)
### 3.5 [Сценарій участі в опитуванні](https://github.com/MkZb/ODB/blob/master/doc/usecases/pollanswering.md)
### 3.6 [Сценарій редагування існуючого опитування](https://github.com/MkZb/ODB/blob/master/doc/usecases/pollediting.md)
### 3.7 [Сценарій видалення існуючого опитування](https://github.com/MkZb/ODB/blob/master/doc/usecases/polldeletion.md)

***
## 4. Функціональність

###  4.1 Система
   - Пропонує користувачу ввести логін та пароль для реєстрації.
   - Перевіряє правильність наповнення змісту опитування.
   - Створює опитування.
  
###  4.2 Користувач

   - Може зареєструватися для подальшого користування сайтом.
   - Може обрати опитування("Мозговий штурм", опитування для компаній, статистичне опитування). та пройти його.
   - Може перервати  опитування щоб продовжити його пізніше.
   - Може продовжити незакінчене опитування.
   - Може змінити розкладку з англійської на українську і навпаки.

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
