# common commands

## adiciona dependências de desenvolvimento

yarn add -D

## adiciona eslint e prettier

yarn add -D eslint prettier eslint-config-prettier eslint-plugin-prettier

## instala eslint

yarn eslint --init

√ How would you like to use ESLint? · force style
√ What type of modules does your project use? · javascript
√ Which framework does your project use? · none
√ Does your project use TypeScript? · No
√ Where does your code run? · browser
√ How would you like to define a style for your project? · guide
√ Which style guide do you want to follow? · airbnb
√ What format do you want your config file to be in? · JSON
√ Would you like to install them now? · Yes
√ Which package manager do you want to use? · yarn

## adiciona sass

yarn add -D sass

## sass architecture

sass/
|
|– abstracts/
| |– \_variables.scss # Sass Variables
| |– \_mixins.scss # Sass Mixins
|
|– vendors/
| |– \_bootstrap.scss # Bootstrap
|
|– base/
| |– \_reset.scss # Reset/normalize
| |– \_typography.scss # Typography rules
|
|– layout/
| |– \_navigation.scss # Navigation
| |– \_grid.scss # Grid system
| |– \_header.scss # Header
| |– \_footer.scss # Footer
| |– \_sidebar.scss # Sidebar
| |– \_forms.scss # Forms
|
|– components/
| |– \_buttons.scss # Buttons
| |– \_carousel.scss # Carousel
| |– \_cover.scss # Cover
| |– \_dropdown.scss # Dropdown
|
|– pages/
| |– \_home.scss # Home specific styles
| |– \_contact.scss # Contact specific styles
|
|– themes/
| |– \_theme.scss # Default theme
| |– \_admin.scss # Admin theme
|
– main.scss # Main Sass input file

## script sass

sass <input.scss> [output.css]

## execultar script scss

yarn build:scss
