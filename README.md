مشروع التنبؤ بأداء الطلاب (Student Performance Regression)
نموذج تعلم آلة (Machine Learning) مبني في Google Colab باستخدام مكتبة scikit-learn للتنبؤ بقيمة مؤشر أداء الطالب (Performance Index) بناءً على بيانات مجموعة Student Performance من Kaggle.
جدول البيانات
- المصدر (Source): Kaggle — Student Performance
- الحجم (Shape): 10,000 صف × 6 أعمدة
- عمود الهدف (Target): Performance Index
- نوع المهمة (Task): تنبؤ بقيمة (Regression)
- عدد الخصائص بعد التجهيز: 5
جدول النتائج
- متوسط الخطأ المطلق (MAE): 1.81
- مرجع التخمين (Baseline) لو أخذنا المتوسط MAE: 16.21
- معامل التحديد (R²) على التدريب: 0.987
- معامل التحديد (R²) على الاختبار: 0.988
- حفظ أم فهم؟: الأداء متقارب على التدريب والاختبار
أهم 5 خصائص (Top Features)
- Previous Scores
- Hours Studied
- Sleep Hours
- Sample Question Papers Practiced
- Extracurricular Activities_Yes
  طريقة التشغيل
-افتح دفتر المشروع في Google Colab أو من المستودع على GitHub
- ارفع ملف البيانات CSV الخاص بـ Student Performance عند التشغيل
- شغّل الخلايا بالترتيب لمراجعة المعالجة والتدريب والتقييم والنتائج
ماذا تعلمت؟
- بناء نموذج انحدار (Regression) وتقييمه ومقارنته بمرجع التخمين (Baseline)
- قراءة مؤشرات الأداء MAE و R² والتحقق من تقارب الأداء بين التدريب والاختبار
- تنظيم ملفات المشروع وبطاقة المشروع (project_card.md) على GitHub
المصدر
مجموعة بيانات Student Performance على Kaggle:
https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression
تمت صياغة هذا الملف بمساعدة أداة ذكاء اصطناعي، وراجعت محتواه وتأكدت من صحة أرقامه.
