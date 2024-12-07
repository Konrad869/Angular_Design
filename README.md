The Angular_Design application is an Angular application that adds users to the database. The application is unfinished but I am working on completing it. The application is built using mainly Angular v16, Typescript, Rxjs, SPA, Angular material technologies. To run it, download the ZIP files and open them in the IDE in the src directory. you need to install ng_modules using npm install and then issue the command ng s -o or npm start or ng serve  to run it.then you need to copy the https/4200 address to the web browser to see the applications.



Tech


Angular_Design is developed using following technologies:



![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)   ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white) ![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![RxJS](https://img.shields.io/badge/rxjs-%23B7178C.svg?style=for-the-badge&logo=reactivex&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)




# Article HTML Converter

## Wymagania systemowe
- Node.js (wersja 16+ recommended)
- npm (Node Package Manager)

## Instalacja zależności
```bash
# Klonowanie repozytorium
git clone [adres-repozytorium]
cd article-html-converter

# Instalacja zależności
npm install dotenv openai readline
```

## Konfiguracja API
1. Utwórz plik `.env` w głównym katalogu projektu
2. Dodaj klucz API OpenAI:
```
OPENAI_API_KEY=twój_klucz_api_z_openai
```

## Jak uzyskać klucz API
1. Zarejestruj się na stronie [platform.openai.com](https://platform.openai.com/)
2. Przejdź do sekcji API Keys
3. Wygeneruj nowy klucz
4. Skopiuj klucz do pliku `.env`

## Uruchomienie aplikacji
```bash
# Uruchomienie skryptu
node index.js

# Lub z npx
npx article-converter
```

## Przykładowe użycie
```bash
# Po uruchomieniu, podaj ścieżkę do pliku tekstowego
Podaj ścieżkę do artykułu: /sciezka/do/twojego/artykulu.txt
```

## Rozwiązywanie problemów
- Upewnij się, że masz zainstalowany Node.js
- Sprawdź poprawność klucza API
- Potwierdź, że plik `.env` istnieje

## Uwagi bezpieczeństwa
- Nie udostępniaj publicznie klucza API
- Dodaj `.env` do `.gitignore`
