# Plan audytu — f95-gallery-gleaner

## Status
AUDYT ZAKOŃCZONY — 2026-09-12.

## Ustalenia
Lokalny katalog/aktualizator kolekcji gier z indeksowaniem zmian, metadanymi, watcherem i checksumami. README opisuje źródła zewnętrzne, automatyczne sprawdzanie aktualizacji oraz opcjonalne LLM.

## Ryzyka
Treści NSFW, prawa autorskie, agregowanie zewnętrznych źródeł, pobieranie artefaktów, bezpieczeństwo archiwów i ryzyko nieautoryzowanego dostępu do serwisów. Deklarowany checksum/sandbox extraction wymaga potwierdzenia w kodzie.

## Dalsza praca
Utrzymać wyłącznie legalny, osobisty charakter narzędzia. Zweryfikować parsery, źródła, rate limiting, integralność pobrań, path traversal przy ekstrakcji i izolację instalacji. Nie implementować omijania paywall/DRM/anti-bot.
