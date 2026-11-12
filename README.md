# Prologi — game audio portfolio

Одностраничник для GitHub Pages.

## Чего не хватает (положить в `src/`, потом прогнать `process.sh`)

```
./process.sh "src/Sailor's Home.mp3"    spilled-sailors-home.mp3
./process.sh "src/Water Bender.wav"     spilled-water-bender.mp3
./process.sh "src/Ice Caves.mp3"        spilled-ice-caves.mp3
./process.sh "src/Squirrel signs.wav"   spilled-squirrel-signs.mp3
./process.sh "src/Rocks Waltz.wav"      spilled-rocks-waltz.mp3
./process.sh "src/SFX reel.wav"         spilled-sfx-reel.mp3
```

`process.sh` обрезает тишину по краям, выравнивает громкость до −14 LUFS с потолком −1.5 dBTP и кодирует MP3 192 kbps.

Папку `src/` в репозиторий не добавлять — там исходники.

## Публикация

1. GitHub → New repository → имя `SergeiPolev.github.io` (Public).
2. Загрузить `index.html`, `audio/`, `README.md` (через GitHub Desktop или Add file → Upload files).
3. Settings → Pages → Source: Deploy from a branch → `main` / root.
4. Через 1–2 минуты сайт будет на https://sergeipolev.github.io
