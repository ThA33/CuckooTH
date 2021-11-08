<h2 dir='rtl' align='right'>المقدمة</h2>
<p dir='rtl' align='right'>تستخدم منصة تحليل الفايروسات “Cuckoo” لتحليل البرامج الغير موثوقة وغير معروفة داخل بيئة معزولة ليتم تشغيل الملف وتحليل السلوكيات التي يقوم بها الملف عبر النظام أو الشبكة. ولجعل المنصة أكثر قيمة تم ربطها مع منصة “MISP” التي تحتوي على قاعدة بيانات كبيرة جدا من مؤشرات الاختراق IOCs  التي يتم اضافتها بشكل مستمر من قبل مجتمع مهتم بمشاركة التهديدات التي تشكل خطرا على الأنظمة والشبكات، وكذلك تم ربط أداة "Moloch" والتي تساعد في تحليل تدفق حزم البيانات التي تخرج من الشبكة اثناء تحليل البرمجيات الخبيثة.</p>

<h2 dir='rtl' align='right'>منصة Cuckoo</h2>
<p dir='rtl' align='right'>تعمل على عزل البرامج الغير معروفة والغير الموثوقة وتنفيذها. يتم استخدام المنصة لتحليل البرامج الضارة تلقائيًا وديناميكيًا في بيئة معزولة، ثم استخراج السلوكيات الديناميكية مثل سلوك العملية وسلوك الشبكة أثناء تشغيله.</p>

</br>
<p dir='rtl' align='right'>
  للتحميل من 
<a  href="url">هنا</a>
(تم تجربته فقط على VMWare)
</p>
</br>
<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140654540-326bb2f3-103b-42d9-ba84-105f8320eaf3.jpg">





</br></br></br></br></br></br></br></br></br></br></br></br></br></br>
<h2 dir='rtl' align='right'>منصة MISP</h2>

<p dir='rtl' align='right'>منصة مفتوحة المصدر لمشاركة المعلومات في مجال الأمن السيبراني وهي عملية تبادل المعلومات بين المهتمين في الحماية على مستوى العالم لرفع مستوى حماية البنى التحتية من خلال مشاركة مؤشرات الاختراق IOCs فيما بينهم.(جميع الملفات التي يتم تحليلها من خلال Cuckoo يتم تخزينها فالنظام فقط وليس للعامة)</p>


<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140654824-bc9a66f7-637d-4fae-b491-874d8c5e5c86.png">


</br></br></br></br></br></br></br></br></br></br></br></br></br></br>

<h2 dir='rtl' align='right'>منصة Moloch</h2>
<p dir='rtl' align='right'>تستخدم لتسجيل والبحث عند مرور حزم البيانات عبر الشبكة مما تساعد المحلل بمعرفة سلوكيات الملف المشبوة في الشبكة.</p>
<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140655112-2ea7082e-39ad-41d2-9329-c7013ec3d7f5.png">


</br></br></br></br></br></br></br></br></br></br></br></br></br></br>
<h2 dir='rtl' align='right'>الميزات</h2>
<ul>
  <li dir='rtl' align='right'>اضافة منصة MISP </li>
  <li dir='rtl' align='right'>اضافة أداة Moloch</li>
  <li dir='rtl' align='right'>نسخة 18.04 من نظام Ubuntu</li>
  <li dir='rtl' align='right'>يعمل على مواصفات منخفضة 4RAM و2 Processor (يفضل رفعها لأداء أسرع)</li>
</ul>  

<h2 dir='rtl' align='right'>طريقة الاستخدام</h2>
<h5 dir='rtl' align='right'>معلومات تسجيل الدخول</h5>
<ul>
  <li dir='rtl' align='right'>أسم المستخدم: cuckoo</li>
  <li dir='rtl' align='right'>كلمة السر: students</li>
</ul>

<h5 dir='rtl' align='right'>فتح ثلاثة نوافذ أوامر طرفية والكتابة كل أمر في طرفية مختلفة</h5>
<ul>
  <li dir='rtl' align='right'>cuck1</li>
  <li dir='rtl' align='right'>cuck2</li>
  <li dir='rtl' align='right'>cuck3</li>
</ul>
<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140656104-15b6ff03-b7ed-4b08-8f3a-3328dddaea28.png">
<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140656258-c3296e8c-15b4-45ac-b08f-c2955e00de4a.png">
<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140656323-ead38007-63a7-46e6-b31f-d8694f68357f.png">
</br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br>
<ol dir='rtl' align='right'>
  <li>يرمز الى رقم الحادثة التي تطابقت مع تحليل منصة Cuckoo</li>
  <li>يرمز الى تاريخ إضافة الحادثة الى قاعد بيانات MISP</li>
  <li>يرمز الى مؤشر الاختراق الذي تطابق مع قاعدة بيانات MISP وهنا يظهر لنا تطابق الهاش</li>
  <li>هنا توضيح بعض المعلومات عن الحادثة</li>
</ol> 
<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140656570-bd3000a5-1d42-421a-b1ce-1f850b191712.png">
<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140656629-14e66235-cc4c-497f-b2db-09062a20a3aa.png">
<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140656677-4a4d5ee8-48e6-41c1-bcc6-48dbcff0c293.png">
</br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br>
<h2 dir='rtl' align='right'>حلول لبعض المشاكل</h2>



<table dir='rtl' align='right' border="1px solid black">
  <tr>
    <th>الخطأ</th>
    <th>الحل</th>
  </tr>
  <tr>
    <td>CuckooCriticalError: Unable to bind ResultServer on 192.168.56.1</td>
    <td>فتح برنامج الVirtualbox  وتشغيل نظام الويندوز بشكل يدوي</td> 
  </tr>
   <tr>
    <td>فشل الاتصال في اداة Moloch</td>
    <td>service molochviewer stop && service molochviewer start#~
     </td> 
  </tr>
   <tr>
    <td>لحذف الملفات من قاعدة البيانات</td>
    <td>cuckoo clean#~
     </td> 
  </tr>
</table>


