PROCESS CHECKLIST

[x] Sloučení všech CSV souborů do jednotného datasetu
[x] Kontrola a odstranění duplicit (ride_id)
[x] Standardizace datových typů
[x] Převod časových sloupců (started_at, ended_at) na datetime
[x] Výpočet délky jízdy v minutách
[x] Odstranění nevalidních jízd (duration <= 0)
[x] Vytvoření časových features (start_hour, day_of_week, is_weekend, month)
[x] Kontrola chybějících hodnot
[x] Kontrola realistických rozsahů (čas, latitude/longitude)
[x] Uložení vyčištěného datasetu a nahrání do MS SQL Server
