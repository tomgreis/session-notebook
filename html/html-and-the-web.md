# HTML and the Web

HTML (Hypertext Markup Language) ist eine Auszeichnungssprache, die Texten Elemente zur Verfügung stellt, um die Texte besser strukturieren und dadurch handhabbar zu bekommen. Der britische Informatiker Tim Barner-Lee hat den Prototyp der der Sprache 1989 entwickelt, um sich besser mit seinen Kolleg.innen austauschen zu können. Auf HTML baut das WWW auf. Tim Barner-Lee gilt seitdem als “Erfinder des Internets”.

Ergänzend zu Markup Language wurde ein vereinfachtes HTML entwickelt, Markdown. Es soll HTML ergänzen und die Textauszeichnung vereinfachen und beschleunigen.

## HTML interaktiv lernen

https://web-active-learning.vercel.app/documents/html-and-the-web

## Definitionen

- Deklaration = Eine spezielle Anweisung in einem HTML-Dokument, wie z.B. `<!DOCTYPE html>` für HTML 5
- Element = Zentraler Baustein eines HTML-Dokuments, bestehend aus Start-Tag, Inhalt, End-Tag, wie z.B. `<title>Meine Website</title>`
- Selbstschließendes Element = Ein Element, dass keine schließende Klammer braucht, wie z.B. `<img>`, man kann optional es auch inerhalb der Klammern schließen `<img />`
- Attribut = Zusätzliche Information oder Eigenschaft eines Elements, Attribute bestehen immer aus einem Namen und einem Wert, wie z.B. im Element `<a href=”xyz” target=”_blank”>` wurden die Attribute href und target zugefügt.
- Tag = Das definierende Zeichen für ein Element bezeichnet man als Tag, wie z.B. `<p>`-Tag, `<meta>`-Tag oder `<title>`-Tag

## Grundstruktur

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

- Das Html-Tag `<html lang=”en”>` teilt dem Browser mit, dass der Inhalt des Dokuments auf Englisch ist.
- Das Meta-Tag `<meta charset="UTF-8">` teilt dem Browser mit (deklariert), das der Inhalt des Dokuments in im character set UTF-8 kodiert ist. Das UTF-8 (Unicode Transformation Format -- 8-bit) kann bis zu 1,1 Mio. Zeichen darstellen.
- Das Meta-Tag `<name=”viewport” content=”width=device-width, inital-scale=1.0”>` teilt dem Bowser mit, wie die Ansichtseigenschaften der Website festzulegen und zu kontrollieren sind und spielt daher eine zentrale Rolle im Responsive Web Design, um auf allen Bildschirmen gut dargestellt zu werden und entsprechend gezoomt werden zu können. Das Attribut `width=device-width` setzt die Breite des Viewports auf die Breite des Geräts, das Attribut `initial-scale=1.0` setzt den anfänglichen Zoomfaktor auf 1.0.
