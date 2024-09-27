# QuizApp

QuizApp to aplikacja służąca do wykonywania quizów zadanych przez inną osobę.

**APLIKACJA NIE WSPIERA URZĄDZEŃ Z SYSTEMEM iOS! Jest to związane z wysokimi kosztami uzyskania certyfikatu potrzebnego do wydania aplikacji na systemy iOS (ok. 400zł rocznie)**

### Instalacja aplikacji na urządzenia z systemem Android (>7):
1. Wybierz najnowszą wersję aplikacji z dopiskiem **-ANDROID** (przykład: **1.0.0-ANDROID**)
2. Zainstaluj plik **.apk** oraz uruchom go na swoim urządzeniu. Gdy plik zostanie pobrany, otwórz go za pomocą "Instalator pakietu"
3. Potwierdź instalację aplikacji.
4. Poczekaj na zainstalowanie aplikacji.
5. Uruchom aplikację i postępuj według instrukcji pojawiających się w aplikacji.

### Informacja dotycząca wersji aplikacji:
W przypadku wydania aktualizacji interfejsu API aplikacji (jest on wspólny dla obu wersji aplikacji - ucznia i nauczyciela), aktualizowane są obie aplikacje (ucznia i nauczyciela).
Wersje obu aplikacji są numerowane identycznie, z różnicą w określeniu systemu operacyjnego urządzenia w przypadku aplikacji dla ucznia. Przykład kompatybilnych wersji aplikacji:

> 1.1.0 - Aplikacja dla nauczyciela.
> 
> 1.1.0-ANDROID - Aplikacja dla ucznia na systemy Android.
>
> 1.1.5-ANDROID - Aplikacja dla ucznia na systemy Android.

Patch aplikacji nie wpływa na rozumienie zakodowanych informacji o zestawie pytań, więc podczas sprawdzania kompatybilności jest pomijany (*patch to trzecia liczba od lewej w zapisie wersji*).

W przypadku tworzenia zestawu pytań przez nauczyciela, należy upewnić się, czy uczniowie posiadają odpowiednią wersję aplikacji. **Po wydaniu nowej wersji nie ma obowiązku wykonywania aktualizacji!**

W wydaniu aplikacji może znaleźć się informacja o kompatybilności wstecznej. Oznacza to, że starsza wersja aplikacji dla nauczyciela jest kompatybilna z nowszą wersją aplikacji dla ucznia.
Jeżeli taka informacja się nie znajdzie, oznacza to że nie występuje kompatybilność wsteczna.

Wersje aplikacji mające tą samą liczbę major (*np. 1.1.0, 1.4.3, 1.8.0, 1.37.15*) posiadają kompatybilny system zapisu danych zestawu pytań do pliku (**dotyczy tylko aplikacji w wersji dla nauczyciela**).
