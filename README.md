<div dir="rtl" align='right'>

 ## المقدمة
تستخدم منصة تحليل البرمجيات الضارة  “Cuckoo” لتحليل البرامج والملفات الضارة والغير موثوقة وغير معروفة. وتتم عملية التحليل للملفات داخل بيئة معزولة حيث يتم تشغيل الملف وتحليل الاكواد البرمجية وتحليل السلوكيات التي يقوم بها الملف عبر النظام أو الشبكة. ولجعل المنصة ذات قيمة تم ربطها مع منصة “MISP” التي تحتوي على قاعدة بيانات كبيرة جدا من مؤشرات الاختراق IOCs التي يتم تحديثها بشكل مستمر من قبل المجتمع المعني بمشاركة التهديدات التي تشكل خطرا على الأنظمة والشبكات، وكذلك تم ربط هذه المنصة بأداة "Moloch" والتي تساعد في تحليل تدفق حزم البيانات التي تخرج من الشبكة اثناء تحليل البرمجيات الخبيثة.
  
 ### الميزات:
  - اضافة وربط منصة MISP 
  - اضافة وربط أداة Moloch
  - متوافق مع نسخة نسخة 18.04 من نظام Ubuntu
  - يعمل على مواصفات منخفضة 4RAM و2 Processor (يفضل رفعها لأداء أسرع)
  
## منصة Cuckoo
  تعمل المنصة على عزل البرامج الغير معروفة والغير الموثوقة وتنفيذها. حيث يتم استخدام المنصة لتحليل البرامج الضارة ديناميكيًا في بيئة معزولة، ثم استخراج السلوكيات الديناميكية مثل سلوك العملية وسلوك الشبكة أثناء تشغيله.

</br>
<p dir='rtl' align='right'>
  للتحميل من 
<a  href="url">هنا</a>
(تم تجربته فقط على VMWare)
  </br>
</br>
<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140654540-326bb2f3-103b-42d9-ba84-105f8320eaf3.jpg">
</br>

</br>
</br>
</br>
</br>
</br> 
</br>
</br>
</br>
</br>
</br>
</br>
</br>


## منصة MISP


منصة مفتوحة المصدر لمشاركة المعلومات في مجال الأمن السيبراني وهي عملية تبادل المعلومات بين المهتمين في الحماية على مستوى العالم لرفع مستوى حماية البنى التحتية من خلال مشاركة مؤشرات الاختراق IOCs فيما بينهم.(جميع الملفات التي يتم تحليلها من خلال Cuckoo يتم تخزينها في النظام الداخلي ولا يتم مشاركتها باي شكل من الاشكال مع المجتمع حتى تقوم بالسماح بذلك )


<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140654824-bc9a66f7-637d-4fae-b491-874d8c5e5c86.png">


</br></br></br></br></br></br></br></br></br></br></br></br></br>

## منصة Moloch

تستخدم لتسجيل والتقاط واجراء عمليات البحث عند مرور حزم البيانات عبر الشبكة مما تساعد المحلل بمعرفة سلوكيات الملف المشبوة في الشبكة.

<img align="right" width="500" height="300" src="https://user-images.githubusercontent.com/38037944/140655112-2ea7082e-39ad-41d2-9329-c7013ec3d7f5.png">


</br></br></br></br></br></br></br></br></br></br></br></br></br></br>

## طريقة الاستخدام
معلومات تسجيل الدخول
- أسم المستخدم: cuckoo
- كلمة السر: students

###  فتح ثلاثة نوافذ أوامر طرفية والكتابة كل أمر في طرفية مختلفة
- الامر الاول: cuck1
- الامر الثاني: cuck2
- الامر الثالث: cuck3

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

## مشاكل و حلول


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


