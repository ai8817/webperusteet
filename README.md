# Web-perusteet

## Julkaistu verkkosivu

https://ai8817.github.io/webperusteet/

## Tehtävä: HTML-elementin osien kuvaus

### Esimerkkikoodi

```html
<h1 id="heading1">This <strong>is</strong> header 1</h1>
```

### Koodin rakenne

1. `<h1>` aloittaa otsikkoelementin.
2. `id="heading1"` määrittää otsikon yksilöllisen tunnisteen.
3. `This` on tavallista tekstisisältöä.
4. `<strong>` aloittaa tekstin korostamisen.
5. `is` on korostettava sana.
6. `</strong>` päättää korostuksen.
7. `header 1` on otsikon loppuosa.
8. `</h1>` sulkee otsikkoelementin.

HTML-koodi luo ensimmäisen tason otsikon. Otsikolla on yksilöllinen `heading1`-tunniste, ja sana `is` on korostettu `<strong>`-elementillä.

## HTML – Muistiinpanot

### 1. Mikä on HTML?

HTML (HyperText Markup Language) on merkintäkieli, jolla määritellään verkkosivujen rakenne ja sisältö.

HTML:llä voidaan luoda esimerkiksi:

- Otsikoita
- Kappaleita
- Linkkejä
- Kuvia
- Listoja

### 2. HTML-elementit

HTML koostuu elementeistä, jotka määrittelevät sivun sisältöä.

Elementti sisältää yleensä kolme osaa:

- **Aloitustagi:** `<p>`
- **Sisältö:** `Hello world!`
- **Lopetustagi:** `</p>`

Esimerkki:

```html
<p>Hello world!</p>
```

### 3. Sisäkkäiset elementit

HTML-elementtejä voidaan sijoittaa toisten elementtien sisälle. Tätä kutsutaan sisäkkäisyydeksi (Nesting).

Esimerkki:

```html
<p>This is <strong>important</strong> text.</p>
```

Elementit täytyy sulkea oikeassa järjestyksessä. Viimeisenä avattu elementti suljetaan ensimmäisenä.

### 4. Attribuutit

Attribuutit antavat HTML-elementeille lisätietoja. Ne kirjoitetaan aloitustagin sisälle.

Esimerkki:

```html
<p id="example" class="text">Hello world!</p>
```

- `id` antaa elementille yksilöllisen tunnisteen.
- `class` määrittää elementin luokan.
- Attribuutin arvo kirjoitetaan yleensä lainausmerkkien sisään.

### 5. Tyhjät elementit

Kaikki HTML-elementit eivät tarvitse lopetustagia tai sisältöä. Näitä kutsutaan tyhjiksi elementeiksi (Void elements).

Esimerkkejä:

```html
<br />
<img src="image.jpg" alt="Example image" />
```

- `<br>` lisää rivinvaihdon.
- `<img>` lisää kuvan sivulle.

### 6. HTML-dokumentin rakenne

HTML-dokumentin perusrakenne näyttää tältä:

```html
<!DOCTYPE html>
<html lang="fi">
  <head>
    <meta charset="UTF-8" />
    <title>Oma verkkosivu</title>
  </head>
  <body>
    <h1>Hei maailma!</h1>
    <p>Tämä on verkkosivuni.</p>
  </body>
</html>
```

- `<!DOCTYPE html>` määrittää dokumentin HTML5-dokumentiksi.
- `<html>` on dokumentin juurielementti.
- `<head>` sisältää sivun metatiedot.
- `<title>` määrittää selaimen välilehden otsikon.
- `<body>` sisältää verkkosivulla näkyvän sisällön.

### 7. Muut tärkeät asiat

- **Sisennykset:** Helpottavat koodin lukemista ja rakennetta.
- **Erikoismerkit:** Esimerkiksi `<` kirjoitetaan `&lt;` ja `>` kirjoitetaan `&gt;`.
- **Kommentit:** Kirjoitetaan muodossa `<!-- kommentti -->`. Ne eivät näy verkkosivulla.
- **Kirjainkoko:** HTML-tagit eivät ole kirjainkoon suhteen merkitseviä. Pienet kirjaimet ovat suositeltu käytäntö.

### 8. Yhteenveto

HTML määrittelee verkkosivun rakenteen. Sen tärkeimmät perusasiat ovat elementit, tagit, attribuutit ja sisäkkäisyys.

HTML:n oikea rakenne ja elementtien sulkeminen ovat tärkeitä, jotta verkkosivu toimii oikein ja koodi pysyy helposti luettavana.

### Lähteet

- [MDN – HTML](https://developer.mozilla.org/en-US/docs/Glossary/HTML)
- [MDN – Basic HTML syntax](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Basic_HTML_syntax)
