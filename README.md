Goed idee voor je toets. Ik heb alle **unieke HTML-tags** uit jouw code verzameld (dus geen dubbelen) en leg per tag uit:

* **Wat het is**
* **Waarvoor je het gebruikt**
* **Een voorbeeld**

# Basisstructuur

### `<html>`

De hoofdcontainer van een HTML-document.

**Gebruik:** Alles op de pagina staat hierin.

```html
<html>
  ...
</html>
```

---

### `<head>`

Bevat informatie over de pagina die niet zichtbaar is op de website.

**Gebruik:**

* Titel
* CSS koppelen
* Meta-data

```html
<head>
  <title>Mijn pagina</title>
</head>
```

---

### `<body>`

Bevat alles wat zichtbaar is op de webpagina.

```html
<body>
  Hallo wereld
</body>
```

---

### `<!DOCTYPE html>`

Vertelt de browser dat dit een HTML5-document is.

```html
<!DOCTYPE html>
```

---

# Metadata

### `<title>`

Titel van de pagina in het browsertabblad.

```html
<title>Mijn Website</title>
```

---

### `<meta>`

Extra informatie voor browser en zoekmachines.

**Veel gebruikt voor:**

* Tekenset
* Schermgrootte mobiel

```html
<meta charset="UTF-8">
```

---

### `<link>`

Verbindt een extern bestand zoals CSS.

```html
<link rel="stylesheet" href="styles.css">
```

---

# Tekst

### `<h1>`

Grootste kop.

```html
<h1>Welkom</h1>
```

---

### `<h2>`

Tweede niveau kop.

```html
<h2>Over mij</h2>
```

---

### `<p>`

Paragraaf tekst.

```html
<p>Dit is een tekst.</p>
```

---

# Links en afbeeldingen

### `<a>`

Maakt een hyperlink.

```html
<a href="contact.html">Contact</a>
```

**Gebruik:**

* Naar andere pagina
* Naar website
* Naar anker op dezelfde pagina

---

### `<img>`

Toont een afbeelding.

```html
<img src="cat.png" alt="Kat">
```

**Belangrijk:**

| Attribuut | Betekenis          |
| --------- | ------------------ |
| src       | locatie afbeelding |
| alt       | alternatieve tekst |

---

# Lijsten

### `<ul>`

Unordered List (opsomming met bolletjes).

```html
<ul>
</ul>
```

---

### `<li>`

List Item.

```html
<li>Appel</li>
```

---

# Formulieren

### `<form>`

Container voor invoervelden.

```html
<form action="/login">
</form>
```

**action**
= waar de gegevens naartoe gestuurd worden.

---

### `<label>`

Label voor een invoerveld.

```html
<label for="email">Email</label>
```

---

### `<input>`

Invoerveld.

```html
<input type="text">
```

Veel soorten:

| Type     | Gebruik     |
| -------- | ----------- |
| text     | tekst       |
| email    | emailadres  |
| password | wachtwoord  |
| checkbox | vinkje      |
| radio    | keuze       |
| range    | schuifbalk  |
| color    | kleurkiezer |
| date     | datum       |

---

### `<button>`

Knop.

```html
<button>Submit</button>
```

---

### `<select>`

Dropdown-menu.

```html
<select>
</select>
```

---

### `<option>`

Optie binnen een dropdown.

```html
<option>Beginner</option>
```

---

### `<textarea>`

Groot tekstvak voor meerdere regels.

```html
<textarea></textarea>
```

---

### `<fieldset>`

Groepeert invoervelden.

```html
<fieldset>
</fieldset>
```

---

### `<legend>`

Titel van een fieldset.

```html
<legend>Kies een maat</legend>
```

---

### `<div>`

Algemene container.

```html
<div>
  Inhoud
</div>
```

**Gebruik:**

* Groeperen
* Layout maken
* CSS toepassen

---

# Tabellen

### `<table>`

Tabel.

```html
<table>
</table>
```

---

### `<caption>`

Titel boven een tabel.

```html
<caption>Leeftijden</caption>
```

