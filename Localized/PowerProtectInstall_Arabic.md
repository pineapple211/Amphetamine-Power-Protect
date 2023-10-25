# أهلا 👋🏼

على أجهزة الكمبيوتر المحمولة Apple Silcon Mac، قد لا يعمل وضع العرض المغلق كما هو متوقع بعد توصيل جهاز Mac الخاص بك أو فصله عن مصدر طاقة خارجي مثل محول طاقة أو شاشة مزودة بمصدر طاقة. لتجنب أية مشكلات، يمكنك تثبيت برنامج نصي وملف تكوين يعالج المشكلة.

أنا آسف حقًا لهذا، لكن Apple لا توفر أي طريقة أخرى. تعتقد شركة Apple أنها تعرف أفضل منك، ولن تسمح لك بالسماح لـ Amphetamine بتثبيت البرنامج النصي وملف التكوين المطلوب مباشرة لتجنب المشكلات المتعلقة بوضع العرض المغلق. لجعل الأمور "تعمل فقط" في الوقت الحاضر، يبدو أن عليك أن تفعل ذلك بنفسك. 🔨💪🏼

---

# كيفية تثبيت حماية الطاقة

1. <b>[قم بتنزيل البرنامج النصي Power Protect](https://raw.githubusercontent.com/x74353/Amphetamine/master/Files/PowerProtect_Script.zip)</b> وقم بتثبيته في الموقع التالي:

   ```/Users/YourUserAccount/Library/Application Scripts/com.if.Amphetamine/```

3. <b>[قم بتنزيل ملف تكوين Power Protect](https://raw.githubusercontent.com/x74353/Amphetamine/master/Files/PowerProtect_Configuration.zip)</b> وقم بتثبيته في الموقع التالي:

   ```/private/etc/sudoers.d/```

3. افتح Terminal.app من ```/Applications/Utilities/```، ثم انسخ الأمر التالي والصقه في نافذة طرفية:

     ```defaults write com.if.Amphetamine 'Enable Power Protect Install' -bool TRUE```

    ثم اضغط على مفتاح العودة لتنفيذ الأمر
