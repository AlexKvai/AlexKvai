### Hi there 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Computer+science+student)](https://git.io/typing-svg)

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=AlexKvai)](https://github.com/AlexKvai/github-readme-stats)

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=AlexKvai)](https://git.io/streak-stats)

<img align="left" alt="codeSTACKr's GitHub Stats" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlexKvai&langs_count=8&layout=compact" />
    <br />
<img align="left" alt="codeSTACKr's GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=AlexKvai&show_icons=true" />

- uses: AlexKvai/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.AlexKvai }}

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