---

### `<thead>`

Kopgedeelte van een tabel.

```html
<thead>
</thead>
```

---

### `<tbody>`

Inhoud van een tabel.

```html
<tbody>
</tbody>
```

---

### `<tfoot>`

Voetgedeelte van een tabel.

```html
<tfoot>
</tfoot>
```

---

### `<tr>`

Table Row (rij).

```html
<tr>
</tr>
```

---

### `<th>`

Table Header (kolomkop).

```html
<th>Naam</th>
```

---

### `<td>`

Table Data (cel).

```html
<td>Frank</td>
```

---

# Belangrijke attributen uit jouw code

Deze staan niet tussen tags, maar worden vaak gevraagd op toetsen:

| Attribuut   | Gebruik                  |
| ----------- | ------------------------ |
| href        | linkadres                |
| src         | afbeelding               |
| alt         | alternatieve tekst       |
| id          | unieke naam              |
| for         | koppelt label aan input  |
| name        | naam van verzonden veld  |
| type        | soort input              |
| value       | waarde                   |
| placeholder | voorbeeldtekst           |
| required    | verplicht veld           |
| checked     | standaard aangevinkt     |
| selected    | standaard geselecteerd   |
| disabled    | uitgeschakeld            |
| rows        | aantal rijen textarea    |
| cols        | aantal kolommen textarea |
| min         | minimumwaarde            |
| max         | maximumwaarde            |
| action      | verzendadres formulier   |

## Kortste samenvatting voor je toets

De tags die je vrijwel zeker moet kennen:

* `<html>` = hele pagina
* `<head>` = instellingen
* `<body>` = zichtbare inhoud
* `<title>` = titel tabblad
* `<h1>` t/m `<h6>` = koppen
* `<p>` = tekst
* `<a>` = link
* `<img>` = afbeelding
* `<ul>` = lijst
* `<li>` = lijstitem
* `<form>` = formulier
* `<label>` = label
* `<input>` = invoerveld
* `<button>` = knop
* `<select>` = dropdown
* `<option>` = keuze in dropdown
* `<textarea>` = groot tekstvak
* `<div>` = container
* `<table>` = tabel
* `<tr>` = rij
* `<th>` = kopcel
* `<td>` = gegevenscel
* `<fieldset>` = groep formulieronderdelen
* `<legend>` = titel van een groep formulieronderdelen

Als je wilt, kan ik er ook een **toets-spiekbrief van 1 A4** maken met alleen de dingen die je moet onthouden.


# HTML Elementen en Semantiek – Samenvatting

## 1. `<span>`

### Wat is het?

`<span>` is een **inline-element** zonder semantische betekenis. Het wordt gebruikt om een klein deel van tekst of inhoud te groeperen zodat je er CSS of JavaScript op kunt toepassen.

### Kenmerken

* Inline-element
* Geen semantische betekenis
* Wordt vaak gebruikt voor styling

### Voorbeeld

```html
<p>Dit is een <span class="highlight">belangrijk</span> woord.</p>
```

### Gebruik wanneer

* Je een specifiek woord of stukje tekst wilt stylen.
* Je geen semantisch element nodig hebt.

---

## 2. `<div>`

### Wat is het?

`<div>` is een **block-element** zonder semantische betekenis. Het wordt gebruikt als algemene container voor andere HTML-elementen.

### Kenmerken

* Block-element
* Geen semantische betekenis
* Veel gebruikt voor lay-outs en groepering

### Voorbeeld

```html
<div class="container">
  <h2>Titel</h2>
  <p>Inhoud van de sectie.</p>
</div>
```

### Gebruik wanneer

* Je meerdere elementen wilt groeperen.
* Er geen geschikter semantisch element bestaat.

---

# 3. Semantiek in HTML

## Wat betekent semantiek?

Semantische HTML gebruikt elementen die beschrijven **wat de inhoud betekent**, niet alleen hoe deze eruitziet.

### Niet-semantisch

```html
<div class="navigation">
  ...
</div>
```

