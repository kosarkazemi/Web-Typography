@import url(https://fonts.googleapis.com/css?family=Barrio);
<style>
main-content {
    font-family: 'Scheherazade', Tahoma;
}
</style>

  font family به مجموعه‌ای از font face ها گفته می‌شود که ظاهر یکسان دارند ولی با style و weight های متفاوت طراحی شده‌اند زیرا در بسیاری از فونت‌ها برای تغییر در وزن و استایل باید همه حروف مجددا طراحی شوند. مثلا حالت italic یک فونت ممکن است کاملا با حالت عادی آن تفاوت داشته باشد. در نتیجه در صورتی که بخواهیم از حالت italic یک فونت استفاده کنیم باید فایل آن را نیز در اختیار مرورگر قرار دهیم. اگرچه در صورتی که مرورگر این فایل را در اختیار نداشته باشد به صورت synthesized فونت را به حالتی مشابه دلخواه تبدیل می‌کند اما نتیجه این روش فونتی با ظاهر نه چندان ایده‌آل خواهد بود. پس برای استفاده از یک فونت خاص باید فایل‌های متعددی را در اختیار مرورگر گذاشته و نیز با فرمتsrc: }  :font-family}@font-face در فایل css مسیر دسترسی به فایل فونت و خانواده فونت را مشخص کنیم.  انتقال فایل حاوی فونت به مرورگر سمت کاربر از دو راه ممکن است. راه اول (locally hosted) ارسال فایل فونت‌ها توسط سرور با بقیه فایل‌های مربوط به صفحه برای کاربر است. راه دوم (externally hosted) این است که فایل‌های حاوی فونت از سروری غیر از سرور اصلی به کاربر فرستاده ‌شود. این کار با استفاده از Google Fonts انجام می‌پذیرد.






### Markdown
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text
[Link](url) and ![Image](src)
```
