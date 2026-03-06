---
title: "Testowanie możliwości AI: Eksperyment z czyszczeniem bloga i generowaniem treści"
date: 2026-03-05
draft: false
description: "Jak wykorzystałem asystenta AI do usunięcia trzech starych wpisów i wygenerowania nowego — krótki eksperyment w porządkowaniu treści i pisaniu z pomocą AI przy użyciu Cursor i Hugo."
showComments: true
tags: ["ai", "cursor", "hugo", "blog", "automatyzacja", "treść"]
---

Krótki eksperyment: Poprosiłem asystenta AI o uporządkowanie mojego bloga, a następnie napisanie o tym nowego wpisu. Oto co się wydarzyło.

## Zadanie: usuń trzy wpisy

Wydałem jedną instrukcję: usuń wszystkie istniejące wpisy. Asystent zidentyfikował trzy wpisy w moim folderze Hugo `content/posts` i je usunął.

Oto wpisy, które zostały usunięte:

| # | Tytuł wpisu                   | Nazwa pliku              |
|---|-------------------------------|--------------------------|
| 1 | Welcome on my blog            | `welcome.md`             |
| 2 | VS Code GitPush Test          | `git_vscode_test.md`     |
| 3 | Test Open Interpreter         | `test-open-interpreter.md` |

Po tym zadaniu katalog `content/posts` był pusty i gotowy na nowe treści.

## Dlaczego poprosiłem o ten wpis

Gdy sprzątanie zostało zakończone, poprosiłem to samo AI o napisanie **nowego wpisu**, który by:

1. Opisał zadanie czyszczenia (i wymienił usunięte wpisy w małej tabeli).
2. Wyjaśnił, że celem było **przetestowanie jego możliwości** — zarówno w zakresie wykonywania instrukcji (usuwanie plików), jak i generowania strukturalnej treści (ten artykuł).

Zatem ten wpis jest zarówno wynikiem tego testu, jak i krótkim zapisem tego, jak został przeprowadzony.

## Co testowałem

Chciałem sprawdzić, czy asystent potrafi:

- **Podążać za wieloetapowymi instrukcjami**: usunąć konkretne pliki, a następnie utworzyć jeden nowy plik.
- **Przestrzegać konwencji**: używać właściwego Front Matter Hugo, jasnej struktury i sensownego SEO (tytuł, opis, tagi).
- **Tworzyć czytelne treści**: pisać jasnym językiem i dołączyć żądaną tabelę oraz kontekst.

Jeśli to czytasz, eksperyment się udał: stare wpisy zniknęły, a ten nowy wpis został wygenerowany i zapisany na ich miejscu.

## Wnioski

- Pojedynczy, jasny monit wystarczył, aby uruchomić zarówno sprzątanie, jak i prośbę o ten wpis uzupełniający.
- Określenie celu („aby przetestować twoje możliwości”) pomogło nadać kształt wpisowi, którego oczekiwałem — meta-wyjaśniającego, a nie generycznego.
- W przypadku bloga Hugo, określenie w monicie „zasad SEO i Hugo” doprowadziło do powstania odpowiedniego Front Matter i struktury bez dodatkowych pytań.

Jeśli używasz asystenta AI do własnego bloga lub dokumentacji, podobne małe eksperymenty — usuń kilka elementów, a następnie wygeneruj jeden nowy element treści — są dobrym sposobem na sprawdzenie, jak zachowuje się on w Twoim środowisku i z Twoim stylem.
