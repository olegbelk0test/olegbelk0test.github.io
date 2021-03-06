# Інструкція оператора контакт-центру

Ця інструкція призначена для операторів контакт-центру та показує, як обробляти Вхідні.  
Вхідні &mdash; це повідомлення від клієнтів, які потрібно реєструвати у системі.

## Екран Вхідних
Оператор працює з системою на **Екрані Вхідних**. Він автоматично відкривається після [входу у систему](../login_logout.md). Якщо цього не відбулося, або ви знаходитесь на іншому екрані &mdash; відкрийте Екран Вхідних, натиснувши на правій панелі кнопку ![](incoming_btn.png):  
![картинка єкрана входящих](incoming_list.png)  

На екрані представлено список Вхідних з короткою інформацією про кожне Вхідне (номер, статус, присутніть прив'язаних об'єктів ![](link_list.png) та додатків ![](add_file.png), ким і коли створено, опис, адреса, контакт).

Можливості оператора:
1. Перегляд Вхідного ![](incoming_view_1.png) 
2. Редагування Вхідного ![](incoming_edit_1.png)
3. [Створення Вхідного](#створення-вхідного)
4. [Пошук та фільтрація Вхідних](#сортування-та-фільтри)
5. ...

|                                                |
|------------------------------------------------|
| [Наверх](#інструкція-оператора-контакт-центру) |
___

## Створення Вхідного 

Вхідні можуть надходити до оператора 3-мя різними способами:
 >
 >* Телефонний дзвінок
 >* Звернення з мобільного додатка
 >* Зворотній зв'язок (e-mail)

 Оператор реєструє вхідне у системі за допомогою  інтерфейсу створення Вхідного.

 Незалежно від способу надхождення, натиснувши кнопку ![](incoming_create_btn.png) зліва зверху Екрана Вхідних, оператор потрапляє до **Екрану створення Вхідного**:

![](incoming_create.png)

Вхідному при створенні присвоєються унікальний ID-номер ()

Щоб створити Вхідне, заповніть обов'язкові поля:  
1. Додайте контакт клієнта ():
    * Натисніть () <img src="select_contact_btn.png">
    * Виберіть або додайте новий контакт у бічному меню: <img src="select_contact.png" width="500">
    * Оберіть потрібний контакт, натиснувши ![](checkbox.png)  
<br/>   
2. Додайте адресу, за якою звертається клієнт ():
    * Натисніть () <img src="select_address_btn.png"> 
    * Виберіть або знайдіть адресу у бічному меню:  <img src="select_address.png" width="500">
    * Оберіть потрібну адресу, натиснувши ![](checkbox.png)
<br/>

3. Введіть причину зверення клієнта у поле ()  
4. Натисніть () <img src="save_user.png" width="100"> 
<br/>

    >Якщо Клієнт та/або Адреса існують у системі &mdash; зліва на Екрані створення Вхідного покажуться прив'язані до них заявки та звернення. 
    Ви можете детально подивитися всі заявки по клієнту або адресі, та при необхідності додати їх до Вхідного, натиснувши ![](link.png):
    ![](incoming_add_inc.png)

|                                                |
|------------------------------------------------|
| [Наверх](#інструкція-оператора-контакт-центру) |
___

### Додаткові дії при створенні Вхідного 

- [Створення Заявки з Вхідного](#створення-заявки-з-вхідного)
- [Коментарі](#коментарі)
- [Історія Вхідного](#історія-вхідного)
- [Робота з додатками](#робота-з-додатками)
- [Вимогливий клієнт](#вимогливий-клієнт)
- [Додаткова інформація](#додаткова-інформація)
- [Питання вирішено](#питання-вирішено)
- [Назад](#назад)

###### Створення Заявки з Вхідного
При створенні Вхідного ви можете створити Заявку, яка далі піде на обробку Диспетчером. Для цього натисніть ![](incoming_add_request.png),щоб відкрився Екран створення Заявки:
![](incoming_add_request_form.png)
Поля "Опис", "Додатки", "Клієнт" та "Адреса" автоматично переносятся з Вхідного. При необхідності ви можете їх змінити. 

<details>
<summary>Редагування адреси при створенні Заявки з Вхідного</summary>

Для змінення адреси в режимі створення Вхідного натисніть "Обрати іншу адресу":
![](incoming_create_address.png)
Виберіть адресу зі списку або за допомогою пошуку. 
Якщо адреси клієнта не існує &mdash; додайте ії, натиснувши ![](incoming_add_address.png):
![](incoming_create_add_address.png)
>Якщо адреса клієнта не обслуговується &mdash; ви побачите відповідне повідомлення. Заявка автоматично стане платною, і поставиться відповідна галочка:
![](inc_req_paid.png)
⚠️ Обов'язково сповістіть клієнта про те, що його заявка стала платною
</details>

</br>
  
1. Оберіть відповідний опису Тип Робіт та визначте пріоритет Заявці
>⚠️ Якщо ви поставите галочку ![](inc_req_crush.png) &mdash; автоматично виставиться Високий пріоритет
Далі ці приоритети може змінити Диспетчер
2. Додайте контактний телефон, за яким можна зв'язатися к клієнтом
3. Натисніть ![](add_request.png) для збереження змін. Заявка автоматично прикріпиться до Вхідного:
![](incoming_request_add.png)
Або відмініть створення, натиснувши ![](incoming_add_request_cancel.png)

###### Коментарі
Ви можете додавати та переглядати коментарі до Вхідного, наприклад, додаткову інформацію про клієнта:
![](incoming_comments.png)

###### Історія Вхідного
Внизу сторінки Вхідного в режимі перегляду ви бачите повну історію роботи з ним:
![](incoming_history.png)

###### Робота з додатками  
![](incoming_add_files.png)
Ви можете завантажити додаток (1) до Вхідного &mdash;  прикріпити будь-яку додаткову інформацію, як текстові документи, таблиці, зображення чи інші файли, які стосуються звернення клієнта.
Також ви можете переглянути (2) або видалити (3) вже існуючі додатки з Вхідного.

###### Вимогливий клієнт
<img src="incoming_fuck.png" width="150"> &mdash; поставте цю галочку, якщо кліент поводиться зухвало або підвищує голос (?)

###### Додаткова інформація
 Якщо звернення клієнта потребує додаткової інформації (наприклад, його треба перенаправити до іншої служби), на Екрані створення Вхідного присутній телефонний довідник з телефонами та адресами аварійних служб міста, який ви можете відкрити кнопкою (9) ![](add_info.png).    

###### Питання вирішено
 Якщо протягом дзвінка питання було вирішено &mdash; переведіть Вхідне у закритий статус кнопкою () ![](problem_solved.png)
   
###### Назад
Щоб повернутися до Екрану Вхідних без збереження змін, натисніть () ![](back_btn.png)

|                                                |
|------------------------------------------------|
| [Наверх](#інструкція-оператора-контакт-центру) |
___

## Сортування та фільтри 
Ви можете сортувати вхідні по типам, шукати по номеру Вхідного або телефону клієнта та застосовувати фільтри ![](filter.png)

Фільтри бувають трьох типів:
>
>* *за адресою* &mdash; сортування по місту, вулиці, номеру будинку та квартирі
>* *за атрибутами* &mdash; сортування по типу Вхідного, статусу, типу робіт та підрозділом
>* *за датою* &mdash; сортування по даті створення та даті закриття

Після вибору необхідних параметрів фільтрів натисніть <img src="filter_apply.png" width="250"> для перегляду вхідних, які відповідають обраним параметрам
Натисніть ![](filter_clear.png), щоб очистити всі фільтри
Натисніть ![](filter_openall.png), щоб розкрити або сховати всі типи фільтрів

|                                                | |
|------------------------------------------------|-|
| [Наверх](#інструкція-оператора-контакт-центру) | [До змісту](ToC.md) |
___