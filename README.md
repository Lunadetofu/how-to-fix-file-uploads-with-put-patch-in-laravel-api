# Laravel API — File Upload Fix for PUT / PATCH Requests

Easily handle file uploads in Laravel API when using PUT or PATCH requests — avoid common issues where files don’t show up and `$request->file()` returns null.

👉 Read the full guide: https://itstuffsolutiotions.io/how-to-fix-file-uploads-with-put-patch-in-laravel-api/

---

## 🔧 Why This Repo

When updating resources via API (PUT / PATCH), multipart/form-data with files often fails — the request appears empty. This repo demonstrates a reliable fix/workaround so file uploads work seamlessly even on updates.

---

## ✅ What You’ll Learn / Benefit

- Why standard PUT/PATCH + multipart/form-data fails in PHP/Laravel :contentReference[oaicite:0]{index=0}  
- How to fix it (spoof HTTP method, use POST + `_method`) and ensure file data reaches backend properly :contentReference[oaicite:1]{index=1}  
- Best practices for file validation and secure storage (file type, size, MIME checking, storage location) :contentReference[oaicite:2]{index=2}  
- Example code and request setup for APIs accepting uploads + other fields  

---

