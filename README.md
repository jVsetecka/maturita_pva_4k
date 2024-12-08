# Procvičování

Naklonujte si tento repozitář a vypracujte jednotlivé úlohy do připravených projektů. Hotovou práci odevzdejte jako odkaz na váš repozitář na Teams.

## 2. Konvence, klíčová slova, datové a výčtové typy, proměnná, konstanta, přetypování a konverze datových typů, referenční a hodnotové datové typy

### Level 1

1. Vytvořte program, který definuje následující proměnné:
   - celočíselnou proměnnou `a` s hodnotou `10`,
   - desetinnou proměnnou `b` s hodnotou `15.75`,
   - textovou proměnnou `c` s hodnotou `"Hello"`,
   - výčtový typ pro roční období (`Spring`, `Summer`, `Autumn`, `Winter`).

2. Zaveďte konstantu `PI` s hodnotou `3.14159`.

3. Proveďte přetypování z `a` na `b` (implicitní i explicitní konverze).

4. Uložte hodnotu výčtového typu do proměnné a vypište ji na konzoli.

5. Zobrazte všechny proměnné na výstupu.

### Level 2

1. Definujte výčtový typ `Season` se 4 ročními obdobími. Kromě toho vytvořte výčtový typ `WeatherCondition` se stavy jako `Sunny`, `Rainy`, `Snowy`, atd.

2. Napište metodu, která přijme proměnnou typu `Season` a vrátí výčet možných `WeatherCondition` pro dané období (např. `Spring` může mít `Rainy` a `Sunny`).

3. Vytvořte třídu `Location`, která bude mít vlastnosti:
   - `Name` (string),
   - `Season` (typ `Season`),
   - a dynamicky generované náhodné `WeatherCondition` na základě aktuálního období a pravidel definovaných výše.

4. Vytvořte instanci třídy `Location` a vypište na konzoli, jaké počasí může nastat pro zvolenou lokalitu v daném ročním období.

---

## 3. Druhy operátorů, snižování a zvyšování hodnoty proměnných, složené přiřazení

### Level 1

1. Definujte dvě celočíselné proměnné `x` a `y` s hodnotami `8` a `3`.

2. Proveďte na nich následující operace:
   - Přičtěte k `x` hodnotu `2` a výsledek uložte zpět do `x`.
   - Násobte hodnotu `y` `4` a uložte výsledek zpět do `y`.
   - Zvyšte hodnotu `x` o `1` a snižte hodnotu `y` o `1` (inkrementace a dekrementace).

3. Použijte logický operátor k vyhodnocení podmínky, zda `x` je větší než `y` a `y` je větší než `0`.

4. Výsledky každé operace vypište na konzoli.

### Level 2

1. Vytvořte třídu `InventoryItem`, která bude mít vlastnosti:
   - `Name` (název předmětu),
   - `Quantity` (množství),
   - a `Price` (cena za jednotku).

2. Implementujte metodu `ApplyDiscount`, která na základě množství položky upraví její cenu:
   - Pokud je množství větší než `50`, aplikujte `10%` slevu.
   - Pokud je větší než `100`, aplikujte `20%` slevu.

3. Použijte složené přiřazení (např. `+=`, `*=`) při aplikaci slevy.

4. Vytvořte instanci třídy `InventoryItem`, upravte její množství a cenu, a vypište výsledné hodnoty po aplikaci slevy.

---

## 4. Řízení toku programu, definice prvočísla, algoritmus pro určení prvočísla

### Level 1

1. Napište program, který vyzve uživatele k zadání čísla.

2. Implementujte funkci `IsPrime(int number)`, která vrátí hodnotu `true`, pokud je číslo prvočíslem, nebo `false`, pokud není.
   - Prvočíslo je číslo větší než `1`, které je dělitelné pouze `1` a sebou samým.
   - Algoritmus by měl optimalizovaně kontrolovat dělitelnost čísly od `2` do odmocniny z daného čísla.

3. Program následně vypíše, zda je zadané číslo prvočíslo.

### Level 2

1. Napište program, který nejenže zkontroluje, zda je číslo prvočíslo, ale také:
   - Vypíše všechna prvočísla menší než zadané číslo.
   - Po zjištění, že číslo není prvočíslo, vypíše jeho nejmenšího dělitele.

2. Program by měl mít metodu `GetPrimeFactors`, která rozdělí dané číslo na jeho prvočíselné činitele.

3. Uživatel zadá číslo, program vypíše, zda je číslo prvočíslo, a pokud ne, vypíše rozklad tohoto čísla na prvočísla a všechna prvočísla menší než toto číslo.

