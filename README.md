# Pronalaženje skrivenog znanja (PSZ)

Materijali, zadatak i projekat sa predmeta **Pronalaženje skrivenog znanja**
(13M111PSZ) — master studije na [Elektrotehničkom fakultetu Univerziteta u
Beogradu](https://www.etf.bg.ac.rs/). Repo je uključen kao git submodule
super-projekta [ETF-Master](https://github.com/MegatronJeremy/ETF-Master).

> Zvanični sajt predmeta: <https://rti.etf.bg.ac.rs/rti/ms1psz/>
> Profesori: B. Nikolić, D. Drašković · asistent: J. Cincović

## Sadržaj

| Putanja | Opis |
| --- | --- |
| [`PSZ_Projekat_2026.pdf`](PSZ_Projekat_2026.pdf) | Postavka aktuelnog projektnog zadatka (2025/2026) |
| [`Sea-Of-Sorrow/`](Sea-Of-Sorrow) | Projekat — scraping, analiza, vizuelizacija i ML nad podacima o beloj tehnici (submodule) |
| [`materijali/predavanja/`](materijali/predavanja) | Slajdovi sa predavanja (analiza podataka, nadgledano ML, probabilistički modeli, široki pojas, stabla odlučivanja, kNN, k-Means) |
| [`materijali/literatura/`](materijali/literatura) | Dodatna literatura po temama (regresije, SVM, naivni Bajes, evaluacija modela, mašinsko učenje) |
| [`materijali/vezbe/`](materijali/vezbe) | Kodovi sa vežbi (`psz_*.zip/7z`) + Weka podaci (`weka/*.arff`) |
| [`materijali/raniji/`](materijali/raniji) | Postavka zadatka iz ranije godine (2024/2025) |

Materijali su preuzeti sa [zvaničnog sajta predmeta](https://rti.etf.bg.ac.rs/rti/ms1psz/)
(sekcija *Literatura*).

## Submoduli

| Putanja | Upstream |
| --- | --- |
| `Sea-Of-Sorrow` | https://github.com/MegatronJeremy/Sea-Of-Sorrow |

## Kloniranje

```bash
git clone --recursive https://github.com/MegatronJeremy/PSZ
# ili, ako je već kloniran bez submodula:
git submodule update --init --recursive
```
