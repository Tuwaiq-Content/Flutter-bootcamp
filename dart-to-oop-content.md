# معنى Object oriented programming – OOP


**البرمجة الكائنية OOP – Object oriented programming :**

هي عبارة عن نمط برمجة متقدمة، وفيه يقسم البرنامج إلى وحدات تسمى الكائنات (Objects)، كل كائن عبارة عن حزمة من البيانات والمتغيرات والثوابت والدوال ووحدات التنظيم وواجهات الاستخدام.

ويتم بناء البرنامج بواسطة استخدام الكائنات وربطها مع بعضها البعض وواجهة البرنامج الخارجية باستخدام هيكلية البرنامج وواجهات الاستخدام الخاصة بكل كائن.


## **ماهو Object؟**

لعل كل ما نراه في حياتنا اليومية من بشر وفواكه وحيوانات ووو هو كائن “object”…. , لو نظرنا لفئة الحيوانات مثلا فالأسد والنمر والغزال والأرنب كلٌ منهم يمثل كائناً مستقلا بذاته, و له خصائص تميزه عن الآخر , ويقوم بسلوكيات ووظائف.
إذن لكل كائن خصائص يتميّز بها و سلوكيات يقوم بها ومن هذه السلوكيات تنتج أحداث، وبهذه الثلاث عوامل يتميز كل كائن عما سواه: 


## **خصائص Properties :** 

وهي ما نسميه في البرمجة Data. 


## سلوكيات behavior أو وظائف يقوم بها: 
****
وهي ما نسميه بلغة البرمجة Methods or Functions.


## أحداث Events: 
****
تخص الكائن وتنتج عن سلوكياته! وكل كائن ( object ) ينتمي لفئة أعلى منه (class) فمثلا الفراولة هو كائن وهو ينتمي لفئة الفواكه, الأسد هو كائن وينتمي لفئة الحيوانات, السيارة والطائرة والسفينة هي كائنات وهي تنتمي للفئة التي هي وسائل النقل وهكذا …

فالبرمجة الكائنية هي طريقة جديدة لتصميم وكتابة البرامج، و الفكرة الرئيسية منها هي ان تقوم بتحويل البرنامج الى اجزاء مختلفة وكل جزء يمثل هدف او عمل معين، لكن حتى نشرح هذا الموضوع يجب ان نتبعد عن البرمجة قليلاً و نبسطها في بعض النظريات من خلال واقعنا.

فهنالك قاعدة تقول ان كل شي عبارة عن كائن – **Every things is an Object**

فلو اخذناها على لغة جافا Dart يعني ان كل شئ في لغة جافا عبارة عن كائن مثل المتغيرات والكلاسات والدوال وغيرها..
اما لو طبقناها على واقعنا يعني كل شئ عبارة عن كائن مثل السيارة او الهاتف او الانسان ..الخ .. وان لكل كائن له خصائص وافعال مثلاً الهاتف الذكي له خصائص مثل اللون (احمر,اسود,ازرق..) وله افعال مثل الاتصال وامور كثيرة تساعدنا في حياتنا اليومية.



> من اللغات التي تعمل بمفهوم  OPP:
> لغة Dart
> لغة C++ 
> لغة  Java
> لغة Python
> لغة C#
> لغة  JavaScript
> وغيرها الكثير من اللغات تدعم هذا المفهوم 
> 

 

##  البرمجة بستخدام مفهوم OPP عبارة عن نمط برمجة متخصص في المفاهيم التالية:


- **الكائنات Objects** :

وهو حزم البيانات والطرق الوظيفية والاحداث معاً في وحدات تعمل ضمن برنامج .وتعتبر الكائنات هي أساس هيكلية برمجة الحاسوب الكائنيّة.


- **المثيل** :

وهو شكل الصنف أو كائن محدد والذي ينشأ في وضع التشغيل، وبشكل آخر يمكن أن نسمي الصنف (نموذج).
التجريد Abstraction – قدرة البرنامج على تجاهل بعض واجهات المعلومات المتلاعبة، أي التركيز على المفهوم الأساسي للكائن وهيكليته النظرية وتجريده من طريقة العمل النهائية والتوجهات الخارجية.


- **التغليف Encapsulation** :

