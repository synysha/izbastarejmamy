# Tajomná izba Starej mamy

Spolupracujúca úniková hra pre 3 hráčky (každá na vlastnom telefóne), s úlohami v skutočnom dome.

## Nahratie na GitHub (GitHub Pages)
1. Na github.com vytvor nový repozitár (napr. `izba-starej-mamy`), verejný.
2. **Add file → Upload files** a nahraj VŠETKY súbory z tohto priečinka (index.html, sw.js, manifest.webmanifest, ikony…).
3. **Settings → Pages → Branch: main / (root) → Save**.
4. Po minúte bude hra na `https://<tvoje-meno>.github.io/izba-starej-mamy/`.
5. Na telefóne otvor odkaz → v menu prehliadača **Pridať na plochu**. Ikona sa objaví ako aplikácia.

## Ako sa hrá
- Jeden telefón dá **Vytvoriť hru** a ukáže 4-ciferný kód. Ostatné dva zadajú kód v **Pripojiť sa**.
- Každá si vyberie inú rolu. S 2 telefónmi sa dá spustiť **testovací režim**: zobrazia sa stopy všetkých rolí.
- Skutočné úlohy v dome nastavíš v **⚙️ Pre rodiča** (vidí ich len telefón, ktorý hru vytvoril).
- Telefón, ktorý hru vytvoril, musí zostať otvorený a zapnutý celú hru. Ak ho obnovíš, hra sa začne odznova.

## Technické
Spojenie telefónov ide cez PeerJS (WebRTC); verejný server sprostredkuje len nadviazanie spojenia, hra sa neukladá nikam. Knižnica sa načítava z jsDelivr, takže treba internet.
