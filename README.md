# SQL Kódy

Tento dokument obsahuje přehled SQL operací a technologií používaných v rámci certifikací. Zaměřuje se na manipulaci s databázemi v PostgreSQL a Oracle.

## Obsah
- [Popis](#popis)
- [Použité technologie](#použité-technologie)
- [SQL operace - Certification LovelyData SQL 2](#sql-operace---certification-lovelydata-sql-2)
- [SQL operace - Certification Lovelydata.cz SQL1](#sql-operace---certification-lovelydata-cz-sql1)
- [SQL operace - Sample SQL Code in Practice](#sql-operace---sample-sql-code-in-practice)

## Použité technologie

- **SQL**: Jazyk pro správu a manipulaci s databázemi.
- **PostgreSQL**: Databázový systém používaný pro certifikaci LovelyData.
- **Oracle Database**: Databázový systém používaný pro praktické aplikace a reportování.

## Použité SQL operace

### Certification LovelyData SQL 2 (PostgreSQL)

- **Vytvoření tabulky**: Vytvoření nové tabulky na základě dat z jiné tabulky.
- **Přidání sloupce**: Přidání nového sloupce do existující tabulky.
- **Aktualizace dat**: Nastavení hodnoty v nově přidaném sloupci.
- **Odstranění sloupce**: Odstranění existujícího sloupce z tabulky.
- **Podmínkové vkládání**: Vložení dat do tabulky na základě podmínky.
- **Vytvoření pohledu**: Vytvoření virtuální tabulky (pohledu) s filtrovanými daty.
- **Dotazování pohledů**: Výběr dat z pohledu na základě podmínky na časové období.

### Certification Lovelydata.cz SQL1 (PostgreSQL)

- **Výběr a filtrování dat**: Výběr dat na základě časového rozmezí a specifických podmínek.
- **Skupinové agregace**: Výpočet agregovaných hodnot (minimální, maximální, průměrné ceny) podle skupin.
- **Joins**: Spojení tabulek na základě společných klíčů pro získání komplexních dat.
- **Unikátní výběr**: Výběr jedinečných hodnot a řazení podle specifických kritérií.
- **Filtrace podle počtu záznamů**: Skupinování dat a filtrování na základě počtu záznamů ve skupině.

### Sample SQL Code in Practice (Oracle Database)

- **LEFT JOIN**: Spojení dvou tabulek, kde jsou zahrnuta všechna data z levé tabulky a odpovídající data z pravé tabulky.
- **INNER JOIN**: Spojení dvou tabulek na základě odpovídajících záznamů v obou tabulkách.
- **Subqueries**: Použití poddotazů pro získání počtu záznamů nebo maximální hodnoty na základě hlavního dotazu.
- **Podmínkový výběr**: Výběr dat na základě specifických podmínek (např. platnost ceníku).
- **Distinct**: Výběr jedinečných hodnot bez duplicit.

---

Tyto SQL operace zahrnují širokou škálu technik pro manipulaci s daty a vytváření komplexních dotazů v databázích PostgreSQL a Oracle.
