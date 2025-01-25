## Formátování kódu HTML a CSS

Formátování kódu HTML a CSS lze rozdělit do několika typů, které pomáhají zajistit čistý, čitelný a konzistentní kód. Zde jsou hlavní typy formátování:

### HTML Formátování

1. **Struktura a zanoření**:
   - Dodržujte správné zanoření, aby byla struktura HTML kódu přehledná.
   - Uzavřete každý prvek správně (otevřené a zavírací značky).

2. **Konzistentní používání atributů**:
   - Atributy uzavírejte do dvojitých uvozovek.
   - Používejte jasné a konzistentní názvy atributů a hodnot.

3. **Sémantické značky**:
   - Používejte správné HTML značky pro různé části obsahu (např. `<article>`, `<section>`, `<header>`).
   - Dbejte na sémantiku pro lepší přístupnost a SEO.

### CSS Formátování

1. **Konzistentní zanoření a mezery**:
   - Používejte konzistentní zanoření (obvykle dvě nebo čtyři mezery).
   - Mezi selektory a bloky pravidel používejte mezery pro čitelnost.
   
   ```css
   .class {
       property: value;
   }
   ```

2. **Konzistentní pojmenování**:
   - Používejte konzistentní pojmenování tříd a ID (např. kebab-case: `.header-title`).
   
3. **Kaskáda a konkrétnost**:
   - Vyvarujte se nadbytečného zanoření selektorů.
   - Používejte specifické selektory, když je to nutné, ale dodržujte správnou úroveň konkrétnosti.

4. **Komentáře**:
   - Přidávejte komentáře pro lepší přehlednost a popisování bloků kódu.
   
   ```css
   /* Tohle je komentář */
   .class {
       property: value; /* Popis vlastnosti */
   }
   ```

### Praktiky pro údržbu kódu

1. **Modularizace**:
   - Rozdělte CSS do modulárních souborů pro různé části aplikace.
   - Používejte techniky jako BEM (Block Element Modifier) pro lepší strukturování CSS.
   
   ```css
   .block__element--modifier {
       /* Pravidla */
   }
   ```

2. **Preprocesory**:
   - Používejte CSS preprocesory jako Sass nebo Less pro lepší údržbu a strukturování kódu.
   
3. **Optimalizace**:
   - Optimalizujte kód pro výkon a načítání stránky.
   - Minimalizujte a kombinujte soubory CSS, pokud je to možné.

### Formátovací nástroje

- **HTML Tidy**: Nástroj pro kontrolu a opravu HTML kódu.
- **Prettier**: Automatický formátovací nástroj, který podporuje více jazyků, včetně HTML a CSS.
- **Stylelint**: Linter pro CSS, který pomáhá dodržovat konzistentní styl kódu.

Použitím těchto metod můžete zajistit, že váš kód bude snadno čitelný, udržovatelný a přístupný jak pro vás, tak pro další vývojáře.

Mohu vám pomoci s něčím konkrétním ohledně HTML nebo CSS kódu?
