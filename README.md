# 📌 **CyHackers Tool - Termux MultiTool v6.0**  
**أداة متعددة الاستخدامات لتيرمكس لأغراض الأمن السيبراني، اختبار الاختراق، وإدارة النظام.**  

---

## 📋 **الوصف**  
**CyHackers** هي أداة متكاملة تعمل على **Termux** وتوفر مجموعة من الأدوات المفيدة في:  
✅ **أدوات واتساب** (فحص الأرقام، إرسال رسائل)  
✅ **أدوات الشبكات** (مسح المنافذ، اختبار اتصال TCP)  
✅ **أدوات الأمان** (إنشاء كلمات مرور قوية، فحص التجزئة)  
✅ **أدوات Termux** (تحديث الحزم، إدارة التطبيقات)  
✅ **أدوات الواي فاي** (فحص الشبكات، اختبار السرعة)  
✅ **نظام تحقق عبر OTP مع بوت تليجرام**  

---

## ⚙️ **التثبيت**  
### **1. تأكد من تثبيت Termux:**  
📥 حمل Termux من [F-Droid](https://f-droid.org/en/packages/com.termux/) (مستحسن) أو [Google Play](https://play.google.com/store/apps/details?id=com.termux).  

### **2. قم بتشغيل الأوامر التالية في Termux:**  
```bash
pkg update -y && pkg upgrade -y
pkg install git python -y
git clone https://github.com/coderxeg/cyHackers.git
cd cyHackers
pip install -r requirements.txt
python p.py
```

---

## 🔑 **كيفية الاستخدام**  
1. **تشغيل الأداة:**  
   ```bash
   cd cyHackers && python p.py
   ```
2. **استخدام بوت التليجرام:**  
   - افتح البوت على [تليجرام](https://t.me/TermuxMultiToolBot).  
   - اضغط على `🔐 إنشاء كود التحقق` للحصول على OTP.  
   - أدخل **User ID** و **OTP** في الأداة.  
3. **اختر الأدوات من القائمة:**  
   - أدوات واتساب 📲  
   - أدوات الشبكات 🌐  
   - أدوات الأمان 🔒  
   - أدوات Termux ⚙️  
   - أدوات الواي فاي 📶  

---

## 📢 **ميزات البوت التليجرام**  
- إنشاء أكواد OTP آمنة.  
- التحقق من حالة الجلسة.  
- دعم فوري عبر القناة.  

### **رابط القناة:**  
👉 [CyHackers على تليجرام](https://t.me/Story_GA)  

---

## ⚠️ **تحذير**  
- هذه الأداة للأغراض **التعليمية والأمنية فقط**.  
- لا تُستخدم لأي أنشطة غير قانونية.  
- المطور غير مسؤول عن أي سوء استخدام.  

---

## 📜 **الترخيص**  
هذا المشروع مرخص تحت **MIT License**.  

---

## 📬 **الدعم والاتصال**  
- **تليجرام:** [@coderxeg](https://t.me/coderxeg)  
- **القناة:** [Story_GA](https://t.me/Story_GA)  
- **GitHub:** [coderxeg](https://github.com/coderxeg)  

---

**🔥 تابعنا للتحديثات والأدوات الجديدة!** 🚀  

---

### **ملاحظة:**  
- إذا واجهتك مشكلة في تثبيت `pyfiglet`، جرب:  
  ```bash
  pkg install figlet -y
  pip install pyfiglet
  ```  
- تأكد من أن **Termux API** مثبت إذا أردت استخدام أدوات الواي فاي:  
  ```bash
  pkg install termux-api -y
  ```  

---

**🎉 استمتع باستخدام CyHackers!** 😃
