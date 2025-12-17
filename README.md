# Netflix EDA Project

## Project Overview

المشروع ده عبارة عن 
Exploratory Data Analysis
Netflix على بيانات أفلام ومسلسلات .


## Dataset

 المصدر: Kaggle
 الاسم: Netflix Movies and TV Shows
 الملف: netflix_titles.csv

الداتا فيها معلومات عن الأفلام والمسلسلات زي:

 نوع المحتوى (Movie / TV Show)
 العنوان
 المخرج الممثلين
 الدولة
 سنة الإصدار
 التصنيف العمري (Rating)
 المدة
 النوع (Genre)



## Project Goal: فهم شكل الداتا وعدد الأعمدة والصفو تنظيف الداتا والتعامل مع القيم الناقص تحليل الفرق بين الأفلام والمسلسلا تحليل المحتوى حسب السنة، الدولة، النوع، والتصني عرض النتائج بشكل بسيط باستخدام الرسوم البيانية



## Tools Used
 Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook



## Analysis Steps

1. قراءة الداتا واستكشافها

 عرض أول شوية صفوف
 معرفة حجم الداتا
 فحص أنواع الأعمدة

2. Data Cleaning

 اتعامل مع Missing Values
 تعديل أنواع البيانات لو محتاجة
 التأكد إن مفيش بيانات مكرر

3. EDA

 مقارنة عدد Movies و TV Shows
 تحليل الإصدارات حسب السنين
 معرفة أكتر الدول إنتاجًا
 تحليل أشهر Genres
 تحليل Rating



## Visualizations

* Bar charts
* Line charts
* Count plots

تم استخدام Matplotlib و Seaborn في الرسومات.



## Expected Insights

 هل Netflix بتركز أكتر على الأفلام ولا المسلسلات؟
 أكتر سنوات كان فيها محتوى جديد
 أكتر دول منتجة للمحتوى
 أشهر Genres و Ratings


* تحليل مدة الأفلام والمسلسلات
* مقارنة أعمق بين Movies و TV Shows
* إضافة تحليلات أكتر حسب الوقت


## Project Structure

netflix-eda/

 data/

  * netflix_titles.csv
 notebooks/

  * netflix_eda.ipynb
 README.md
 







