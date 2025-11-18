# That Open Engine

Aplikacja do wizualizacji modeli BIM 3D z systemem uwierzytelniania użytkowników.

## 🚀 Funkcje

- 🔐 **Uwierzytelnianie** - System logowania i rejestracji
- 📐 **Przeglądarka projektu** - Interaktywna wizualizacja modeli 3D
- 📄 **Odczyt plików IFC** - Wsparcie dla formatów BIM
- 💰 **Kalkulator kosztów** - Planowane
- ✅ **Weryfikacja konstrukcji** - Planowane

## 🛠️ Technologie

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS
- **Routing**: React Router v6
- **3D Viewer**: Three.js, OpenBIM Components
- **Testing**: Vitest, React Testing Library
- **UI Components**: Radix UI, shadcn/ui

## 📦 Instalacja

```bash
# Klonuj repozytorium
git clone https://github.com/Agataodsprojekt/frontend_beginning_18_11.git

# Przejdź do folderu projektu
cd frontend_beginning_18_11

# Zainstaluj zależności
npm install

# Uruchom serwer deweloperski
npm run dev
```

## 🧪 Testowanie

```bash
# Uruchom wszystkie testy
npm test

# Uruchom testy z UI
npm run test:ui

# Sprawdź coverage
npm run test:coverage
```

### Test Coverage

Aplikacja posiada 52 testy jednostkowe obejmujące:
- ✅ Komponenty UI (Button, Input)
- ✅ Strony (SignIn, SignUp)
- ✅ Routing aplikacji
- ✅ Funkcje pomocnicze (utils)

## 📂 Struktura projektu

```
src/
├── components/
│   └── ui/              # Komponenty UI (Button, Input, etc.)
├── lib/
│   └── utils.ts         # Funkcje pomocnicze
├── pages/
│   ├── SignIn.tsx       # Strona logowania
│   ├── SignUp.tsx       # Strona rejestracji
│   └── Viewer.tsx       # Przeglądarka 3D
├── test/
│   └── setup.ts         # Konfiguracja testów
├── App.tsx              # Główny komponent z routingiem
└── main.tsx             # Entry point aplikacji
```

## 🔧 Dostępne skrypty

```bash
npm run dev      # Uruchom serwer deweloperski
npm run build    # Zbuduj wersję produkcyjną
npm run preview  # Podgląd wersji produkcyjnej
npm test         # Uruchom testy
npm run test:ui  # Uruchom testy z interfejsem UI
```

## 🎯 Roadmap

- [x] System uwierzytelniania
- [x] Przeglądarka 3D BIM
- [x] Testy jednostkowe
- [ ] Backend API
- [ ] Zarządzanie projektami
- [ ] Kalkulator kosztów
- [ ] Weryfikacja konstrukcji

## 👥 Autor

Agata Paszek - [ODS Projekt](https://www.ods-projekt.pl/)

## 📄 Licencja

Private - © 2025 ODS Projekt

