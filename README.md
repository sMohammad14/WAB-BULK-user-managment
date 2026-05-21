# یه ابزار باحال برای مدیریت دسته‌جمعی کاربران والیکس

با این ابزار که یه فایل HTML ساده‌ست، می‌تونید هر تعداد کاربر Wallix Bastion رو یکجا مدیریت کنید. کافیه فایل رو تو مرورگر باز کنید.

## دقیقا چه کار میکنه؟

می‌تونید اون دسته از مشخصات کاربر رو که برای گروهی از کاربرا معنی داره (گروه های کاربری نه)، با هم تغییر بدید. مثلاً:

-  پروفایل کاربر

- تاریخ انقضا

- رمز عبور
- وضعیت Disable و   Enable

- هرچیز دیگه‌ای که بشه دسته‌جمعی عوض کرد

مهم نیست کاربرا تو چه گروهی هستن یا چه دسترسی‌هایی دارن. شما لیستشون رو می‌دید، ابزار کار رو انجام میده.

## یه سری قابلیت‌های جالب

- کاربرا رو با یه فایل متنی ساده به ابزار بدید (هر خط یه کاربر)
- اگر اسم کاربری عددی باشه و کمتر از ۱۰ رقم داشته باشه، می‌تونید با گذاشتن یک تیک به ابتداش صفر اضافه کنید (مثلاً برای کدملی‌ها خیلی به کار میاد)
- انتخابگر تاریخ، خودش میلادیه ولی بعد از انتخاب، تاریخ شمسی رو نشون میده. شاید بعدا تقویم فارسی پروزه های دیگه رو هم بزارم داخلش
- آخر کار یه گزارش کامل از اینکه چی شد، بهتون میده

## با چه ورژنی کار می‌کنه؟

این ابزار از ورژن 9 ولیکس تا نسخه آخر که فعلا 12 هست، جواب میده. برای همین نسخه API استفاده شده، پایین هست!

## چطور استفاده کنم؟

1. فایل `.html` رو تو مرورگر باز کنید.
2. فایل متنی که توش اسم کاربرا رو خط به خط نوشتید آپلود کنید.
3. تنظیمات تغییرات رو انجام بدید (تاریخ انقضا، پروفایل، رمز و...)
4. اگر خواستید گزینه «اضافه کردن صفر به ابتدای اعداد کم‌رقم» رو فعال کنید.
5. بزنید بریم! بعد از تموم کار، گزارش کامل رو ببینید.



# A Cool Tool for Batch Managing Wallix Users

This is a simple HTML file. Just open it in your browser and you can manage as many Wallix Bastion users as you want, all at once.

## What exactly does it do?

You can update the kind of user attributes that make sense to change for a bunch of users at the same time (not user groups, just the users themselves). For example:

- User profile
- Expiration date
- Password
- Enable / Disable status
- Anything else that can be changed in bulk

It doesn't matter which groups your users are in or what permissions they have. You give the tool a list, and it does the job.

## Some neat features

- Feed the tool a simple text file with usernames (one per line)
- If a username is numeric and has fewer than 10 digits, you can just tick a box to add leading zeros (super handy for national IDs)
- The date picker uses Gregorian dates, but after you pick one, it shows you the Jalali (Persian) date. Maybe later I'll add a full Persian calendar picker.
- When it's done, you get a complete report of what happened.

## Which versions does it work with?

This tool works from Wallix Bastion version 9 up to the latest (currently 12). The API version used here is on the lower side – that's intentional.

## How do I use it?

1. Open the `.html` file in your browser.
2. Upload a text file containing the usernames (one per line).
3. Configure the changes you want (expiration date, profile, password, etc.).
4. If needed, enable the "Add leading zeros to numbers shorter than 10 digits" option.
5. Hit go! After it finishes, check out the full report.
