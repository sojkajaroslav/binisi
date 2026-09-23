# Lovely Binisi

Statický web v Astru. Bez databáze a administrace; zdrojové soubory lze průběžně měnit.

## Spuštění

```bash
npm install
npm run dev
```

## Vercel

Importujte tuto složku jako projekt. Vercel rozpozná Astro, příkaz sestavení je `npm run build` a výstupní složka `dist`. Před změnou DNS doporučujeme zkontrolovat náhled Vercelu.

## Úpravy

Texty stránek jsou v `src/pages`, společná hlavička a patička v `src/layouts/Base.astro`, barvy a typografie v `src/styles.css`. Fotografie a logo jsou v `public/images`. Při výměně souboru při zachování jména se odkazy na fotku nemusí upravovat. Údaje o vrzích odpovídají současnému webu k září 2026; pro nové vrhy upravte `src/pages/stenata.astro`.
