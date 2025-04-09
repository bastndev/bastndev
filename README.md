<!-- README para @bastndev (Full-width Edition) -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=250&section=header&text=bastndev%20Lab&fontSize=50&fontAlignY=40&desc=Experiments%20in%20code%20and%20design%20beyond%20the%20edge&descAlignY=60&descAlign=50" />
</p>

---

<h2 align="center">🧠 Welcome to my code garden</h2>

<p align="center">
  I’m <strong>bastndev</strong> — part developer, part designer, fully experimental.<br>
  My work revolves around building interfaces that feel like magic ✨.
</p>

---

<h3 align="center">🧪 Lab Notes (2025)</h3>

<div align="center">

```yaml
IDEAS:
  - AI-assisted dev UX
  - Interfaces that evolve with you
  - Systems that feel alive
  - ✨ Unreasonable levels of polish
```



<!-- TODO: Visit View -->
<p align="center" ><img width="18%" src="https://profile-counter.glitch.me/{bastndev}/count.svg"/></p>

<img src="https://readme-typing-svg.herokuapp.com/?lines=Hola+mundo!;Soy+bastndev;Creo+cosas+locas&center=true&color=0FFFB7&size=24">

<!-- 🧠 START PROJECTS -->
<details>
  <summary>🔍 Ver proyectos secretos</summary>

  - 👻 `ghost-theme`: Tema que se adapta a la hora del día
  - 🪐 `galactic`: UI kit interestelar

</details>
<!-- 🧠 END PROJECTS -->

<table>
  <tr>
    <td width="100%" align="center">
      <img src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" width="100px"><br/>
      <sub><b>Vibe Check</b></sub>
    </td>
  </tr>
</table>


<details>
  <summary>¿Qué estoy haciendo ahora?</summary>

  <details>
    <summary>🧪 Proyecto experimental</summary>
    Estoy explorando UIs que responden al ritmo de música 🎵.
  </details>

  <details>
    <summary>📚 Aprendiendo</summary>
    Rust + WebAssembly, baby!
  </details>
</details>


[![Spotify](https://spotify-github-profile.vercel.app/api/view?uid=31b1r5da4mncf0np1u4qgi6flr4u&cover_image=true&theme=novatorem&bar_color=53b14f&bar_color_cover=false)](https://open.spotify.com/user/bastndev)


[🔗 Jump into the unknown](https://example.com)


[![Button](https://img.shields.io/badge/-Click%20Me-black?style=for-the-badge)](https://bastndev.dev)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:212121,100:0F0F0F&height=100&section=footer&text=bastndev%20zone&fontColor=00FFAA" />

```ansi
[1;35m        ███████╗ █████╗ ███████╗████████╗███╗   ██╗██████╗ ███████╗██╗   ██╗
[1;35m        ██╔════╝██╔══██╗██╔════╝╚══██╔══╝████╗  ██║██╔══██╗██╔════╝╚██╗ ██╔╝
[1;35m        ███████╗███████║███████╗   ██║   ██╔██╗ ██║██║  ██║█████╗   ╚████╔╝ 
[1;35m        ╚════██║██╔══██║╚════██║   ██║   ██║╚██╗██║██║  ██║██╔══╝    ╚██╔╝  
[1;35m        ███████║██║  ██║███████║   ██║   ██║ ╚████║██████╔╝███████╗   ██║   
[0m



name: Dynamic README

on:
  schedule:
    - cron: "0 */6 * * *" # cada 6 horas
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Update README
        run: |
          echo "🌤️ Tiempo ahora en Lima: $(curl wttr.in/Lima?format=3)" > README.md
      - name: Commit changes
        run: |
          git config --global user.name 'GitHub Action'
          git config --global user.email 'action@github.com'
          git add .
          git commit -m "update: clima"
          git push
```

> ¿Qué tipo de desarrollador eres?

[🧙‍♂️ Mago del Backend](https://github.com/bastndev/bastndev/issues/new?title=soy-backend)
[🎨 Artista del Frontend](https://github.com/bastndev/bastndev/issues/new?title=soy-frontend)
[🧠 Hacker de IA](https://github.com/bastndev/bastndev/issues/new?title=soy-ia)


## 😂 Meme del día

<img src="https://raw.githubusercontent.com/bastndev/bastndev/main/memes/meme_04.jpg" width="500"/>


name: Actualizar meme
on:
  schedule:
    - cron: '0 */12 * * *' # cada 12 horas
  workflow_dispatch:
jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Escoger meme
        run: |
          MEME=$(ls memes | shuf -n 1)
          echo "![Meme del día](memes/$MEME)" > README.md
      - name: Commit
        run: |
          git config --global user.name 'meme-bot'
          git config --global user.email 'meme@bot.com'
          git commit -am "nuevo meme 😂"
          git push


HOUR=$(TZ=America/Lima date +"%H")
if (( HOUR < 12 )); then
  GREETING="🌅 Buenos días, bastndev está tomándose un café ☕"
elif (( HOUR < 19 )); then
  GREETING="🌞 Hora de codear fuerte. Let's go!"
else
  GREETING="🌙 Modo hacker activado. No hay sueño."
fi

echo "## $GREETING" > README.md
