# Catalog Review MVP

واجهة عربية RTL لمراجعة صور الكتالوج، تعمل كـ static frontend على GitHub Pages وتستخدم نفس Supabase backend الحالي فقط.

## Backend
- Supabase project ref: `tdcahqjkidmhmqjaajwq`
- لا يتم إنشاء قاعدة بيانات جديدة.
- الجداول: `projects`, `project_members`, `catalog_images`, `image_versions`, `feedback`, `annotations`
- التخزين الخاص: `catalog-images`, `voice-feedback`

## المزايا
- Supabase Auth
- Admin / Reviewer
- Projects + project instructions
- Multi-image upload
- Approved / Approved with note / Needs changes / Rejected
- Written feedback
- Voice recording + Arabic browser transcript fallback
- Annotation pins
- Version history + new versions
- Editing tasks
- Client-side AI Edit Prompt generator بدون API مدفوع

## GitHub Pages
المشروع لا يحتاج build step. الملف الرئيسي هو `index.html`.
