# 🥤 Refri Showcase

Uma interface web interativa e visual desenvolvida para apresentar diferentes sabores de refrigerantes por meio de um carrossel com animações, transições e navegação entre os produtos.

◉ **[Acessar projeto online](https://refri-showcase-carrossel-interativo.vercel.app/)**

## Sobre o projeto

O **Refri Showcase** é um projeto front-end desenvolvido para praticar a construção de interfaces modernas utilizando **HTML, CSS e JavaScript**.

A aplicação apresenta diferentes sabores de refrigerante em uma experiência visual baseada em slides. O usuário pode navegar entre os sabores utilizando os botões de **anterior** e **próximo**, enquanto os elementos da interface recebem animações durante a transição.

O projeto também explora o uso de imagens em camadas, posicionamento de elementos e variáveis CSS para criar diferentes identidades visuais para cada sabor.

##  Funcionalidades

*  Exibição de diferentes sabores de refrigerante
*  Navegação para o slide anterior
*  Navegação para o próximo slide
*  Navegação circular entre os slides
*  Animações durante a troca dos slides
*  Alteração dinâmica da cor de fundo de acordo com o sabor
*  Utilização de imagens em diferentes camadas
*  Estrutura preparada para diferentes tamanhos de tela


##  Tecnologias utilizadas

* **HTML5** — estrutura da página
* **CSS3** — estilização, posicionamento e animações
* **JavaScript** — lógica de navegação e controle do carrossel


##  Conceitos praticados

Durante o desenvolvimento foram trabalhados conceitos importantes de desenvolvimento front-end, como:

* Estrutura semântica com HTML5
* Seletores e propriedades CSS
* Posicionamento absoluto de elementos
* Variáveis CSS
* `@keyframes` e animações
* Manipulação do DOM
* Eventos de clique com JavaScript
* Manipulação de classes com `classList`
* Estruturas condicionais
* Controle de índices em listas
* Organização de arquivos e recursos do projeto

##  Lógica do carrossel

A navegação é controlada pelo JavaScript.

O projeto identifica todos os elementos `.item` e mantém uma variável responsável pelo slide atualmente ativo.

Ao clicar em **próximo**, o slide atual é removido e o próximo elemento recebe a classe `active`.

Ao chegar ao último slide, a navegação retorna automaticamente para o primeiro.

O mesmo conceito é utilizado no botão **anterior**, permitindo uma navegação circular entre os sabores.

##  Interface

Cada sabor possui uma identidade visual própria, definida através da variável CSS:



Dessa forma, o mesmo componente pode receber diferentes cores de fundo sem a necessidade de criar várias classes CSS.



Este projeto faz parte da minha prática de desenvolvimento **Front-end**, com foco no aprendizado de **HTML, CSS e JavaScript**, especialmente na criação de interfaces interativas, animações e manipulação do DOM.

---

**Desenvolvido por Sarah Oliveira Ferreira**
