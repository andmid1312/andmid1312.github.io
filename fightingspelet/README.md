# BOBBAN KOMBAT – fightingspelet

2D-fightingspel i 32-bitars arkadstil (som Street Fighter / Mortal Kombat / Tekken) med figurerna från "bobban och halte balto" plus Grok Bot och Grok. Gjort för Andreas, Love och Sigge.

Spela: öppna `dist/index.html` i en webbläsare (fungerar offline, allt finns i filen). Online: https://andmid1312.github.io/fightingspelet/

Nytt: tvåknappskombos (5-6 per figur, se hjälpsidorna i spelet), kedjekombos, retas-knapp (Y/U), fallande saker, yrsel. Skallen kastar mobiler och telefonlurar. Ny fighter: Gullebullen / Isdrottningen. Bobban har nu stor kofot och stor skruvmejsel.

Nytt (okt 2026): 11 fighters – Love, Sigge, Mila och Ferdi har tillkommit. KLÄDSEL-val på väljskärmen (R/O eller knappen "R/O: KLÄDSEL"): Love (brun t-shirt / college-hoodie med keps och regnbågsglasögon), Sigge (spindeldräkt / t-shirt med fidget spinner och randiga mjukisbyxor), Mila (ljus/rosa body), Ferdi (FK-tröja / grön tröja), Bobban (fleece/bröllop). AVSLUTA HONOM!/AVSLUTA HENNE!-läge med FNISSALITY-finisher. Ferdi får tankebubblor med kyrilliskt nonsens. Gullebullen har ny grafik och tvåknappsdraget FROSTIS-KLUNK (dricker iskall läsk, frostaura, kastar burken).

Musik: lägg en fil `music.mp3` bredvid `index.html` så spelas den i loop som bakgrundsmusik (M = musik av/på). Utan fil spelas en egen chiptune-slinga.

Bygg om: `python3 tools/prepare_assets.py && python3 tools/build.py`. Test: `cd test && node run.js` (skärmdumpar i `screens/`).
