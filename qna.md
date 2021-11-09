# Klausimai

## SL2

1. Kas ir kada atsitiko prijungus laikmeną?
2. Kada ir ar tikrai piktavalis prisijungė, po to kai buvo prijungta USB laikmena?
3. Kada šie veiksmai buvo atlikti?
4. Kokius tolimesnius veiksmus ir kada atliko piktavalis?
5. Kokia informacija buvo nutekinta?

## SL5

1. Kaip buvo užvaldyta svetainė?

- `HTTP POST` užklausa įkeltas `index2.php` failas veikiantis kaip reverse shell ir `exploit.sh` gauti `root` teisėms.

2. Kada tai atlikta?
3. Koks TVS įskiepis buvo pažeidžiamas?
4. Kokia kenksminga užklausa buvo atsiųsta.
5. Kada ji buvo atsiųsta?
6. Iš kokio IP adreso tai buvo padaryta?
7. Koks buvo jos tikslas?
8. Koks CVE buvo išnaudotas?
9. Kokius veiksmus atliko piktavalis
10. Kada šie veiksmai buvo atlikti?
11. Iš kokio IP adreso tai buvo atlikta?

- `83.171.40.125:2021`

12. Kokie failai buvo parsisiųsti / nutekinti?

- `/backup/asmenu_duomenys_is_DB.csv`
- `/backup/asmenu_duomenys_is_DB.xlsx`
- `/backup/wp_ks2021.sql`
- `/etc/passwd`

13. Iš kurio katalogo parsisiuntė failus?
14. Kada parsisiuntė failus?
15. Kas parsisiuntė failus?
16. kokia jautri informacija buvo saugoma `wp_ks2021.sql`
17. Kaip dar įsilaužėlis pateko į virtualų privatų serverį.
18. Kada prasidėjo ataka?
19. Kada įsilaužėlis pateko į virtualų privatų serverį?
20. Kaip piktavalis gavo naudotojų sąrašą?

- iš `/etc/passwd` failo

21. Kaip piktavalis gavo sudo/root teises?

- paleisdamas `exploit.sh`

22. Kada piktavalis gavo root?
23. Per kokį vartotoją gavo root teises?
24. Kur randasi sudo “exploit” failiukas?
25. Koks sudo exploit failo pavadinimas?
26. Kaip piktavalis žinojo kokie failai yra “backup” direktorijoje.

## SL6

1. Ar galite nustatyti kokiu mobiliuoju telefonu darbuotojas naudojosi?
2. Ar galite paaiškinti QR kodo paskirtį?
3. Ar galite nustatyti kokia kenkėjiška programinė įranga buvo sudiegta į mobilųjį telefoną?
4. Ar galite paaiškinti kam konkrečiai yra skirta QRC0DE programinė įranga ir kokius
5. veiksmus jos pagalbą galėjo atlikti piktavalis?
6. Kokius failus galėjo paimti piktavalis?
7. Kokiu įrenginiu ir kada buvo fotografuojamas duomenį centras?
8. Ar galite pasakyti kur yra duomenų centras?
