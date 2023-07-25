<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=7CFC00&height=120&section=header"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=8B008B&size=35&center=true&vCenter=true&width=1000&lines=Opa,+Meu+Nome+é+Vitor+Dias;Eu+Tenho+21+Anos+;Sou+de+Jaguaruna,+SC;Um+Dia+Eu+Vou+Ser+Um+Exelente+Programador!!+:%29)](https://git.io/typing-svg)

# Nome da Actions:  
name: Snake Game

# Controlador do tempo que sera feito a atualização dos arquivos.
on:
  schedule:
      # Será atualizado a cada 5 horas.
    - cron: "0 */5 * * *"

# Permite executar na na lista de Actions (utilizado para testes de build).
  workflow_dispatch:

# Regras
jobs:
  build:
    runs-on: ubuntu-latest
    steps:

    # Checks repo under $GITHUB_WORKSHOP, so your job can access it
      - uses: actions/checkout@v2

    # Repositorio que será utilizado para gerar os arquivos.
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: VitorSam0w0 #Seu usuario
          gif_out_path: dist/github-contribution-grid-snake.gif
          svg_out_path: dist/github-contribution-grid-snake.svg

      - run: git status

      # Para as atualizações.
      - name: Push changes
        uses: ad-m/github-push-action@master
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          branch: master
          force: true

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          # the output branch we mentioned above
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  
  ##
  
  <div align="center">
  
  <div>
            <a href="https://steamcommunity.com/profiles/76561198438412285"><img src="https://cdn-icons-png.flaticon.com/128/3670/3670382.png" class"media-object
  <img align="center" alt="Rafa-Ts" height="55" width="55" src="https://cdn-icons-png.flaticon.com/128/3670/3670382.png">
        <a href="https://discord.gg/bFUYdPDhaN"><img src="https://img.icons8.com/bubbles/70/discord-logo.png" class"media-object
  <img align="center" alt="Rafa-Ts" height="70" width="70" src="https://img.icons8.com/bubbles/70/discord-logo.png"> 
          </div>

  ##
  

  
  <div>

<div align="center">  
  <img width="49%" height="195px" src="https://github-readme-stats.vercel.app/api?username=VitorSam0w0&show_icons=true&count_private=true&hide_border=true&title_color=7CFC00&icon_color=8B008B&text_color=00FFFF&bg_color=0d1117" alt="Vitor Dias github stats" /> 
  <img width="41%" height="195px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VitorSam0w0&layout=compact&hide_border=true&title_color=7CFC00&text_color=00FFFF&bg_color=0d1117" />
</div>
  
    
<div style="display: inline_block"><br>
    <a href="https://github.com/VitorSam0w0"><img src="https://img.icons8.com/bubbles/70/pixel-cat.png" class"media-object
  <img align="center" alt="Rafa-Ts" height="70" width="70" src="https://img.icons8.com/bubbles/70/pixel-cat.png">
    <a href="https://github.com/VitorSam0w0"><img src="https://img.icons8.com/bubbles/70/bright-moon.png" class"media-object
  <img align="center" alt="Rafa-React" height="70" width="70" src="https://img.icons8.com/bubbles/70/bright-moon.png">
      <a href="https://github.com/VitorSam0w0"><img src="https://img.icons8.com/bubbles/70/kawaii-pizza.png" class"media-object
  <img align="center" alt="Rafa-HTML" height="70" width="70" src="https://img.icons8.com/bubbles/70/kawaii-pizza.png">
      <a href="https://github.com/VitorSam0w0"><img src="https://img.icons8.com/bubbles/70/pokemon.png" class"media-object
  <img align="center" alt="Rafa-CSS" height="70" width="70" src="https://img.icons8.com/bubbles/70/pokemon.png">
        <a href="https://github.com/VitorSam0w0"><img src="https://img.icons8.com/bubbles/70/mana.png" class"media-object
  <img align="center" alt="Rafa-Python" height="70" width="70" src="https://img.icons8.com/bubbles/70/mana.png">

  
  
</div>


##

<a href="https://www.webcontadores.com" title="contador para blog"><img src="https://counter9.stat.ovh/private/webcontadores.php?c=lxt7ml67nch3xe4lfxzkzstjszk2hur2" border="0" title="contador para blog" alt="contador para blog"></a>

##

</div>

https://user-images.githubusercontent.com/111717270/193470913-c6f4639b-9941-4d1f-a460-fdedf726b36e.mp4


<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=7CFC00&height=120&section=footer"/>

