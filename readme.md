# Дипломная работа.  
## Ссылка на деплой [здесь](https://abramsea.github.io/polk/)

---

Приветствую! в данном репозитории находится небольшой сайт-каталог.


_version 1.0.0_

---

### Клонирование


    git clone https://github.com/abramsea/polk.git

### Зависимости

    "devDependencies": {
        "@babel/cli": "^7.10.4",
        "@babel/core": "^7.10.4",
        "@babel/plugin-proposal-class-properties": "^7.10.4",
        "@babel/preset-env": "^7.10.4",
        "autoprefixer": "^9.8.5",
        "babel-loader": "^8.1.0",
        "cross-env": "^7.0.2",
        "css-loader": "^3.6.0",
        "cssnano": "^4.1.10",
        "file-loader": "^6.0.0",
        "gh-pages": "^2.2.0",
        "html-webpack-plugin": "^4.3.0",
        "image-webpack-loader": "^6.0.0",
        "mini-css-extract-plugin": "^0.9.0",
        "optimize-css-assets-webpack-plugin": "^5.0.3",
        "postcss-loader": "^3.0.0",
        "style-loader": "^1.2.1",
        "webpack": "^4.43.0",
        "webpack-cli": "^3.3.12",
        "webpack-dev-server": "^3.11.0",
        "webpack-md5-hash": "0.0.6"
    },
    "dependencies": {
        "babel-polyfill": "^6.26.0",
        "core-js": "^3.4.1"

### Сборка

&bull; для запуска production сборки:

    npm run build 

&bull; для запуска development сборки:

    npm run dev 
    


&bull; для размещения проекта на github-pages:

    npm run deploy 