# PO Theme - Combio Theme

Tema padrão da Totvs para aplicações desenvolvidas com [PO UI](http://po-ui.io).

.
### Como usar o tema

O **PO UI** possui o seu próprio tema, mas disponibilizamos um tema com os padrões da TOTVS.

Para utilizá-lo, instale o pacote `@rafaelaraujo/combio-theme` conforme abaixo:

```
npm i @rafaelaraujo/combio-theme
```

Em seguida, atualize o arquivo `angular.json` para utilizar o tema.

```json
  "styles": [
              "node_modules/@rafaelaraujo/combio-theme/css/po-theme-custom-variables.min.css",
              "node_modules/@rafaelaraujo/combio-theme/css/po-theme-custom.min.css",
              "node_modules/@po-ui/style/css/po-theme-core.min.css",
              "src/styles.scss"
            ],
```

> Leia mais sobre [como criar seu próprio tema customizado do PO UI][create-theme-customization].

[create-theme-customization]: https://po-ui.io/guides/create-theme-customization
