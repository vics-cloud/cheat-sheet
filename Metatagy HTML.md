# Metatagy HTML

Meta tagy jsou HTML značky, které poskytují metadata o webové stránce a pomáhají prohlížečům, vyhledávačům nebo sociálním sítím lépe porozumět obsahu stránky. Níže je seznam nejběžnějších meta tagů s vysvětlením:

---

### 1. ` <metaznaková sada> ` 
- **Účel**: Nastavuje znakovou sadu, kterou stránka používá.
- **Příklad**: `<meta charset="UTF-8">`
- **Popis**: Zajišťuje správné zobrazení textu (např. české znaky). Nejčastější hodnota je `UTF-8`, což podporuje širokou škálu znaků.

---

### 2. ` <meta name="viewport"> ` 
- **Účel**: Optimalizace stránky pro mobilní zařízení.
- **Příklad**: `<meta name="viewport" content="width=device-width, initial-scale=1">`
- **Popis**: Zajišťuje responzivní design tím, že přizpůsobí šířku stránky šířce zařízení.

---

### 3. ` <meta name="robots"> ` 
- **Účel**: Pokyny pro vyhledávače ohledně indexování stránky.
- **Příklad**: `<meta name="robots" content="index, follow">`
- **Popis**:
  - `index` / `noindex`: Povolit nebo zakázat indexování.
  - `follow` / `nofollow`: Povolit nebo zakázat sledování odkazů.
  - **Další hodnoty**: `noarchive` (nearchivovat stránku), `nosnippet` (nezobrazovat náhled ve vyhledávačích).

---

### 4. ` <meta name="description"> ` 
- **Účel**: Popis obsahu stránky.
- **Příklad**: `<meta name="description" content="Toto je popis mé stránky.">`
- **Popis**: Krátký popis, který se často zobrazuje ve výsledcích vyhledávání. Má významný vliv na SEO.

---

### 5. `<meta name="keywords">`
- **Účel**: Klíčová slova související se stránkou.
- **Příklad**: `<meta name="keywords" content="programování, HTML, meta tagy">`
- **Popis**: Dříve důležitý pro SEO, dnes má minimální význam, protože vyhledávače jej již nevyužívají.

---

### 6. `<meta name="author">`
- **Účel**: Identifikace autora stránky.
- **Příklad**: `<meta name="author" content="Jakub Růžička">`
- **Popis**: Užitečné pro přiřazení autorství webu, zejména v interních nebo firemních prostředích.

---

### 7. `<meta name="copyright">`
- **Účel**: Informace o autorských právech.
- **Příklad**: `<meta name="copyright" content="© 2024 Jakub Růžička">`
- **Popis**: Informuje o vlastnictví obsahu stránky.

---

### 8. `<meta http-equiv="refresh">`
- **Účel**: Automatické přesměrování nebo obnovení stránky.
- **Příklad**: `<meta http-equiv="refresh" content="5;url=https://example.com">`
- **Popis**: Přesměruje uživatele na jinou stránku po určeném čase (zde po 5 sekundách).

---

### 9. `<meta http-equiv="X-UA-Compatible">`
- **Účel**: Určuje kompatibilitu se staršími verzemi Internet Exploreru.
- **Příklad**: `<meta http-equiv="X-UA-Compatible" content="IE=edge">`
- **Popis**: Doporučuje prohlížeči použít nejnovější dostupnou verzi vykreslovacího jádra.

---

### 10. `<meta name="theme-color">`
- **Účel**: Nastavuje barvu motivu prohlížeče na mobilních zařízeních.
- **Příklad**: `<meta name="theme-color" content="#4CAF50">`
- **Popis**: Umožňuje změnu barvy panelu nástrojů nebo adresního řádku.

---

### 11. `<meta property="og:*">` (Open Graph)
- **Účel**: Nastavení sdíleného obsahu na sociálních sítích.
- **Příklad**:
  ```html
  <meta property="og:title" content="Název stránky">
  <meta property="og:description" content="Popis stránky">
  <meta property="og:image" content="https://example.com/image.jpg">
  ```
- **Popis**:
  - `og:title`: Název obsahu.
  - `og:description`: Popis obsahu.
  - `og:image`: URL obrázku pro sdílení.
  - `og:url`: URL sdílené stránky.

---

### 12. `<meta name="twitter:*">`
- **Účel**: Metadata specifická pro Twitter.
- **Příklad**:
  ```html
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Název stránky">
  <meta name="twitter:description" content="Popis stránky">
  <meta name="twitter:image" content="https://example.com/image.jpg">
  ```
- **Popis**:
  - `twitter:card`: Typ obsahu (např. `summary` nebo `summary_large_image`).
  - Další tagy podobné Open Graph.

---

### 13. ` <meta name="generator"> ` 
- **Účel**: Informace o nástroji, který vytvořil stránku.- **Příklad**: `<meta name="generator" content="WordPress 6.3">`- **Popis**: Informuje o softwaru použitým k vytvoření stránky.



---

### 14. ` <meta name="název-aplikace"> ` 
- **Účel**: Název aplikace, ke které stránka patří.- **Příklad**: `<meta name="application-name" content="Moje Aplikace">`- **Popis**: Používá se zejména u progresivních webových aplikací (PWA).



---

### 15. ` <meta name="rating"> ` 
- **Účel**: Hodnocení stránky z hlediska obsahu.- **Příklad**: `<meta name="rating" content="general">`- **Popis**:  - `general`: Obsah vhodný pro všechny.  - `mature`: Obsah pro dospělé.





---

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTUyNjA3MTQ4Ml19
-->