---

## 5. Náhodná čísla a náhodná čísla bez opakování, kryptografická kvalita náhodných čísel

### Level 1

1. Vytvořte program, který vygeneruje `10` unikátních náhodných čísel v rozsahu `1` až `100`.

2. Použijte třídu `Random` k vytvoření náhodných čísel.

3. Vytištěte všechna vygenerovaná čísla na konzoli.

### Level 2

1. Vytvořte program, který vygeneruje `10` unikátních náhodných čísel v rozsahu `1` až `100`.

2. Použijte třídu `RNGCryptoServiceProvider` k vytvoření kryptograficky bezpečných náhodných čísel.

3. Zajistěte, aby se vygenerovaná čísla neopakovala.

4. Vytištěte všechna vygenerovaná čísla na konzoli.

---

## 6. Jednorozměrné a dvourozměrné pole, Eratostenovo síto

### Level 1

1. Vytvořte jednorozměrné pole o velikosti `10`.

2. Naplňte pole hodnotami `1` až `10`.

3. Zobrazte hodnoty tohoto pole na konzoli.

4. Vytvořte metodu, která najde maximální hodnotu v poli.

5. Vypište maximální hodnotu na konzoli.

### Level 2

1. Vytvořte dvourozměrné pole (matice) o velikosti `3x3`.

2. Naplňte matici hodnotami od `1` do `9`.

3. Zobrazte tuto matici ve formátu tabulky na konzoli.

4. Vytvořte metodu, která vypočítá součet hodnot v každém řádku matice.

5. Vypište výsledky na konzoli.

---
## 7. Kolekce (List, Dictionary) a dešifrování

### Level 1: List

1. Vytvořte seznam (`List`) celých čísel.
2. Naplňte seznam hodnotami od `1` do `5`.
3. Zobrazte hodnoty seznamu na konzoli.
4. Přidejte další hodnoty do seznamu.
5. Znovu zobrazte aktualizovaný seznam na konzoli.

### Level 2: Dictionary

1. Vytvořte slovník (`Dictionary`), kde klíčem bude číslo (`int`) a hodnotou jeho slovní vyjádření.
2. Přidejte do slovníku alespoň `5` klíčů a hodnot.
3. Zobrazte všechny klíče a hodnoty slovníku na konzoli.

### Level 3: Dešifrování pomocí Dictionary

1. Vytvořte šifrovací slovník (`Dictionary`), kde každé písmeno abecedy bude přiřazeno jinému písmenu.
2. Uživatel zadá zašifrovanou zprávu (řetězec).
3. Program pomocí slovníku dešifruje zprávu.
4. Zobrazte dešifrovanou zprávu na konzoli.

---

## 8. Komplexní datové struktury (Stack, Queue, Binary tree, Hash table)
https://www.youtube.com/watch?v=gxdQiBkidWk&t

### Level 1

#### Zásobník (Stack)
- Udělejte program, kde:
  - Vytvoříte zásobník na čísla (`Stack<int>`).
  - Do zásobníku vložíte čísla `1, 2, 3, 4, 5`.
  - Pak z něj jedno číslo odeberete a vypíšete, co v zásobníku zůstalo.

#### Fronta (Queue)
- Napište program, kde:
  - Vytvoříte frontu na texty (`Queue<string>`).
  - Do fronty přidáte tři jména: `"Anna"`, `"Petr"`, `"Lucie"`.
  - Odstraníte první jméno ve frontě a vypíšete, co ve frontě zbylo.

### Level 2

#### Binární strom (Binary Tree)
- Napište program, kde:
  - Vytvoříte jednoduchý binární strom na čísla.
  - Do stromu přidáte čísla: `10, 5, 15, 2, 7`.
  - Vytvoříte funkci, která zjistí, jestli ve stromu je konkrétní číslo (např. `7`).

#### Hashovací tabulka (Hash Table)
- Vytvořte program, kde:
  - Vytvoříte hashovací tabulku (`Dictionary<int, string>`).
  - Klíčem bude číslo (např. ID studenta) a hodnotou jméno studenta.
  - Přidáte do tabulky studenty: `(1, "Jan")`, `(2, "Eva")`, `(3, "Tomáš")`.
  - Najdete podle ID studenta a vypíšete jeho jméno.

---

## 9. Správa chyb a výjimek

### Level 1

1. Vyzvěte uživatele k zadání dvou čísel.
2. Vypočítejte jejich podíl.
3. Ošetřete výjimku `DivideByZeroException`, pokud uživatel zadá nulu jako druhé číslo.
4. Zobrazte vhodnou chybovou zprávu.
5. Program neukončujte a pokračujte dál.

