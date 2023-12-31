---
title: "Ob'ektga yo'naltirilgan dasturlash"
datePublished: Mon Nov 20 2023 18:28:25 GMT+0000 (Coordinated Universal Time)
cuid: clp78pqip00030al40j3zfkha
slug: obektga-yonaltirilgan-dasturlash

---


### Ob'ektga yo'naltirilgan dasturlash nima?
> Ob'ektga yo'naltirilgan dasturlash (OOP) - bu kompyuter dasturlash modeli bo'lib, u funktsiyalar va mantiq emas, balki ma'lumotlar yoki ob'ektlar atrofida dasturiy ta'minot dizaynini tashkil qiladi. Ob'ektni noyob atributlar va metodlarga ega bo'lgan ma'lumotlar maydoni orqali aniqlash mumkin.

> OOP asosiy e'tiborni ishlab chiquvchilar ularni manipulyatsiya qilish uchun zarur bo'lgan mantiqqa emas, balki boshqarmoqchi bo'lgan ob'ektlarga qaratadi. Dasturlashning bunday yondashuvi katta, murakkab va faol yangilanadigan yoki saqlanuvchi dasturlar uchun juda mos keladi. Bunga ishlab chiqarish va dizayn dasturlari, shuningdek, mobil ilovalar kiradi; masalan, OOP tizimi simulyatsiya dasturlarini ishlab chiqarish uchun ishlatilishi mumkin.

> Ob'ektga yo'naltirilgan dasturni tashkil etish, shuningdek, loyihalarni guruhlarga bo'lingan holda hamkorlikda ishlab chiqish uchun foydali bo'ladi. OOP ning qo'shimcha afzalliklariga kodning qayta ishlatilishi, kengaytirilishi va samaradorligi kiradi.

### Ob'ektga yo'naltirilgan dasturlashning tuzilishi qanday?
**Ob'ektga yo'naltirilgan dasturlashning tuzilishi yoki qurilish bloklari quyidagilarni o'z ichiga oladi:**
- Sinflar - bu foydalanuvchi tomonidan belgilangan ma'lumotlar turlari bo'lib, ular alohida ob'ektlar, atributlar va usullar uchun loyiha sifatida ishlaydi.
- Ob'ektlar - bu maxsus belgilangan ma'lumotlar bilan yaratilgan sinf namunalari. Ob'ektlar real dunyo ob'ektlariga yoki mavhum ob'ektga mos kelishi mumkin.
- Metodlar - bu ob'ektning xatti-harakatlarini tavsiflovchi sinf ichida belgilangan funktsiyalar. 
- Atributlar sinf shablonida aniqlanadi va ob'ekt holatini ifodalaydi. Ob'ektlar atributlar maydonida saqlanadigan ma'lumotlarga ega bo'ladi. Sinf atributlari sinfning o'ziga tegishlidir.

### OOP ning asosiy tamoyillari qanday?
** Ob'ektga yo'naltirilgan dasturlash quyidagi printsiplarga asoslanadi:**
- Inkapsulyatsiya. Ushbu printsip barcha muhim ma'lumotlar ob'ekt ichida joylashganligini va faqat tanlangan ma'lumotlarning ochiqligini bildiradi. Har bir ob'ektning amalga oshirilishi va holati ma'lum bir sinf ichida shaxsiy saqlanadi. Boshqa ob'ektlar ushbu sinfga kirish huquqiga yoki o'zgartirishlar kiritish huquqiga ega emas. Ular faqat mavjud funktsiyalari yoki usullari ro'yxatini chaqirishlari mumkin. Ma'lumotlarni yashirishning bu xususiyati dastur xavfsizligini ta'minlaydi va ma'lumotlarning noto'g'ri buzilishining oldini oladi.
- Abstraktsiya. Abstraktsiya yordamida biz kodimizning ichki tuzilishini yashiramiz. Ya’ni, tashqaridan qaraganda obyektimiz 2 ta parameter va 2 ta metoddan iborat bo’lishi mumkin, lekin obyekt to’g’ri ishlashi uchun uning ichida o’nlab boshqa o’zgaruvchilar va funksiyalar yashirin bo’ladi. 
Klassdan foydalanishda esa uning ichki tuzilishi va qanday ishlashini bilish talab qilinmaydi. Bu o’zimizga ham boshqa dasturchilarga ham bu klassdan foydalanishda qulayliklar yaratadi
- Meros olish. Sinflar boshqa sinflardagi kodlarni qayta ishlatishi mumkin. Ob'ektlar o'rtasidagi munosabatlar va kichik sinflar tayinlanishi mumkin, bu esa ishlab chiquvchilarga yagona ierarxiyani saqlab qolgan holda umumiy mantiqni qayta ishlatishga imkon beradi. OOP ning bu xususiyati ma'lumotlarni chuqurroq tahlil qilishga majbur qiladi, ishlab chiqish vaqtini qisqartiradi va yuqori darajadagi aniqlikni ta'minlaydi.
- Polimorfizm. Ob'ektlar metodlarni almashish uchun mo'ljallangan va ular bir nechta shaklga ega bo'lishi mumkin. Dastur ota-sinfdan ushbu ob'ektning har bir  metodlarni oladi va kodni takrorlash zaruratini kamaytiradi. Keyin ota-sinfning funksionalligini kengaytiradigan bolalar sinfi yaratiladi. Polimorfizm har xil turdagi ob'ektlarning bir xil interfeys orqali o'tishiga imkon beradi.

