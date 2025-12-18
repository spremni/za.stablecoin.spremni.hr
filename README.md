# Stablecoin: budućnost plaćanja ili uvod u novu krizu?

Interaktivni kronološki pregled panel diskusije o stablecoinima održane 3. prosinca 2025. u Moneteri, Muzeju novca HNB-a, u sklopu serije javnih predavanja "Zbog čega guverneri noću ne spavaju?".

## O projektu

Ovaj landing page vizualizira panel diskusiju između:

**Panelisti:**
- **Marko Škreb** - Bivši guverner HNB-a, konzultant u središnjem bankarstvu
- **Nikola Škorić** - Osnivač i CEO Electrocoina

**Moderator:**
- **Božidar Pavlović** - Aymo Ventures

## Funkcionalnosti

- **Embedded YouTube player** - Sticky video player s YouTube IFrame API integracijom
- **Interaktivni timeline** - Kronološki pregled ključnih izjava s timestampovima
- **Screenshot galerija** - 59 screenshotova s ključnih trenutaka panela
- **Seek funkcionalnost** - Klik na timestamp ili screenshot automatski seeka video
- **Sinkronizacija** - Aktivna timeline kartica se ažurira u realnom vremenu
- **Responsive dizajn** - Optimizirano za desktop i mobilne uređaje
- **Social sharing** - Open Graph i Twitter Card meta tagovi

## Tehnologije

- HTML5 / CSS3
- Vanilla JavaScript
- YouTube IFrame API
- Google Fonts (Instrument Serif, DM Sans, JetBrains Mono)

## Struktura projekta

```
za.stablecoin.spremni.hr/
├── index.html                              # Glavni HTML dokument
├── images/                                 # Screenshot galerija (59 slika)
├── timestamp_screenshots_Er5CcLF4xyg.json  # Metadata screenshotova
├── timestamp_screenshots_schema.json       # JSON schema
├── transcript_croatian_*.txt               # Transkripti (original i uređen)
├── za_stablecoin_spremni_hr_og_image_*.png # OG slika za social sharing
├── README.md                               # Ovaj dokument
└── LICENSE                                 # MIT licenca
```

## Lokalni razvoj

Pokretanje lokalnog servera:

```bash
npx ws -p 8080
```

Zatim otvoriti http://localhost:8080 u pregledniku.

## Izvor

- **Video:** [YouTube - Monetera HNB](https://www.youtube.com/watch?v=Er5CcLF4xyg)
- **Serija:** "Zbog čega guverneri noću ne spavaju?"
- **Datum:** 3. prosinca 2025.
- **Lokacija:** Monetera, Muzej novca HNB-a, Zagreb

## Autor

Ovaj projekt kreirao je **Matija Stepanić**, softverski inženjer, CEO @ [ITalk](https://italk.hr), korištenjem alata [Claude Code](https://claude.com/product/claude-code) (LLM model Opus 4.5).

## Licenca

Ovaj projekt je licenciran pod MIT licencom - pogledajte [LICENSE](LICENSE) datoteku za detalje.
