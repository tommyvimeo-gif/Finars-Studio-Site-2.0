# FIN ARS – Prenovljena spletna stran

Sodobna, odzivna (mobile + desktop) spletna stran arhitekturnega biroja **FIN ARS d.o.o.**

## Značilnosti

- **Dizajn**: Minimalističen, Apple-inspired + visokokakovostni arhitekturni portfolio stil
- **Animirano hero ozadje** (Ken Burns efekt)
- **Lightbox zoom** na vseh slikah (klik → povečava)
- **Odzivno** za mobilne telefone in namizne računalnike
- **Strani**:
  - `index.html` – Domov
  - `projekti.html` – Pregled vseh projektov
  - `o-nas.html` – O biroju + ekipa + storitve
  - `kontakt.html` – Kontaktni podatki + obrazec
  - `projekti/*.html` – Posamezne podstrani projektov

## Vključeni projekti

- Olimpijski bazen in wellness (Libija, 2013)
- Prenova OŠ Revirski borci (Trbovlje, 2013)
- Urbana dnevna soba na deželi (2011)
- Prenova dvoran ČZS (2011)
- Stanovanja R (Rogaška Slatina, 2010–2011)
- Vrtec Kisovec (2010)
- Mercator Škofja Loka (2010)
- SPAR Litija (2007)
- Blok K3 (2007)
- Stanovanjsko naselje Podčetrtek (2013)
- Avtohiša S (2007)

## Kako zamenjati slike z originalnimi

Ker je originalna stran finars.si zaščitena, so trenutno uporabljeni visokokakovostni arhitekturni placeholderji (Unsplash).

**Za originalne barvne slike:**

1. Prenesite slike iz map na https://finars.si/projekti/ (npr. `2013 7 olimpijski bazen libija/`)
2. Shranite jih v mapo `images/` (ali neposredno v `projekti/`)
3. V HTML datotekah zamenjajte `src="https://images.unsplash.com/..."` z lokalnimi potmi, npr.:
   ```html
   <img src="../images/olimpijski-bazen-01.jpg" alt="..." data-zoom>
   ```

Vse slike z atributom `data-zoom` ali znotraj `.gallery-item` se samodejno odprejo v lightboxu.

## Zagon

Odprite `index.html` v brskalniku ali postavite celotno mapo na spletni strežnik / GitHub Pages.

Za lokalni predogled:
```bash
cd Finars-Studio-Site-2.0
python3 -m http.server 8000
```
Nato odprite http://localhost:8000

## Kontaktni podatki (iz originalne strani)

- **Kristijan Čuk** u.d.i.a. (strokovni direktor)  
  +386 41 686 959 · kristijan.cuk@finars.si

- **Borut Dolar** (poslovni direktor)  
  +386 31 370 172 · borut.dolar@finars.si

- Naslov: Podvine 36, 1410 Zagorje ob Savi  
- Matična št.: 2144921000  
- Davčna št.: 70790817

---

Narejeno z natančnostjo in občutkom za sofisticiran arhitekturni nastop.
