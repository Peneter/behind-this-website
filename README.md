
<div dir="auto">
 
نویسندگان اصلی :
By Priyanjana Bengani ([@acookiecrumbles](https://twitter.com/acookiecrumbles)) and Jon Keegan ([@jonkeegan](https://twitter.com/jonkeegan))
IRE NICAR Conference - March 4, 2022
Slides: [English](https://docs.google.com/presentation/d/1tRae65Eln072zLbbdIPyeJxt6I_JflRmEYH8cp4Xc84/edit?usp=sharing) | [Russian](https://docs.google.com/presentation/d/1TxynZrKKrYMvPFk3oxYMNRkx8fp0Gs_AhQufuVkKOOo/edit?usp=sharing) 

*Thank you to Svetlana Borodina at Harriman Institute for the Russian translation!*
 
 مستند فارسی :

  https://docs.google.com/document/d/1tMQSHr7ek3Eld1fmxH9yNoWDhRYS5ef7FTFEELQ7uQw/

  ### چک لیست جهت شناسایی صاحب سایت (ترجمه و اضافه کردن یک سری تکنیک) Persian . 
### اوسینت تکنیک هایی که توسط آن ها اطلاعات  متن عکس فیلم موقعیت جغرافیایی را می توان جمع آوری کرد.سایتهایی که سرویس اوسینت ارایه میکنند در واقع از موتورهای جستجو مختلف استفاده میکنند.برخی از سایتها سرویس رایگان میدهند و برخی پولی.همچنین ابزارهای متن بازی که به صورت خودکار فرآیند اوسینت را انجام میدهند در واقع از APIهای سایتها استفاده میکنند. 
 [@soheilhashemi](https://twitter.com/soheilhashemi_)</br>
 [Document]( https://docs.google.com/document/d/1tMQSHr7ek3Eld1fmxH9yNoWDhRYS5ef7FTFEELQ7uQw/)</br>
  [OSINT?](https://twitter.com/soheilhashemi_/status/1446899535826100230?s=20)</br>
  [Blog_Peneter](https://blog.peneter.com)</br>
  [OSINT1](https://blog.peneter.com/clubhouse-osint-1-preparation/)</br>
  [OSINT_Image](https://blog.peneter.com/clubhouse-osint-2-email/)</br>
  [OSINT_Email](https://blog.peneter.com/clubhouse-osint-3-email/)</br>
  [OSINT_Domain&IP](https://blog.peneter.com/clubhouse-osint-4-5-domain-ip/)</br>
  [OSINT_SocialMedia](https://blog.peneter.com/clubhouse-osint-6-social-network-twitter/)</br>
  

#### این چیست ؟
این چک لیست قرار است به عنوان یک ابزار گزارش برای کمک به روزنامه نگاران و محققان در هنگام تلاش برای یافتن اینکه چه کسی یک وب سایت را منتشر کرده است، استفاده شود. این به معنای استفاده در ارتباط با تکنیک های گزارش دهی آفلاین است. 

استفاده از این چک لیست تضمین نمی کند که می توانید نویسنده ناشناس وب سایتی را که نمی خواهد پیدا شود، را شناسایی کنید، اما می تواند به کشف سرنخ ها و ارتباطات مهمی کمک کند که می توانند به عنوان سرنخ برای گزارش بیشتر عمل کنند. 

🌟 توصیه جدی: در حین اجرای این چک لیست، یک ادیتور ایجاد کنید — می تواند یک سند TextEdit، یک Google Doc، فقط برنامه Notes باشد، هر چه باشد. مهم است که بتوانید مراحل خود را دوباره دنبال کنید. 

#### محتوای سایت 

##### متن
- ✍️ آیا نویسندگانی لیست شده اند؟
 - اگر سایت وردپرس است، این مانند لینک زیر در گوگل سرچ کنید تا لیست نویسندگان را مشاهده کنید:<br/> 
  - `https://yourwebsite.com/author/*/` <br/>
   - به عنوان مثال اگر روی سایت پنتر بزنید می بینید که یوزرنیم نویسنده "Peneter" است:<br/>
  -  `https://blog.peneter.com/author/*/`

- [ ] 📫 آیا آدرس ایمیل یا اطلاعات تماس وجود دارد؟
   - اگر آدرس های ایمیل وجود دارد، آیا ایمیل با دامین سایت هست یا میل سرور عمومی هست؟ در قسمت ایمیل های لینک زیر ابزارهای اوسینت معرفی شده اند:
 1. https://osintframework.com/ </br>
 2. https://map.malfrats.industries/ </br>
 3. https://lampyre.io/ </br>
 
   - آیا ایمیل در [haveibeenpwned.com](https://haveibeenpwned.com) نمایش داده می شود؟ (اگر توسط ایمیل در جایی ثبت نام شده باشد که دیتابیسش لیک شده باشد می توانید در بعضی مواقع پسورد یا اسم و فامیل نویسنده را بدست آورید)
   - بررسی کنید که آیا گراواتار مرتبط با آن آدرس وجود دارد یا خیر:
     - https://en.gravatar.com/site/check/XXXXX@gmail.com </br>
     
- [ ] 🕑 ساعت محلی سرور چقدر است؟
   - به ویژگی 'datetime' در سورس HTML سایت های وردپرس نگاه کنید. CTLR + U سپس دنبال <Time> بگردید :<br/> 
   ``<time datetime="1401-01-06"><i class="remixicon remixicon-calendar-line"></i> 6 فروردین 1401</time>``
- [ ] 🕶 آیا وب سایت قانون حفظ حریم خصوصی یا شرایط و ضوابطی دارد که به یک LLC اشاره می کند، یا چه قوانین منطقه ای اعمال می شود؟
- [ ] 📡 آیا وبسایت فید RSS دارد؟
   - آیا فید RSS اطلاعات بیشتری در مورد نویسندگان یا پستهایی که در سایت قابل مشاهده نیستند ارائه می دهد؟
   - میتوانید با استفاده از [IMPORTFEED](https://infoinspired.com/google-docs/spreadsheet/how-to-use-importfeed-function-in-google-sheets) پیوندهای مقاله RSS را به برگه‌های Google بکشید 
​
##### ویژگی ها و عملکرد
- [ ] 🗞 آیا وبسایت خبرنامه دارد؟
   - آدرس پستی فیزیکی را بررسی کنید - طبق قانون CAN-SPAM در ایالات متحده لازم است
- [ ] 💸 آیا وب سایت کمک های مالی جمع آوری می کند؟ (اگر آدرس والت کریپتو باشد می توانید تراکنشها را مشاهده کنید.)
- [ ] 🛒 آیا وب سایت قسمت فروشگاه دارد ؟
     - سعی کنید مراحل پرداخت را طی کنید (بدون پرداخت). گاهی اوقات نام گیرنده واقعی درست قبل از تایید پرداخت فاش می شود. 
​
##### پیوندها
- [ ] 🔗 وب سایت بیشتر به چه دامنه هایی لینک می دهد؟ (نیاز به کرال کردن دارد)از linkgopher استفاده کنید.
- [ ] ❤️ چه کسی بیشتر به دامنه لینک می دهد؟
     - اپراتور جستجوی گوگل: "link:yourwebsite.com"
     -💵 بک لینک ها را در [ahrefs.com](https://ahrefs.com) بررسی کنید 
- [ ] آیا پیوندها دارای کدهای UTM هستند؟ 
​
##### عکس ها، تصاویر و اسناد
- [ ] 📸 آیا عکس های نویسنده وجود دارد؟
  - در صورتی که عکس در اپلودری که متادیتا را حذف نکرده باشد اپلود شده باشد می توان اطلاعات آن را توسط سایت زیر استخراج کرد.
exif.regex.info/exif.cgi
نکاتی در مورد عکس: 
-بررسی خود عکس از لحاظ محیط اطراف جهت شناسایی موقعیت جغرافیایی یا تمامی المان های داخل عکس جزو بررسی هایی هست که می توان اطلاعات را استخراج کرد. مثلا پلاک ماشین نوع ماشین ساختمان های اطراف منظره اطراف اشخاص داخل عکس
-عکس ها قابلیت Reverse دارند یعنی شما می تواند از موتورهای جستجو استفاده کنید تا به منبع اصلی عکس در اینترنت دست پیدا کنید گاهی از همین روش برای شناسایی افراد داخل عکس استفاده می شود جهت این عمل از منابع زیر می توان استفاده نمود:
1. https://images.google.com/?gws_rd=ssl </br>
2. https://www.bing.com/images </br>
3. https://yandex.ru/images/ </br>
4. https://image.baidu.com </br>
5. https://tineye.com/ </br>
Addons : </br>
https://addons.mozilla.org/nl/firefox/addon/who-stole-my-pictures/ </br>

نکته :
- استفاده از هر کدام از این سرویس ها باعث می شود عکس مد نظر شما در cloud آپلود شود اگر عکس حساس هست از Tineye استفاده نکنید
- اگر عکسی را دریافت کردید می توانید توسط سایت زیر متوجه بشوید که آیا فتوشاپ شده است یا نه اگر شده است چه بخش از عکس فتوشاپ شده است.
http://fotoforensics.com/  </br>

- [ ] 📄 آیا فایل های PDF در سایت میزبانی می شود؟
  - در موتور جستجو، "filetype:pdf site:<yourwebsite.com>"
  - اگر تعدادی پیدا کردید، متادیتا را با "دریافت اطلاعات" در نمایشگر PDF خود بررسی کنید. (اگر پاک نشده باشد شما به اسم نویسنده،ایمیل، تکنولوژی، یوزنیم سیستم عامل دست پیدا خواهید کرد)
  -شما می توانید از موتورهای جستجو دیگر برای انجام سرچ (دورک) استفاده کنید برخی از موتورهای جست و جو:

 1. https://www.google.com/ </br>
  2. https://www.google.com/advanced_search </br>
  3. http://www.googleguide.com/print/adv_op_ref.pdf </br>
  4. https://www.bing.com/ </br>
  5. https://www.bruceclay.com/blog/bing-google-advanced-search-operators/ </br>
  6. https://yandex.com/ </br>
  7. https://duckduckgo.com/ </br>
  8. https://help.duckduckgo.com/duckduckgo-help-pages/results/syntax/ </br>
  9. https://baidu.com </br>
 -این کار می توانید با دو ابزاز زیر به صورت اتومات انجام دهید (متادیتا خودشان استخراج می کنند)</br>
   [metagoofil](https://www.kali.org/tools/metagoofil) و [FOCA](https://github.com/ElevenPaths/FOCA)
  
​
#### رسانه های اجتماعی

اگر پروفایل های رسانه های اجتماعی در سایت ذکر شده است، ارزش بررسی دارند.

- [ ] 👤 آیا هیچ حساب رسانه اجتماعی در بخش \<meta\> HTML وجود دارد؟
- [ ] 📅 حساب های فردی چه زمانی ایجاد شدند؟ آیا با تاریخچه سایت مطابقت دارد؟
- [ ] 📊 کدام پلتفرم بیشترین دسترسی را دارد؟
- [ ] 📣 آیا پیام رسانی در پلتفرم ها متفاوت است؟
- [ ] 📇 آیا نام‌های حساب کاملاً متمایز در پلتفرم‌های رسانه‌های اجتماعی دارند یا کم و بیش یکسان هستند؟
   - توجه: فقط به این دلیل که نام حساب یکسانی را در پلتفرم‌ها پیدا می‌کنید، لزوماً به این معنی نیست که آنها متعلق به یک شخص هستند!  


##### فیس بوک
در نمایه فیس بوک، به صفحه شفافیت بروید:
- [ ] ☎️ آیا آدرس و شماره تلفن صفحه وجود دارد؟
- [ ] ⏪ آیا تاریخچه صفحه نام دیگری را نشان می دهد؟
   - آیا صفحه موضوعات را تغییر داده است؟
- [ ] 🐣 صفحه فیس بوک چه زمانی ایجاد شد؟
- [ ] آیا این صفحه گروهی را اجرا می کند؟
- [ ] 🗳 آیا صفحه تبلیغاتی دارد؟ آیا این صفحه تبلیغات سیاسی دارد؟
- [ ] 🤖 آیا فیس بوک هر "صفحه مرتبط" را برای صفحه داده شده پرچم گذاری می کند؟ برای یافتن اتصالات به الگوریتم های فیس بوک تکیه کنید! 
​
##### توییتر
در توییتر، حساب ممکن است بخشی از یک پاد یا شبکه باشد که یکدیگر را تقویت می کند. با استفاده از [en.whotwi.com](https://en.whotwi.com/)، ارزش بررسی را دارد:
- [ ] 👯‍♀️ اکانت با چه کسی درگیر است؟
- [ ] 🐦 الگوهای توییت کردن حساب کاربری چیست؟
- [ ] #️⃣ چه هشتگ هایی با حساب کاربری مرتبط هستند؟
- [ ] اولین فالوور/فالوور حساب چه کسانی بودند؟
     - این را اینجا پیدا کنید:
   `https://en.whotwi.com/` 
​دورک در توییتر:</br>
https://twitter.com/search-advanced
بر اساس یوزرنیم و تاریخ می توانید سرچ کنید.</br>
ابزارهای اوسینت توییتر:</br>
1. https://socialbearing.com/
2. https://www.twitonomy.com/
3. https://tweetbeaver.com/
4. http://spoonbill.io/
5. https://tinfoleak.com/
##### پلتفرم های دیگر
فراموش نکنید که بررسی کنید ببینید آیا سایت دارای حساب‌هایی در یوتیوب، اینستاگرام، ردیت، گیت‌هاب، 

#### زیرساخت ( منظور سرور)
- [ ] 🗄 آیا وب سایت را بایگانی کرده اید؟ (تو همیشه باید!)
   - می توانید این کار را در archive.org انجام دهید یا از [Waybackmachin](chrome-extension://fpnmgdkabkmnadcjpehmlllkndpkmiak/about.html) آن استفاده کنید. برای مرورگر فایرفاکس هم این پلاگین وجود دارد.
   - می توانید کل وب سایت را در ترمینال با «wget» بگیرید یا برنامه httrack را استفاده کنید: </br>
    `wget -mpEk <yourwebsite.com>` 

- [ ] 🖥 وب سایت از چه چیزی استفاده می کند؟ برای اینکار می توانید از پلاگین [Wappalyzer](https://www.wappalyzer.com) را روی مرورگر خود نصب کنید یا آنلاین مشاهده کنید.
   - آیا از Wordpress، Squarespace، چیز دیگری استفاده می کند؟ 
- [ ] ☁️ کجا میزبانی می شود؟
  - آیا در Google Cloud، AWS، Cloudflare، و چیز دیگری وجود دارد؟
- [ ] 🪳 آیا ردیاب هایی وجود دارد؟
  - برای شروع می توانید [Blacklight](https://themarkup.org/blacklight) را بررسی کنید.
- [ ] 🛍 ​​کسب درآمد از سایت چگونه است؟
  - آیا پیوندهای وابسته (آمازون و غیره) وجود دارد؟
- [ ] 🧬 شناسه های مختلف ردیابی چیست و آیا آن ها با دامنه های دیگر به اشتراک گذاشته می شوند؟
  - Google Analytics، Facebook Pixel، Quantcast، NewRelic و غیره را بررسی کنید.
  - از ابزارهایی مانند [builtwith](https://builtwith.com)، [RiskIQ](https://www.riskiq.com/)، یا [Dnslytics](https://dnslytics.com/) استفاده کنید تا ببینید آیا دامنه های دیگر همان شناسه را به اشتراک می گذارند.
- [ ] آیا زیر دامنه های مرتبطی وجود دارد؟
  - از سرویس [DNSDBScout](https://www.farsightsecurity.com/tools/dnsdb-scout/)ابرای پیدا کردن دامنه های مرتبط استفاده کنید.
- [ ] 📜 آیا سوابق تاریخی WHOIS وجود دارد؟
  - به [Whoxy](https://www.whoxy.com/) یا [RiskIQ](https://www.riskiq.com/) نگاه کنید.
- [ ] ⌛️ آیا سایت در طول زمان تغییر کرده است؟
  - به [archive.org](https://archive.org/) نگاه کنید تا ببینید در چه زمانهایی چه تغییراتی روی سایت رخ داده است.
- [ ] 🗑 آیا نسخه قبلی سایت اطلاعات بیشتری داشت؟
  - ممکن است پستی از سایت در طول زمان حذف شده باشد.
#### منابع و ابزار

##### کتاب
تکنیک های هوشمند منبع باز - مایکل بزل
https://inteltechniques.com/book1.html

کتابچه راهنمای تأیید - ویرایش شده توسط کریگ سیلورمن
https://datajournalism.com/read/handbook/verification-3

##### زیرساخت وب سایت
- [Blacklight](https://themarkup.org/blacklight): بازرس حریم خصوصی وب سایت مارکاپ در زمان واقعی.
- [builtwith.com](https://builtwith.com):تکنولوژی های استفاده شده در سایت.
- [DNSDBScout]((https://www.farsightsecurity.com/tools/dnsdb-scout/)): به شما امکان جستجو و «جستجوی انعطاف‌پذیر» برای جستجوهای پسیو dns از جمله نقشه‌برداری دامنه IP <-> را می‌دهد.
- [Dnslytics](https://dnslytics.com/): طیف وسیعی از ابزارها از جمله تجزیه و تحلیل معکوس و جستجوی معکوس DNS، و همچنین داده های WHOIS را ارائه می دهد. فریمیوم.
- [RiskIQ](https://www.riskiq.com/): ابزاری «هوش تهدید» که به شما امکان می دهد IP معکوس، تجزیه و تحلیل معکوس، WHOIS، SSL، زیر دامنه ها و غیره را دریافت کنید.
- [Whoxy](https://www.whoxy.com/): ابزاری که به شما امکان می‌دهد ثبت‌های WHOIS تاریخی را مشاهده کنید. رایگان.
- آرشیو اینترنت [پلاگین کروم](chrome-extension://fpnmgdkabkmnadcjpehmlllkndpkmiak/about.html). 


###### حساب های رسانه های اجتماعی
- [Sensity AI](https://sensity.ai/deepfakes-detection/): شناسایی تصویر فیک.
- [whotwi.com](https://en.whotwi.com/):اوسینت توییتر رایگان. 
    </div>
