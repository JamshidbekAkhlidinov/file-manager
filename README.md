
## Talablar

- PHP 5.5.0 yoki undan yuqori.
- Fileinfo, iconv, zip, tar va mbstring kengaytmalari tavsiya etiladi.

## Qanday ishlatish mumkun

Default username/password: **admin/admin@123** and **user/12345**.


### :loudspeaker: Xususiyatlari

- :cd: Ochiq manba, yengil va juda oddiy
- :iphone: Touch qurilmalar uchun mobil qulay ko'rinish
- :information_source: Yaratish, o'chirish, o'zgartirish, ko'rish, yuklab olish, nusxalash va ko'chirish kabi asosiy funktsiyalar
- :arrow_double_up: Ajax yuklash, burish imkoniyati, URL manzilidan yuklash, fayl kengaytmalari filtrlash bilan bir nechta fayllarni yuklash imkoniyati
- :file_folder: Papka va fayllarni yaratish imkoniyati
- :gift: Fayllarni bzip, tar formatlari bo'yicha bzip qilish va chiqarish imkoniyati
- :sunglasses: Foydalanuvchi ruxsatlari - sessiyaga asoslangan va har bir foydalanuvchi bosh papka taqsimoti asosida
- :floppy_disk: To'g'ri fayl URL'sini nusxalash
- :pencil2: Cloud9 IDE - `150+` tillar uchun sintaksis belgilash, Sizning sevimli dasturlash usulingiz bilan `35+` mavzular
- :page_facing_up: Google/Microsoft hujjat ko'rinishchisi PDF/DOC/XLS/PPT/h.k. ko'rishga yordam beradi. 25 MB Google Drive ko'rinishchisi bilan ko'rsatilishi mumkin
- :zap: Fayllarni ehtiyotlashtirish va IP qora va oq ro'yxatlari
- :mag_right: Qidiruv - Datatable js yordamida fayllarni qidirish va filtrlash
- :file_folder: Ro'yxatdan chiqarish uchun papka va fayllarni ehtiyot qilish imkoniyati
- :globe_with_meridians: Ko'plab tillarni (32+) qo'llab-quvvatlash va tarjimalar uchun `translation.json` fayli talab qilinadi
- :bangbang: Boshqa ko'plab imkoniyatlar...


Origin:

```php
// Root path for file manager
// use absolute path of directory i.e: '/var/www/folder' or $_SERVER['DOCUMENT_ROOT'].'/folder'
$root_path = $_SERVER['DOCUMENT_ROOT'];

// Root url for links in file manager.Relative to $http_host. Variants: '', 'path/to/subfolder'
// Will not working if $root_path will be outside of server document root
$root_url = '';
```

Modified:

```php
// Root path for file manager
// use absolute path of directory i.e: '/var/www/folder' or $_SERVER['DOCUMENT_ROOT'].'/folder'
$root_path = $_SERVER['DOCUMENT_ROOT'].'/data';

// Root url for links in file manager.Relative to $http_host. Variants: '', 'path/to/subfolder'
// Will not working if $root_path will be outside of server document root
$root_url = 'data/';
```