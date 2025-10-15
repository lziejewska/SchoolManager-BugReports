---
name: Błąd logowania - komunikat 'Invalid credentials' przy poprawnych danych
about: Użytkownik z rolą 'nauczyciel' nie może się zalogować do systemu pomimo wprowadzenia
  prawidłowego loginu i hasła. System wyświetla błąd 'Invalid credentials'.
title: ''
labels: bug, critical, login
assignees: ''

---

**Kroki do reprodukcji:**
1. Otwórz stronę logowania (https://app.schoolmanager.pl/login)
2. Wpisz login: jan.kowalski@szkola.pl
3. Wpisz hasło: Test123!
4. Kliknij przycisk "Zaloguj"

**Oczekiwany rezultat:**
Użytkownik zostaje zalogowany i przekierowany do panelu nauczyciela

**Rzeczywisty rezultat:**
Wyświetla się komunikat "Invalid credentials" i użytkownik pozostaje na stronie
logowania

**Środowisko:**
Windows 11, 
Chrome 120, 
Wersja aplikacji: 2.3.1

**Priorytet:**
[x] Krytyczny
[ ] Wysoki
[ ] Średni
[ ] Niski

**Update:** Problem występuje również w przeglądarce Safari.
Testowałem na macOS Sonoma.
