---
title: Vim
author: Edwar Martinez Vale
---
|                         |
|-------------------------|
| ██╗░░░██╗██╗███╗░░░███╗ |
| ██║░░░██║██║████╗░████║ |
| ╚██╗░██╔╝██║██╔████╔██║ |
| ░╚████╔╝░██║██║╚██╔╝██║ |
| ░░╚██╔╝░░██║██║░╚═╝░██║ |
| ░░░╚═╝░░░╚═╝╚═╝░░░░░╚═╝ |


# Puntos a cubrir


1. ¿Qué es vim?
2. Vim y Neovim
3. ¿Porqué usar Neovim?
4. ¿Cómo Neovim puede incrementar tu productividad programando?
5. Neovim puede hacer todo lo que hace tu editor
6. ¿Cómo dar los primeros pasos en Neovim?


---
# ¿Qué es vim?


El acrónimo de Vim es Vi Improved. Escrito por Bram Moolenar, es un editor de texto gratuito y de codigo abierto que biene instalado por defecto en la mayoria de sistema UNIX. Fue lanzado por primera vez 1991, y su propósito principal fue desarrollar el editor Vi que fue lanzado en 1976


---
# Vim y Neovim


Neovim es un fork de Vim, el cual fue creado con el principal objetivo de que fuera un proyecto impulsado por la comunidad, ya que Vim es un proyecto mantenido casi enteramente por Bram Moolenar lo que conlleva a que Neovim implemente nuevas características mucho más antes que Vim.


---
|                                                     |
|-----------------------------------------------------|
| ███╗   ██╗███████╗ ██████╗ ██╗   ██╗██╗███╗   ███╗  |
| ████╗  ██║██╔════╝██╔═══██╗██║   ██║██║████╗ ████║  |
| ██╔██╗ ██║█████╗  ██║   ██║██║   ██║██║██╔████╔██║  |
| ██║╚██╗██║██╔══╝  ██║   ██║╚██╗ ██╔╝██║██║╚██╔╝██║  |
| ██║ ╚████║███████╗╚██████╔╝ ╚████╔╝ ██║██║ ╚═╝ ██║  |
| ╚═╝  ╚═══╝╚══════╝ ╚═════╝   ╚═══╝  ╚═╝╚═╝     ╚═╝  |


# ¿Porqué usar Neovim?


* Rendimiento
* Personalizable
* Syntax highlighting
* LSP
* Cross-platform
* Omnipresente


---
# ¿Cómo Neovim puede incrementar tu productividad programando?


Neovim es editor de texto que puede incrementar tu productividad cuando programas. La velocidad de tipeo hasta cierto nivel, mientras que la habilidad de navegar a través del código es mucho más importante. Aquí es donde Neovim, junto a sus combinaciones de teclas, diseño y configuración, puede ayudarnos a acelerar este proceso.


<!-- stop -->


## Vim Text Objects


Estructura:


```<number><command><text object or motion>```


Veamos unos ejemplos.


<!-- stop -->


## Tabs, Splits y Sessions


### Tabs y Splits


Los tabs y splits, nos da la habilidad de visualizar mantener nuestro código de una manera organizada y de agruparlos para poder movernos rapidamente entre ellos


### Sessions


Usualmente es molesto que cuando estamos trabajando en nuestro editor y lo cerramos, perdemos la forma en la que estabamos visualizando nuestro código. Aqui es donde las sesiones vienen en nuestra ayuda, estas crean un archivo en el que se guarda toda la informacion sobre la disposición de nuestros tabs y splits.


<!-- stop -->


## Plugins


Algunos plugins que pueden ayudarnos a movernos de una manera más eficiente


1. leap.nvim
2. fzf
3. nvim-surround

---
# Neovim puede hacer todo lo que hace tu editor


Gracias a la gran comunidad que hay detras de Neovim es que existen una gran cantidad de plugins que implementan las funciones que tienen los editores de texto modernos como Visual Studio Code

