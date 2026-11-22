# 🕰️ Óraiskola

Interaktív, magyar nyelvű oktató webalkalmazás az analóg óra leolvasásának megtanulásához és gyakorlásához. Egyetlen HTML-fájlból áll, külső függőségek és telepítés nélkül működik asztali számítógépen és mobilon is.

## ✨ Funkciók

- **Egyetlen fájl, nulla függőség**: tiszta HTML, CSS, SVG és JavaScript (`ora-iskola.html`).
- **Érintőképernyő- és egérbarát vezérlés**: a mutatók Pointer Events segítségével húzhatók körbe a számlapon (`touch-action: none` támogatással).
- **Magyar nyelvű időmegnevezések**: automatikusan megjeleníti a helyes magyar kifejezéseket is (pl. *3 óra pontosan*, *negyed 4*, *fél 4*, *háromnegyed 4*).
- **Reszponzív kialakítás**: alkalmazkodik kisebb képernyőkhöz is, valamint figyelembe veszi a `prefers-reduced-motion` beállítást.

### 📚 Tanulás mód
- Szabadon forgatható **rövid (rózsaszín) óramutató** és **hosszú (kék) percmutató**.
- Az óramutató valósághűen, fokozatosan halad az óraszámok között a percek előrehaladtával.
- Valós idejű digitális órakijelzés, szöveges kiírás és rövid magyarázat a mutatók állásáról.
- Gyorsgombok a visszaállításhoz (`↺ 3:00-ra`) és véletlen időpont generálásához (`✨ Mutass mást!`).

### 🎯 Gyakorlás mód
- A megadott célidőt kell beállítani az analóg órán, majd a **✓ Ellenőrzés** gombbal ellenőrizhető a válasz.
- **5 választható nehézségi szint**:
  1. **Egész órák** (60 perces lépések)
  2. **Fél órák** (30 perces lépések)
  3. **Negyed órák** (15 perces lépések)
  4. **Ötpercesek** (5 perces lépések – alapértelmezett)
  5. **Perces kihívás** (1 perces pontosság)
- **Pontozás és sorozat**: minden helyes válasz `10` pontot ér, plusz a hibátlan sorozat (*streak*) alapján további bónuszpontot ad (legfeljebb `+10` pontot válaszonként), és akár 3 csillag (`★★★`) is összegyűjthető.

## 🚀 Használat

1. Töltsd le vagy klónozd a repót:
   ```bash
   git clone <repo-url>
   ```
2. Nyisd meg az [`ora-iskola.html`](ora-iskola.html) fájlt bármely modern böngészőben (Chrome, Edge, Firefox, Safari).

> **Tipp GitHub Pageshez:** ha online is meg szeretnéd osztani, a GitHub repó beállításainál kapcsold be a *GitHub Pages*-t, majd nyisd meg az oldalt az `/ora-iskola.html` útvonalon (vagy másold/nevezd át `index.html`-re).

## 📁 Fájlstruktúra

```text
.
├── ora-iskola.html   # A teljes alkalmazás (HTML + CSS + SVG + JS)
└── README.md         # Dokumentáció
```
