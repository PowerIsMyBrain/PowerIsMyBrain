# Alfabet Prepersów – Wersja Wstępna

## Mapa alfabetu prepersów

| Rozdział | Typ sygnału | Przykładowe znaki | Modyfikatory / warianty | Opis funkcji |
|----------|------------|-----------------|-------------------------|--------------|
| 1        | Gesty rąk | Otwarta dłoń, Pięść, Dwie dłonie razem, Palce w „V” | Kierunek, liczba powtórzeń, szybkość gestu | „Pomoc”, „Jedzenie”, „Przybywaj”, „Ostrożność” |
| 2        | Światło | Flara czerwona, flara zielona, latarka migająca | Częstotliwość migania, kąt rozproszenia | Alarm, lokalizacja, oznaczenie trasy |
| 3        | Dźwięk | Gwizd 1s, 2x klaśnięcia, bęben 3 uderzenia | Tempo, rytm, liczba powtórzeń | Sygnały kontaktowe, wezwanie pomocy, ostrzeżenie |
| 4        | Dym / ogień | Kolor dymu: biały, czerwony, zielony | Intensywność, czas emisji, kierunek | Alarm, zgromadzenie, oznaczenie obszaru |
| 5        | Znaki w terenie | Patyki ułożone w strzałkę, kamienie w linie, liście w kształt | Długość linii, kąt, powtarzalność | Wskazanie kierunku, obszar niebezpieczny, miejsce ukrycia |
| 6        | Graffiti / symbole | Znaki geometryczne, litery, skróty | Kolor, grubość, czas naniesienia | Komunikaty długoterminowe, ostrzeżenia, kodowane wiadomości |
| 7        | Kombinacje | Gest + Dym, Flara + Dźwięk | Dowolne połączenie rozdziałów | Tworzenie własnych szyfrów w razie potrzeby |

---

## Zasady rotacji i bezpieczeństwa

1. Każdy rozdział ma aktywne symbole + modyfikatory, które można szybko wymienić.  
2. W razie ujawnienia alfabetu, nowa wersja rozdziału jest rozsyłana offline przez drony w formie zaszyfrowanej księgi.  
3. Dwukierunkowa komunikacja: każdy sygnał ma podpis (sygnatura użytkownika), więc prepers i dron wiedzą, kto nadał komunikat.  
4. Autoryzacja alarmów dronów: tylko hierarchia wyższej rangi może uruchomić sygnały świetlne lub dźwiękowe publiczne.  
5. Indywidualność loginów: gest + hash urządzenia + cecha biologiczna (np. odcisk palca) → unikalny identyfikator offline.  
6. Szybkie modyfikacje: zmiana kombinatorów, kolorów, liczby powtórzeń → nowy szyfr w razie zdrady.  

---

## Przykładowy scenariusz użycia

1. Prepers wysyła sygnał „Pomoc” → gest otwartej dłoni + dwa klaśnięcia.  
2. Dron odbiera i zapisuje offline, dekoduje w aplikacji.  
3. Odbiorcy w pobliżu dostają wiadomość tekstową lub głosową.  
4. Prepers wyższej rangi autoryzuje publiczny sygnał alarmowy → dron wyświetla flary czerwone w formie ostrzeżenia.  

---

*Możliwość rozszerzenia*: dodanie dodatkowych rozdziałów, sygnałów, wariantów modyfikatorów i szybkiej aktualizacji alfabetu offline.
