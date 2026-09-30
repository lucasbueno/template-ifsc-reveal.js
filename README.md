# Template IFSC para Reveal.js

Este repositório contém um template de apresentação do Instituto Federal de Santa Catarina (IFSC) feito com [Reveal.js](https://revealjs.com/). O arquivo principal é `template-ifsc-revealjs.html` e reúne exemplos de slides, navegação, código, fórmulas matemáticas, fragmentos e layouts.

**Autor:** Prof. Lucas Bueno  
**Setor:** DAGCTC, Câmpus Florianópolis  
**Contato:** [lucas.bueno@ifsc.edu.br](mailto:lucas.bueno@ifsc.edu.br)

## Como usar

1. Baixe ou clone este repositório.
2. Abra `template-ifsc-revealjs.html` no navegador. É necessária conexão com a internet para carregar Reveal.js, Open Sans, MathJax e as imagens externas.
3. Edite o slide de capa: troque o título, a disciplina e os dados do professor.
4. Na `<div class="slides">`, cada `<section>` representa um slide. Altere os exemplos existentes ou duplique uma seção para criar novos slides.
5. Salve o arquivo e atualize a página no navegador para conferir a apresentação.

### Slides verticais

Para criar slides navegáveis na vertical, coloque seções dentro de outra seção:

```html
<section>
    <section>
        <h2>Tópico principal</h2>
    </section>
    <section>
        <h2>Detalhamento do tópico</h2>
    </section>
</section>
```

Use as setas para navegar horizontalmente e verticalmente. A tecla `Esc` abre a visão geral dos slides.

### Recursos do template

- Adicione `class="fragment"` a um elemento para revelá-lo gradualmente.
- Use `<pre><code class="python">...</code></pre>` para exibir código com realce de sintaxe. Troque `python` pela linguagem desejada.
- Escreva fórmulas em LaTeX entre `\(` e `\)` para fórmulas em linha, ou entre `\[` e `\]` para fórmulas em bloco.
- As seções demonstram também colunas com Flexbox e slides com cor de fundo personalizada.

Para conhecer mais opções, consulte a [documentação do Reveal.js](https://revealjs.com/).
