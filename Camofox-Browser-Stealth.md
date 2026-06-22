# Camofox Browser — متصفح مخفي لوكلاء AI

**المصدر:** [@theromanknox](https://www.instagram.com/theromanknox) + بحث GitHub  
**المستودع:** [jo-inc/camofox-browser](https://github.com/jo-inc/camofox-browser)  
**النجوم:** ⭐ 7,084  
**الترخيص:** مفتوح المصدر

---

## الوصف

متصفح headless خفي (stealth) مصمم لوكلاء الذكاء الاصطناعي — يتجاوز:
- Cloudflare protection
- Bot detection systems
- Anti-scraping measures
- Fingerprinting

**Drop-in replacement** للمتصفحات العادية — يعمل كـ headless browser عادي لكن بخواص تمويه متقدمة.

## لماذا في مستودع hak (الأمن والاختراق)؟

- **تجاوز الحماية**: يتخطى أنظمة كشف البوتات و Cloudflare
- **بصمة متخفية**: يمنع fingerprinting — لا يترك أثراً
- **استخدامات دفاعية وهجومية**:
  - 🛡️ دفاعي: اختبار أنظمة الحماية الخاصة بك
  - ⚔️ هجومي: scraping وأتمتة دون كشف (OSINT)
- **للباحثين الأمنيين**: أداة أساسية لاختبار الاختراق وتجاوز الحماية

## المميزات التقنية

| الميزة | التفاصيل |
|--------|---------|
| **Drop-in** | يستبدل المتصفح العادي مباشرة |
| **REST API** | نسخة بخادم REST للتكامل |
| **AI Agents** | مصمم خصيصاً لوكلاء AI |
| **Anti-detection** | يتجاوز كشف البوتات |
| **Cloudflare bypass** | يتجاوز حماية Cloudflare |

## الاستخدامات العملية

```bash
# كمتصفح headless عادي
camofox-browser --url https://example.com

# مع وكلاء AI (مثال مع OpenClaw)
camofox-browser --server --port 8080
```

## صلة بأدوات hak الأخرى

- **متوافق مع**: Metasploit, SpiderFoot, Sherlock (OSINT)
- **استخدام**: reconnaissance بدون كشف
- **تكامل**: يمكن تشغيله عبر Docker في بيئات CI/CD

---

## مراجع

- المستودع: https://github.com/jo-inc/camofox-browser
- منشور theromanknox: https://www.instagram.com/p/DZkE8_rDl9i/