التأكد أن المستخدم لا يستطيع أن يغير البيانات الداخلية لكائن بطريقة مفاجئة، فقط طرق الكائن الداخلية يسمح لها بتعديل حالة الكائن وبياناته.
أي أنه لا يمكن التلاعب بالكائن وتغير معلوماته بأي طريقة بل أن هناك واجهة استخدام خاصة يضعها المبرمج ومن خلالها يمكن تغيير بيانات الكائن الداخلية وحالته.


- **تعدد الأوجه Polymorphism** :

بدلاً من استدعاء الإجراءات الفرعية مباشرة، تستطيع البرمجة الشيئية إرسال رسائل، الإجراء المعين الذي يتم نداؤه نتيجة الرسالة يعتمد على نوع الكائن الذي أُرسل له.
أي أنه باستخدام نفس اسم الاستدعاء يمكن استدعاء إجراءات وطرق مختلفة اعتماداً على نوع الكائن.


- **الوراثة** :

يستطيع الكائن وراثة خصائص كائن معين والزيادة عليها دون أن يتأثر الكائن الأصلي، فقد يكون هناك كائن «مركبة» فيه الخصائص العامة لكل المركبات مثل الاسم واللون ورقم التسجيل.
الكائن «الطائرة» ممكن أن يرث الكائن «مركبة» ويضيف عليه خصائص «الطائرة»، كذلك يمكن أن يكون هناك مثلاً كائن «مربع» فيه خصائص الطول والعرض ويمكن للكائن «مكعب» أن يرث من «المربع» ويضيف عليه خصائص العمق والحجم.

---


# Class and Object
عند البدء في كتابة برامجك فسوف تجد أنك بحاجة إلى تنظيم برنامجك بتنظيم الشيفرات البرمجية الي تكتبها بطريقة تُساعدك على جعل البرنامج مُقسم بطريقة منظمة تكون قابلة للإضافة والحذف والمعالجة والتصحيح وغيرها من عمليات التطوير الي يقوم بها المبرمج بالإضافة إلى أنها قابلة لإعادة الاستخدام في برامج أخرى إن أمكن. توفر لغة Dart البرمجة بأسلوب Object Oriented Porgramming واختصاره OOP . يوفر لك هذا الأسلوب أوالنموذج البرمجي طريقة منظمة لكتابة برمجياتك وتصحيحها والتعامل معها بشكل يساعدك على التطوير المستمر للشيفرة البرمجية وتوفر الوقت والجهد في ذلك من خال القدرة على إعادة استخدامها كما ذكرنا في برامج أخرى.
لذى لغة  Dart هي لغة برمجة object-oriented programming ، فهي تدعم مفهوم Class ، Object ,Inheritance ... إلخ.  


## مقدمة في مفهوم Object Oriented Programming في لغة Dart 

توفر Dart دعمًا مكثفًا لتطوير التطبيقات Object Oriented Programming واختصارها OOP، وهي طريقة برمجة تتضمن تقسيم متطلباتنا إلى أجزاء أصغر يمكن إدارتها. كل جزء منفصل قائم بذاته، ويمكن إعادة استخدامه في مكان اخر، وهذهِ الأجزاء هي ما نشير إليها باسم Object. عندما نخطط/نبرمج  Object فإننا نفعل ذلك مع Class، ويمكن اعتبار Class على أنه مخطط Object.
ننفذ Object من خلال Classes، وهذا يسمى نسخة من Class. كمثال للتوضيح عندما يكون هناك مخطط منزل فلا يمكننا العيش فيه لكن يمكننا بناء منزل من هذا المخطط لذلك يمكننا إنشاء نسخة منه. في كثير من الأحيان عندما نصمم Classes لتطبيقاتنا نكتبها لتمثيل أشياء من العالم الحقيقي. 

مبادئ OOP الأساسية ثلاثة وهي: Encapsulation و Polymorphism و Inheritance وسنتعرف عليها لاحقًا. 



## مفهوم Object

