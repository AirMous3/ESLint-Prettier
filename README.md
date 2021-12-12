# ESLint-Prettier

##WebStorm
## В настройках в поисковой строке ввести eslint -> Keymap  fix es lint problems -> добавить хот кей 
## Так же в поисковой строке ввести eslint -> Languages & frameworks -> JavaScript -> Code Quality Tools -> EsLint -> включить Automatic ESLint configuration 

## Проинсталировать все пакеты 


yarn add -D eslint prettier
yarn add -D eslint-plugin-react => exclude writing anti-patterns
yarn add -D eslint-plugin-react-hooks => check valid hooks in react code
yarn add -D eslint-plugin-import => check all imports for correct work
yarn add -D eslint-plugin-prettier
yarn add -D eslint-plugin-jsx-a11y => check code, for people with disabilities
yarn add -D eslint-plugin-html

yarn add -D eslint-config-airbnb => airbnb config
yarn add -D eslint-config-prettier => prettier config, no conflict with airbnb
yarn add -D eslint-import-resolver-typescript => for correct work eslint-plugin-import package with typescript

yarn add -D @typescript-eslint/parser => eslint parser code for typescript
yarn add -D @typescript-eslint/eslint-plugin


## Создать файлы 
Создать файл .env и скопировать содержимое из файла .env этого проекта
Создать файл .prettierrc и скопировать содержимое из файла .prettierrc этого проекта
Создать файл .eslintrc.json и скопировать содержимое из файла .eslintrc.json этого проекта
Создать файл .eslintignore и скопировать содержимое из файла .eslintignore этого проекта
Добавить в гитигнор .env и .idea файлы


## Если ошибка -> "context.getPhysicalFilename is not a function", https://issueexplorer.com/issue/prettier/eslint-plugin-prettier/434 (yarn upgrade -R eslint)