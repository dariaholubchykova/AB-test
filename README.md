# A/B Test: Вплив кольору фону на поведінку користувачів  

## Опис проєкту  
Цей проєкт проводить A/B-тестування, щоб визначити, чи впливає зміна кольору фону вебсайту на час перебування користувачів та конверсію.  

Контрольна група (A) – стандартний білий фон.  
Експериментальна група (B) – чорний фон.  

Головна мета тесту – оцінити вплив зміни кольору на середній час перебування на сайті та рівень конверсії.  

---

## Методологія
1. Очищення даних – перевірка на дублі, пропущені значення, викиди.  
2. Перевірка розподілу даних – тест Шапіро-Вілка, візуалізація розподілу.  
3. Статистичне тестування:  
   - Mann-Whitney U-тест – для оцінки різниці у часі перебування.  
   - Chi-square test – для оцінки змін у рівні конверсії.  
4. Візуалізація результатів – графіки розподілу часу та зміни рівня конверсії.  

---

## Результати та інсайти  
✔ Час перебування на сайті практично не змінився між групами.  
✔ Колір фону сайту впливає на рівень конверсії.  
✔ Виявлено низьку кореляцію між часом перебування та конверсією.  

Це означає, що аналіз лише часу, проведеного на сайті, не є ефективним критерієм оцінки дизайну.  
Для майбутніх тестів варто зосередитися на ключових метриках (конверсія, клікабельність, взаємодія).




