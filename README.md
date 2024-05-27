# linux commend (دستورات لینوکس)
### 1.ls
Display the list of folders and files (نمایش لیست پوشه و فایل ها)
```ruby
ls
```

نمایش بر اساس زمان ایجاد فایل و پوشه.
```ls -t```
نمایش تمام پوشه و فایل های مخفی و قابل نمایش.
```ls -a```
نمایش فایل و دایرکتوری با اطلاعات بیشتر.
```ls -l```
استفاده ترکیبی.
```ls -l -t -a ```
استفاده ترتیبی.
```ls -lta```

---
### cd
رفتن به لوکیشن مورد نظر در ترمینال.
```
cd <name location switch>
```
اسلش برای ادرس دهی و فاصله ان اختن بین پوشه ها
```cd name-directory/name-directory```
برگشت به پوشه قبلی.
```
cd ..
```

---
#### clear
پاک کردن ترمینال.
```
clear
```
مخفی کردن داده ها در ترمینال.
```ctrl``` + ```l```

---
#### exit
خروج از ترمینال.
```
exit
```

---
#### mkdir
ساخت پوشه.
```
mkdir <name-directory>
```
ساخت چند پوشه.
```mkdir <name-directory> <name-directory>```

---
#### touch
ساخت فایل.
```
touch <name-file>
```

---
#### cat
چاپ تمام داده های یک فایل در ترمینال.
```
cat <name-file>
```

---
#### nano
باز کردن فایل در ادیتور ترمینال.
```
nano <name-file>
```

سیو تغیرات.
```ctrl``` + ```o```
خروج از ادیتور.
```ctrl``` + ```x```

---
#### pwd
نمایش لوکیشن ما در ترمینال.
```
pwd
```

---
#### rm
حذف فایل.
```
rm <name-file>
```
حذف پوشه خالی.
```
mkdir <name-directory>
```
حذف پوشه پر و خالی.
```
rm -r <name-directort>
```

---
#### ln
لینک یه فایل به یک فایل جدید ایجاد شده به نام دلخواه.
```
ln <name-file> <name-file>
```

---
#### man
ننایش اطلاعات دستورات لینوکس.
```
man ls
```
```
man cd
```
```
man man
```

---
#### cp
کپی یک فایل از یک لوکیشن به یک لوکیشن دیگر.
```
cp <location-file>/<name-file> <location-file>
```

---
#### mv
انتقال فایل به لوکیشن دیگر.
```
cp <location-file>/<name-file> <location-file>
```

---
#### locate
نمتیش لوکیشن یک فایل.
```
locate <name-file>
```

---
#### history
نمایش هیستوری کامند های استفاده شده.
```
history
```

---
#### find
پیدا کردن فایل در هر مکانی از حافظه.
```
find -name `<name-file>`
```

---
#### file bash
فایا هایی اجرایی هستن که دستورات نوشته شده درون انها در ترمینال اجرا میشوند.
ساخت فایل bash با پسوند .sh در ترمینال.
```
touch <name-file>.sh
```
دسترسی به فایل bash برای اجرا.
```
sudo chmod +x <file-name>.sh
```
اجرای فایل bash.
```
./<file-name>.sh
```

---
#### commend for bash in file
اضافه کردن مفسر bash به فایل.
```
!/bin/bash
```
نکته: در برخی از نسخه های لینچکس لازم می باشد.

---






