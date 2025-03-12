# Revisão HTML

### Introdução ao HTML:

- O HTML(Hypertext Markup Language) é basicamente uma linguagem de marcação projetada para definir e apresentar textos

- É um arquivo de texto, geralmente com a extensão .html

- Define a estrutura do conteúdo do site

- Estrutura Básica

### Tipos de páginas

- Página estática: é uma página que não se atualiza dinamicamente e permanece fixa, sem realizar requisições ao servidor após ser carregada. Geralmente, as páginas estáticas são usadas para exibir conteúdo que não muda com frequência, como informações descritivas sobre uma empresa, portfólios, blogs pessoais ou sites institucionais. Esse tipo de página é simples e não depende de interações complexas ou atualizações em tempo real.

- Página dinâmica: é uma página que se atualiza automaticamente e pode mudar seu conteúdo em tempo real, geralmente com base nas interações do usuário ou em dados do servidor. Elas podem exibir informações personalizadas, como feeds de redes sociais, resultados de pesquisa, ou conteúdo interativo, e são mais comuns em sites com funcionalidades avançadas, como e-commerce, redes sociais e etc...

### Curiosidade: Como lançar um site no ar

- Para colocar um site no ar é preciso de uma hospedagem(servidor/backend), um dominimo e o uso do dns para fazer o link dos dois

- DNS(Domain Name System) converte o endereço ip(ex:. 192.0.22.44) em um dominio com nome.

- Domínio é basicamente uma maneira mais simples de interagir com o usuário, pois substitui os endereços IP numéricos (que são difíceis de lembrar) por nomes mais amigáveis e fáceis de recordar.

### Estrutura básica do HTML

- O atalho ! seguido de Tab no Visual Studio Code (VS Code) ou em alguns editores de código, como o Sublime Text, Atom, ou Brackets, gera automaticamente a estrutura básica do HTML5. Esse é um recurso muito útil para desenvolvedores, pois evita a digitação repetitiva de tags e facilita a criação rápida de um esqueleto HTML.

```

## Esqueleto HTML

<!DOCTYPE html>  <!-- Declaração de tipo de documento, indicando HTML5 -->
<html lang="en"> <!-- Definindo que o idioma da página é inglês -->
<head> <!-- Cabeçalho da página, onde ficam os metadados e configurações -->
    <meta charset="UTF-8"> <!-- Especifica a codificação de caracteres, garantindo que caracteres especiais sejam exibidos corretamente -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Para tornar a página responsiva, ajustando o layout para diferentes dispositivos -->
    <title>Document</title> <!-- Título da página que aparece na aba do navegador -->
</head>
<body> <!-- Corpo da página, onde fica o conteúdo visível para o usuário -->
    <!-- O conteúdo da página vai aqui -->
</body>
</html>

```

### Tags no HTML:

- Tags são elementos HTML usados para estruturar e organizar o conteúdo de uma página web, informando ao navegador como ele deve exibir esse conteúdo. As tags podem definir títulos,parágrafos,listas, links, imagens, e muito mais. No HTML, temos dois tipos principais de tags: as tags de abertura e fechamento e as tags de autofechamento.

- Tags de abertura e fechamento:São aquelas que precisam de duas partes: uma para iniciar e outra para fechar. A primeira parte marca o começo de um conteúdo, e a segunda parte indica onde esse conteúdo termina.

```
<body>  - Indica onde inicia o conteudo web.
</body> - Indica onde termina o conteudo web.
```

- Tags de autofechamento: Essas tags não precisam de uma parte para fechar. Elas se fecham automaticamente quando são usadas. Normalmente, são usadas para elementos que não contêm conteúdo dentro delas, como uma imagem ou uma linha.

```
<meta charset="UTF-8"> - Esse é um exemplo de tag de autofechamento.
```

### Trabalhando com Texto
- No HTML, você pode estruturar o conteúdo textual utilizando diversas tags, como:

- Título: Para definir o título de uma página, usamos a tag <h1> até <h6>, onde <h1> é o título principal e <h6> é o título de menor importância.

```
<h1>Título Principal</h1>
<h2>Subtítulo</h2>

```
- Parágrafos: Para definir parágrafos de texto, utilizamos a tag <p>.

```
<p>Este é um parágrafo de texto.</p>
```
- Quebras de linha: Para inserir uma quebra de linha, usamos a tag <br>.

```
<p>Texto antes da quebra<br>Texto após a quebra de linha.</p>
```


### Lista e Links

### Imagens, Tabelas Formulários

### Estrutura Semântica

### HTML Avançado
