# PJATK - Absolutorium
## Autor
Oliver Gocał
s22332
## Opis Projektu

PJATK - Absolutorium to gra przygodowa stworzona przy użyciu Pygame Zero. W grze wcielasz się w postać studenta, który musi przejść przez różne pomieszczenia, zaliczać ITNy , aby ukończyć studia i uzyskać dyplom.

## Funkcjonalności

### Podstawowe funkcje gry:
- **Ekran wprowadzający:** Zawiera historię gry oraz instrukcje dla gracza.
- **Ekran końcowy:** Wyświetla czas ukończenia gry oraz możliwość wyjścia z gry.
- **Ruch bohatera:** Możliwość poruszania się w lewo i prawo, a także wchodzenia przez drzwi.
- **Zbieranie kluczy:** Gracz musi znaleźć i zebrać wszystkie klucze, aby uzyskać dostęp do finałowego pomieszczenia.
- **Muzyka i efekty dźwiękowe:** Tło muzyczne oraz dźwięki towarzyszące różnym akcjom w grze.

### Klasy i ich funkcjonalności:
- **Game:** Zarządza stanem i logiką gry. Odpowiada za inicjalizację gry, rysowanie ekranu wprowadzającego i końcowego, ruch bohatera, zbieranie kluczy oraz aktualizację stanu gry.
- **Key:** Reprezentuje klucz, który gracz musi znaleźć. Każdy klucz ma swoje unikalne właściwości takie jak pozycja w pomieszczeniu oraz czy został już zebrany.
- **Door:** Reprezentuje drzwi, przez które bohater może przejść do innego pomieszczenia. Każde drzwi mają swoje właściwości, takie jak pozycja i stan otwarcia.
- **Room:** Reprezentuje pomieszczenie w grze. Każde pomieszczenie ma swoje unikalne właściwości, takie jak numer pokoju, nazwa, możliwość poruszania się w lewo/prawo oraz lista drzwi.

### Użyte technologie:
- **Pygame Zero:** Framework do tworzenia prostych gier 2D w Pythonie.
- **Python:** Język programowania użyty do stworzenia logiki gry.

## Instalacja i Uruchomienie

1. **Zainstaluj Pygame Zero:**
   ```bash
   pip install pgzero
   ```

2. **Uruchomienie gry:**
   - Zapisz kod gry do pliku `main.py`.
   - Uruchom grę za pomocą komendy:
     ```bash
     pgzrun main.py
     ```

## Sterowanie

- **Strzałka w lewo:** Ruch bohatera w lewo.
- **Strzałka w prawo:** Ruch bohatera w prawo.
- **Strzałka w górę:** Wejście przez drzwi.
- **Strzałka w dół:** Podniesienie ITNa.
- **Spacja:** Rozpoczęcie gry na ekranie wprowadzającym.
- **Q:** Wyjście z gry.

## Źródła i Inspiracje
Gra została stworzona z pomocą podręcznika "Koduj w Pythonie - Tworzymy grę przygodową". Dziękujemy za cenne wskazówki i inspiracje, które pomogły w realizacji tego projektu.

Gra została stworzona jako projekt edukacyjny na PJATK.
