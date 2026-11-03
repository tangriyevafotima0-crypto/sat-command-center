# SAT Command Center (30 Math & 30 Desmos Darslari)

Ushbu loyiha Zafarbekning 2026-yil 3–15-noyabr kunlari uchun to'liq 30 ta SAT Math mavzu darslari va 30 ta Desmos video kursini yagona, minimalist AMOLED interfeysda birlashtirgan boshqaruv paneli.

## Tarkibi
- `sat_command_center.html`: Barcha 30 ta Math va 30 ta Desmos darslarining to'g'ridan-to'g'ri Drive havolalari, formulalar cheatsheeti, Pomodoro taymer va 50 misollik Ingestion progress hisoblagichi.
- `curriculum_30_lessons.json`: 13 kunga to'liq kalibrlangan taqvim va metadata.
- `launch.sh`: macOS da panelni bir zumda brauzerda ochish skripti.

## Tezkor Ishga Tushirish
Mac terminalida:
```bash
open sat_command_center.html
```

## GitHub ga Yuklash (1-Click Push)
Ushbu papkani yangi GitHub repozitoriyingizga joylash uchun Mac terminalida:
```bash
git init
git add .
git commit -m "feat: complete SAT Command Center with 30 Math and 30 Desmos lessons"
git branch -M main
git remote add origin https://github.com/<your-username>/sat-command-center.git
git push -u origin main
```
