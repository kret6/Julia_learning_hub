# 🎓 Julia's Learning Hub (Centrum Nauki)

![Status](https://img.shields.io/badge/Status-Active-success)
![Accessibility](https://img.shields.io/badge/Accessibility-High_Contrast-blue)
![Platform](https://img.shields.io/badge/Platform-Samsung_%7C_Android-orange)
![Technology](https://img.shields.io/badge/Tech-Pure_HTML_%2F_JS-yellow)

**Dedykowane, bezbarierowe środowisko edukacyjne zaprojektowane specjalnie dla Julii.**

Aplikacja zamienia standardowe, niedostępne materiały szkolne (skany, PDF) w interaktywne, audytywne i dotykowe lekcje cyfrowe (SPA).
https://kret6.github.io/Julia_learning_hub/
---

## 🎯 Misja i Cel

Tradycyjne metody sprawdzania wiedzy (tabele w Wordzie, mała czcionka, presja czasu) często sprawdzają bardziej sprawność obsługi formularza niż samą wiedzę. Ten system pozwala:
* ✅ **Uczyć się samodzielnie** w trybie audio (TTS - Text to Speech).
* ✅ **Sprawdzać wiedzę bez zbędnych barier** (duże przyciski, brak pisania, interfejs dotykowy).
* ✅ **Budować poczucie sprawstwa** i pewności siebie przed sprawdzianami w szkole.

---

## 🚀 Zastosowane Metodyki (Protokoły)

System opiera się na ściśle zdefiniowanych scenariuszach nauki, dostosowanych do przedmiotu i stopnia opanowania materiału.

### 🟢 Protokół 3.0 (Tryb Weryfikacji)
*Stosowany do przedmiotów humanistycznych i ścisłych (Historia, Chemia), gdzie materiał jest już częściowo znany.*
1.  **Wstęp Motywacyjny:** Głos wirtualnego asystenta ("Hania") wprowadza w temat.
2.  **Fiszki (Przypomnienie):** Szybka powtórka kluczowych pojęć (Awers/Rewers + Audio).
3.  **Pigułka Wiedzy:** Synteza materiału tuż przed testem.
4.  **Quiz Sprawdzający:** Pytania zamknięte oparte wyłącznie na dostarczonych materiałach.

### 🟠 Protokół 4.0 (Tryb "Full Immersion")
*Stosowany do języków obcych (Angielski, Hiszpański) i nowego materiału.*
1.  **Lekcje Audio:** Podział materiału na bloki tematyczne czytane przez lektora (Native Speaker).
2.  **Inteligentne Fiszki:** Nauka z wykorzystaniem `Emoji` i dwujęzycznego lektora (np. EN -> PL).
3.  **Quiz Totalny:** Weryfikacja 100% materiału (bez losowania). Każde pojęcie z lekcji musi zostać "odklikane".

---

## 📚 Dostępne Moduły

| Przedmiot | Temat | Protokół | Status |
| :--- | :--- | :---: | :---: |
| **Chemia** | Budowa Atomu, Izotopy | 3.0 | ✅ Gotowe |
| **Historia** | Ziemie Polskie po Powstaniu (Zabory) | 3.0 | ✅ Gotowe |
| **Hiszpański** | Wygląd i Charakter (*Ser/Tener*) | 4.0 | ✅ Gotowe |
| **Angielski** | Zakupy i Pieniądze (*Shopping*) | 4.0 | ✅ Gotowe |

---

## 🛠️ Stack Technologiczny

Projekt zbudowany w filozofii **"No-Build"** – ma być niezawodny, szybki i łatwy do edycji przez rodzica w notatniku.

* **HTML5 / CSS3:** Pełna responsywność, duże elementy dotykowe, wysoki kontrast, palety kolorów dopasowane do przedmiotu.
* **Vanilla JavaScript:** Brak frameworków. Czysta logika obsługi stanów.
* **Web Speech API:** Wykorzystanie natywnych syntezatorów mowy Androida (Google TTS) do generowania głosu nauczyciela w czasie rzeczywistym.
* **Emoji-First Design:** Zastąpienie ciężkich grafik systemem unicode dla szybkości ładowania.

---

## 📱 Instrukcja Obsługi (Dla Julii)

1.  Otwórz link do strony na telefonie Samsung.
2.  Upewnij się, że dźwięk jest włączony.
3.  Jeśli pojawi się przycisk **"Zmień Głos"**, klikaj go, aż usłyszysz wyraźny, polski głos (Google).
4.  W przypadku języków obcych (EN/ES), telefon automatycznie przełączy lektora.
5.  Postępuj zgodnie z instrukcjami na ekranie (Lekcja -> Fiszki -> Test).

---

## 👨‍💻 Instrukcja Aktualizacji (Dla Rodzica)

Aby wgrać nowy przedmiot:

1.  **Przygotuj wsad:** Zeskanuj podręcznik/zeszyt lub spisz słówka.
2.  **Otwórz plik** `index.html` w edytorze kodu.
3.  **Podmień sekcję danych:**
    * Zaktualizuj tablicę `const vocab = [...]` (dla języków) lub `const questions = [...]` (dla przedmiotów ogólnych).
4.  **Zaktualizuj teksty:** Zmień treści zmiennych `intro`, `summary`, `outro`.
5.  **Commit & Push:** Zapisz zmiany. GitHub Pages zaktualizuje się automatycznie.

---

## ⚖️ Prawa i Licencja

Projekt prywatny, stworzony na użytek własny w celach edukacyjnych.
Wszelkie prawa do treści merytorycznych (skany podręczników) należą do ich wydawców. Kod źródłowy służy jedynie jako narzędzie dostępności (Accessibility Tool).

---
*Created with ❤️ by Dad & AI Assistant.*
