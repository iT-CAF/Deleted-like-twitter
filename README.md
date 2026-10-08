<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/projects/Deleted-like-twitter-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/projects/Deleted-like-twitter-light.png">
  <img alt="حذف الإعجابات — Bulk Unlike for X" src="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/projects/Deleted-like-twitter-dark.png" width="100%">
</picture>

<p>
  <img alt="Earlier work · 2022" src="https://img.shields.io/badge/Earlier_work_%C2%B7_2022-596268?style=flat-square">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-1A2024?style=flat-square&logo=javascript&logoColor=E8A33D">
</p>

<div dir="rtl" align="right">

### ‹ مقتطف لوحة تحكم المتصفح لحذف إعجاباتك في X دفعة واحدة.

افتح صفحة الإعجابات في حسابك، ثم الصق الكود في Console المتصفح.

</div>

**A browser-console snippet that removes your likes on X in bulk.**

Open your Likes page, then paste the snippet into the browser console.


## `$` Usage · الاستخدام

```js
setInterval(() => {
  for (const d of document.querySelectorAll('div[data-testid="unlike"]')) d.click();
  window.scrollTo(0, document.body.scrollHeight);
}, 1000);
```

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/footer-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/footer-light.png">
  <img alt="{ build quietly } — iT CAF" src="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/footer-dark.png" width="100%">
</picture>

<p align="center"><sub>Built by <a href="https://github.com/iT-CAF">Abdulrhman Alyazidi · iT CAF</a> — <a href="https://it-caf.com">it-caf.com</a></sub></p>
