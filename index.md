<html>
<head>
<link href='//fonts.googleapis.com/css?family=Chewy' rel='stylesheet'>
<style>
@font-face {
  font-family: 'BRoya'; 
  src: url('BRoya.eot') format('eot'),  /* IE6–8 */
       url('BRoya.woff') format('woff'),  /* FF3.6+, IE9, Chrome6+, Saf5.1+*/
       url('BRoya.ttf') format('truetype');  /* Saf3—5, Chrome4+, FF3.5, Opera 10+ */
} 


body {
     text-align: justify;    
}

h2 {
    direction: rtl; 
    font-family: 'BRoya' , Chewy ;
    padding: 0 3px;
    font-size: 1.9em;
    margin-bottom: .2em;
    margin-top: 2.5em;
}

p {
    direction: rtl; 
    font-family: 'BRoya' , Chewy ;
    font-size: 1.4em;
    margin-bottom: .3em;
    padding-top: .4em;
}
</style>

</head>

<body>

<h2>تاریخچه</h2>
<p>
 با ورود انسان به عصر کامپیوتر و اینترنت، نیاز به ابزاری مانند دستگاه چاپ جهت نمایش اطلاعات در این دنیا نیز به ایجاد شد، این نیاز منجر به پیدایش موضوع Web-Typography شد که در واقع نحوه استفاده از فونت و ابزارهایی نوشتاری جهت نمایش متن به صورت دلخواه در دنیای دیجیتال است. در ابتدای راه وب امکان ارسال فونت توسط سرور به کاربر موجود نبود پس برای نمایش صفحات وب، دسته‌ای از فونت‌ها به نام web safe fonts بر روی همه سیستم‌ها نصب شدند و گسترش‌دهندگان وب تنها امکان استفاده از این فونت‌ها را داشتند. اگر طراحی برای نمایش صفحه‌ای به فونت دیگری نیاز داشت ناچار بود متن با فونت مورد نظر خود را به صورت تصویر<img> برای کاربر ارسال کند. در حدود سال 2010 فونت‌های طراحی شده و شخصی نیز توسط مرورگر‌ها پشتیبانی شدند، اما مشکلی که در آن زمان وجود داشت تفاوت فرمت‌‌هایی بود که هر مرورگر یا دستگاه برای خواندن فونت‌ها لازم داشت که در نتیجه آن‌ سرور مجبور به ارسال انواع زیادی فایل بود. امروزه ولی این مشکل نیز با ایجاد فایل‌های Web Open File Format با فرمت .woff برطرف شده است. اکثر مرورگر‌ها توانایی پشتیبانی از این فرمت و همچنین نسل دوم این فونت که دارای همان ویژگی‌های نسل اول اما با حجم فایل کمتر است را دارند.
</p>




<h2>فونت‌های خانوادگی! </h2>
<p>
font family به مجموعه‌ای از font face ها گفته می‌شود که ظاهر یکسان دارند ولی با style و weight های متفاوت طراحی شده‌اند زیرا در بسیاری از فونت‌ها برای تغییر در وزن و استایل باید همه حروف مجددا طراحی شوند. مثلا حالت italic یک فونت ممکن است کاملا با حالت عادی آن تفاوت داشته باشد. در نتیجه در صورتی که بخواهیم از حالت italic یک فونت استفاده کنیم باید فایل آن را نیز در اختیار مرورگر قرار دهیم. اگرچه در صورتی که مرورگر این فایل را در اختیار نداشته باشد می‌تواند به صورت synthesized  فونت را به حالتی مشابه دلخواه تبدیل ‌کند اما نتیجه این روش فونتی با ظاهر نه چندان ایده‌آل خواهد بود. پس برای استفاده از یک فونت خاص باید فایل‌های متعددی را در اختیار مرورگر گذاشته و نیز با فرمت  css در فایل آن مسیر دسترسی به فایل فونت و خانواده فونت را مشخص کنیم. 
</p>




<h2>چگونه فونت خود را به مقصد برسانیم؟</h2>
<p>
انتقال فایل حاوی فونت به مرورگر سمت کاربر از دو راه ممکن است. راه اول یا locally hosted، ارسال فایل فونت‌ها توسط سرور با بقیه فایل‌های مربوط به صفحه برای کاربر است. راه دوم یا externally hosted این است که فایل‌های حاوی فونت از سروری غیر از سرور اصلی به کاربر فرستاده ‌شود. این کار با استفاده از Google Fonts انجام می‌پذیرد. به عنوان مثال در همین تمرین از هر دو این روش‌ها برای انتقال فونت به صفحه استفاده کرده‌ایم.
</p>




<h2>وب و فارسی‌زبانان</h2>
<p>
یکی از مهم‌ترین مشکلاتی که رو در روی توسعه‌دهندگان وب به زبان‌هایی غیر از انگلیسی قرار گرفته است عدم وجود پایگاهی غنی از فونت‌ها و همین‌طور به روز و متنوع نبودن فونت‌های موجود است. به عنوان مثال فونت‌های فارسی نصب شده بر روی سیستم‌ها تنها سه فونت arial ، Tahoma و mono-type هستند در حالی که برای زبان انگلیسی حداقل نزدیک به 10 فونت در دسترس است. 
</p>
<p>
 با در نظر گرفتن زبان فارسی می‌توان متوجه شد که طراحان فونت‌های فارسی به دلیل خصوصیات مربوط به این خط با مشکلات زیادی روبرو هستند. مهم‌ترین مشکل تفاوت جهت نوشتاری در این زبان است که در خلاف جهت اکثر خطوط معمول است. مشکل دیگر نیز تنوع ارتفاعی کاراکتر‌های این زبان است. زبان‌های لاتین عموما دارای کاراکترهایی با ارتفاع یکسان هستند، اما زبان‌هایی مانند زبان فارسی، عربی و اردو دارای کاراکترهای کاملا متفاوتی هستند، برخی به سمت بالا کشیده می‌شوند و برخی به سمت پایین. این تفاوت ظاهری در فونت‌های لاتین و زبان‌های دیگر باعث شده که استانداردهای تدوین شده، که عموما بر اساس رسم‌الخط لاتین وضع شده‌اند، فارسی‌زبانان را دچار مشکل کند. متاسفانه این قبیل مشکلات موجب شده‌اند که فونت‌های فارسی همچنان غیراستاندارد باشند. البته با این وجود هم اکنون تعداد فونت‌های فارسی Google Fonts روز به روز در حال افزایش است.
</p>




</body>
</html>
