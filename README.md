[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=40&pause=1000&color=780F97&random=false&width=900&height=60&lines=Hei+sann!;Mitt+navn+er+Kolbj%C3%B8rn+B%C3%B8lgen.;Velkommen+til+Github-profile+min!)]() 

## Elsyser / Student
### Elektronisk Systemdesign og Innovasjon, ved Institutt for Elektroniske Systemer, Norges teknisk-naturvitenskapelige universitet (MTELSYS, IES, NTNU).

#### August 2021 - Juni 2026


# Teknisk Verktøykasse

<img src=https://github.com/SkaugJr/SkaugJr/blob/main/Bilder/Matlab_Logo.png height=60 /> <img src=https://github.com/SkaugJr/SkaugJr/blob/main/Bilder/Python_logo.png height=60 /> <img src=https://github.com/SkaugJr/SkaugJr/blob/main/Bilder/linux_logo.png height=60 /> <img src=https://github.com/SkaugJr/SkaugJr/blob/main/Bilder/C%2B%2B_logo.png height=60 /> <img src=https://github.com/SkaugJr/SkaugJr/blob/main/Bilder/Overleaf_logo.png height=60 />  <img src=https://github.com/SkaugJr/SkaugJr/blob/main/Bilder/Github_logo2.png height=60 /> <img src=https://github.com/SkaugJr/SkaugJr/blob/main/Bilder/vscode_logo.png height=60 />


# Ta kontakt!
[<img src='https://github.com/SkaugJr/SkaugJr/blob/main/Bilder/linkedin_logo2.png' alt='linkedin' height='100'>](https://www.linkedin.com/in/kolbjørn-bølgen-572b942b5//) [<img src='https://github.com/SkaugJr/SkaugJr/blob/main/Bilder/gmail_logo.png' alt='gmail' height='100'>](mailto:skaugjr@gmail.com) [<img src='https://github.com/SkaugJr/SkaugJr/blob/main/Bilder/outlook_logo.png' alt='microsoftoutlook' height='100'>](mailto:kolbjosk@stud.ntnu.no)


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

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