يمكننا تعريف بساطة في حال نظرنا للأشياء في عالمنا الواقعي على أنها مجموعة  objects ، فمثل لو نظرنا للناس على أنها مجموعة كائنات وكل شخص هو عبارة عن كائن object ونظرنا للسيارات على أنها كائنات وكل سيارة منها عبارة عن كائن object ونظرنا لكل ما حولنا من أشياء بهذا الأسلوب فسيصبح العالم من حولنا هو عبارة عن مجموعة من الكائنات المترابطة مع بعضها البعض والي تتواصل مع بعضها البعض بطريقة معينة.
يحتوي Object على بيانات data ودوال function تمثل العمليات.يتم تسمية البيانات بإسم attributes او Properties ويتم تسمية الدوال بإسم methods وهنا نقول أن Object هو عبارة عن مجموعة من البيانات attributes والدوال methods .يتكون الكائنات (Objects) ياخذ هذه الصفات من Class 

## مفهوم Class  ****

إذا قلنا أنك  object ، فأنت لست وحدك على هذه الأرض! هناك أشخاص آخرين، أليس كذلك؟ وهم object أيضاً، فأنت شخص، وهناك شخص غيرك أيضاً وإذا نظرنا لكل شخص على أنه object فسنقول أنهم يتشاركون في أشياء ويختلفون في أشياء، 
لذى نستطيع تعريف Class هو عبارة عن حاوية لمجموعة من التعليمات البرمجية التي يمكن أن تحتوي على دوال ومتغيرات وحلقات وغيرها، ويمكن  تعريف كل Class جديد في ملف dart منفصل. ويكون اسم الملف بنفس اسم Class. ويمكن انشاء من هذا الكلاس object 


مالذي استنتجناه من مما سبق ؟
يتم تمثيل Class بشكل بسيط على انه هو الهيكل العام او المخطط لشيء معين
ويتم تمثيل Object على انه هو شيء حقيقي تم انشاءه بهذا الهيكل او المخطط 

مثال توضيحي :

نستطيع انشاء Class خاص في الطلاب وهو الهيكل العام لوصف الطالب بشكل عام ويحتوي على خصائص التاليه :

-  اسم الطالب  
- الرقم الأكاديمي
- عمره 
- درجاته 

ويمكن تعريف الدوال بانها هي السلوك والتصرفات الخاصه في الطالب :

- مثل التحدث
- الحضور والغياب

وما إلى ذلك 
 


## تعريف Class في Dart 

قبل أن يتم إنشاء Object، نحتاج أولاً إلى إنشاء Class كما ذكرنا مسبقًا ليكون مخطط Object.
عند إنشاء Class في Kotlin نستخدم الكلمة المحجوزة class وبعدها يتم كتابة اسم لـ Class.
الصيغة الأساسية كما يلي:
**Syntax:**  


    class class_name {
    
       // Body of class comtains Properties and Methods}
    }

كلمة Class هي الكلمه الاساسية المستخدمه لانشاء Class  وما يوجد داخل {} يعتبر هو الجسم الخاص في Class 


داخل Class  يمكن كتابة  Properties وهي المتغيرات والثوابت التي يتم تضمينها في Class، ويتم تعريفها بنفس الطريقة التي يتم بها تعريف أي متغير آخر في Dart.
يوجد قسم الدوال Methods ويتم تعريف الدوال ليتم استدعاؤها. هذهِ الدوال خاصة في Class التي تؤدي عملية معينة عند استدعائها.



في المثال التالي سننشئ Class حساب بنكي:


    class BankAccount {
     
    }

الآن بعد أن أصبح لدينا Class، فإن الخطوة التالية هي إضافة بعض الخصائص إليه.

## إضافة الخصائص Properties إلى Class 

الهدف الرئيسي من OOP هو مفهوم يشار إليه باسم Data encapsulation أي تغليف البيانات. الفكرة وراء هذا المفهوم هو أنه يجب تخزين البيانات داخل Classes والوصول إليها فقط من خلال الطرق المحددة في تلك Class. وهي بستخدام dot notation و  يشار إلى البيانات المغلفة في Class على أنها خصائص أو متغيرات.
سنحتاج لنسخة من BankAccount class لدينا لتخزين بعض البيانات، وتحديدًا رقم الحساب المصرفي والرصيد الموجود حاليًا داخل الحساب. يتم إنشاء الخصائص بنفس الطريقة التي يتم بها إنشاء المتغيرات في Dart. لذلك يمكننا إضافة هذهِ المتغيرات على النحو التالي:

    class BankAccount {
        num accountBalance = 0.0;
        int accountNumber = 0;
    }

