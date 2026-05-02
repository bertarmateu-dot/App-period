# 🌸 El meu cicle

App de seguiment del cicle menstrual, hormones i estat d'ànim. Funciona com a PWA (Progressive Web App) — es pot afegir a la pantalla d'inici del mòbil com una app real, sense necessitat de l'App Store.

## Funcionalitats

- 📅 Calendari mensual amb fases del cicle
- 💗 Dies de fertilitat i finestra fèrtil
- 😊 Registre diari d'estat d'ànim i símptomes
- 📊 Historial de registres
- 🌙 Mode fosc automàtic
- 💾 Dades guardades al dispositiu (sense servidor)

## Com publicar-la (GitHub Pages)

1. Crea un repositori nou a [github.com](https://github.com) — anomena'l `cicle-app`
2. Puja tots els fitxers d'aquesta carpeta
3. Ves a **Settings → Pages**
4. A *Source* selecciona **main** i **/ (root)**
5. Guarda — en uns minuts tindràs la URL: `https://el-teu-usuari.github.io/cicle-app`

## Com afegir-la al mòbil (iPhone)

1. Obre la URL de GitHub Pages a **Safari**
2. Toca el botó de compartir (□↑)
3. Toca **"Afegir a la pantalla d'inici"**
4. Ja apareixerà com una app amb icona pròpia 🌸

## Fitxers

| Fitxer | Descripció |
|--------|------------|
| `index.html` | L'app completa |
| `manifest.json` | Configuració PWA (icona, nom, colors) |
| `sw.js` | Service worker (funciona sense internet) |
