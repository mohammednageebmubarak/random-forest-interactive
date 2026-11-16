# Random Forest — Interactive Data Mining Lab

## الغابة العشوائية | Random Forest

An offline-ready **single-file bilingual (Arabic/English) interactive lesson** for Master's-level Information Systems learners and introductory Data Mining study.

درس تفاعلي عربي/إنجليزي عن **الغابة العشوائية** يعمل مباشرة في المتصفح دون مكتبات خارجية أو اتصال بالإنترنت.

### Launch | فتح الدرس
- **Live site (after GitHub Pages is enabled):** https://mohammednageebmubarak.github.io/random-forest-interactive/
- **Offline:** download [index.html](./index.html) and open it in your browser.
- **GitHub Pages configuration:** Settings → Pages → Deploy from a branch → **main** → **/ (root)**.
- **Repository name:** `random-forest-interactive` (already renamed).

### Contents | المحتويات
- Bilingual introduction and Information Systems example / مقدمة ومثال من نظم المعلومات.
- Algorithm explanation and core equation / خطوات الخوارزمية ومعادلتها.
- Interactive Random Forest demonstration / محاكاة تفاعلية مخصصة.
- Python example (display only) / مثال برمجي بلغة Python.
- Multilingual graded quiz / اختبار مع التصحيح الفوري.
- Developer notes and inline source comments / ملاحظات تطوير داخل الكود.

### How to extend | كيف تطور المشروع؟
Open **index.html** and read the comments near JavaScript functions:
- `COURSE` stores lesson content and bilingual quiz options.
- `TXT` contains shared UI translations.
- `initialize`, `draw*`, and `nextStep` implement the algorithm-specific chart.
- `renderQuiz`, `grade`, and `switchLanguage` handle the self-assessment and RTL/LTR language switch.

To keep offline compatibility, avoid third-party CDN dependencies. Test sliders, charts, reset, grading and both language directions after every change.

### Learning limitation | تنبيه أكاديمي
The demo uses **synthetic educational examples** and is not a validated study or production classifier. The Python snippet is instructional and not run in-browser.

هذه التجارب مصممة للتعلم ولا تعني إثبات تفوق علمي أو صلاحية الاستخدام على بيانات حقيقية دون دراسة منهجية.

### About the developer | عن المطور
**Mohammed Nageeb Mubarak holds a bachelor's degree in Computer Engineering and Computer Science and is pursuing a master's degree in Information Systems. His professional and academic interests include data analysis, data mining, applied research, and intelligent information systems.**

محمد نجيب مبارك حاصل على البكالوريوس في هندسة وعلوم الكمبيوتر، ويدرس الماجستير في نظم المعلومات. تشمل اهتماماته المهنية والأكاديمية تحليل البيانات والتنقيب عنها والبحث العلمي التطبيقي ونظم المعلومات الذكية.

GitHub: https://github.com/mohammednageebmubarak

### License
No software license has been selected for this project.
