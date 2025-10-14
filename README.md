# mtmdpl — Szablon pracy dyplomowej MTM (EAIiIB, AGH)

Szablon klasy LaTeX dla kierunku **Mikroelektronika w Technice i Medycynie (MTM)**, wydział **EAIiIB**, AGH.

Oparty na [aghdpl v4.0](https://github.com/pkleczek-agh/aghdpl) autorstwa Pawła Kłeczka i oryginalnym szablonie prof. Marcina Szpyrki.

## Status
> Wersja: 0.9.0-beta
> Stabilna funkcjonalnie, możliwe drobne poprawki w układzie i przykładach.

## Szybki start
```bash
git clone https://github.com/piotrkaczmarczyk1/mtmdpl
cd mtmdpl
pdflatex thesis.tex


Klasa **aghdpl** (szablon dokumentu) została opracowana w celu ułatwienia studentom naszej Uczelni składania prac dyplomowych w systemie LaTeX. Odpowiednie opcje pozwalają na skład zarówno prac inżynierskich jak i magisterskich przez studentów wszystkich wydziałów AGH. Praca może zostać przygotowana w języku polskim lub angielskim.

Prezentowana wersja 4.0 jest zgodna z obowiązującym od roku akademickiego 2019/20 formatem przygotowania prac dyplomowych na Wydziale EAIiIB (zob. [Zasady dyplomowania](https://www.eaiib.agh.edu.pl/egzamin-dyplomowy-i-prace-dyplomowe/)).


## Autorzy ##

  * [Piotr Kaczmarczyk](https://home.agh.edu.pl/pkaczmar)
  * [Andrzej Kozdrowski]
  * [Paweł Kłeczek](https://skos.agh.edu.pl/osoba/pawel-kleczek-8552.html)
  * [Grzegorz J. Nalepa](https://skos.agh.edu.pl/osoba/grzegorz-jacek-nalepa-5324.html)
  * [Marcin Szpyrka](https://skos.agh.edu.pl/osoba/marcin-szpyrka-5059.html)


## Pliki ##

Repozytorium zawiera zawiera:
  * plik mtmdpl.cls z klasą dokumentu,
  * logo AGH w formacie JPG (potrzebne przy kompilacji programem _pdflatex_),
  * przykładowe pliki źródłowe ilustrujące wykorzystanie klasy _mtmdpl_.


## Uwagi ##

  * Wszystkie pliki zostały zapisane w kodowaniu **UTF-8**.
  * Klasa została zoptymalizowana do pracy z programem **pdflatex**.
  * Skrypt do usuwania wiszących przyimków: [tex-fixer](https://github.com/Alexander3/tex-fixer) (autor: Aleksander Kawala)
  * Uwagi dotyczące działania klasy _mtmdpl_ proszę przesyłać na adres e-mail: [piotr.kaczmarczyk@agh.edu.pl](mailto:piotr.kaczmarczyk@agh.edu.pl)


## Changelog ##

### v0.9.0-beta ###
  * zmiana formatowania strony tytułowej zgodnie z szablonem
  * zmiana nagłówka: strony parzyste - tytuł rozdziału, strony nieparzyste - tytuł sekcji
  * zmiana formatowania stopki - krótki tytuł pracy wyrównany do prawej
  * dostosowanie pakietu siunitx do języków pl i en
  * usunięcie wcięcia w pierwszym akapicie rozdziału/sekcji/podsekcji/...
  * usunięcie wcięć tytułów sekcji/podsekcji/...
  * zmiana numerowania wstępnej części pracy (tj. przed pierwszym rozdziałem) na rzymskie
  * dodatkowe przykład