بعد تحديد الخصائص، فإن الخطوة التالية هي إضافة بعض الدوال.

وللوصول الى هذه المتغيرات الموجوده داخل Class يجب انشاء Object من هذا Class ثم استخدام مفهوم dot notation للوصول الى المتغيرات من داخل هذا Object الذي اخذ تفاصيل Class كما في المثال التالي : 


     class BankAccount {
       String accountName = "Fahad";
        num accountBalance = 0.0;
        int accountNumber = 0;
    }
    main(){
     BankAccount account1 = BankAccount();
     print(account1.accountName);
      print(account1.accountNumber);
      print(account1.accountBalance);
    }

المخرجات :


    Fahad
    0
    0



## مفهوم الدوال Methods  

يعتبر Methods class في الأساس إجراءات من الأوامر يمكن استدعاؤها لأداء مهام محددة ضمن سياق أي Class.
يتم إنشاء Methods داخل أقواس Class ويتم إنشائها باستخدام صيغة Function التي تعرفنا عليها بالسابق.
على سبيل المثال، سوف ننشئ Method لعرض رصيد الحساب، وسنقوم بإنشائه على النحو التالي:


    class BankAccount {
        var accountBalance: Double = 0.0
        String accountName = "";
     
     class BankAccount {
        num accountBalance = 0.0;
        int accountNumber = 0;
      
        displayBalance()
        {
           print("Name $accountName");
           print("Current balance is $accountBalance");
        }
    }
    }


## عمل نسخة من Class  

كل ما فعلناه حتى الآن هو تحديد مخطط Class فقط من أجل استخدام هذا Class، نحتاج إلى إنشاء Instance له. الخطوة الأولى في هذهِ العملية هي تعريف متغير لتخزين مرجع Instance عند إنشائه.
 نقوم بهذا على النحو التالي:

    BankAccount account1 = BankAccount();

عند التنفيذ سيتم إنشاء Instance من BankAccount class الخاصة بنا ويمكن الوصول إليها عبر متغير account1.
على النحو التالي:

    class BankAccount {
        num accountBalance = 0.0;
        String accountName = "";
     
        displayBalance()
        {
           print("Name $accountName");
           print("Current balance is $accountBalance");
        }
    }
    
    main(){
     BankAccount account1 = BankAccount();
     account1.accountBalance = 103.5;
     account1.accountName = "Fahad Alazmi";
    }

نلاحظ في داخل دالة Main استطعنا الوصول الى accountBalance عن طريق Object account1 الذي تم انشائه داخل Class BankAccount وتم اعطائه رصيد 103.5

 وايضاً تم الوصول الى accountName بنفس الطريقه وعطائه اسم Fahad Alazmi
 
 الان لو ادنا استعراض الرصيد يتم عن الطريق التالي :


    class BankAccount {
        num accountBalance = 0.0;
        String accountName = "";  
        displayBalance()
        {
           print("Name $accountName");
           print("Current balance is $accountBalance");
        }
    }
    
    main(){
     BankAccount account1 = BankAccount();
     account1.accountBalance = 103.5;
     account1.accountName = "Fahad Alazmi";
    
     account1.displayBalance(); //display Balance
    }

المخرجات :


    Name Fahad Alazmi
    Current balance is 103.5

بستخدام الدوالة باسم displayBalance تم عرض الرصيد ورقم الحساب لان Object باسم  account1 اخذ الخصائص والدوال الموجوده داخل class BankAccount 


---

# Constructors

سيحتاج أي Class غالبًا إلى تنفيذ بعض مهام التهيئة عند نقطة الإنشاء. يمكن تنفيذ هذهِ المهام باستخدام Constructors ****في ****داخل Class.

لتوضيح مفهوم Constructors او ماتسمى دالة البناء لنفترض عند انشاء Object تريد اعطاء القيم له مباشره في وقت الانشاء بدون استخدام Instances لذالك نحتاج استخدام Constructor ويتم انشائه بنفس اسم Class لنخذ مثال يوضح هذا المفهوم 

 في حالة BankAccount class  المثال في السابق سيكون من المفيد أن تكون قادرًا على تهيئة رقم الحساب ورصيد الحساب  بالقيم عند إنشاء نسخة جديدة من هذا Class. لتحقيق ذلك يمكن تعريف constructor داخل Class على النحو التالي:



    
    class BankAccount {
        num accountBalance = 0.0;
        String accountName = 'Fahad Alazmi';
      
      BankAccount(this.accountBalance,this.accountName);
      
        displayBalance()
        {
           print("Name: $accountName");
           print("Current balance is $accountBalance");
        }
    }