### Semantisch

```html
<nav>
  ...
</nav>
```

### Voordelen

* Betere toegankelijkheid (screenreaders)
* Betere SEO
* Duidelijkere code
* Makkelijker onderhoud

---

# 4. `<nav>`

## Wat is het?

`<nav>` bevat belangrijke navigatielinks van een website.

### Voorbeeld

```html
<nav>
  <a href="/">Home</a>
  <a href="/about">Over ons</a>
  <a href="/contact">Contact</a>
</nav>
```

### Gebruik wanneer

* Hoofdmenu's
* Zijmenu's
* Navigatieblokken

### Niet gebruiken voor

* Elke willekeurige verzameling links.

---

# 5. `<header>`

## Wat is het?

`<header>` bevat introductie-informatie of navigatie voor een pagina of sectie.

### Mogelijke inhoud

* Logo
* Titel
* Navigatie
* Zoekfunctie

### Voorbeeld

```html
<header>
  <h1>Mijn Website</h1>
  <nav>
    ...
  </nav>
</header>
```

---

# 6. `<main>`

## Wat is het?

`<main>` bevat de belangrijkste inhoud van de pagina.

### Kenmerken

* Slechts één `<main>` per pagina
* Bevat unieke inhoud van de pagina
* Geen herhalende onderdelen zoals header of footer

### Voorbeeld

```html
<main>
  <article>
    <h2>Nieuwsbericht</h2>
    <p>Tekst...</p>
  </article>
</main>
```

### Voordeel

Screenreaders kunnen direct naar de hoofdinhoud springen.

---

# 7. `<footer>`

## Wat is het?

`<footer>` bevat informatie onderaan een pagina of sectie.

### Mogelijke inhoud

* Copyright
* Contactgegevens
* Juridische informatie
* Extra links

### Voorbeeld

```html
<footer>
  <p>&copy; 2026 Mijn Website</p>
</footer>
```

---

# 8. `<audio>`

## Wat is het?

Met `<audio>` kun je audiobestanden afspelen in de browser.

### Voorbeeld

```html
<audio controls>
  <source src="muziek.mp3" type="audio/mpeg">
</audio>
```

### Belangrijke attributen

| Attribuut | Functie              |
| --------- | -------------------- |
| controls  | Toont afspeelknoppen |
| autoplay  | Start automatisch    |
| loop      | Herhaalt audio       |
| muted     | Dempt geluid         |

---

# 9. `<video>`

## Wat is het?

Met `<video>` kun je videobestanden rechtstreeks in de browser afspelen.

### Voorbeeld

```html
<video controls width="600">
  <source src="video.mp4" type="video/mp4">
</video>
```

### Belangrijke attributen

| Attribuut | Functie                  |
| --------- | ------------------------ |
| controls  | Toont videobediening     |
| autoplay  | Speelt automatisch af    |
| loop      | Herhaalt video           |
| muted     | Dempt geluid             |
| poster    | Voorvertoningsafbeelding |

---

# Overzichtstabel

| Element    | Type       | Doel                           |
| ---------- | ---------- | ------------------------------ |
| `<span>`   | Inline     | Kleine stukken tekst groeperen |
| `<div>`    | Block      | Algemene container             |
| `<nav>`    | Semantisch | Navigatie                      |
| `<header>` | Semantisch | Introductie van pagina/sectie  |
| `<main>`   | Semantisch | Hoofdinhoud                    |
| `<footer>` | Semantisch | Afsluitende informatie         |
| `<audio>`  | Media      | Audio afspelen                 |
| `<video>`  | Media      | Video afspelen                 |

# Conclusie

Gebruik semantische HTML-elementen zoals `<header>`, `<nav>`, `<main>` en `<footer>` wanneer mogelijk. Ze maken je website toegankelijker, beter voor SEO en makkelijker te onderhouden. Gebruik `<div>` en `<span>` alleen wanneer er geen specifiek semantisch element beschikbaar is. Voor multimedia gebruik je `<audio>` voor geluid en `<video>` voor videobestanden.
