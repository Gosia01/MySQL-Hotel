# MySQL-Hotel
Baza danych Hotelu, skrypt+diagram

Opis projektu Baza Danych Hotelu MySQL


Projekt zawiera bazę niewielkiego hotelu. Może być ona obsługiwana z dwóch poziomów – gościa (który domyślnie będzie miał ograniczony dostęp do informacji) i personelu hotelu. Na ich podstawie można znaleźć informacje na temat rezerwacji poszczególnych gości, zsumować koszty pobytu i sprawdzić dostępność pokoju w danym terminie. 
System zawiera 17 tabel – 10 głównych i 7 relacyjnych.
- tabela goscie – przechowuje informacje na temat osób aktualnie mieszkających w hotelu (imię, nazwisko, numer dowodu osobistego)
- rodzaj_pokoju - określa standard i cenę pokoju oraz ilość osób mogących w nim zamieszkać
- tabele dotyczące usług dodatkowych (sniadania, obiadokolacje, parking, pakiet_SPA) – określają usługi, które goście mogą wykupić, ich cenę i wykupioną przez gościa ilość
- rodzaj_platnosci – zawiera informacje na temat sposobu uiszczenia opłat w hotelu: kartą lub gotówką
- rezerwacje – przechowuje informacje na temat okresu pobytu gości
- tabele logowanie_goscia i logowanie_admin – przechowują informacje dotyczące loginów i haseł gości i pracowników hotelu