نلاحظ تم انشاء Constructor بنفس اسم Class وهو BankAccount داخل Class وتم استخدام this للاشاره الى المتغير الموجود داخل هذا Class 

ملاحظه : this يتم استخدامها بالنيابه عن  Class للاشاره الى شيء  موجود داخله 

الان في حال تم انشاء Object من نفس Class الموجود داخل Constructor سوف يتم اعطاء القيم الخاصه في accountBalance and accountName مباشره  


    class BankAccount {
        num accountBalance = 0.0;
        String accountName = 'Fahad Alazmi';
      
      BankAccount(this.accountBalance,this.accountName);
      
        displayBalance()
        {
           print("Name: $accountName");
           print("Current balance is $accountBalance");
        }
    }
    
    main(){
     BankAccount account1 = BankAccount(103.5,'Fahad Alazmi');
     account1.displayBalance();
    }

بهذا الشكل تم انشائه وعطاء القيم مباشره وقت الانشاء 

المخرجات :

    Name: Fahad Alazmi
    Current balance is 103.5

ايضا يمكن انشاء Constructor يتم تنفيذ في وقت الانشاء بنفس الشكل السابق فقط يتم اضافة اقواس Object {} على Constructor 


    class BankAccount {
        num accountBalance = 0.0;
        String accountName = 'Fahad Alazmi';
      
      BankAccount(this.accountBalance,this.accountName){
        print("Welcome to our Bank");
      }
      
        displayBalance()
        {
           print("Name: $accountName");
           print("Current balance is $accountBalance");
        }
    }

نلاحظ تم اضافة جملة "Welcome to our Bank"  داخل Constructor  الان في حال تم انشاء اوبجكت من هذا الكلاس سوف يتم طباعة "Welcome to our Bank” في وقت الانشاء  كما هو في المثال التالي :


    class BankAccount {
        num accountBalance = 0.0;
        String accountName = 'Fahad Alazmi';
      
      BankAccount(this.accountBalance,this.accountName){
        
        print("Welcome th our Bank");
      }
      
        displayBalance()
        {
           print("Name: $accountName");
           print("Current balance is $accountBalance");
        }
    }
    
    main(){
     BankAccount account1 = BankAccount(103.5,'Fahad Alazmi');
    }

المخرجات :


    Welcome to our Bank

---

# Inheritance
في هذا الدرس ان شاءالله راح نتعلم على واحد من أهم المفاهيم  في البرمجة كائنية التوجه او الـ object oriented programming  وهو مفهوم اinheratance او الوراثة

# المفهوم | Concept

الوراثة تعني inheritance وفي البرمجة تعني أن ترث صفات وأفعال من class محدد. 
مفهوم الوراثة يتيح لك أن تعيد استخدام class بدون أن تعيد انشائه من الصفر
ملاحظة: يرث class من class واحد وايضاً يمكن  أن يورّث Class  اكثر من class ويسمى أول class في التسلسل الوراثي base class او super Class

