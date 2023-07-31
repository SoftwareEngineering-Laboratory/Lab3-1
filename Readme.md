# داک پروژه

در این قسمت به مستندات پروژه می‌پردازیم.
قسمت اول مربوط به اجرای دستور العمل و قسمت دوم مربوط به افزودن مسئله مطرح شده در آزمایش ۳ می‌باشد.
## BDD-1
در این پروژه ما ابتدا طبق دستور العملی که داده شده بود، مراحل را پیش بردیم و یک پروژه ساده ماشین حساب با یک عملیات جمع را زدیم که برای آن با استفاده از زبان Gherkins یک تست BDD نیز نوشتیم. پس از اینکه مرحله آخر دستور العمل را انجام دادیم با یک ارور در هنگام تست مواجه شدیم. طبق سوالات داک پیش می‌رویم و مشکل را شرح می‌دهیم.

### پرسش‌ها 
#### ۱. این موارد تست کدامند؟
تست‌هایی که حداقل یکی از اعداد منفی باشند دچار مشکل می‌شوند.

#### ۱. علت بروز مشکل چیست؟
در تعریف تابع Given برای این calculator ، رجکسی که زده شده است تنها اعداد مثبت را قبول می‌کند و علامت منفی قبل از عدد برای آن تعریف نشده است.

#### ۱. چگونه آن را رفع کردید؟
کافی است که عبارات (\d+) در تابع Given را با عبارت (-?\d+) تعویض کنیم تا اعداد منفی نیز پذیرفته شوند.



## BDD-2

