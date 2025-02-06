---
title: Przewodnik
draft: false
tags:
---
## Wskaźniki
### Kluczowe wskaźniki wyboru lokalizacji (KPI) 
Głównym elementem pulpitu jest koralowe koło położone w lewym górnym rogu ekranu. Zawiera ono dwie kluczowe informacje
- współrzędne wybranego punktu (rozważanej lokalizacji inwestycyjnej)
- Wartość mieszczącą się w zakresie 0 - 100, przy czym z założenia - należy dążyć do maksymalizacji tej wartości. Za pomocą strzałek pojawiających się po prawej i lewej stronie, można przewijać tę wartość, szukając optymalnego kryterium. Opis techniczny wskaźników znajduje się w sekcji [[5.2 Metody wyboru wariantu optymalnego (KPI)]].
![[Pasted image 20250206041713.png]]

### Wskaźniki oraz miary oceny poszczególnych aspektów
Poniższe miary składają się na poprzedni element pulpitu. 
- Po lewej stronie tabeli zostały umieszczone cztery wskaźniki, wszystkie mieszczące się w zakresie 0 - 100 (dla czynników pozytywnych) lub -100 - 0 (dla czynników negatywnych). W obu przypadkach należy dążyć do maksymalizacji wartości, odpowiednio 100 i 0 dla poszczególnych wskaźników. 
	- **Poziom konkurencyjności**  
	    Określa intensywność konkurencji w danym obszarze. Pokazuje, jak duża jest obecność innych firm, co wpływa na trudność wejścia na rynek i presję rynkową.
	- **Atrakcyjność okolicy**  
	    Ocenia potencjał turystyczny i komercyjny obszaru, uwzględniając popularność lokalnych atrakcji oraz ich ocenę przez użytkowników.
	- **Utracona wartość turystyczna**  
	    Wskazuje, jak wiele obszar traci na atrakcyjności w wyniku oddalenia od kluczowych miejsc turystycznych.
	- **Dostępność komunikacyjna**  
	    Mierzy łatwość dostępu do infrastruktury drogowej, co wpływa na wygodę transportu, logistykę i dostępność lokalizacji.
- Po prawej stronie znajdują się cztery najważniejsze statystyki opisujące bliską konkurencję w danej okolicy (o definicji bliskiej konkurencji dalej).
	- Średnia ocena hoteli w okolicy wg Google Places z uwzględnieniem liczby ocen
	- Liczba hoteli w okolicy
	- Średnia wielkość hoteli w okolicy, mierzona maksymalną potencjalną liczbą gości
	- Maksymalna liczba miejsc w hotelach w okolicy w ogóle
![[Pasted image 20250206042521.png]]
### Grafiki pomocnicze panelu bocznego
W razie zainteresowania daną miarą, możliwe jest pozyskanie dodatkowych informacji na temat jej składowych poprzez kliknięcie danego przycisku. O takiej możliwości interakcji świadczy koralowa kreska pojawiająca się po lewej stronie wartości wskaźnika.  
![[Pasted image 20250206044112.png]]

W celu ukrycia panelu bocznego należy wybrać przycisk z ikoną 'cofnij' w jego górnej lewej części.
![[Pasted image 20250206044518.png]]

Inną funkcjonalnością wspierającą bardziej szczegółowe przeglądanie danych, jest opcja wyświetlenia dodatkowych informacji (nazwa hotelu, wielkość, ulica, komentarze) po najechaniu na punkt na mapie lub użyciu mechanizmu `drillthrough`:
![[Pasted image 20250206095546.png]]
### Wybór lokalizacji
Podstawową funkcjonalnością pulpitu jest możliwość definiowania lokalizacji, dla której przeliczane są wszystkie wskaźniki oraz promienia bliskiej konkurencji. Jako bliską konkurencję określa się wszystkie hotele, które znajdują się w analizowanym promieniu - są one odznaczone koralowym kolorem, natomiast inwestycja wyświetlana jest jako biały domek na zielonym tle z ikoną dolara. Promień bliskiej konkurencji można zdefiniować w prawym dolnym rogu ekranu, w okienku `analizowany promień`. Dopuszczalne wartości są w zakresie 500m-5km. Z kolei pionowy suwak po prawej stronie oraz poziomy suwak w górnej części ekranu, pozwalają na dynamiczny wybór lokalizacji inwestycji (koordynatów). Po zmianie któregokolwiek  z omówionych parametrów, wszystkie wskaźniki zostaną na nowo przeliczone.
![[Pasted image 20250206045015.png]]

### Filtry oraz pogląd
W lewym górnym rogu ekranu znajdują się dwa przyciski, filtrów oraz odsyłacz do tego przewodnika. Ten pierwszy posiada dodatkowy wskaźnik, który informuje o stanie filtrów - w razie filtrowania wartości, jego kolor zamienia się na czerwony, a wartość wskazuje na liczbę aktywnych filtrów.
![[Pasted image 20250206045240.png]]

 Po najechaniu na ten wskaźnik aktywowany jest podgląd stanu wskaźników. Z kolei wybranie przycisku filtrów (ikona zakładki), wyświetli się okno wyboru filtrów, którym można zawężać wartości wskaźników (KPI) o konkretne pola filtrujące. 
![[Pasted image 20250206045220.png]]