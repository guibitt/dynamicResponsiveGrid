# Grid Flexivel e Sugestão de estrutura de pastas

Segue abaixo como usar o grid e a estrutura da pasta usada.

## Estrutura das pastas

```
.root or theme project
├── gulp/
|   ├── node_modules/
|   ├── tasks/
|   |   ├── clone-file.js
|   |   ├── concat-min-js.js
|   |   ├── sass.js 'converte o sass para css e minifica'
|   |   └── watch.js
|   |
|   ├── Gulpfile.js
|   └── package.json
|
├── src/
|   ├── css/
|   ├── fonts/  'esta pasta será clonada com o gulp'
|   ├── js/
|   └── sass/
|       ├── base/
|       |   ├── fonts/
|       |   |   └── nome_da_fonte/	'Para ficar organizado colocar a fonte dentro de pastas com seu respectivo nome'
|       |   |
|       |   ├── _fonts.scss
|       |   └── _reset.scss
|       |
|       ├── helpers/
|       |   ├── mixins/
|       |   |   ├── _grid.scss
|       |   |   └── _micro-mixins.scss
|       |   |
|       |   ├── _mixins.scss
|       |   └── _variables.scss
|       |
|       ├── layout/
|       |   ├── _grid.scss
|       |   └── _main.scss
|       |
|       ├── libs/
|       └── all.scss
|
├── static/
|   ├── css/    'receberá o arquivo minificado'
|   ├── fonts/  'esta pasta foi clonada da pasta src com o gulp'
|   ├── js/     'receberá o arquivo minificado'
|   └── images/
|									
├── .gitignore	
└── README.md
```