> [!WARNING]
> Baza danych została stworzona za pomocą programu Microsoft Access w wersji 365 i nie była testowana na innych wersjach pakietu Office.


# Wymagania z moodle

Zmodyfikuj bazę danych z I sem:

- [x] Znormalizuj bazę tzn. doprowadź przynajmniej do trzeciej postaci normalnej.
- [ ] Obsługa bazy danych powinna się odbywać na odpowiednich formularzach (wprowadzanie danych, edycja, usuwanie). Możliwość dodawania, usuwania produktów z bazy przy pomocy odpowiedniej kwerendy/makra/kodu VBA - dla użytkownika jest to formularz z przyciskiem a do przycisku przypisane jest odpowiednie zdarzenie.
Jeżeli w bazie nie było np. tabel klienci i sprzedaz albo wypozyczenia to należy takie tabele utworzyć i odpowiednio powiązać z produktami.
- [ ] Dodaj zdjęcia do bazy - np. obiekt OLE albo załącznik  w tabeli - (np. zdjęcie produktu). Zdjęcia powinny być widoczne w formularzu.
- [ ] Dodaj możliwość wyszukiwania danych np. wg nazwy, kodu itp. Użytkownik widzi okienko dialogowe/formularz z polami tekstowymi, w które wpisuje kryteria. Wyniki mogą być wyświetlane jako lista albo inny formularz (wtedy ten należy automatycznie zamknąć). Powinna być możliwość wybrania produktu i przejścia do formularza umożliwiającego edycję produktu.
- [ ] Utwórz formularz do przeglądania zamówień z listami/polami kombi (np. wybierasz klienta z listy albo pola kombi, obok jest lista w której wyświetlają się np. zamówienia albo nr faktury albo daty zakupów klienta, klikając na konkretny numer widzisz szczegóły zakupów/zamówienia mogą być wyświetlane w liście albo podformularzu).
- [ ] Utwórz formularz typu faktura, w którym odpowiednie pola są np. sumowane, może być naliczony rabat, kwota do zapłaty, podatek. Napisz stosowne funkcje przynajmniej 1.
- [ ] Utwórz raport faktury z własnym firmowym nagłówkiem np. nazwa, logo firmy, data (to będzie twoja wersja drukowanej faktury).
- [ ] Możliwość wystawienia faktury dla danego klienta. Np. wybieram Klienta, któremu chcę wystawić fakturę, po zatwierdzeniu automatycznie ładuje się formularz faktura, na którym pojawiają się dane wybranego klienta. Teraz podajemy kod albo wybieramy z listy produkt i on "wskakuje" na fakturę (odpowiednie dane produktu: nazwa, cena, liczony jest podatek). Można dodać kilka produktów do jednej faktury.
- [ ] Jeżeli nie uzupełnimy jakiegoś pola to pokazuje się odpowiedni komunikat aby je uzupełnić. Np. nie powinno pozwolić wystawić faktury, do której nie dodano żadnego produktu tzw. pustej faktury.
- [ ] Możliwość drukowania faktury tzn. wyświetlania podglądu wydruku raportu faktury z logo i nagłówkami.
- [ ] Baza powinna być w pełni funkcjonalna.
- [ ] Zabezpiecz całą bazę danych hasłem oraz dodatkowo formularz z danymi klienta zabezpiecz hasłem.
- [ ] Obsługa błędów w formularzach.

# Podziękowania

Podziękowania dla [Mord0reK](https://github.com/Mord0reK) za przetestowanie bazy danych i wskazanie błędów.

# Wykonali
- [JanDziaslo](https://github.com/JanDziaslo) (Bartosz N.)
- [Szopen2137](https://github.com/Szopen2137) (Szymon T.)
