# Oficjalna Strona RSS MFI UG 💻🎓

Repozytorium zawiera kod źródłowy wielozakładkowej strony internetowej **Rady Samorządu Studentów Wydziału Matematyki, Fizyki i Informatyki Uniwersytetu Gdańskiego**. 

Strona służy jako główne centrum informacyjne dla studentów wydziału. Została stworzona w czystym HTML i CSS, bez skomplikowanych systemów CMS, co pozwala na jej darmowe i bezawaryjne hostowanie na platformie GitHub Pages. Projekt w pełni opiera się na wytycznych Księgi Identyfikacji Wizualnej UG (oficjalny granat `#0041D2` oraz typografia `DM Sans`).

## 📁 Struktura Podstron (Zakładki)

Strona składa się z 5 głównych plików HTML:

1. `index.html` – **Strona Główna**: Wizytówka samorządu, najważniejsze odnośniki i powitanie.
2. `aktualnosci.html` – **Aktualności**: Tablica ogłoszeń w formie pionowych kart z plakatami wydarzeń (proporcje 1080x1440).
3. `poznaj-nas.html` – **Poznaj nas**: Skład Prezydium i członków RSS wraz ze zdjęciami i zakresem obowiązków.
4. `amfiteatr.html` – **aMFIteatr nauki**: Baza nadchodzących i minionych wykładów popularnonaukowych (np. dr Tomasz Miller, prof. Andrzej Dragan).
5. `mentoring.html` – **Mentoring**: Opis programu wsparcia przedsesyjnego oraz akcji "Nocna Nauka na MFI".

## 🖼️ Niezbędne pliki graficzne
Aby strona wyświetlała się poprawnie, w głównym folderze repozytorium muszą znajdować się następujące grafiki:
* **Logotypy (górny pasek):** `UG_logo_RGB_pionowy_negatyw_bialy_achromatyczny_PL.png`, `Logo MFI.png`, `logo-rss-biale.PNG`, `amfiteatr-logo-biale.png`
* **Ikony:** `instagram-logo.png`
* **Zdjęcia zarządu (do zakładki Poznaj nas):** `maja.jpg`, `martyna.jpg` (najlepiej portretowe/pionowe)
* **Plakaty wydarzeń:** Różne nazwy plików `.png` lub `.jpg`, najlepiej w proporcjach pionowych (1080x1440 px). Kod strony automatycznie je wykadruje.

## ⚙️ Instrukcja Obsługi i Aktualizacji

### Jak dodać nową aktualność?
1. Wgraj plakat promujący wydarzenie do repozytorium na GitHubie.
2. Otwórz plik `aktualnosci.html` i kliknij ikonę ołówka (Edytuj).
3. Znajdź komentarz ``.
4. Wklej poniżej gotowy blok kodu karty (Skopiuj go z poprzedniego ogłoszenia).
5. Zmień datę, treść oraz nazwę pliku z plakatem w znaczniku `<img src="...">`.
6. Kliknij zielony przycisk **Commit changes**.

### Jak dodać nową zakładkę do menu?
Ponieważ strona jest zbudowana z czystych plików HTML, pamiętaj o jednej złotej zasadzie: **Górne menu (`<nav>`) znajduje się w każdym pliku osobno**.
Jeśli stworzysz nowy plik (np. `kola-naukowe.html`), musisz skopiować do niego cały kod paska nawigacyjnego, a następnie w plikach `index.html`, `aktualnosci.html` itd. dopisać nowy link, aby z każdej strony dało się wejść w nową zakładkę.

## 🚀 Hosting (GitHub Pages)
Strona jest wdrożona na darmowym serwerze GitHub Pages. 
* Aktualizacje na stronie (po kliknięciu *Commit changes*) pojawiają się zazwyczaj w ciągu 1-2 minut.
* Konfiguracja hostingu znajduje się w zakładce **Settings > Pages** (źródło: gałąź `main`).

---
**Kontakt z Samorządem:**
✉️ E-mail: samorzad.mfi@studms.ug.edu.pl
📸 Instagram: [@mfiugsamorzad](https://instagram.com/mfiugsamorzad)
