# 📊 تحليل المبيعات والأرباح - Dashboard تفاعلي باستخدام Power BI

## نظرة عامة
مشروع تحليل بيانات مبيعات وأرباح تفاعلي باستخدام Power BI، يهدف إلى تحليل الأداء المالي ومتابعة الإيرادات والأرباح حسب تصنيفات المنتجات والفترات الزمنية.

## الهدف من المشروع
- تحليل الإيرادات والأرباح عبر الأرباع السنوية (Quarters)
- دراسة أداء فئات المنتجات المختلفة (Product Categories)
- متابعة عدد الطلبات حسب كل فئة
- توفير رؤى استراتيجية لتحسين الربحية

## الأدوات والتقنيات المستخدمة
- **Microsoft Power BI**: 
  - Power Query لاستيراد وتحويل البيانات
  - DAX لإنشاء المقاييس والحقول المحسوبة
  - العلاقات بين الجداول (Relationships)
  - الرسوم البيانية التفاعلية
  - Slicers للتصفية الديناميكية

## محتويات Dashboard
- **مؤشرات الأداء الرئيسية KPIs**:
  - إجمالي الإيرادات (Total Revenue)
  - إجمالي الأرباح (Total Profit)
  - عدد الطلبات (Total Orders)
  
- **الرسوم البيانية**:
  - تحليل الإيرادات والأرباح حسب الربع السنوي (Line Chart)
  - عدد الطلبات حسب فئة المنتج (Column Chart)
    - Toys
    - Art & Crafts
    - Games
    - Sports & Outdoors
    - Electronics

## معالجة البيانات باستخدام Power Query
- استيراد بيانات من ملفات منفصلة (CSV/Excel)
- تنظيف البيانات وإزالة التكرارات
- دمج الجداول (Merge Queries)
- إنشاء أعمدة مخصصة
- تحويل أنواع البيانات

## نموذج البيانات والعلاقات
- **الجداول الرئيسية**: Sales, Products, Date
- **العلاقات**: Many-to-One بين جدول المبيعات وجداول الأبعاد
- **نموذج Star Schema** لتحسين الأداء

## ملاحظة
البيانات المستخدمة في هذا المشروع هي **بيانات وهمية** لأغراض التدريب والتطوير، وتم استيرادها من ملفات منفصلة ودمجها باستخدام Power Query.

## معاينة المشروع
![Dashboard الرئيسي](../images/dashboard1.png)
*صورة 1: نظرة عامة على Dashboard مع تحليل الإيرادات والأرباح وفئات المنتجات*
![Dashboard الرئيسي](images/dashboard2.png)

## كيفية الاستخدام
1. قم بتحميل ملف Power BI (.pbix)
2. استخدم أدوات التصفية (Slicers) لتحديد:
   - فئة المنتج (Product Category)
   - اسم المتجر (Store Name)
   - الربع السنوي (Quarter)
3. شاهد التحديث الفوري للرسوم البيانية والمؤشرات
4. تفاعل مع الرسوم البيانية (تصفية متقاطعة - Cross Filtering)

## المهارات المعروضة
- تحليل البيانات Data Analysis
- Power Query (ETL)
- بناء نموذج بيانات Data Modeling
- إنشاء العلاقات Relationships
- كتابة DAX
- تصميم Dashboards احترافية
- تصور البيانات Data Visualization

## هيكل المشروع
```
PowerBI-Sales-Analysis/
│
├── Muwafaq_Alkmali_PowerBI_Dashboard.pbix
├── README.md
│
├── data/
│   ├── sales_data.csv
│   ├── products.csv
│   └── stores.csv
│
└── images/
    └── dashboard1.png
    
```

## تحميل المشروع
- 📥 [ملف Power BI الرئيسي](Muwafaq_Alkmali_PowerBI_Dashboard.pbix)
- 📂 [ملفات البيانات المصدر](Data/)
- 📸 [معاينة Dashboard](images/)

## تواصل معي

- البريد الإلكتروني: [muwaffaqalkmaly@gmail.com]
