# Resume in LATEX Format [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fgithub.com%2Fdharm18%2Fresume&via=vdharm&text=Get%20your%20own%20beautiful%20and%20stunning%20look%20resume%20in%20Latex%20Format.%20&hashtags=latex-resume-template%2C%20resume-template%2C%20resume%2Ccv)
## About
This is my experimentation in making resume in Latex format. It gives a beautiful and stunning resume.

## Getting Started

These instructions will get you a copy of my resume up and running on your local/online for further development and testing purposes.

## How To Use Template

There are mainly two approach in which you can get started.

### Installation
1. **Online** - Create [Overleaf project](https://www.overleaf.com/project) online and edit [.tex](dharmendra_vishwakarma_resume.tex) file with your details.
2. **Offline** - You can use Desktop application to edit offline document such as [TexStudio](https://www.texstudio.org/).
    - You need to set up TexStudio and Latex Offline before start editing [.tex](dharmendra_vishwakarma_resume.tex) document.

### Editing Examples

1. **Modifying Header**
    Make changes in author sectio to display your name
    ```
    \author{Your Name}
    ```
    Make changes in maketitle section. Here, href section follows URL and content which you want to display. 
    ```
    \renewcommand{\maketitle}{
    \begin{center}
    {\LARGE\bfseries
    \theauthor}

    \vspace{0.25em}
    \href{mailto:vxxxxxx@gmail.com}{vxxxxxxx@gmail.com} --- \href{http://vdharam.com}{http://vdharam.com}
    \end{center}	
    }

    ```
## Built With

* [LaTeX](https://www.latex-project.org/) - LaTex Distribution for local setup
* [TexStudio](https://www.texstudio.org) - LaTeX editor

## License
This work is distributed under the [MIT license](https://opensource.org/licenses/MIT) see the [LICENSE](LICENSE) file for details.