![Derived Class (child) -  هو class  parent اللذي يرث من الـ  Base Class (parent) - هو class اللذي يورث](https://paper-attachments.dropbox.com/s_8E9EF3802D29B5FF299CEA84504B6FE1923FFBF6EEF82F33958CACEAF581152F_1626188552487_Capture2.PNG)



لاحظ في الرسمة التالية بأن class B يرث من class A, وكل من class C و class D يرثان من class B


![User-uploaded image: Screen+Shot+1442-09-13+at+2.13.08+PM.png](https://paper-attachments.dropbox.com/s_6DB43611255FEB5D95F3A3AFA097D69F41EE068F9FA63453E2854A824FC3CB17_1619349200698_Screen+Shot+1442-09-13+at+2.13.08+PM.png)


ملاحظة جانبية: يسمى أول class في التسلسل الهرمي للوراثة superClass وتسمى class المتفرعة sub class


**نقاط مهمة:** 

- عند عمل الوراثه يتم وراثة من superClass جميع الخصائص والدوال ما عدا دالة البناء constructor الخاصه في superClass.
- لا تدعم Dart أيضًا الوراثة المتعددة.
- يتم استخدام كلمة extends لعمل الوراثه 

لناخذ مثال يوضح فكرة الوراثه في لغة dart :


    class Human {
      String name;
      int yearOfBirth;
      Human(this.name, this.yearOfBirth);
      displayInfo() {
        print("Name: $name");
        print("Year of birth is $yearOfBirth");
      }
    }
    void main() {
      Human object1 = Human("Fahad", 1994);
      object1.displayInfo();
    }

المخرجات :

    Name: Fahad
    Year of birth is 1994

في المثال في الاعلى نلاحظ انه يوجد Class باسم Human فيه بعض الخصائص والدوال بداخله هي موجوده في كل انسان 

لو اردنا انشاء Class اخر خاص في الطلاب يرث من Class Human  لان الصفات التي يحملها الطالب موجوده في Class Human فكل طالب لديه اسم وايضا لديه سنة ميلاد سوف يتم بالشكل التالي :


     class Human {
      String name;
      int yearOfBirth;
      Human(this.name, this.yearOfBirth);
      displayInfo() {
        print("Name: $name");
        print("Year of birth is $yearOfBirth");
      }
    }
    class Person extends Human{
      
    }
    void main() {
      Human object1 = Human("Fahad", 1994);
      object1.displayInfo();
    }

نلاحظ تم انشاء Class  باسم Person واضافة extends ثم اسم Class الذي سوف يتم عمل الوراثه منه وهو Human

بهذا الشكل سوف نجد ان الكلاس Person  يشير الى ان هناك خطاء في هذه الحاله لان Class الذي يرث منه وهو Class Human  لديه دالة بناء تطلب بعض المدخلات وهي الاسم وتاريخ الميلاد فيتم اسناد دالة بناء باسم Class يتم اعطائها القيم الذي يطلبها كلاس الاب (Class Human) ويتم بستخدام كلمة super للاشاره للمتغيرات الموجوده في Class الاب  كما في الشكل التالي :

      Person(super.name, super.birthday);

سوف يصبح الكود بهذا الشكل :


    class Human {
      String name;
      int birthday;
      Human(this.name, this.birthday);
      displayInfo() {
        print("Name: $name");
        print("Date of birth is $birthday");
      }
    }
    class Person extends Human{
      Person(super.name, super.birthday);
    }
    void main() {
      Human object1 = Human("Fahad", 1994);
      object1.displayInfo();
    }
    

الان اصبح  Class Person يرث من Class Human  جميع الخصائص والدوال ولو تم انشاء اوبجكت من Class Person نستطيع الوصول الى جميع محتويات الموجوده في Class Human كما في المثال التالي :


     class Human {
      String name;
      int birthday;
      Human(this.name, this.birthday);
      displayInfo() {
        print("Name: $name");
        print("Date of birth is $birthday");
      }
    }
    class Person extends Human {
      Person(super.name, super.birthday);
    }
    void main() {
      Person object = Person("Saleh", 1994);
      print(object.name);
      object.displayInfo();
    }

المخرجات :


    Saleh
    Name: Saleh
    Date of birth is 1994



## **مفهوم Overriding :** 

عند استخدام الوراثة ،اذا كنا نريد استخدام دالة موجودة في superclass ولكن نحتاج لتعديل على هذه الدالة للتوافق مع مانحتاجة، من الممكن ان نستدعي الداله  ولكن نغير فعلها في subclass يسمى هذا المفهوم override 
قبل البدء في مثال ، هناك ثلاث قواعد يجب اتباعها عند استخدام override . 

- أولاً ، يجب أن تأخذ الدالة بنفس عدد المدخلات في الدالة الموجودة في superclass ,
- ثانيًا ، يجب أن يكون لدالة الجديدة نفس نوع الإرجاع مثل الدالة الأصلية. 


في  Human class لدينا ، لدينا دالة تسمى displayInfo والتي تعرض اسم الحساب وسنة الميلاد . في  Person class الخاصة بنا ، قد نرغب أيضًا في طباعةالتفاصيل بطريقه مختلفه. لتحقيق ذلك ، نعلن ببساطة عن إصدار جديد من دالة  displayInfo في Human  الخاصة بنا ، مسبوقة بالكلمة الأساسية override:


    class Human {
      String name;
      int birthday;
      Human(this.name, this.birthday);
      displayInfo() {
        print("Name: $name");
        print("Date of birth is $birthday");
      }
    }
    class Student extends Human {
      Student(super.name, super.birthday);
      @override
      displayInfo() {
        print("my name is ${super.name} and my Date of birth is ${super.birthday}");
      }
    }
    void main() {
      Student object = Student("Saleh", 1994);
      print(object.name);
      object.displayInfo();
    }
    

ولكن قبل استخدام دالة displayInfo داخل Person class  يفضل علينا استخدام @override قبل الداله : 

المخرجات :

    Saleh
    my name is Saleh and my Date of birth is 1994

في المثال اعلاه تم استخدام الدالةdisplayInfo في subclass مع إضافة بعض التعديلات . 

---



# Const, Final and late Keyword

ß
تدعم لغة Dart تخصيص قيمة ثابتة لمتغير. يتم ذلك عن طريق استخدام الكلمة الأساسية التالية:


1. const keyword
2. final keyword

تُستخدم هذه الكلمات الرئيسية للحفاظ على قيمة المتغير ثابتة في جميع أنحاء الكود ، مما يعني أنه بمجرد تحديد المتغير لا يمكن تغيير حالته. لا توجد قيود او شروط إذا كانت هذه الكلمات الأساسية لها نوع بيانات محدد أم لا.


## مفهوم Final keyword

يتم استخدام final keyword لعطاء القيمه للمتغير في وقت عملية runTime ثم تخزين قيم المتغير بشكل ثابت ولا يمكن تغييرها في المستقبل ، ولا يمكن لأي نوع من العمليات التي يتم إجراؤها على هذه المتغيرات تغيير قيمتها.

لناخذ مثال بسيط يوضح فكرة final 
لنفترض لدينا متغير باسم nameAcademy هو يشري الى اسم الاكاديمية 


    void main(){
      
    String nameAcademy = "Tuwaiq Academy";
    print(nameAcademy);
    }

المخرجات :


    Tuwaiq Academy

في هذه الحال نستطيع تغير قيمة المتغير  عند استدعائه ثم اعطائه قيمه جديده كما في المثال التالي :


    void main(){
      
      String nameAcademy = "Tuwaiq Academy";
      nameAcademy = "Tuwaiq";
      print(nameAcademy);
    }

المخرجات :


    Tuwaiq

اما في حال تم استخدام كلمة final قبل اسم المتغير لن يتم تغير قيمة وسوف يظهر خطاء يشير الى عدم امكانية تغير القيمه المتغير بعد تعريفها بانها final كما في المثال التالي 


    void main(){
      
     final String nameAcademy = "Tuwaiq Academy";
      nameAcademy = "Tuwaiq";
      print(nameAcademy);
    }

المخرجات :


    Error: Can't assign to the final variable 'nameAcademy'.
      nameAcademy = "Tuwaiq";
      ^^^^^^^^^^^
    Error: Compilation failed.


ايضا في حال تم انشاء متغير وتم تعريفه على انه final بدون اعطاءه قيمه يمكن اعطاءه قيمه في وقت عملية runtime وسوف يتم تخزين القيمه ولا يسمح فيه تغيرها بعد تخزينها كما في المثال التالي :

    void main(){
      
     final String nameAcademy;
      nameAcademy = "Tuwaiq Academy";
      print(nameAcademy);
    }

المخرجات :

    Tuwaiq Academy

وايضا في حال تم انشاء Class يحتوي على properties داخل Class هو عباره عن final  سوف يتم اسناد القيمه له مره واحده ثم لن يسمح لك بتغير القيمه مره اخرى 


     class BankAccount {
     static String nameBank = "Tuwaiq Bank";
     String accountName;
        num accountBalance = 0.0;
        int accountNumber = 0;
       BankAccount(this.accountName,this.accountBalance,this.accountNumber);
       
        displayBalance()
        {
           print("Name: $accountName");
           print("Current balance is $accountBalance");
        }
       
    }
    
    void main(){
      
      BankAccount ob1 = BankAccount("Fahad",14.58,1);
    
      ob1.displayBalance();
      
      ob1.accountName = "Saleh";
      ob1.displayBalance();
    }




## مفهوم const keyword




يتم استخدام const keyword لعطاء القيمه للمتغير قبل عملية runTime و تخزين قيم المتغير بشكل ثابت ولا يمكن تغييرها ، ولا يمكن لأي نوع من العمليات التي يتم إجراؤها على هذه المتغيرات تغيير قيمتها.

لناخذ مثال بسيط يوضح فكرة const 
لنفترض لدينا متغير يشير الى الوقت  باسم timeNow 


    void main() {
      String timeNow = "${DateTime.now()}";
      print(timeNow);
    }

دالة DateTime.now هي لجلب الوقت من النظام في وقت عملية تشغيل البرنامج (runtime) في هذا الحاله سوف يتم طباعة 
المخرجات :

    2022-05-24 15:08:23.344470

لقد اخذ الوقت وتم اسناده للمتغير timeNow على نص لان تم استخدام مفهوم String Interpolation بستخدام علامة $ داخل علامات “” التنصيص

الان لو جعلنا هذا المتغير هو عباره عن final مثل ماتعلمنا سابقاً لان يصبح هناك اي مشكله  لان مفهوم final يتم اسناد القيمه وقت علمية تشغيل البرنامج (runTime) 


    void main() {
      final String timeNow = "${DateTime.now()}";
      print(timeNow);
    }

بستخدام كلمة final سوف يتم اسناد القيمه وتخزينها ولن يتم تغيرها في اي حال من الاحوال الا اذا تم تشغيل البرنامج مره اخرى 

المخرجات :


    2022-05-24 15:08:23.344470

الان سوف نلاحظ الفرقات بين استخدام final و const لو تم تغير كلمة final الى const سوف يتم اظهار لك رساله خطاء تخبرك ان قيمة الوقت سوف يتم اسناده في وقت عملية تشغيل البرنامج (runtime) واستخدام const يتم اسناد لها القيمه قبل تشغيل البرنامج في وقت كتابة الكود وتطوير البرنامج 


    void main() {
      const String timeNow = "${DateTime.now()}";
      print(timeNow);
    }

المخرجات :

    : Error: Cannot invoke a non-'const' constructor where a const expression is expected.
    bin/dart_project.dart:2
    Try using a constructor or factory that is 'const'.
      const String timeNow = "${DateTime.now()}";

لذى أستخدام const يجب تعريف المتغير وعطائه قيمه قبل تشغيل البرنامج  كما هو في المثال التالي :


    void main() {
      const String timeNow = "time for now";
      print(timeNow);
    }

المخرجات :

    time for now



الفروقات بين final and const :


- يتم استخدام final لانشاء المتغير وسناد قيمته قبل او بعد تشغيل البرنامج ثم لا يمكن تغير قيمته 
- يتم استخدام const في حال اردت انشاء متغير وتعريف قيمته قبل عملية تشغيل البرنامج ولا يمكن تغير قيمته




## مفهوم late keyword

يمكن استخدام late  أثناء انشاء متغير تريد تعريف يقيمته في وقت اخر.

كما في المثال التالي :


    String title;
    main(){
    getTitle();
    }
    
    void getTitle(){
    title = 'Dart';
    print('Course of $title');
    }

لدينا متغير خارج main هو عباره عن title  من نوع String ولدي Function عند استدعائها يتم وضع داخل هذا المتغير قيمه في هذه الحاله سوف يتم اظهار لي خطاء يوضح لي انه يجب ان اضع داخل المتغير title قيمه 

المخرجات :

    Error: Field 'title' should be initialized because its type 'String' doesn't allow null.
    String title;


لحل هذه المشكله يتم استخدام كلمة late لاخبار المترجم (complier) ان القيمه سوف يتم وضعها في وقت اخر كما في المثال التالي :


    late String title;
    main(){
    getTitle();
    }
    
    void getTitle(){
    title = 'Dart';
    print('Course of $title');
    }

باضافة كلمة late سوف يتم حل المشكله وسوف ينتظر المترجم القيمه التي سوف يتم اسنادها في وقت لاحق  وسوف يتم اظهار لي النتيجه التاليه عند عمل run

    Course of Dart

لذى فا استخدام كلمة late يسمح لانا في تاخير اسناد القيمه للمتغير الى وقت اخر في عملية runtime 



