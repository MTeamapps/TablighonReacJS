**راهنمای استفاده از پکیج تبلیغان**
<br/>
ابتدا با دستور
<br/>
*npm install tablighan*
<br/>
این پکیج را در پروژه ری اکت خود نصب کنید 
<br/>
![setup](https://github.com/mahooresorkh/tablighan-image/blob/main/01.png)
<br/>
سپس تگ
<br/>
GetImage
<br/>
را با دستور زیر در داخل کامپوننت دلخواه ری اکت وارد نمایید
<br/>
*import GetImage from 'tablighan';*
<br/>

![import](https://github.com/mahooresorkh/tablighan-image/blob/main/04.png)
<br/>

در نهایت می توان کامپوننت مذکور را در داخل کد برنامه به شکل زیر استفاده کرد
<br/>
```<GetImage hostId="شناسه مربوط به تصویر تبلیغاتی که از سایت تبلیغان گرفته شده است" />```
<br/>

![use](https://github.com/mahooresorkh/tablighan-image/blob/main/02.png)
<br/>
*توجه*
این کامپوننت تصویر تبلیغاتی را به صورت سایز اصلی نمایش خواهد داد 
چنانچه تمایل دارید که عکس به ابعاد کوچکتر یا بزرگتر نمایش داده شود می توانید از دستور زیر استفاده نمایید

```<div style={{width:'عرض دلخواه(به پیکسل)'}}>```
    ```<GetImage hostId="شناسه مربوط به تصویر تبلیغاتی که از سایت تبلیغان گرفته شده است">```
```</div>```

![output](https://github.com/mahooresorkh/tablighan-image/blob/main/03.png)

