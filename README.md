# Modern Shopify Theme

Moderní a responzivní Shopify theme vytvořený s důrazem na výkon, přístupnost a uživatelskou přívětivost.

## 🚀 Funkce

- **Moderní design** - Čistý a minimalistický vzhled
- **Plně responzivní** - Optimalizováno pro všechna zařízení
- **Rychlé načítání** - Optimalizováno pro výkon
- **SEO optimalizované** - Strukturovaná data a meta tagy
- **Přístupné** - Splňuje standardy přístupnosti WCAG
- **Konfigurovatelné** - Rozsáhlé možnosti přizpůsobení
- **Vícejazyčné** - Podpora lokalizace

## 📦 Instalace

### Metoda 1: Přímé nahrání do Shopify

1. Stáhněte nebo naklonujte tento repozitář
2. Zabalte všechny soubory do ZIP archivu
3. V Shopify Admin přejděte na **Online Store > Themes**
4. Klikněte na **Upload theme**
5. Nahrajte ZIP soubor
6. Publikujte theme

### Metoda 2: Shopify CLI

```bash
# Naklonujte repozitář
git clone https://github.com/your-username/shopify-template.git
cd shopify-template

# Připojte se k vašemu obchodu
shopify theme dev

# Nebo nahrajte theme
shopify theme push
```

### Metoda 3: GitHub integrace

1. Forkněte tento repozitář
2. V Shopify Admin přejděte na **Online Store > Themes**
3. Klikněte na **Add theme > Connect from GitHub**
4. Vyberte váš forknutý repozitář

## 🎨 Přizpůsobení

### Barvy

Theme obsahuje kompletní systém barev, který můžete upravit v **Theme settings > Colors**:

- **Primary color** - Hlavní barva značky
- **Secondary color** - Sekundární barva
- **Accent color** - Zvýrazňovací barva
- **Text color** - Barva textu
- **Background color** - Barva pozadí

### Typografie

Nastavte fonty v **Theme settings > Typography**:

- **Heading font** - Font pro nadpisy
- **Body font** - Font pro běžný text
- **Base font size** - Základní velikost písma

### Layout

Upravte rozložení v **Theme settings > Layout**:

- **Container width** - Maximální šířka kontejneru
- **Sticky header** - Lepkavá hlavička
- **Animations** - Animace

## 📱 Sekce

### Hero sekce
Velká úvodní sekce s obrázkem na pozadí, nadpisem a tlačítkem.

**Nastavení:**
- Nadpis a podnadpis
- Obrázek na pozadí
- Tlačítko s odkazem
- Výška sekce
- Zarovnání textu

### Featured Collection
Zobrazení doporučených produktů z vybrané kolekce.

**Nastavení:**
- Výběr kolekce
- Počet produktů
- Počet sloupců
- Poměr stran obrázků

### Image with Text
Sekce kombinující obrázek s textem.

**Nastavení:**
- Obrázek
- Nadpis a text
- Pozice obrázku
- Tlačítko s odkazem

### Newsletter
Formulář pro přihlášení k newsletteru.

**Nastavení:**
- Nadpis a popis
- Barevné schéma

## 🛒 E-commerce funkce

### Produktové stránky
- Galerie obrázků s lightboxem
- Výběr variant
- Množstevní selektor
- Tlačítko "Přidat do košíku"
- Doporučené produkty

### Košík
- Drawer košík (výsuvný)
- Aktualizace množství
- Poznámky k objednávce
- Rychlé placení

### Kolekce
- Filtrování produktů
- Řazení
- Responzivní mřížka

## 🔧 Technické detaily

### Struktura souborů

```
├── assets/           # CSS, JS, obrázky
├── config/           # Konfigurační soubory
├── layout/           # Layout soubory
├── locales/          # Překlady
├── sections/         # Sekce
├── snippets/         # Znovupoužitelné úryvky
├── templates/        # Template soubory
└── README.md
```

### CSS architektura
- CSS custom properties (proměnné)
- Mobile-first přístup
- BEM metodologie pro třídy
- Flexbox a CSS Grid

### JavaScript
- Vanilla JavaScript (bez závislostí)
- Web Components
- Lazy loading
- Intersection Observer API

## 🌐 Podpora prohlížečů

- Chrome (poslední 2 verze)
- Firefox (poslední 2 verze)
- Safari (poslední 2 verze)
- Edge (poslední 2 verze)
- iOS Safari (poslední 2 verze)
- Android Chrome (poslední 2 verze)

## 📈 Výkon

Theme je optimalizován pro rychlost:

- Minimalizované CSS a JavaScript
- Optimalizované obrázky
- Lazy loading
- Kritické CSS inline
- Preload fontů

## 🆘 Podpora

Pokud narazíte na problém nebo máte otázku:

1. Zkontrolujte [Issues](https://github.com/your-username/shopify-template/issues)
2. Vytvořte nový issue s detailním popisem
3. Použijte vhodné štítky

## 🤝 Přispívání

Příspěvky jsou vítány! Prosím:

1. Forkněte repozitář
2. Vytvořte feature branch
3. Commitněte změny
4. Pushněte do branch
5. Vytvořte Pull Request

## 📄 Licence

Tento projekt je licencován pod MIT licencí - viz [LICENSE](LICENSE) soubor pro detaily.

## 🙏 Poděkování

- Shopify za skvělou platformu
- Komunitě vývojářů za inspiraci
- Všem přispěvatelům

---

**Vytvořeno s ❤️ pro Shopify komunitu**
