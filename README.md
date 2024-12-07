The Angular_Design application is an Angular application that adds users to the database. The application is unfinished but I am working on completing it. The application is built using mainly Angular v16, Typescript, Rxjs, SPA, Angular material technologies. To run it, download the ZIP files and open them in the IDE in the src directory. you need to install ng_modules using npm install and then issue the command ng s -o or npm start or ng serve  to run it.then you need to copy the https/4200 address to the web browser to see the applications.



Tech


Angular_Design is developed using following technologies:



![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)   ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white) ![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![RxJS](https://img.shields.io/badge/rxjs-%23B7178C.svg?style=for-the-badge&logo=reactivex&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)



# Article HTML Converter 🚀

## 📋 Spis Treści
- [Opis Projektu](#-opis-projektu)
- [Instalacja](#-instalacja)
- [Konfiguracja](#-konfiguracja)
- [Użycie](#-użycie)
- [Funkcjonalności](#-funkcjonalności)
- [Wymagania](#-wymagania)
- [Rozwiązywanie Problemów](#-rozwiązywanie-problemów)

## 🔍 Opis Projektu

Narzędzie **Article HTML Converter** automatyzuje konwersję dokumentów tekstowych do semantycznego, dostępnego formatu HTML5 z wykorzystaniem zaawansowanych modeli AI.

## 💻 Instalacja

### Wymagania wstępne
- Node.js (v16+)
- npm

### Kroki instalacji
```bash
# Klonowanie repozytorium
git clone https://github.com/twoj-uzytkownik/article-converter.git

# Przejście do katalogu projektu
cd article-converter

# Instalacja zależności
npm install
```

## 🛠 Konfiguracja

### Zmienne środowiskowe
Utwórz plik `.env` w katalogu głównym:

```
OPENAI_API_KEY=twoj_klucz_api
```

### Parametry konfiguracyjne
```javascript
const CONFIG = {
  MAX_FILE_SIZE: 50 * 1024,     // Maks. rozmiar pliku
  MODEL: 'gpt-4-turbo-preview', // Model AI
  MAX_TOKENS: 1500,             // Limit tokenów
}
```

## 🚀 Użycie

### Podstawowe uruchomienie
```bash
node converter.js /sciezka/do/pliku.txt
```

### Przykładowe scenariusze
- Konwersja artykułów
- Przetwarzanie dokumentów akademickich
- Automatyzacja publikacji treści

## ✨ Funkcjonalności
- Generowanie semantycznego HTML5
- Automatyczna strukturyzacja dokumentu
- Hierarchizacja nagłówków
- Wielojęzyczne przetwarzanie tekstu

## ⚠️ Wymagania
- Klucz API OpenAI
- Plik tekstowy do konwersji
- Stabilne połączenie internetowe

## 🐞 Rozwiązywanie Problemów

### Najczęstsze problemy
1. **Brak klucza API**
   - Sprawdź konfigurację `.env`
   - Wygeneruj nowy klucz w OpenAI

2. **Błędy konwersji**
   - Upewnij się, że plik jest czytelny
   - Sprawdź limity rozmiaru pliku

## 📄 Licencja
MIT License

## 🤝 Kontakt
[Twój email lub link do repozytorium]

