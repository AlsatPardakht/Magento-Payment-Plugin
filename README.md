<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="./logo.png" alt="Project logo"></a>
</p>

<h3 align="center">Alsat IPG Magento</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/AlsatPardakht/AlsatIPGAndroid.svg)](https://github.com/AlsatPardakht/AlsatIPGAndroid/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/AlsatPardakht/AlsatIPGAndroid.svg)](https://github.com/AlsatPardakht/AlsatIPGAndroid/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">با استفاده از این کتابخانه میتوانید اپلیکیشنتون رو به شبکه پرداخت آل‌سات پرداخت وصل کنید و به راحتی محصولات خودتون رو داخل اپلیکیشن بفروشید
    <br> 
</p>
# alsatpardakht magento payment module


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
