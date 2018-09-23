# Project Title
>  SASS within the TUC pattern

* responsive sass build that supports custom grid settings
* lite weight sass based grid with variables, mixes, and some standard container definitions

## Getting Started
- REQUIRE node ^8.9.4 
- git clone https://github.com/JackBeNimbleBeQuick/responsiveSASS.git
- cd src
- npm install -g node-sass
- npm install

### Command lines are fun within responsiveSASS/src 
- npm run css

### Goals
To provide the basics for:
- sass
  - sass provides a basic grid, variables, and mix-ins

### Sass Files
- _main.scss:_ 
  - gathers the files used in compiling and provides the basic grid setup
- _partials/\_grid:_ 
  - is just that
- _partials/\_main:_ 
  - is start of project / name-spaced styles for your project
    * edit to meet your needs
- _vars/\_var:\_ 
  - hold the grid setup, you may want to clean this to support your color theming scheme
    * edit to meet your needs
- _vars/\_mixes:\_ 
  - some sample mix-ins are provided
    * edit to meet your needs
