# LM335
## LM335 teplotní čidlo pro Cerbo

### Návod na výrobu teplotního čidla pro Cerbo - Victron

![image](https://github.com/user-attachments/assets/b0c7f3f4-096e-49ff-9f75-bd2c920f423f)

### Potřebné nářadí:
- Štípačky
- Krimpovací kleště na dutinky
- Odizolovací kleště na kabely
- Páječku
- Horkovzdušnou pistoli

### Potřebný materiál na výrobu čidel:
- **LM335Z/NOPB** [(GME.cz)](https://www.gme.cz/v/1490445/texas-instruments-lm335z-nopb-analogovy-teplotni-sensor) [(Datasheet)](https://img.gme.cz/files/eshop_data/eshop_data/4/530-003/dsh.530-003.1.pdf)
- Krimpovací dutinky (pouze prodloužené verze!)
- Dvojlinka (doporučená červeno/černá, průřez 0.35 mm²)
- Smrštovací bužírka 4.8/2.4 mm (na pájené spoje)
- Smrštovací bužírka 8.4/4.8 mm (na samotné LM335Z/NOPB)

---

### Postup výroby:

![image](https://github.com/user-attachments/assets/a6200894-769b-4986-8994-85f4339aef27)

1. Nastříhejte kabely na požadovanou délku a konce cca 2 cm odizolujte. Doporučená délka: 1,2 m.
2. Na PIN **(-)** zapájejte černý kabel s navlečenou smrštovací bužírkou.
3. Na PIN **( + )** zapájejte červený kabel s navlečenou smrštovací bužírkou.
4. **PIN ADJ není zapojen.**
5. Přes LM335Z/NOPB navlékněte smrštovací bužírku **8.4/4.8 mm** a vše důkladně zafoukněte horkovzdušnou pistolí.
6. Na druhý konec kabelů navlékněte a **nakrimpujte prodloužené dutinky** (krátké nebudou v konektoru držet!).
7. **Vycvakněte prostřední konektor z Cerba.**

![image](https://github.com/user-attachments/assets/20d74aaf-b144-4b10-9c09-34ec530adbc0)

8. **Zapojení do Cerba:** PIN nejblíže ke stěně je **GND**, tam připojte černý kabel. Červený kabel zapojte nad něj.
9. **Další nastavení:** [YouTube video](https://www.youtube.com/watch?v=RvLgENfeDKw&ab_channel=Holomint)

---

### Nastavení v Cerbu:
- Zapněte odpovídající počet teplotních čidel. (Např. 4 pro měniče L1, L2, L3 a teplotu racku.)
- **Pojmenujte čidla**: Měnič L1, Měnič L2, Měnič L3, Teplota Racku.

![image](https://github.com/user-attachments/assets/ba0930d4-3ba9-4dad-b5f6-389ead1f7267)

### Výstup ve VRM:
- **Zobrazení v přehledu:**

![image](https://github.com/user-attachments/assets/b34ad341-60ea-45ef-a76c-dbfd2c5d9b71)

- **Statistiky:**

![image](https://github.com/user-attachments/assets/7b769453-bb14-473c-ad2d-ceff55462c1c)

- **Seznam zařízení:**

![image](https://github.com/user-attachments/assets/a87c6dda-d599-4484-84d3-983186d410f6)

---

## Pracujte pečlivě! Dvakrát měř, jednou řež...

---

## Zřeknutí se odpovědnosti

Autor tohoto projektu neposkytuje žádné záruky, výslovné ani implicitní, ohledně správnosti, spolehlivosti, funkčnosti nebo vhodnosti k jakémukoli účelu. Veškeré použití tohoto softwaru, kódu, schémat, návodů, technických řešení, produktů a jakýchkoli dalších poskytnutých materiálů je na vlastní odpovědnost uživatele.

Autor nenese žádnou odpovědnost za jakékoli škody, ztráty, finanční náklady, přímé či nepřímé škody vzniklé v důsledku použití těchto materiálů, a to včetně, ale nejen, ztráty dat, poškození zařízení, výpadků systému, poruchy elektrických či jiných instalací, požárů, ztrát příjmů nebo jiných nepředvídatelných následků.

Uživatel bere na vědomí, že jakékoli úpravy, sestavování, instalace, zapojení či implementace na základě poskytnutých informací provádí výhradně na vlastní riziko. Autor neposkytuje žádné garance funkčnosti, bezpečnosti ani souladu s platnými právními normami a předpisy.

Uživatel se zavazuje, že nevyužije žádné právní kroky vůči autorovi v souvislosti s jakýmikoli škodami nebo jinými nároky vyplývajícími z používání tohoto softwaru, produktů, schémat nebo návodů. Jakékoli právní nároky vůči autorovi jsou tímto výslovně vyloučeny a nevymahatelné, a to i soudní cestou.

Použitím těchto materiálů uživatel potvrzuje svůj souhlas s výše uvedenými podmínkami. Pokud s nimi nesouhlasíte, nepoužívejte tento software, schémata, návody ani jiné poskytnuté materiály.

