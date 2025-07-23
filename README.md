
✅ أولاً: تثبيت جميع الحزم المطلوبة

pkg update && pkg upgrade

pkg install python -y

pkg install python3 -y

pkg install git -y

pkg install wget -y

pkg install curl -y

pkg install openssl -y

pkg install libjpeg-turbo -y

pkg install clang -y

pkg install libffi -y

pkg install libxml2 -y

pkg install libxslt -y

pkg install freetype -y

pkg install libpng -y

pkg install libjpeg-turbo libpng freetype -y


---

📦 ثانياً: تثبيت المكاتب المطلوبة

pip install -r requirements.txt


---

💻 ثالثاً: تشغيل أداة الإخترا

python tracker_server.py


---

🌐 رابعاً: تشغيل ngrok

> تأكد من أنك قمت بتثبيت أداة ngrok وتسجيل الدخول بحسابك.




---

🖼️ خامساً: فتح أداة تلغيم الصورة

python make_pdf.py


---

📝 ملاحظات إضافية:

تأكد من أنك تعمل داخل بيئة Termux.

إذا ظهرت لك أخطاء أثناء التثبيت، راجع أسماء الحزم أو تأكد من اتصالك بالإنترنت
