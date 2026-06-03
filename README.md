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
