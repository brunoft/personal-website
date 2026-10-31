# Bruno Fortunato — site pessoal

Código do meu site pessoal, publicado em [brunofortunato.dev](https://brunofortunato.dev).

É uma página única com minha apresentação, trajetória, tecnologias que uso e formas de contato.

## Recursos

- Conteúdo em português, inglês e espanhol, com o idioma escolhido salvo no navegador
- Tema escuro (padrão) e tema claro
- Layout responsivo, do celular ao desktop
- Navegação por teclado, link para pular ao conteúdo e rótulos para leitores de tela
- Tags Open Graph para prévias de link em redes sociais

## Tecnologias

HTML, CSS e JavaScript puro. Sem framework, sem etapa de build e sem dependências.

## Estrutura

```
index.html   Marcação, textos nos três idiomas e scripts da página
index.css    Estilos, incluindo os dois temas
image/       Foto, favicon e ícones SVG
CNAME        Domínio personalizado do GitHub Pages
```

## Rodando localmente

Abra o `index.html` no navegador ou sirva a pasta com qualquer servidor estático:

```bash
npx serve .
```

## Editando os textos

Os textos ficam no objeto `translations`, dentro do `<script>` no fim do `index.html`, com uma chave para cada idioma (`pt`, `en` e `es`). O HTML usa o atributo `data-i18n` para indicar qual chave cada elemento exibe. Ao alterar um texto em português, atualize também o texto fixo no HTML, que aparece antes de o script rodar.

## Publicação

O site é publicado pelo GitHub Pages a partir da branch `master`, no domínio definido em `CNAME`.

## Contato

- E-mail: [bruno.gcft@gmail.com](mailto:bruno.gcft@gmail.com)
- LinkedIn: [linkedin.com/in/bruno-ft](https://www.linkedin.com/in/bruno-ft/)
- GitHub: [github.com/brunoft](https://github.com/brunoft)
