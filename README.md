# 📌 Angular + Spring Boot – Kurs 🚀

Kompleksowa instrukcja instalacji i konfiguracji Angular oraz TypeScript.

---

## ⚙️ Instalacja i konfiguracja TypeScript  

🛠️ Inicjalizacja TypeScript i utworzenie pliku `tsconfig.json`:
```sh
tsc --init
```

⚡ Kompilacja pliku `.ts` do JavaScript (ES5), bez generowania pliku w przypadku błędów:
```sh
tsc --target ES5 --noEmitOnError plik.ts
```

🗑️ Czyszczenie builda (usuwanie wygenerowanych plików):
```sh
tsc --build --clean
```

🚀 Kompilacja i uruchomienie skryptu TypeScript w Node.js:
```sh
tsc plik.ts
node plik.js
```

---

## 🌍 Instalacja Angular CLI  

📦 Instalacja Angular CLI w określonej wersji (globalnie na komputerze):
```sh
npm install --location=global @angular/cli@19.2.1
```

📌 Sprawdzenie poprawnej instalacji Angular CLI:
```sh
ng version
```

---

## 🏗️ Tworzenie nowego projektu Angular  

📂 Tworzenie projektu Angular o nazwie `nazwa-projektu` (bez trybu standalone):
```sh
ng new --no-standalone nazwa-projektu
```

📂 Przejście do katalogu projektu:
```sh
cd nazwa-projektu
```

---

## 🌐 Uruchamianie serwera Angular  

🚀 Uruchomienie serwera deweloperskiego Angular i podgląd na `localhost:4200`:
```sh
ng serve
```

🌍 Uruchomienie Angular z automatycznym otwarciem przeglądarki:
```sh
ng serve --open
```

---

## 🛠️ Generowanie elementów w Angular  

📌 Generowanie nowego komponentu:
```sh
ng generate component nazwa-komponentu
```

📌 Generowanie nowej klasy w określonym katalogu:
```sh
ng generate class katalog/nazwa-klasy
```

---

💡 **Teraz Twój projekt Angular jest gotowy do działania!**  
🔗 Wejdź na `http://localhost:4200/` i zobacz aplikację w akcji. 🎉
