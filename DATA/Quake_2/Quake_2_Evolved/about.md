На данный момент проект заброшен, а ведь неплохую картинку давал, шельмец. Тем не менее, игра с ним полностью играбельна и проходима.

**Версия 0.40** \- последняя официальная, после распаковки в папку с игрой перенесите содержимое папки base в папку BASEQ2.  
**Версия 1.0a** \- самостоятельная сборка, в которую включен модифицированый HUD, текстуры высокого разрешения и много ещё чего. Увы, часть пунктов меню для настройки графики отключены (пользуйтесь консолью). К тому же, по-умолчанию включено безумно высокое разрешение, которое не каждый монитор потянет. Чтобы исправить - открываем блокнотом baseq2/q2econfig.cfg и меняем следдующие строчки:  

seta r\_mode "8"  
на  
seta r\_mode "4"  
и  
seta r\_customWidth "1440"  
seta r\_customHeight "900"  
на  
seta r\_customWidth "800"  
seta r\_customHeight "600"  
(или иное).