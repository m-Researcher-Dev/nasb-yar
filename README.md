# Nasb-Yar — Smart Windows Software Installer
# نصب‌یار — نصب‌کننده هوشمند نرم‌افزار ویندوز

🏆 **3rd Place Nationally — Young Khwarizmi Festival 1404 (Computer Science)**
🏆 **رتبه سوم کشوری — جشنواره جوان خوارزمی ۱۴۰۴ (گروه کامپیوتر)**

---

### 🇬🇧 English Description

**Nasb-Yar** is a desktop application with a web-based UI (Flask) that fully automates the software lifecycle on Windows. By taking user needs in natural Persian language, it finds, downloads, extracts, and silently installs software without user intervention. The output is a standalone `EXE` file requiring no Python installation.

**✨ Key Features:**
- **Drastic time reduction:** Cuts installation time for 10 apps from ~45 minutes to ~5 minutes (88.7% reduction).
- **Advanced download manager:** Multi-threaded downloading for chunked files.
- **Smart extraction:** Supports multi-volume archives and auto-applies standard passwords.
- **AI Integration:** Uses OpenAI-compatible APIs for generating and executing custom scripts (e.g., managing helper or crack files if present in the package).
- **Hardware detection:** Reads system specs and installed versions via Windows Registry (`winreg`) to select the most compatible version.
- **Format support:** EXE, MSI, ZIP, 7z, RAR.
- **Web UI:** Simple interface to manage installed apps and uninstall them.

**🛠 Tech Stack:**
- **Language & Framework:** Python, Flask
- **Automation:** Selenium, webdriver-manager, PyAutoGUI, pywinauto
- **System Management:** psutil, pywin32, pefile, py-cpuinfo, winreg
- **Compression:** py7zr, rarfile
- **AI & Translation:** OpenAI-compatible API, translate, Unidecode
- **Web Scraping:** requests, beautifulsoup4, ddgs

**⚠️ Limitations:**
- Currently supports ~80% of single-file apps (cannot distinguish similar names like Notepad vs. Notepad++).
- Windows only.

**🚀 How to Run:**
```bash
pip install -r requirements.txt
python app.py
```
Or run `nasbyar.exe` directly.

---

### 🇮🇷 توضیحات فارسی

**نصب‌یار** یک اپلیکیشن دسکتاپ با رابط کاربری وب (Flask) است که فرآیند نصب نرم‌افزار در ویندوز را به صورت کاملاً خودکار و هوشمند انجام می‌دهد. این برنامه با دریافت نیاز کاربر به زبان فارسی، نرم‌افزار مناسب را پیدا کرده، دانلود می‌کند، استخراج می‌کند و بدون نیاز به دخالت کاربر (Silent Install) آن را نصب می‌کند. خروجی نهایی برنامه یک فایل مستقل `EXE` است که نیازی به نصب پایتون ندارد.

**✨ ویژگی‌های کلیدی:**
- **کاهش چشمگیر زمان نصب:** نصب ۱۰ نرم‌افزار را از حدود ۴۵ دقیقه به حدود ۵ دقیقه کاهش می‌دهد (کاهش ۸۸.۷ درصدی).
- **مدیریت دانلود پیشرفته:** استفاده از دانلود همزمان برای فایل‌های پارت‌بندی شده با تقسیم به بخش‌های متعدد (Chunk) و اتصال مجدد آن‌ها برای افزایش سرعت.
- **استخراج هوشمند:** پشتیبانی از آرشیوهای چندپارته (Multi-volume) و اعمال خودکار رمزهای عبور استاندارد.
- **یکپارچه‌سازی با هوش مصنوعی:** استفاده از APIهای سازگار با OpenAI برای دریافت و اجرای کدهای اختصاصی جهت مدیریت فایل‌های کمکی و کرک (در صورت وجود در پکیج).
- **تشخیص سخت‌افزار:** خواندن مشخصات سیستم و نسخه‌های نصب‌شده از رجیستری ویندوز (`winreg`) برای انتخاب بهترین نسخه سازگار.
- **پشتیبانی از فرمت‌های متنوع:** EXE, MSI, ZIP, 7z, RAR.
- **رابط کاربری وب:** طراحی ساده و کاربرپسند با قابلیت‌های مدیریت نرم‌افزارهای نصب‌شده و حذف (Uninstall).

**🛠 تکنولوژی‌ها:**
- **زبان و فریمورک:** Python, Flask
- **اتوماسیون:** Selenium, webdriver-manager, PyAutoGUI, pywinauto
- **مدیریت سیستم:** psutil, pywin32, pefile, py-cpuinfo, winreg
- **فشرده‌سازی:** py7zr, rarfile
- **هوش مصنوعی و ترجمه:** OpenAI-compatible API, translate, Unidecode
- **وب اسکرپینگ:** requests, beautifulsoup4, ddgs

**⚠️ محدودیت‌ها:**
- برنامه در حال حاضر توانایی نصب خودکار حدود **۸۰٪** از نرم‌افزارهای تک‌فایله را دارد (به دلیل عدم امکان تشخیص تفاوت بین نام‌های مشابه مانند Notepad و Notepad++).
- فقط برای سیستم‌عامل ویندوز توسعه یافته است.

**🚀 نحوه اجرا:**
```bash
pip install -r requirements.txt
python app.py
```
یا اجرای مستقیم فایل `nasbyar.exe`.

---
### 📢 Notice / اطلاعیه
*This project has been renamed.*
**This project will be developed under the name «[Dorj](https://github.com/m-Researcher-Dev/dorj-view)» from now on.**


**این پروژه تغییر نام داده است. این پروژه از این پس با نام «دورج ([Dorj](https://github.com/m-Researcher-Dev/dorj-view))» توسعه داده می‌شود.**
