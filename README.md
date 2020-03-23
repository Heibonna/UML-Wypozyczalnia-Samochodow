# UML - Wypozyczalnia Samochodow
Projekt zrealizowany w ramach zajęć z Inżynierii Oprogramowania.

## Opis projektu:
Projekt przedstawia system wypożyczalni samochodów. Umożliwia przeglądanie samochodów, składanie, edytowanie i realizowanie zamówień, a także rejestrację i modyfikację danych konta. Ponadto opisuję budowę systemu i przebieg procesu składania zamówienia

#### Diagram klas
  Klasy Klient i Admin dziedziczą z klasy Uzytkownik. Wypozyczony samochód jest aktualizowany w bazie poprzez obiekt klasy Zamowienie, które tworzone jest przez Admina na zlecenie Klienta.
#### Diagram obiektów
  Przedstawia przykładowe obiekty stworzone przez klasy z diagramu klas.
#### Diagram przypadków użycia
  Aktorem jest Klient, który może się zarejestrować, aktualizować dane, przeglądać samochody oraz składać, anulować i modyfikować zamówienie.
#### Diagram przebiegu i kooperacji
  Przedstawia przebieg komunikatów pomiędzy obiektami Klienta, Admina, Bazy_samochodów i Zamówienia podczas składania zamówienia.
#### Diagram stanu
  Przedstawia stany zamówienia: złożone, nieopłacone, anulowane, opłacone, w trakcie, ukończone.
#### Diagram czynności
  Przedstawia pełen proces wypożyczenia samochodu przez klienta. Zaczynając od złożenia zamówienia przez klienta po jego zwrot.
#### Diagram komponentów
  Przedstawia komponenty bazy danych: GUI- Program zarządzający transakcjami; baza.dll - sterownik bazy danych; platnosci.dll - plik, który pozwala zarządzać płatnościami; Klient_account - plik który pozwala na poprawne wyświetlenie informacji o członkach; Admin_account - plik który pozwala na poprawne wyświetlanie informacji o administratorach.
#### Diagram wdrożenia
  Przedstawia powiązania pomiędzy bazą danych, serwerem www koniecznym do realizacji płatności, sprzętem i osobami fizycznymi (Admin i Klient)
