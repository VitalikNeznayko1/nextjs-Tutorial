# NEXT.JS TUTORIAL
## Part 1

Було створено новий проєкт на Next.js і розглянуто вже заготовлений код.

## Part 2

Було додано стилі до сайту

![Add_Shape](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part2/add_Shape.png)

І тепер він стилізований і на сторінці по завданню треба було відобразити чорний трикутник, що було і зроблено

![shape_on_page](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part2/shape_on_page.png)

## Part 3

Було створено окремий файл з основними шрифтами на сайті і застосовано ці шрифти на сторінку

![addFonts](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part3/addFonts.png)

В результаті вийшло отак

![results](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part3/results.png)

Було додано картинку, яка відображається на більших екранах

![imageforDekstop](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part3/imageforDekstop.png)

І також картинка, яка  відображається на мобільних пристроях з меншим екраном

![addImageForMobile](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part3/addImageForMobile.png)

## Part 4

Було створено 3 нові сторінки, а саме `dashboard`, `dashboard/customers`, `dashboard/invoices`

![CreatePages](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part4/CreatePages.png)

Якщо перейдемо по правильній URL-адресі, можемо побачити, що все правильно відображається

![Pages](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part4/Pages.png)

Далі до сторінки `dashboard` було додано `layout.tsx` і він застосувався до всіх дочірніх сторінок, тобто до `dashboard/customers` і `dashboard/invoices`

![LayoutDashboard](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part4/LayoutDashboard.png)

## Part 5

Було замінено тег `<a>` на тег `<Link>` і тепер URL-адреса може змінюватися без повної перезагрузки сторінки

![Link](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part5/Link.png)

## Part 6
Було задеплоєно проєкт на Vercel

![Vercel_Deploy](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part6/Vercel_Deploy.png)

Потім створили на Vercel нову базу даних, підключили її до проєкту і перевірили чи все працює

![SeedingDB_and_complete_query](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part6/SeedingDB_and_complete_query.png)
І все працює)

## Part 7

Тут змінюємо сторінку `dashboard` тепер вона відображає певну інформацію, яку бере з БД

![FetchDataToDB](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part7/FetchDataToDB.png)

В результаті

![Results](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part7/Results.png)

## Part 8

Додаємо штучну затримку отримання даних з БД. Це дозволяє побачити, що сторінка не відображається, поки всі дані повністю не будуть отримані.

![receiving_data](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part8/receiving_data.png)

## Part 9
Було додано Streaming, щоб розділити сторінку на кілька частин, які рендеряться незалежно одна від одної. Це дозволяє відображати частину контенту одразу, поки інші дані ще завантажуються, щоб користувач не бачив порожню сторінку.

![Streaming](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part9/Streaming.png)

## Part 10

Додано на сторінку `dashboard/invoices` пошук

![Search](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part10/Search.png)

Додано на сторінку `dashboard/invoices` пагінацію

![Pagination](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part10/Pagination.png)
## Part 11
Реалізуємо створення нового запису таблиці

![FuncCreateInvoice](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part11/FuncCreateInvoice.png)

Перевіримо роботу

![CreateInvoice](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part11/CreateInvoice.png)
![CreatedInvoice](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part11/CreatedInvoice.png)

Тепер реалізуємо редагування запису таблиці 

![CreateInvoice](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part11/EditInvoice.png)
![EditedInvoice](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part11/image.png)

Також було реалізовано видалення
## Part 12
Було створено сторінку, яка відображається, коли поточної сторінки не знайдено, тобто при помилці 404

![notFoundPage](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part12/notFoundPage.png)

А також створено сторінку, яка відображається при інших помилках

![errorPage](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part12/errorPage.png)

## Part 13

Додаємо перевірку чи всі поля заповненні при створенні нового запису

![EditedInvoice](https://github.com/VitalikNeznayko1/nextjs-Tutorial/blob/master/public/screenshots/part13/requiredField.png)

## Part 14
## Part 15
