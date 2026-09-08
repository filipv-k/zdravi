# Kontext – aktuální adresáře

Tento soubor je jediný zdroj pravdy o umístění dat projektu. Agent i člověk si cesty bere odsud, nedomýšlí je a při změně upraví **pouze tento soubor**.

Aktualizováno: 2026-09-08

---

## Seznam adresářů

| Účel | Cesta | Načítání |
| :--- | :--- | :--- |
| **Knowhow** | `C:\Users\Lenovo\Documents\GitHub\zdravi` | **vždy** |
| **Fotodokumentace** | `G:\My Drive\Zdravi\cviceni` | **podle potřeby** |

- **Knowhow** – textová znalostní báze (Markdown, verzováno v gitu). Standardní místo pro ukládání a sdílení dokumentů a výstupů.
- **Fotodokumentace** – obrazové podklady ke cvikům a lekcím (Google Drive). Načítat jen tehdy, když je obrázek pro odpověď relevantní.

---

## Obsah knowhow adresáře

- `beh-implikace.md` – zdravotní profil, biomechanická omezení, závazná pravidla pro běh, výběr obuvi a stélek.
- `prehled-cviku.md` – přehled rehabilitačních, stabilizačních a posilovacích cviků včetně provedení, dávkování a častých chyb; na konci journal z lekcí.
- `tydenni-plan.md` – aktuální týdenní tréninkový a rehabilitační plán a pravidla pro řízení zátěže.
- `attachments/` – obrázkové přílohy k dokumentům.
- `.ai/instructions.md` – závazné instrukce pro AI agenty.
- `.ai/kontext.md` – tento soubor.

---

## Pravidla práce s adresáři

- Trvalé výstupy patří do **knowhow adresáře**, ne do dočasného pracovního prostoru agenta.
- Novou informaci zapisuj do **existujícího dokumentu**; nový soubor zakládej jen tehdy, když téma do žádného nepatří – a doplň ho do seznamu výše.
- Adresáře jsou **sdílené** – čtou a zapisují do nich i jiní agenti a lidé. Před zápisem si soubor vždy znovu načti.
- Pokud agent na některý adresář nemá přístup, řekne to a vyžádá si vložení obsahu; cesty ani obsah si nedomýšlí.
- Při změně umístění dat aktualizuj tabulku i datum v hlavičce tohoto souboru.
