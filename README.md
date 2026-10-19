# LinguIA

Personalizovaná online výučba angličtiny nad tvojimi edukáčnymi HTML aplikáciami.

**GitHub:** https://github.com/HenrichHrehor/LinguIA  
**Cieľ v1:** hub + mapa tém (Starter / Support / Advance) + onboarding → návrh online plánu (+2 extra hodiny) pre učiteľa.

## Čo LinguIA nie je (zatiaľ)
- Nie je plne autonómny kurz bez učiteľa.
- Nie je náhrada za odučenie — systém navrhne plán, ty odučíš.

## V1 rozsah
1. Kostra tém a úrovní
2. Mapovanie existujúcich HTML appiek k témam
3. Onboarding (ako dlho sa učí, čo má rád, demotivátory, požadovaná gramatika / kniha+unit)
4. Generovaný **návrh** online plánu + 2 extra hodiny
5. Neskôr: Supabase (kód študenta, progres)

## Úrovne
| Level | Význam |
|-------|--------|
| Starter | Základ, opora, pomalšie tempo |
| Support | Školský stred, upevnenie |
| Advance | Rozšírenie, rýchlejšie tempo |

## Štruktúra repo
```
LinguIA/
  index.html              # test hub
  onboarding/             # vstupný dotazník (v1 mock)
  curriculum/             # témy, úrovne, mapovanie appiek
  apps/                   # (neskôr) alebo odkazy na HTML appky
  docs/                   # koncept a rozhodnutia
```

## Lokálne
Otvor priečinok v Cursor:
`C:\Users\forwa\OneDrive\Dokumenty\Cursor\LinguIA`

## Test na GitHub Pages
Settings → Pages → Deploy from branch `main` / root (alebo `/docs`).
