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

```
<!DOCTYPE html>  - Declarando ao meu navegador, a versão do HTML
<html lang="en"> - Atributo usado para definir o idioma da página.
<head> - Head("cabeça") da página(é nela que vamos fazer a configuração da página)
    <meta charset="UTF-8"> - Usamos para declarar o uso de caracteres especiais
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title> - Titulo da página
</head>
<body> - Body(corpo) da página(é nela que vai conter o conteudo da página web)

</body>
</html>
```

- Trabalhando com Texto

- Lista e Links

- Imagens, Tabelas Formulários

- Estrutura Semântica

- HTML Avançado
