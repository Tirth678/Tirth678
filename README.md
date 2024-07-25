

Readme
<h1 align="center">Hi 👋, I'm Tirth S Pandya</h1>
<h3 align="center">A passionate developer from India</h3>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,apple,cpp,c,css,html,github,js,mysql,notion,selenium,vscode" />
  </a>
</p>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=tirth678&label=Profile%20views&color=0e75b6&style=flat" alt="tirth678" /> </p>

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=tirth678&show_icons=true&locale=en&layout=compact" alt="tirth678" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=tirth678&" alt="tirth678" /></p>

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
