# Ściągawka z poleceń Git

## Spis komend

 **git clone**  
  Pobiera (klonuje) istniejące zdalne repozytorium na Twój lokalny komputer.  
  Przykład: `git clone https://github.com`

 **git status**  
  Wyświetla aktualny stan repozytorium (pokazuje zmodyfikowane pliki oraz pliki oczekujące na dodanie).  
  Przykład: `git status`

 **git add**  
  Dodaje zmiany w plikach do tzw. przechowalni (staging area), przygotowując je do zatwierdzenia.  
  Przykład: `git add docs/warp/git.md`

 **git commit**  
  Trwale zapisuje przygotowane zmiany w lokalnej historii repozytorium wraz z wiadomością opisującą zmiany.  
  Przykład: `git commit -m "docs: add Git cheatsheet"`

 **git push**  
  Wysyła Twoje lokalne zatwierdzenia (commity) do zdalnego repozytorium (np. na GitHub).  
  Przykład: `git push -u origin feature/git-cheatsheet`

 **git pull**  
  Pobiera i automatycznie scala zmiany ze zdalnego repozytorium do Twojej aktualnej gałęzi lokalnej.  
  Przykład: `git pull origin main`

 **git fetch**  
  Pobiera informacje o nowych zmianach ze zdalnego repozytorium, ale nie łączy ich automatycznie z Twoim kodem.  
  Przykład: `git fetch origin`

 **git branch**  
  Wyświetla listę wszystkich lokalnych gałęzi lub pozwala na utworzenie nowej.  
  Przykład: `git branch`

 **git switch**  
  Służy do przełączania się między gałęziami (użycie z flagą `-c` tworzy nową gałąź i od razu na nią przełącza).  
  Przykład: `git switch -c feature/git-cheatsheet`

 **git log**  
  Pokazuje historię wykonanych commitów w bieżącej gałęzi.  
  Przykład: `git log --oneline -3`