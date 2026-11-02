# Mapa strony: Radca Prawny Andrzej Kusiak

Źródło: `docs/brief.md`, `docs/research.md`. Strona nowa (brak własnej witryny). Typ: Local Service (kancelaria jednoosobowa, Myślenice).

## Cel i zasady
- Cel: telefon / zapytanie od osoby z Myślenic i okolic. Jedno główne CTA: **zadzwoń 510 175 906** (+ formularz jako drugie).
- Ton: formalny, rzeczowy, prosty język, Pan/Pani (do potwierdzenia z klientem).
- Tylko fakty zweryfikowane. Braki oznaczone `[DO POTWIERDZENIA]` w plikach treści.
- Reklama radcy prawnego jest ograniczona etyką zawodową: bez "najlepszy", gwarancji wyniku, porównań z innymi kancelariami. Opinie cytować tylko za zgodą.
- Przewaga nad lokalną konkurencją: czysty szablon, działający click-to-call, pełne dane kontaktowe, jasna lista usług.

## Drzewo stron

| # | URL | Cel / intencja | Główna fraza | Plik treści |
|---|-----|----------------|--------------|-------------|
| 1 | `/` | Strona główna, konwersja | radca prawny Myślenice | `content/index.md` |
| 2 | `/uslugi/` | Przegląd usług, hub | usługi prawne Myślenice | `content/uslugi.md` |
| 3 | `/uslugi/porady-prawne/` | Konsultacja, analiza, dokumenty | porada prawna Myślenice | `content/uslugi-porady-prawne.md` |
| 4 | `/uslugi/reprezentacja-sadowa/` | Sprawy sądowe, pisma procesowe | radca prawny sprawy sądowe Myślenice | `content/uslugi-reprezentacja-sadowa.md` |
| 5 | `/uslugi/nieruchomosci/` | Sprawy dot. nieruchomości | prawo nieruchomości Myślenice | `content/uslugi-nieruchomosci.md` |
| 6 | `/uslugi/windykacja/` | Odzyskiwanie należności | windykacja Myślenice | `content/uslugi-windykacja.md` |
| 7 | `/uslugi/rozwod-separacja-podzial-majatku/` | Sprawy rodzinne | rozwód Myślenice | `content/uslugi-rozwod.md` |
| 8 | `/uslugi/umowy-i-regulaminy/` | Umowy, regulaminy | sporządzanie umów Myślenice | `content/uslugi-umowy.md` |
| 9 | `/o-kancelarii/` | Zaufanie: kto, odznaczenia | Andrzej Kusiak radca prawny | `content/o-kancelarii.md` |
| 10 | `/kontakt/` | Telefon, adres, mapa, formularz | kancelaria Myślenice kontakt | `content/kontakt.md` |
| 11 | `/polityka-prywatnosci/` | Wymóg RODO / formularz | n/d (noindex niepotrzebny) | `content/polityka-prywatnosci.md` |

Mapowanie 7 usług z profilu na 6 stron: "sporządzanie pism prawnych i procesowych" jest włączone do reprezentacji sądowej i porad.

## Nawigacja
- Nagłówek: Usługi (rozwijane, 6 pozycji) · O kancelarii · Kontakt · przycisk **Zadzwoń** (`tel:+48510175906`, sticky na mobile).
- Stopka: dane firmy (nazwa, adres, tel., NIP, REGON), linki do usług, Polityka prywatności.
- Linkowanie wewnętrzne: strona główna → wszystkie usługi; każda usługa → `/kontakt/` + 1–2 usługi pokrewne (rozwód ↔ nieruchomości, windykacja ↔ umowy, sądowa ↔ porady).

## Dane strukturalne (Schema.org JSON-LD)
- Cała witryna: `LegalService` (lub `Attorney`) z `name`, `address`, `telephone`, `areaServed`, `identifier` (NIP).
- `aggregateRating` (5,0 / 15) tylko jeśli ocena jest widoczna na stronie i zgodna z wytycznymi Google dla self-serving reviews; w razie wątpliwości pominąć.
- `BreadcrumbList` na podstronach usług.
- Bez FAQPage i HowTo.

## Elementy wspólne
- Title ≤ 60 znaków, meta description ≤ 155, jedno H1 na stronę.
- Jeden spójny blok NAP (nazwa, adres, telefon) identyczny wszędzie i z wizytówką Google.
- Mapa Google (Plus Code RWJW+C5) tylko na `/kontakt/`.
- Odznaki Orły Prawa 2024–2026 na stronie głównej i `/o-kancelarii/`.

## Braki do uzupełnienia przez klienta
Email · godziny przyjęć · numer wpisu OIRP · lata praktyki / bio / wykształcenie · cennik lub zasady wyceny, pierwsza konsultacja bezpłatna? · obszar działania poza Myślenicami · konsultacje online · zgoda na cytowanie opinii z Google (treść opinii) · weryfikacja NIP i REGON (z fragmentów wyszukiwarki) · czy adres jest wspólnym biurem (nie wspominać).
