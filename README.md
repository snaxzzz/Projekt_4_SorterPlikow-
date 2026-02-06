# Projekt_4_SorterPlikow-
# 📂 Automatyczny sorter plików – Python
link do filmiku ktory pokazuje jak to dziala:
https://youtu.be/IKPSJH0dO0c
Program do automatycznego organizowania plików w folderze.

Skrypt skanuje wybrany katalog i przenosi pliki do odpowiednich folderów na podstawie ich rozszerzenia (np. zdjęcia, PDF, wideo, dokumenty).

Projekt pokazuje praktyczne wykorzystanie Pythona do automatyzacji codziennej pracy.

---

## Funkcje

- automatyczne wykrywanie plików w folderze
- tworzenie folderów kategorii (jeśli nie istnieją)
- przenoszenie plików do odpowiednich miejsc
- obsługa wielu typów plików:
  - zdjęcia (.jpg, .png)
  - pdf
  - programy (.exe)
  - tekst (.txt, .docx)
  - wideo (.mp4, .mkv)
- szybkie porządkowanie setek plików jednym kliknięciem

---

## Jak działa

Przed:
folder/
foto.jpg
dokument.pdf
film.mp4
notatka.txt

Po uruchomieniu:
folder/
Zdjecia/
PDF/
Wideo/
Tekst/

Pliki są automatycznie przenoszone do odpowiednich katalogów.

---

## Jak uruchomić

1. Zainstaluj Python 3.x
2. Umieść pliki w folderze testowym (np. `test_folder`)
3. Uruchom:

```bash
python sorter_plikow.py

