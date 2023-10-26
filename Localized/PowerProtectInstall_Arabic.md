# أهلا 👋🏼
<b>View this message in your preferred language:</b><br><a href="https://x74353.github.io/Amphetamine-Power-Protect/Localized/PowerProtectInstall_Arabic.html">العربية</a><b> | </b><a href="https://x74353.github.io/Amphetamine-Power-Protect/Localized/PowerProtectInstall_ChineseSimplified.html">简体中文<a><b> | </b><a href="https://x74353.github.io/Amphetamine-Power-Protect/Localized/PowerProtectInstall_Dutch.html">Nederlands</a><b> | </b><a href="https://x74353.github.io/Amphetamine-Power-Protect/Localized/PowerProtectInstall_French.html">Français</a><b> | </b><a href="https://x74353.github.io/Amphetamine-Power-Protect/">English</a><b> | </b><a href="https://x74353.github.io/Amphetamine-Power-Protect/Localized/PowerProtectInstall_German.html">Deutsch</a><b> | </b><a href="https://x74353.github.io/Amphetamine-Power-Protect/Localized/PowerProtectInstall_Japanese.html">日本語</a><b> | </b><a href="https://x74353.github.io/Amphetamine-Power-Protect/Localized/PowerProtectInstall_Korean.html">한국어</a><b> | </b><a href="https://x74353.github.io/Amphetamine-Power-Protect/Localized/PowerProtectInstall_Portuguese.html">Português Brasileiro</a><b> | </b><a href="https://x74353.github.io/Amphetamine-Power-Protect/Localized/PowerProtectInstall_Vietnamese.html">Tiếng Việt</a>
<br><br>
على أجهزة الكمبيوتر المحمولة Apple Silicon Mac، قد لا يعمل وضع الشاشة المغلقة كما هو متوقع بعد توصيل أو فصل جهاز Mac الخاص بك من مصدر طاقة خارجي مثل محول الطاقة أو الشاشة ذات التغذية بالطاقة. لتجنب أية مشكلات، يمكنك تثبيت سكريبت وملف تكوين يعالج المشكلة.

أنا آسف حقًا لهذا، ولكن Apple لا تقدم وسيلة أخرى. تعتقد Apple أنها تعرف أفضل منك، ولن تسمح لك بالسماح لـ Amphetamine بتثبيت السكريبت وملف التكوين اللازمين لتجنب المشاكل مع وضع الشاشة المغلقة مباشرة. في الوقت الحالي، يبدو أنه يجب عليك القيام به بنفسك لجعل الأمور تعمل "بسهولة". 🔨💪🏼

---

# كيفية تثبيت حماية الطاقة

1. <b>[قم بتنزيل البرنامج النصي Power Protect](https://raw.githubusercontent.com/x74353/Amphetamine/master/Files/PowerProtect_Script.zip)</b> وقم بتثبيته في الموقع التالي:

   ```/Users/YourUserAccount/Library/Application Scripts/com.if.Amphetamine/```

3. <b>[قم بتنزيل ملف تكوين Power Protect](https://raw.githubusercontent.com/x74353/Amphetamine/master/Files/PowerProtect_Configuration.zip)</b> وقم بتثبيته في الموقع التالي:

   ```/private/etc/sudoers.d/```

3. افتح Terminal.app من ```/Applications/Utilities/```، ثم انسخ الأمر التالي والصقه في نافذة طرفية:

     ```defaults write com.if.Amphetamine 'Enable Power Protect Install' -bool TRUE```

    ثم اضغط على مفتاح العودة لتنفيذ الأمر
