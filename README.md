### Oii!! Eu sou a Anelize 👋

- 🌱 I’m currently learning python

![Anelize GitHub stats](https://github-readme-stats.vercel.app/api?username=anelizemeneses&show_icons=true&theme=radical)

![Snake animation](https://github.com/anelizemeneses)
nome : Gerar dados

em :
  cronograma : # executar a cada 12 horas
    - cron : " * * / 12 * * * "
  workflow_dispatch :

empregos :
  construir :
    nome : Trabalhos para atualizar dados
    roda em : ubuntu-mais recente
    passos :
      # Animação de cobra
      - usa : Platane / snk @ master
        id : snake-gif
        com :
          github_user_name : rafaballerini
          svg_out_path : dist / github-Contribution-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : output
          build_dir : dist
        env :
          GITHUB_TOKEN : $ {{secrets.GITHUB_TOKEN}}