### Level 2

1. Vytvořte metodu pro výpočet faktoriálu čísla.
2. Ošetřete výjimku `OverflowException` pro příliš velká čísla.
3. Vypište chybovou zprávu, pokud dojde k přetečení.
4. Program neukončujte a pokračujte dál.

### Level 3

1. Vytvořte třídu `BankAccount` s metodou `Withdraw`.
2. Implementujte vlastní výjimku `InsufficientFundsException` pro nedostatek prostředků na účtu.
3. Ošetřete tuto výjimku v hlavním programu.
4. Vypište vhodnou zprávu, pokud dojde k nedostatku prostředků na účtu.

---

## 10. Datum a čas, šifrování operací XOR, kvalita šifrování

### Level 1

1. Vytvořte program, který vypíše aktuální datum a čas ve formátu `"dd.MM.yyyy HH:mm"`.
2. Implementujte jednoduchý šifrovací algoritmus XOR, který zašifruje textový řetězec pomocí jednoho znaku jako klíče.
3. Vytvořte funkci pro dešifrování textu zašifrovaného pomocí XOR.

### Level 2

1. Vytvořte metodu, která přijme dva parametry typu `DateTime` (počáteční a konečné datum) a vypočítá rozdíl v počtu dnů, hodin a minut mezi těmito dvěma daty.
2. Upravte šifrovací algoritmus XOR tak, aby použil posloupnost znaků jako klíč pro šifrování i dešifrování.

---

## 11. Řetězcové funkce, specifika typu string

### Level 1

1. Napište program, který přijme vstup od uživatele a zjistí délku zadaného řetězce. Vypište délku na konzoli.
2. Implementujte metodu, která zkontroluje, zda zadaný řetězec obsahuje nějaké bílé znaky.
3. Vytvořte program, který porovná dva řetězce bez ohledu na jejich velikost písmen (např. `"Hello"` a `"hello"` jsou stejné).

### Level 2

1. Implementujte metodu, která přijme vstupní řetězec a vrátí jeho obrácenou podobu.
2. Vytvořte metodu, která počítá počet výskytů zadaného znaku v textovém řetězci.
3. Zjistěte, zda zadaný řetězec je palindrom (ignorujte mezery a velikost písmen).

## 12. Regulární výrazy, validace polí a vyhledávání informací v nestrukturovaných datech

### Level 1

1. Napište program, který přijme e-mailovou adresu od uživatele a zkontroluje její platnost pomocí regulárního výrazu.
2. Implementujte metodu, která ověří, zda zadané telefonní číslo má formát `"+420 XXX XXX XXX"`.

### Level 2

1. Vytvořte program, který analyzuje text a zjistí počet výskytů všech slov v zadaném textu.
2. Napište regulární výraz pro vyhledání všech čísel v textu a vypište je na konzoli.
3. Implementujte metodu pro kontrolu formátu IP adresy (IPv4).

---

## 13. Práce s textovými soubory

### Level 1

1. Vytvořte program, který vytvoří textový soubor a zapíše do něj několik řádků textu.
2. Implementujte metodu, která přečte celý obsah textového souboru a vypíše jej na konzoli.

### Level 2

1. Vytvořte program, který najde konkrétní řádek v textovém souboru podle klíčového slova a vypíše ho na konzoli.
2. Implementujte metodu, která spočítá počet řádků v textovém souboru.

---

## 14. Metody (předávání argumentů odkazem a hodnotou), modifikátory přístupu

### Level 1

1. Vytvořte metodu, která vypočítá faktoriál čísla. Použijte předávání parametru hodnotou.
2. Vytvořte metodu, která přijme odkaz na celočíselnou proměnnou a zvýší její hodnotu o `10`.

### Level 2

1. Vytvořte třídu s privátními a veřejnými metodami. Použijte veřejnou metodu, která umožní přístup k privátní metodě a její výsledek zobrazí na konzoli.
2. Vytvořte metodu, která přijme několik parametrů (referenčně i hodnotově) a vypíše jejich hodnoty před i po změně.

---

## 15. Třídy, konstruktory a zapouzdření
https://www.youtube.com/watch?v=m_MQYyJpIjg

### Level 1

- Vytvořte třídu `Osoba`, která bude obsahovat:
  - Veřejné vlastnosti `jmeno` (typu `string`) a `vek` (typu `int`).
  - Konstruktor, který inicializuje tyto vlastnosti při vytváření objektu.
  - Metodu `NastavVek`, která bude kontrolovat, aby zadaný věk nebyl záporný. Pokud bude zadaný věk neplatný, metoda by měla vypsat na konzoli chybovou zprávu.
  - Použijte zapouzdření, aby byl věk chráněný a nebylo možné ho přímo modifikovat.