Un lugar donde puedes encontrar la mayoria de estos plugins es **Awesome Neovim**


---
# ¿Cómo dar los primeros pasos en Neovim?


* vimtutor
* https://vim-adventures.com/
* Extensión de Visual Studio Code - Vim


---
|                                                    |
|----------------------------------------------------|
| ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ |
| ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ |
| ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ |
| ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ |
| ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ |
| ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ |
| ░░░░░░░░░░░░░░░▒▓▓▒░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ |
| ░░░░░░░░░░░░░░░▒█▓▓▓▓▒░░░░░░░░░░░░░░░░░░▒▓██▒░░░░░ |
| ░░░░░░░░░░░░░░░░▒▓▓▓▓▓▓▒░░░░░░░░░░░░░░▓█▓▓▓█░░░░░░ |
| ░░░░░░░░░░░░░░░░░▓▓▒▓▓▓█▓▓████████▓▓▒▓▓▓▓▓▓▓░░░░░░ |
| ░░░░░░░░░░░░░░░░░▒▒▓▓▓▓▓███████████▓▓▓▓▒▒▒▓▒░░░░░░ |
| ░░░░░░░░░░░░░░░░░▒▓▓▓▓▓██▓▓▒▓▓███████▓▓▓▒▒▓░░░░░░░ |
| ░░░░░░░░░░░░░░░░░▒▓▓▓▓▓▒░░░░░▒▓▓▓▓█▓▓▓▓▓▓▓▓▒░░░░░░ |
| ░░░░░░░░░░░░░░░░▓▓▒▒▒▒▒░░░░░░░▒▒▓▓▓▓▓▓▓▓▓▓▓▓▒░░░░░ |
| ░░░░░░░░░░░░░░░▓█▓███▓▒▒░░░░░░░▒▓▓▓▓▓▓▓▓▓▓▓▓▓▒░░░░ |
| ░░░░░░░░░░░░░░░█▓▓▓███▓░░░░░░▒▓███████▓▓▓▓▓▓▓▓░░░░ |
| ░░░░░░░░░░░░░░▓▓▓▓░░▒▒▒░░░░░░▒▓▓▓▓▒▒▒▓▓▓▓▓▓▓▓▓▒░░░ |
| ░░░░░░░░░░░░░▒▓▒▒░░░░░░░░░░░░░░░░░░░░▒▒▒▒▓▓▓▓▒░░░░ |
| ░░░░░░▒▒▒░░░░░▓▒▒▒▒░░░░░░░░░░░░░░▒▒▒▒░░░░░░░░░░░░░ |
| ░░░▒▒▒▒▓▓▒░░░░░▒▒▒▒▒▒░▒▓▓▒░░░░░░▒▒▒▒▒▒░░░░▒▒░▒░░░░ |
| ░░▒▒▒▒▓▓▒▒░░░░░░▒▒▒▒▒▒▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒░░▒▒▒░░░░ |
| ░░▒▒▒▒▓▓▓▒▒▒░░░░░░▒▒▒▒▒▒▒▒▒▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒░░ |
| ░░░░▒▒▒▒▒▒▒▒▒▒░░░░░▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒ |
| ░░░░░░▒▒▒▒▒▒▒▒▒▒▒░▒▒▒▒▒▒▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▒▒▒▒▒▒ |
| ░░░░░░▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒ |


|                                                               |
|---------------------------------------------------------------|
|   #####   #####      ##      ####    ######     ##      ####  |
|  ##       ##  ##    ####    ##  ##     ##      ####    ##     |
|  ##       ##  ##   ##  ##   ##         ##     ##  ##    ####  |
|  ## ###   #####    ##  ##   ##         ##     ##  ##       ## |
|  ##  ##   ## ##    ######   ##  ##     ##     ######       ## |
|   #####   ##  ##   ##  ##    ####    ######   ##  ##    ####  |



---
