# BOUNCE BACK - 2.5D Dino Runner

## O'yin haqida (Description)
"Bounce Back" - bu mashhur Google Chrome Dino o'yinining 3D modellar va zamonaviy grafika bilan boyitilgan 2.5D formatidagi dinamik runner o'yini. 

O'yinda siz dinozavrni boshqarasiz: yo'ldagi toshlar va uchuvchi to'siqlardan sakrab o'tasiz, havoda ikkinchi marta sakrash (Bounce Back) qobiliyatidan foydalanasiz, osmonda suzib yurgan oltin yulduzchalarni terib qo'shimcha ballar to'playsiz hamda maxsus trampolinlar (Bounce Pad) yordamida balandlikka uchasiz.

O'yin uzoq vaqt o'ynaganda ko'z charchamasligi uchun maxsus qorong'u (Dark Mode) va sokin ranglar palitrasida yaratilgan.

---

## Asosiy Imkoniyatlar va Qulayliklar

1. Ko'z uchun qulay Dark Mode (Qorong'u rejim):
   - Charchatmaydigan quyuq fon, sokin shom va tun manzaralari.
   - Har 100 ball to'planganda yangi biom (manzara) ochiladi.
   - Har 300 ball to'planganda shom va chuqur tun rejimlari almashadi.

2. Tezlikni sozlash (Speed Setting):
   - Yuqoridagi menyudan (NavBar) istalgan vaqtda o'yin tezligini o'zgartirish mumkin:
     * 0.5x - Sokin va o'rganish uchun oson rejim
     * 1.0x - Standart o'yin tezligi
     * 1.5x - Tezkor va chaqqon o'yinchilar uchun qiyin rejim

3. Oltin Yulduzchalar va Ball Tizimi:
   - Osmonda aylanib turuvchi yulduzchalarni sakrab ilib olganda +50 ball beriladi.
   - Yig'ilgan yulduzlar va ballar yuqoridagi Navbar'da real vaqtda ko'rinib turadi.

4. Dinoning qulay joylashuvi:
   - Dinozavr ekranning chekkasiga qisilib qolmasligi uchun oldinroqqa surilgan. Bu oldindagi to'siqlarni o'z vaqtida ko'rish va sakrashni osonlashtiradi.

5. Real 3D Modellar:
   - Haqiqiy 3D tosh to'siqlar (kichik tosh va qoyatosh).
   - Qanot qoqib uchuvchi pterodaktillar.
   - Balandga otuvchi neon trampolin (Bounce Pad).

---

## Boshqaruv Tugmalari

- Sakrash (Jump):
  * Bo'sh joy (SPACE)
  * W tugmasi
  * Yuqoriga strelka (UP ARROW)
  * Sichqonchaning chap tugmasi

- Havoda ikkinchi marta sakrash (Bounce Back):
  * Havoda turganda yana bir bor SPACE tugmasini bosing

- Tez pastga sho'ng'ish (Dive):
  * S tugmasi
  * Pastga strelka (DOWN ARROW)

- Tezlikni o'zgartirish:
  * Ekranning yuqorisidagi 0.5x, 1.0x, 1.5x tugmalarini bosing

---

## O'yinni Ishga Tushirish

O'yinni 2 xil usulda o'ynash mumkin:

1. Brauzerda (Oddiy va Tez):
   - Loyiha papkasidagi "index.html" faylini ikki marta bosing.
   - O'yin har qanday zamonaviy brauzerda (Chrome, Edge, Firefox, Opera) to'g'ridan-to'g'ri ochiladi.
   - Internet talab qilinmaydi (barcha 3D modellar va ovozlar offline rejimda ishlaydi).

2. Godot Engine'da:
   - Godot dasturini oching.
   - "bounce-back" papkasini tanlang va "Edit" tugmasini bosing.
   - Yuqori o'ng burchakdagi "Play" (yoki klaviaturada F5) tugmasini bosing.
