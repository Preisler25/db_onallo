# Feladat megoldás

> Első feladat
```sql
SELECT `orszag`,`fovaros` FROM `orszagok`;
```

> Második feladat
```sql
SELECT orszag FROM orszagok WHERE nepesseg * 1000 > 50000;
```

> Harmadik feladat
```sql
SELECT orszag, penznem FROM orszagok;
```

> Negyedik feladat
```sql
SELECT orszag FROM orszagok WHERE gdp > 30000;
```

> Ötödik feladat
```sql
SELECT orszag FROM orszagok WHERE foldr_hely LIKE '%Európa%';
```

> Hatodik feladat
```sql
SELECT orszag FROM orszagok ORDER BY terulet DESC LIMIT 1;
```

> Hetedik feladat
```sql
SELECT AVG(nepsesseg)*1000 FROM orszagok;
```

> Nyolcadik feladat
```sql
SELECT orszag FROM orszagok WHERE nepesseg*1000 BETWEEN 10000 AND 50000;
```

> Kilencedik feladat
```sql
SELECT COUNT(*) FROM orszagok
```

> Tizedik feladat 
```sql
SELECT orszag FROM orszagok WHERE orszag LIKE 'A%';
```

> Tizenegyedik feladat
```sql
SELECT orszag FROM orszagok WHERE LENGTH(fovaros) > 7;
```

> Tizenkettedik feladat
```sql
SELECT orszag FROM orszagok ORDER BY nepesseg DESC;
```

> Tizenharmadik feladat
```sql
SELECT SUM(terulet) FROM orszagok;
```

> Tizennegyedik feladat
```sql
SELECT orszag FROM orszagok WHERE gdp > 25000;
```

> Tizenötödik feladat
```sql
SELECT orszag, telefon FROM orszagok;
```