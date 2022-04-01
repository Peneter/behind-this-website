
<div dir="auto">
 
نویسندگان اصلی :
By Priyanjana Bengani ([@acookiecrumbles](https://twitter.com/acookiecrumbles)) and Jon Keegan ([@jonkeegan](https://twitter.com/jonkeegan))
IRE NICAR Conference - March 4, 2022
Slides: [English](https://docs.google.com/presentation/d/1tRae65Eln072zLbbdIPyeJxt6I_JflRmEYH8cp4Xc84/edit?usp=sharing) | [Russian](https://docs.google.com/presentation/d/1TxynZrKKrYMvPFk3oxYMNRkx8fp0Gs_AhQufuVkKOOo/edit?usp=sharing) 

*Thank you to Svetlana Borodina at Harriman Institute for the Russian translation!*

  ### چک لیست جهت شناسایی صاحب سایت (ترجمه و اضافه کردن یک سری تکنیک) Persian . 

  [@soheilhashemi](https://twitter.com/soheilhashemi_)
  [OSINT?](https://twitter.com/soheilhashemi_/status/1446899535826100230?s=20)
  [Blog Peneter](https://blog.peneter.com]
  [OSINT1](https://blog.peneter.com/clubhouse-osint-1-preparation/)
  [OSINT_Image](https://blog.peneter.com/clubhouse-osint-2-email/)
  [OSINT_Email](https://blog.peneter.com/clubhouse-osint-3-email/)
  [OSINT_Domain&IP](https://blog.peneter.com/clubhouse-osint-4-5-domain-ip/)
  [OSINT_SocialMedia](https://blog.peneter.com/clubhouse-osint-6-social-network-twitter/)

#### این چیست ؟
این چک لیست قرار است به عنوان یک ابزار گزارش برای کمک به روزنامه نگاران و محققان در هنگام تلاش برای یافتن اینکه چه کسی یک وب سایت را منتشر کرده است، استفاده شود. این به معنای استفاده در ارتباط با تکنیک های گزارش دهی آفلاین است. 

استفاده از این چک لیست تضمین نمی کند که می توانید نویسنده ناشناس وب سایتی را که نمی خواهد پیدا شود، را شناسایی کنید، اما می تواند به کشف سرنخ ها و ارتباطات مهمی کمک کند که می توانند به عنوان سرنخ برای گزارش بیشتر عمل کنند. 

🌟 توصیه جدی: در حین اجرای این چک لیست، یک ادیتور ایجاد کنید — می تواند یک سند TextEdit، یک Google Doc، فقط برنامه Notes باشد، هر چه باشد. مهم است که بتوانید مراحل خود را دوباره دنبال کنید. 

#### محتوای سایت 

##### متن
- ✍️ آیا نویسندگانی لیست شده اند؟
 - اگر سایت وردپرس است، این مانند لینک زیر در گوگل سرچ کنید تا لیست نویسندگان را مشاهده کنید:<br/> 
  `https://yourwebsite.com/author/*/` <br/>
   - به عنوان مثال اگر روی سایت پنتر بزنید می بینید که یوزرنیم نویسنده "Peneter" است:<br/>
   `https://blog.peneter.com/author/*/`

- [ ] 📫 آیا آدرس ایمیل یا اطلاعات تماس وجود دارد؟
   - اگر آدرس های ایمیل وجود دارد، آیا ایمیل با دامین سایت هست یا میل سرور عمومی هست؟ در قسمت ایمیل های لینک زیر ابزارهای اوسینت معرفی شده اند:
   - https://osintframework.com/
   - https://map.malfrats.industries/
   - https://lampyre.io/
 
   - آیا ایمیل در [haveibeenpwned.com](https://haveibeenpwned.com) نمایش داده می شود؟ (اگر توسط ایمیل در جایی ثبت نام شده باشد که دیتابیسش لیک شده باشد می توانید در بعضی مواقع پسورد یا اسم و فامیل نویسنده را بدست آورید)
   - بررسی کنید که آیا گراواتار مرتبط با آن آدرس وجود دارد یا خیر:
     - https://en.gravatar.com/site/check/XXXXX@gmail.com </br>
     
- [ ] 🕑 ساعت محلی سرور چقدر است؟
   - به ویژگی 'datetime' در سورس HTML سایت های وردپرس نگاه کنید. CTLR + U سپس دنبال <Time> بگردید : 
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
- [ ] 🔗 وب سایت بیشتر به چه دامنه هایی لینک می دهد؟ (نیاز به تراشیدن دارد)
- [ ] ❤️ چه کسی بیشتر به دامنه لینک می دهد؟
     - اپراتور جستجوی گوگل: "link:yourwebsite.com"
     - بک لینک ها را در [ahrefs.com](https://ahrefs.com) بررسی کنید 💵
- [ ] آیا پیوندها دارای کدهای UTM هستند؟ 
​
##### عکس ها، تصاویر و اسناد
- [ ] 📸 آیا عکس های نویسنده وجود دارد؟
  - از جستجوی عکس معکوس استفاده کنید تا ببینید آیا همان تصاویر در جای دیگری ظاهر می شوند یا خیر
  - [sensity.ai] (https://sensity.ai) را بررسی کنید تا ببینید آیا تصویر GAN تولید شده است یا خیر
  - درباره مشاهده تصاویر تولید شده توسط GAN [اینجا](https://www.theguardian.com/technology/2020/jan/13/what-are-deepfakes-and-how-can-you-spot-them) بیشتر بخوانید.
- [ ] 🔎 آیا تصاویر دارای داده EXIF ​​هستند؟
    - دستورالعمل‌ها [اینجا](https://www.howtogeek.com/289712/how-to-see-an-images-exif-data-in-windows-and-macos/#:~:text=Viewing%20EXIF% 20داده%20در%20ویندوز،%20عکس%20%20با%20گرفته شد.).
- [ ] 👀 آیا تصاویر اطلاعات شناسایی دیگری دارند؟
  - فهرست را اجرا کنید [اینجا](https://themarkup.org/ask-the-markup/2020/03/12/photos-privacy)
- [ ] 🪣 تصاویر کجا میزبانی می شوند؟
  - اگر در AWS S3، نام سطل ممکن است آشکار باشد - یا ممکن است متوجه شوید که سطل امن نیست.
- [ ] 📄 آیا فایل های PDF در سایت میزبانی می شود؟
  - در موتور جستجو، "filetype:pdf site:<yourwebsite.com>"
  - اگر تعدادی پیدا کردید، متادیتا را با "دریافت اطلاعات" در نمایشگر PDF خود بررسی کنید. (اگر پاک نشده باشد شما به اسم نویسنده،ایمیل، تکنولوژی، یوزنیم سیستم عامل دست پیدا خواهید کرد)
  -شما می توانید از موتورهای جستجو دیگر برای انجام سرچ (دورک) استفاده کنید برخی از موتورهای جست و جو:
    https://www.google.com/
    https://www.google.com/advanced_search
    http://www.googleguide.com/print/adv_op_ref.pdf
    https://www.bing.com/
    https://www.bruceclay.com/blog/bing-google-advanced-search-operators/
    https://yandex.com/
    https://duckduckgo.com/
    https://help.duckduckgo.com/duckduckgo-help-pages/results/syntax/
    https://baidu.com
 -این کار می توانید با دو ابزاز زیر به صورت اتومات انجام دهید (متادیتا خودشان استخراج می کنند)
   (https://www.kali.org/tools/metagoofil)[metagoofil]
   (https://github.com/ElevenPaths/FOCA)[FOCA]
  
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
​
##### پلتفرم های دیگر
فراموش نکنید که بررسی کنید ببینید آیا سایت دارای حساب‌هایی در یوتیوب، اینستاگرام، ردیت، گیت‌هاب، 

#### زیرساخت ( منظور سرور)
- [ ] 🗄 آیا وب سایت را بایگانی کرده اید؟ (تو همیشه باید!)
   - می توانید این کار را در archive.org انجام دهید یا از [پسوند مرورگر] آن استفاده کنید (chrome-extension://fpnmgdkabkmnadcjpehmlllkndpkmiak/about.html).
   - می توانید کل وب سایت را در ترمینال با «wget» بگیرید:
    `wget -mpEk <yourwebsite.com>` 

- [ ] 🖥 وب سایت از چه چیزی استفاده می کند؟
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
  - از امنیت Farsight (https://www.farsightsecurity.com/tools/dnsdb-scout)[DNSDBScout]  انعطاف پذیر استفاده کنید.
- [ ] 📜 آیا سوابق تاریخی WHOIS وجود دارد؟
  - به [Whoxy](https://www.whoxy.com/) یا [RiskIQ](https://www.riskiq.com/) نگاه کنید.
- [ ] ⌛️ آیا سایت در طول زمان تغییر کرده است؟
  - به [archive.org](https://archive.org/) نگاه کنید تا ببینید آیا دامنه به شدت تغییر کرده است - و اگر چنین است چه زمانی.
- [ ] 🗑 آیا نسخه قبلی سایت اطلاعات بیشتری داشت؟
  - وقتی یک سایت برای مدتی فعال است، افراد می توانند اطلاعات را حذف کنند.
#### منابع و ابزار

##### کتاب
تکنیک های هوشمند منبع باز - مایکل بزل
https://inteltechniques.com/book1.html

کتابچه راهنمای تأیید - ویرایش شده توسط کریگ سیلورمن
https://datajournalism.com/read/handbook/verification-3

##### زیرساخت وب سایت
- [Blacklight](https://themarkup.org/blacklight): بازرس حریم خصوصی وب سایت مارکاپ در زمان واقعی.
- [builtwith.com](https://builtwith.com): زیرساخت سایت شامل آدرس IP، کدهای تجزیه و تحلیل، پشته فناوری و غیره مدل فریمیوم را در اختیار شما قرار می دهد.
- [DNSDBScout]((https://www.farsightsecurity.com/tools/dnsdb-scout/)): به شما امکان جستجو و «جستجوی انعطاف‌پذیر» برای جستجوهای غیرفعال dns از جمله نقشه‌برداری دامنه IP <-> را می‌دهد.
- [Dnslytics](https://dnslytics.com/): طیف وسیعی از ابزارها از جمله تجزیه و تحلیل معکوس و جستجوی معکوس DNS، و همچنین داده های WHOIS را ارائه می دهد. فریمیوم.
- [RiskIQ] (https://www.riskiq.com/): ابزاری «هوش تهدید» که به شما امکان می دهد IP معکوس، تجزیه و تحلیل معکوس، WHOIS، SSL، زیر دامنه ها و غیره را دریافت کنید.
- [Whoxy](https://www.whoxy.com/): ابزاری که به شما امکان می‌دهد ثبت‌های WHOIS تاریخی را مشاهده کنید. رایگان.
- آرشیو اینترنت [پسوند مرورگر] (chrome-extension://fpnmgdkabkmnadcjpehmlllkndpkmiak/about.html). 


###### حساب های رسانه های اجتماعی
- [Sensity AI](https://sensity.ai/deepfakes-detection/): بررسی کنید که آیا یک تصویر توسط GAN تولید شده است یا خیر. فریمیوم.
- [whotwi.com](https://en.whotwi.com/): یک نمایه در یک نگاه برای هر حساب کاربری در توییتر ایجاد کنید. رایگان. 
    </div>
