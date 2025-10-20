<div align="center">

<img src="https://raw.githubusercontent.com/SP-XD/SP-XD/main/images/hellocoders_rounded.gif" alt="Hello Coders" width="60%"/> <br>
<img src="https://raw.githubusercontent.com/SP-XD/SP-XD/main/images/dev-working_rounded.gif" alt="Workspace" width="40%"/><br> 

</div>

---

## 🧠 About Me
🤖 أنا ميس الشمراني، متخصصة في **الذكاء الاصطناعي وتدريب نماذج ML**  
🌱 مهتمة بتعلم **نشر النماذج (Model Deployment) و MLOps**  
💬 اسألوني عن مشاريع AI أو Python أو تدريب النماذج  
🐧 أحب استكشاف أنظمة **Linux** وأدوات الأتمتة

---

# 🔥 Predicting the Extent of Forest Fire Damage

## 📄 Project Overview
هدف المشروع بناء **نموذج انحدار (Regression Model)** لتوقع مساحة الحرائق (`area`) الناتجة عن الحرائق الغابية باستخدام بيانات الطقس، مكونات **Fire Weather Index (FWI)**، والموقع الجغرافي. ركز المشروع على التعامل مع **مشكلة البيانات غير المتوازنة** لضمان توقع صحيح للحوادث الكبيرة.

## 🎯 Methodology
- معالجة skewness عبر تحويل **log1p** للمتغير `area`.  
- ترميز الخصائص التصنيفية (**One-Hot Encoding**) للأعمدة `month`، `X`، `Y`.  
- تصحيح عدم التوازن عبر **Oversampling** للأحداث النادرة.  
- استخدام نموذج **XGBoost Regressor** لأداء قوي ومرن.

## 📊 Results
- RMSE النهائي: **3.765** على مجموعة الاختبار  
- النموذج الآن يتوقع مناطق حرائق كبيرة بشكل أفضل، مع ميل طفيف للتقدير الزائد (مرغوب في تقييم المخاطر).

---

## 📁 Project Structure

