# 🏋️ PTMS - Personal Trainer Management System

Witaj w wersji wdrożeniowej systemu PTMS! Ten zestaw plików pozwoli Ci uruchomić kompletną aplikację (Frontend + Backend + Baza Danych) na Twoim komputerze w kilka minut, używając technologii Docker.

## 📋 Wymagania
* Zainstalowany **Docker Desktop** (uruchomiony).

## 🚀 Instrukcja Uruchomienia (Step-by-Step)
### Krok 1: Pobierz pliki
Pobierz to repozytorium (jako ZIP lub przez `git clone`) i wejdź do folderu.

### Krok 2: Konfiguracja
W folderze znajdziesz plik `.env.example`. 
1. Skopiuj go i zmień nazwę kopii na `.env`.

### Krok 3: Uruchomienie
Otwórz terminal w tym folderze i wpisz dwie komendy:
=======
### 2. Konfiguracja
1. Skopiuj plik `.env.example` i zmień jego nazwę na `.env`.
2. Otwórz plik `.env` i upewnij się, że hasła są zgodne

```bash
# 1. Pobierz najnowsze wersje aplikacji z chmury
docker-compose pull

# 2. Uruchom system w tle
docker-compose up -d