### Ob'ektga yo'naltirilgan dasturlash tillariga qanday misollar keltiriladi?
**Masalan, mashhur sof OOP tillariga quyidagilar kiradi:**
- Ruby
- Scala

**Asosan OOP uchun moʻljallangan dasturlash tillariga quyidagilar kiradi:**
- Java
- Python
- C++

**OOP bilan bog'langan boshqa dasturlash tillariga quyidagilar kiradi:**
- Visual Basic .NET
- PHP
- JavaScript

### OOP ning qanday afzalliklari bor?
**OOPning afzalliklari quyidagilardan iborat:**
- Modullilik. Inkapsulyatsiya ob'ektlarni o'z-o'zidan saqlashga imkon beradi, bu esa muammolarni bartaraf etish va hamkorlikda ishlab chiqishni osonlashtiradi.
- Qayta foydalanish imkoniyati. Kod meros orqali qayta ishlatilishi mumkin, ya'ni jamoa bir xil kodni bir necha marta yozishi shart emas.
- Hosildorlik. Dasturchilar bir nechta kutubxonalar va qayta foydalanish mumkin bo'lgan kodlar yordamida yangi dasturlarni tezroq qurishlari mumkin.
- Osonlik bilan yangilanadigan va kengaytirilishi mumkin. Dasturchilar tizim funksiyalarini mustaqil ravishda amalga oshirishlari mumkin.
- Interfeys tavsiflari. Ob'ektlar bilan aloqa qilish uchun ishlatiladigan xabarlarni uzatish metodlari tufayli tashqi tizimlarning tavsiflari oddiy.
- Xavfsizlik. Inkapsulyatsiya va abstraktsiyadan foydalanib, murakkab kod yashiringan, dasturiy ta'minotga texnik xizmat ko'rsatish osonroq va internet protokollari himoyalangan.
- Moslashuvchanlik. Polimorfizm bitta funktsiyaga u joylashgan sinfga moslashish imkonini beradi. Turli ob'ektlar ham bir xil interfeys orqali o'tishi mumkin.

### OOPni tanqid qilish!
> Ob'ektga yo'naltirilgan dasturlash modeli ishlab chiquvchilar tomonidan bir necha sabablarga ko'ra tanqid qilingan. Eng katta tashvish shundaki, OOP dasturiy ta'minotni ishlab chiqishning ma'lumotlar komponentiga ortiqcha urg'u beradi va hisoblash yoki algoritmlarga etarlicha e'tibor bermaydi. Bundan tashqari, OOP kodini yozish ancha murakkab va kompilyatsiya qilish ko'proq vaqt talab qilishi mumkin.

**OOPning muqobil usullari quyidagilardan iborat:**
- Funktsional dasturlash.
- Strukturaviy yoki modulli dasturlash. Bunga PHP va C# kabi tillar kiradi.

> Ko'pgina ilg'or dasturlash tillari ishlab chiquvchilarga modellarni birlashtirishga imkon beradi, chunki ular turli xil dasturlash usullari uchun ishlatilishi mumkin. Masalan, JavaScript-dan OOP va funktsional dasturlash uchun foydalanish mumkin.

**OOP va mikroservislar bilan ishlaydigan dasturchilar OOP tamoyillarini qo'llash orqali mikroservislarning umumiy muammolarini hal qilishlari mumkin.**

### 🎁  [Ingliz tilini biladiganlar uchun!](https://shakhzodtojiyev.blogspot.com/2023/03/python-oops-concepts.html)
### 🚀 [GitHub orqali ko'proq misollarni ko'ring!](https://github.com/Vite-Academy/OOP)
