# HTML5/CSS3 Einführung

Enno Hyttrek, November 2024

https://ehy-classroom.github.io/html-css-introduction/

---

### Was ist HTML und wie ist es entstanden?

**HTML** (Hypertext Markup Language) ist die Sprache, die das Grundgerüst jeder Website im Internet bildet. HTML beschreibt, wie Inhalte wie Text, Bilder und Links auf einer Website angezeigt werden sollen. HTML wurde Ende der 1980er Jahre von **Tim Berners-Lee** entwickelt, um Forschern am CERN eine gemeinsame Plattform für den Austausch von Informationen zu bieten. Der erste HTML-Standard kam 1991 heraus und legte die Basis für die Entwicklung von Websites.

---

### Was ist CSS und wie ist es entstanden?

**CSS** (Cascading Style Sheets) ist die Sprache, die das Design und Layout einer HTML-Seite beschreibt. Mit CSS können Farbe, Schriftarten, Abstände und Layouts für HTML-Elemente festgelegt werden. CSS wurde Mitte der 1990er Jahre entwickelt und veröffentlicht, um Design und Inhalte voneinander zu trennen. Dadurch konnte das Layout einer Website an einem zentralen Ort gesteuert werden, ohne den HTML-Code zu überladen.

---

### Die Syntax: HTML und CSS

#### HTML-Syntax

- **Tags**: HTML verwendet Tags, die den Browser anweisen, wie verschiedene Inhalte dargestellt werden sollen. Ein Tag besteht aus einem **Öffnungstag** (`<tag>`) und einem **Schließtag** (`</tag>`).
  
  Beispiel:
  ```html
  <p>Dies ist ein Absatz.</p>
  ```

- **Attribute**: HTML-Tags können Attribute haben, die zusätzliche Informationen bereitstellen. Ein Attribut hat einen **Namen** und einen **Wert**.

  Beispiel:
  ```html
  <img src="bild.jpg" alt="Ein Bild">
  ```

- **Block- und Inline-Elemente**:
  - **Block-Elemente**: Block-Elemente wie `<div>`, `<p>`, und `<h1>` füllen immer die gesamte Breite ihres Containers.
  - **Inline-Elemente**: Inline-Elemente wie `<span>`, `<a>`, und `<img>` nehmen nur so viel Platz wie nötig ein und bleiben in der Zeile.

#### CSS-Syntax

CSS verwendet eine andere Syntax, bei der das Design in Form von **Eigenschaften** und **Werten** beschrieben wird. Ein CSS-Regelwerk besteht aus einem **Selektor** und einem **Deklarationsblock**.

```css
p {
    color: blue;
    font-size: 16px;
}
```

- **Herkunft des CSS-Stils (Style-Attribut)**:
  - CSS kann im HTML-Code selbst durch das **Style-Attribut** definiert werden:
    ```html
    <p style="color: blue;">Blauer Text</p>
    ```
  - Für eine klarere Struktur ist es jedoch besser, CSS entweder im `<style>`-Tag im `<head>` oder in einer externen Datei zu verwenden.

---

### Aufbau einer HTML-Seite (ohne CSS)

Hier erstellen wir eine einfache HTML-Seite mit der grundlegenden Struktur und einigen wichtigen Elementen.

#### Grundstruktur einer HTML-Seite

```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Meine erste HTML-Seite</title>
</head>
<body>
    <!-- Inhalte der Seite kommen hier hin -->
</body>
</html>
```

#### Details zur Struktur

- **`<!DOCTYPE html>`**: Deklariert das Dokument als HTML5.
- **`<html lang="de">`**: Das Attribut `lang="de"` gibt die Sprache des Dokuments an (wichtig für Suchmaschinen und Barrierefreiheit).
- **`<head>`**: Enthält Metadaten über die Seite, die nicht angezeigt werden.
- **`<meta charset="UTF-8">`**: Definiert die Zeichencodierung als UTF-8.
- **`<title>`**: Der Titel der Seite, der im Browser-Tab angezeigt wird.
- **`<body>`**: Enthält den sichtbaren Inhalt der Seite.

---

### Übungsbeispiel „Hello World“: Grundstruktur und erste Elemente

1. **Titel und Überschriftenhierarchie**:
   - `<h1>` bis `<h6>`: Überschriftenelemente, die von `<h1>` (wichtigste Überschrift) bis `<h6>` (unwichtigste Überschrift) reichen.

   ```html
   <h1>Hello World!</h1>
   <h2>Unterüberschrift</h2>
   <h3>Eine weitere Unterüberschrift</h3>
   ```

2. **Absätze mit Blindtext**:
   - Absätze werden mit dem `<p>`-Tag erstellt. Hier fügen wir drei Absätze mit Blindtext ein:

   ```html
   <p>Dies ist ein Beispielabsatz mit Blindtext, der nur als Platzhalter dient.</p>
   <p>Ein weiterer Absatz, der das Layout auflockern soll und zusätzlichen Platz belegt.</p>
   <p>Der dritte Absatz zeigt, wie mehrere Absätze im Layout platziert werden können.</p>
   ```

3. **Hyperlinks**:
   - Hyperlinks werden mit `<a>`-Tags erstellt. Das Attribut `href` gibt die Ziel-URL an.

   ```html
   <a href="https://www.beispiel.com">Besuche Beispiel.com</a>
   ```

4. **Bilder**:
   - Bilder werden mit `<img>`-Tags eingefügt. Das `src`-Attribut enthält die Bildquelle, und das `alt`-Attribut eine Beschreibung.

   ```html
   <img src="bild.jpg" alt="Beispielbild">
   ```

---

### Zusammenfassung

- **HTML** beschreibt die Struktur und den Inhalt einer Webseite, während **CSS** das Design und Layout steuert.
- HTML besteht aus **Tags** und **Attributen**, mit einer klaren Trennung in Block- und Inline-Elemente.
- CSS wird meist getrennt von HTML verwendet, um den Code übersichtlich zu halten.
- Eine vollständige HTML-Seite hat eine festgelegte Struktur mit **`<!DOCTYPE html>`**, **`<html>`**, **`<head>`**, und **`<body>`**.

---

Quellen/Links:

#### Deutsch

https://wiki.selfhtml.org/wiki/HTML/Tutorials/Entstehung_und_Entwicklung

https://wiki.selfhtml.org/wiki/HTML/Tutorials/Einstieg

https://wiki.selfhtml.org/wiki/HTML/Tutorials/Element,_Tag_und_Attribut

#### Englisch

https://www.w3schools.com/html/default.asp

