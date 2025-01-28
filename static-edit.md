Nicméně existují technologie a přístupy, které se blíží tomu, co popisujete, a umožňují strukturovanou práci s HTML a CSS bez nutnosti hlubšího programování v JavaScriptu:

### 1. **Web Components**

Web Components jsou standardní technologie pro vytváření vlastních opakovaně použitelných komponent pomocí HTML, CSS a JavaScriptu. Lze je používat bez velkého JavaScriptového frameworku.

-   **Shadow DOM** umožňuje izolovat styly.
-   Vytvořené komponenty můžete používat jako HTML tagy.

Příklady knihoven:

-   **Lit** (dříve LitElement) – usnadňuje tvorbu Web Components.

### 2. **Handlebars nebo Mustache**

Tyto šablonovací enginy umožňují generování HTML na základě dat. Umožňují vložit dynamické hodnoty do šablon a jsou vhodné pro jednoduché projekty bez komplexní logiky.

### 3. **Alpine.js**

Pokud byste tolerovali minimální JavaScript, Alpine.js je velmi jednoduchý framework pro přidání interaktivity přímo do HTML.

-   Píšete přímo do HTML pomocí atributů, např. `x-show`, `x-data`, `x-on`.

### 4. **Svelte**

Svelte se sice kompiluje do JavaScriptu, ale psaní logiky je velmi přímočaré a blízké práci s HTML a CSS. Nemá tolik vrstvy abstrakce jako React nebo Vue.

### 5. **Static Site Generators**

Pokud nepotřebujete interaktivitu, generátory statických stránek jako **Hugo**, **Eleventy** nebo **Jekyll** vám umožní pracovat hlavně s HTML a CSS. Tyto nástroje generují statické stránky na základě šablon.

### 6. **GrapesJS**

Jelikož pracujete s GrapesJS, můžete ho použít i na tento účel – vytvářet čisté HTML/CSS stránky a designy, přičemž interaktivitu můžete přidávat jen podle potřeby.

Tyto přístupy vám umožní strukturovanou práci s HTML a CSS, aniž byste museli jít hluboko do Reactu nebo jiných složitých JavaScriptových knihoven. Máte-li konkrétnější požadavky, mohu doporučit další možnosti.
