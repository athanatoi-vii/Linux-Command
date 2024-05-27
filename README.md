# linux commend (دستورات لینوکس)
### 1. ls
Display the list of folders and files (نمایش لیست پوشه و فایل ها)
```ruby
ls
```

```ls -t``` Display based on file and folder creation time (نمایش بر اساس زمان ایجاد فایل و پوشه)

```ls -a``` Show file and directory with more information (نمایش تمام پوشه و فایل های مخفی و قابل نمایش)

```ls -l``` Show file and directory with more information (نمایش فایل و دایرکتوری با اطلاعات بیشتر)

```ls -l -t -a ``` Sequential use (استفاده ترتیبی)

```ls -lta``` Combined use (استفاده ترکیبی)

---
### 2. cd
Go to the desired location in the terminal (رفتن به لوکیشن مورد نظر در ترمینال)
```ruby
cd <name location switch>
```

Back to the previous folder (برگشت به پوشه قبلی)
```ruby
cd ..
```

```cd name-directory/name-directory``` Slash for addressing and spacing between folders (اسلش برای ادرس دهی و فاصله ان اختن بین پوشه ها)

---
### 3. clear
Clear the terminal (پاک کردن ترمینال)
```ruby
clear
```

```ctrl``` + ```l``` Hiding data in the terminal (مخفی کردن داده ها در ترمینال)

---
### 4. exit
Rouge from the terminal (خروج از ترمینال)
```ruby
exit
```

---
### 5. mkdir
Create a folder (ساخت پوشه)
```ruby
mkdir <name-directory>
```

```mkdir <name-directory> <name-directory>``` Create multiple folders (ساخت چند پوشه)

---
### 6. touch
Create file (ساخت فایل)
```ruby
touch <name-file>
```

---
### 7.  cat
Print all the data of a file in the terminal (چاپ تمام داده های یک فایل در ترمینال)
```ruby
cat <name-file>
```

---
### 8. nano
Open the file in the terminal editor (باز کردن فایل در ادیتور ترمینال)
```ruby
nano <name-file>
```

```ctrl``` + ```o``` Save changes (سیو تغیرات)
```ctrl``` + ```x``` Exit the editor (خروج از ادیتور)

---
### 9. pwd
Show our location in the terminal (نمایش لوکیشن ما در ترمینال)
```ruby
pwd
```

---
### 11. rm
Delete the file (حذف فایل)
```ruby
rm <name-file>
```

Delete the empty folder (حذف پوشه خالی)
```ruby
mkdir <name-directory>
```

Delete full and empty folder (حذف پوشه پر و خالی)
```ruby
rm -r <name-directort>
```

---
### 12. ln
Link a file to a new file created with the desired name (لینک یه فایل به یک فایل جدید ایجاد شده به نام دلخواه)
```ruby
ln <name-file> <name-file>
```

---
### 13. man
Display information about Linux commands (ننایش اطلاعات دستورات لینوکس)
```ruby
man ls
```
```ruby
man cd
```
```ruby
man man
```

---
#### 14. cp
Copy a file from one location to another location (کپی یک فایل از یک لوکیشن به یک لوکیشن دیگر)
```ruby
cp <location-file>/<name-file> <location-file>
```

---
### 15. mv
Transfer the file to another location (انتقال فایل به لوکیشن دیگر)
```ruby
cp <location-file>/<name-file> <location-file>
```

---
### 16. locate
Show the location of a file (نمایش لوکیشن یک فایل)
```ruby
locate <name-file>
```

---
### 17. history
Display the history of used commands (نمایش هیستوری کامند های استفاده شده)
```ruby
history
```

---
### 18. find
Find files anywhere in memory (پیدا کردن فایل در هر مکانی از حافظه)
```ruby
find -name `<name-file>`
```

---
### 19. file bash
There are executable files in which the commands written in them are executed in the terminal (فایل هایی اجرایی هستن که دستورات نوشته شده درون انها در ترمینال اجرا میشوند)

Create bash file with .sh extension in terminal (در ترمینال .sh با پسوند bash ساخت فایل )
```ruby
touch <name-file>.sh
```

Access the bash file to run (برای اجرا bssh دسترسی به فایل)
```ruby
sudo chmod +x <file-name>.sh
```

Run the bash file (bash اجرای فایل)
```ruby
./<file-name>.sh
```

---
### 20. commend for bash in file
Add the bash interpreter to the file (به فایل bash اضافه کردن مفسر)
```ruby
!/bin/bash
```
❗Note: It is required in some versions of Linux (در برخی از نسخه های لینچکس لازم می باشد)

---

