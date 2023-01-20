# HTML

## Descrição

Uma componente que permite que possamos adicionar tags html direto do JSON. Para podermos estar estruturando o projeto de nossa maneira.
Basicamente esse componente 


## Característica

- ✔ Compatível com CSS Handles
- ✔ Menos linha de código renderizada no HTML em comparado ao Flex.layout
- ✔ Tag HTML dinâmica para cada caso. Podendo adicionar semântica
- ✔ Possibilidade adicionar Textos 


## Estrutura
```html
    <{qualquerTagHtml} class="{acountName}-{appName}-1-x-html {acountName}-{appName}-new-theme-1-x-html--{suaBlockClass} {qualquer classe extra }">
    {children}
    </{qualquerTagHtml}>
```


## HTML vs FLEX.LAYOUT

### html
```html
    <div class="ckm3sintese-ckm3sintese-new-theme-1-x-html">
        {children}
    <div>
```

### flex
```html
    <div class="vtex-flex-layout-0-x-flexRow">
        <section class="vtex-store-components ph3 ph5-m ph2-xl mw9 center">
            <div class="vtex-flex-layout-0-x-flexRowContent pr7">
                <div class="stretchChildrenWidth flex pr7 items-stretch" style="width: 50%;">
                    {children}
                </div>
            </div>
        </section>
    </div>
```
