# magento


## ماژول درگاه پرداخت آلسات پرداخت برای سیستم های مجنتو

مراحل نصب ماژول درگاه پرداخت آلسات پرداخت
## مرحله انتقال فایل ها

وارد پنل هاست خود شوید. سپس وارد مسیر نصب مجنتو شوید.فایل ها زیپ ماژول را در مسیر app اکستراکت کنید.


به حروف بزر گ و کوچک دقت کنید.
## مرحله نصب ماژول

برای این مرحه نیازمند دسترسی ssh هستید. با استفاده از پوتی یا هر نرم افزار دیگری که در اختیا ر دارید وارد حساب خود شوید. وارد مسیر که مجنتو در آن نصب است شوید. در این مسیر کدهای زیر را به ترتیب اجرا کنید.

```bash
$ php bin/magento setup:upgrade
$ php bin/magento setup:di:compile
$ php bin/magento s:s:d -f fa_IR en_US
$ php bin/magento c:f
```

موفق باشید