### Level 2

- Vytvořte třídu `Auto`, která bude obsahovat:
  - Privátní pole `rychlost` (typu `int`).
  - Metodu `NastavRychlost`, která zajistí, aby nebylo možné nastavit zápornou hodnotu rychlosti.
  - Metodu `ZiskejRychlost`, která vrátí aktuální rychlost.
  - Použijte zapouzdření, abyste ochránili rychlost vozidla před přímými nežádoucími změnami.

- Vytvořte třídu `Banka`, která bude obsahovat:
  - Privátní pole `zustatek` (typu `decimal`).
  - Konstruktor, který inicializuje počáteční zůstatek bankovního účtu.
  - Metody `Vklad` a `Vyber`, které představují operace na účtu.
  - Zajistěte, aby metoda `Vyber` neumožnila výběr, pokud by došlo k překročení aktuálního zůstatku.
  - Použijte zapouzdření, aby byla správa zůstatku chráněna před přímými změnami.

---

## 16. Abstraktní třídy, interface, dědičnost, implementace interface. Polymorfismus. Vlastnosti a jejich použití

### Level 1

- Vytvořte abstraktní třídu `Zvire`, která bude obsahovat:
  - Abstraktní metodu `VydavatZvuk()`, která nebude mít žádnou implementaci.
  - Třídy `Pes` a `Kocka`, které dědí z `Zvire` a implementují metodu `VydavatZvuk()`, která vypíše zvuk, který dané zvíře vydává (např. `"Haf haf"` pro psa a `"Mňau"` pro kočku).

- Definujte interface `IVozidlo`, který bude obsahovat:
  - Deklarace metod `Zrychlit()` a `Zastavit()`.
  - Třídu `Auto`, která implementuje tento interface a zajistí, aby tyto metody vykonávaly odpovídající činnosti, jako například zvýšení rychlosti nebo zastavení vozidla.

### Level 2

- Vytvořte třídu `Zamestnanec`, která bude obsahovat:
  - Vlastnosti `jmeno` (typu `string`) a `plat` (typu `decimal`).
  - Třídu `Manazer`, která dědí z třídy `Zamestnanec` a má navíc vlastnost `bonus` (typu `decimal`).
  - Virtuální metodu `Pracovat()`, která vypíše, že zaměstnanec pracuje.
  - Přepište metodu `Pracovat()` ve třídě `Manazer` tak, aby vypisovala, že manažer řídí tým. Tímto způsobem ukážete polymorfismus.

- Definujte interface `IUcet`, který bude obsahovat:
  - Metody `Vklad` a `Vyber`, které představují operace na bankovním účtu.
  - Třídu `SporiciUcet`, která implementuje tento interface a má navíc vlastnost `urokovaMira` (typu `decimal`).
  - Implementujte metody tak, aby pracovali s touto úrokovou mírou, například výpočtem úroku z aktuálního zůstatku.
  - Přidejte metodu `PocitatUrok()`, která vypočte aktuální úrok a přičte ho k zůstatku.

---

## 17. Asynchronní programování (async, await), konkurence, paralelismus
https://www.youtube.com/watch?v=RlM9AfWf1WU&t

### Level 1

1. Základy asynchronního programování:
   - Vytvořte metodu `GetDataAsync` (async `Task<string>`), která simuluje získání dat z internetu s 2sekundovým zpožděním (`Task.Delay(2000)`).
   - Metoda vrátí text `"Data loaded"`.
   - Zavolejte tuto metodu pomocí `await` a vypište text na konzoli.

2. Jednoduchá paralelní operace:
   - Spusťte dvě nezávislé asynchronní úlohy pomocí `Task.Run`.
   - Každá úloha vypíše čísla od `1` do `5` s náhodným zpožděním mezi výpisy.
   - Počkejte, až obě úlohy dokončí, a vypište „Hotovo“.

### Level 2

1. Čekání na více úloh současně:
   - Vytvořte dvě metody `GetData1Async` a `GetData2Async` (async `Task<string>`), které simulují získání dat s různými zpožděními (`Task.Delay`).
   - Použijte `Task.WhenAll`, abyste spustili obě metody najednou a počkali, až obě skončí.
   - Po dokončení vypište výsledky obou metod.

2. Konkurence při zpracování dat:
   - Použijte `Parallel.For`, abyste souběžně zpracovali pole čísel.
   - Každé číslo vynásobte dvěma a vypište na konzoli.
