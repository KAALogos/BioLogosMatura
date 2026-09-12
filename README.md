# Biologia — interaktywne laboratoria

Cztery moduły powtórkowe z biologii (zakres podstawowy i rozszerzony), w całości jako pojedyncze pliki HTML — bez zależności, bez budowania, działają offline w przeglądarce.

| Moduł | Plik | Aktywności |
|---|---|---|
| Bakterie, archeowce i wirusy | `bakterie-i-wirusy.html` | 12 |
| Komórka: system, nie katalog organelli | `komorka.html` | 10 |
| Woda: od dipola do biosfery | `woda.html` | 8 |
| Chemiczne laboratorium życia | `zwiazki-chemiczne.html` | 8 |

`index.html` jest stroną główną z kafelkami do wszystkich modułów.

## Uruchomienie

Otwórz `index.html` w przeglądarce albo skorzystaj z opublikowanej wersji GitHub Pages.

## Uwagi

- Postęp nauki liczony jest w obrębie jednej sesji przeglądarki (nie jest zapisywany).
- Każdy moduł ma arkusz stylów do druku.
- Źródła: podstawa programowa (ZPE) oraz informatory maturalne CKE.

## Ilustracje

Ryciny w `assets/` są skopiowane **bajt w bajt** z kanonicznego repozytorium [KAALogos/BioLogosMR](https://github.com/KAALogos/BioLogosMR) (projekt BioLogos v35.24.10) — bez przekodowywania i skalowania, pod oryginalnymi nazwami i w oryginalnych formatach. SHA-256 każdego pliku zgadza się z polem `payload_sha256` w rejestrze proweniencji BioLogos.

Pełne rekordy proweniencji (pochodzenie, autor/generator, licencja, nota źródłowa, powiązane zadanie) znajdują się w [`assets/PROWENIENCJA.md`](assets/PROWENIENCJA.md).

Zmiana bajtów którejkolwiek ryciny wymaga przejścia procedury `release_gate` z projektu BioLogos — nie wystarczy podmienić pliku.

Projekcja Hawortha α/β-D-glukopiranozy oraz modele sterowane suwakami są rysowane inline w SVG i nie pochodzą z BioLogos.
