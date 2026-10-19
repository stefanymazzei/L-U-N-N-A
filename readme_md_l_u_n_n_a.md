<div align="center">

# L U N N A | Alta Joalheria & Design Digital

<p align="center">
  <i>Uma experiência imersiva de e-commerce conceitual desenvolvida para unir a estética do luxo atemporal à precisão do desenvolvimento Front-End moderno.</i>
</p>

<!-- CAPA CLICÁVEL: Clique na imagem para abrir o site publicado no GitHub Pages -->
<a href="https://stefanymazzei.github.io/L-U-N-N-A/" target="_blank" title="Clique para explorar o site da L U N N A ao vivo">
  <img src="./docs/capas/Capa_LUNNA.jpeg" alt="Capa do Projeto L U N N A" width="100%" style="border-radius: 12px; box-shadow: 0 8px 24px rgba(0,0,0,0.5);" />
</a>

<p align="center">
  <br />
  <a href="https://stefanymazzei.github.io/L-U-N-N-A/" target="_blank">
    <b>🌐 Clique aqui ou na imagem para vivenciar a aplicação ao vivo</b>
  </a>
</p>

---

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)

</div>

---

### 1. A História e o Propósito do Projeto

Como estudante apaixonada pela interseção entre **Front-End**, **UI/UX Design** e **arquitetura de interfaces**, sempre percebi que os e-commerces tradicionais costumam tratar joias de alto padrão como itens de catálogo comum: vitrines cheias de poluição visual, banners promocionais agressivos e dezenas de informações disputando a atenção do cliente ao mesmo tempo. 

O projeto **L U N N A** nasceu exatamente do desejo de quebrar essa lógica. Meu principal objetivo ao idealizar e programar este projeto foi entender como o design digital pode evocar sentimentos de raridade, exclusividade e contemplação. Uma joia de alta costura não é comprada por impulso; ela é escolhida com carinho, carrega memórias afetivas e celebra momentos marcantes da vida. Por isso, a interface digital precisa agir como a vitrine de uma joalheria física na Place Vendôme em Paris ou na 5ª Avenida em Nova York: iluminada com sutileza, silenciosa, elegante e com um ritmo de navegação calmo e envolvente.

Durante o desenvolvimento, dediquei horas analisando grandes marcas globais como Cartier, Tiffany & Co. e Bulgari, buscando extrair os princípios de **Clean Luxury** e transportá-los para linhas de código limpas, organizadas e de alto desempenho, tudo feito do absoluto zero sem recorrer a frameworks pesados prontos, com o intuito de consolidar minha base pura de HTML, CSS e JavaScript.

---

### 2. Ideação Visual, Paleta de Cores e Experiência do Usuário (UI/UX)

Criar uma atmosfera premium exigiu um estudo cuidadoso de psicologia das cores, espaçamento e proporções visuais. A identidade visual da L U N N A foi pensada para transmitir sofisticação sem parecer inacessível ou fria.

### A Construção da Paleta de Cores

A paleta foi inspirada no contraste elegante entre as noites estreladas e o brilho discreto dos metais polidos:

| Nome do Tom | Hexadecimal | Conceito e Aplicação Prática |
| :--- | :---: | :--- |
| **Noir Velvet** | `#0D0D0E` | O fundo principal quase negro. Ele foi escolhido porque elimina qualquer distração ao redor das peças e cria uma sensação de profundidade infinita, fazendo com que as joias pareçam flutuar na tela. |
| **Muted Charcoal** | `#1A1B1E` | Superfície secundária usada em cartões de produtos, barras de navegação e cabeçalhos. Evita o contraste agressivo do preto absoluto e confere textura suave. |
| **Gold Leaf** | `#D4AF37` | O toque de ouro clássico. Aplicado com moderação em microinterações, estados de *hover*, ícones seletos e destaques pontuais para manter o requinte. |
| **Champagne Silk**| `#A39274` | Um dourado acetinado e desbotado, ideal para linhas divisórias, subtítulos e tags de categoria, trazendo requinte sem cansar a visão do usuário. |
| **Pure Platinum** | `#F8F9FA` | Textos principais, títulos e botões de chamada primária (*Call to Action*). Proporciona contraste ideal e conforto de leitura de acordo com as diretrizes de acessibilidade WCAG. |

### Escolha Tipográfica e Hierarquia Visual

A tipografia desempenha um papel emocional indispensável no design de luxo:

1. **Títulos e Logotipo (Serifados Clássicos):** Utilizei fontes com serifas bem esculpidas e proporções refinadas, resgatando a herança editorial das revistas clássicas de moda e o desenho das joias esculpidas à mão.
2. **Textos Corridos e Componentes de Interface (Sans-Serif Modernas):** Para descrições técnicas, preços, botões de ação e menus de navegação, selecionei uma família tipográfica sem serifa geométrica, limpa e com *letter-spacing* levemente expandido, assegurando legibilidade impecável mesmo em telas compactas de smartphones.

### Filosofia do *Whitespace* (Respiro Visual)

Um dos maiores desafios que me impus durante a fase de prototipagem foi **não ter medo do espaço vazio**. No mercado de luxo, o espaço em branco (*whitespace*) não é ausência de conteúdo: é elegância, foco e respeito ao produto. O grid foi calculado com base em múltiplos de `8px`, garantindo proporções simétricas entre cartões, títulos e seções inteiras.

---

### 3. Bastidores do Código e Decisões Técnicas

Construir a L U N N A sem bibliotecas visuais prontas (como Bootstrap ou Tailwind) foi uma escolha consciente para colocar à prova meu domínio de **código nativo**. Eu queria ter o controle total de cada pixel, de cada transição e de cada milissegundo de carregamento da página.

### Tabela de Tecnologias Utilizadas

| Tecnologia | Como e Onde Foi Aplicada |
| :--- | :--- |
| **HTML5 Semântico** | Todo o código foi escrito priorizando tags semânticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<footer>`), permitindo melhor indexação de mecanismos de busca (SEO) e compatibilidade com leitores de tela para pessoas com deficiência. |
| **CSS3 Avançado** | Utilização sistemática de **CSS Custom Properties (Variáveis de CSS)** para facilitar temas e manutenções; layouts criados com **Flexbox** para componentes unidimensionais e **CSS Grid** para a vitrine bidimensional de produtos; transições de aceleração cúbica (*cubic-bezier*) para movimentos naturais de cursor e modais. |
| **JavaScript (ES6+)** | Lógica pura (Vanilla JS) responsável pelo controle do carrinho de compras interativo, cálculo de totais, filtros de categoria em tempo real, controle do menu hambúrguer responsivo e abertura assíncrona de detalhes de cada peça. |
| **GitHub Pages** | Configuração de esteira para hospedagem estática direta do repositório, garantindo entrega rápida e certificação SSL automática. |

### Estrutura e Organização de Arquivos

Para manter o projeto profissional e escalável, organizei os arquivos em uma arquitetura modular clara:

```
L-U-N-N-A/
│
├── index.html                 # Ponto de entrada com marcação estruturada e semântica
│
├── css/
│   ├── style.css              # Reset geral, variáveis de cor, tipografia e estilos globais
│   ├── components.css         # Estilização de botões, cartões de produto, modais e carrinho
│   └── responsive.css         # Breakpoints e regras específicas para tablets e smartphones
│
├── js/
│   ├── main.js                # Lógica de interface, scroll suave, menu móvel e filtros
│   └── cart.js                # Manipulação dos dados do carrinho, cálculo e local storage
│
├── assets/
│   ├── img/                   # Catálogo de fotografias de alta resolução com compressão web
│   └── icons/                 # Vetores em SVG otimizados para ícones e ações de navegação
│
└── README.md                  # Documentação completa e memorial descritivo do projeto
```

---

### 4. Funcionalidades e Detalhes da Experiência

Durante a navegação no site da **L U N N A**, o usuário se depara com uma série de detalhes pensados para encantar:

* **Header Fixo Inteligente (*Sticky Navbar*):** O cabeçalho se mantém acessível conforme a rolagem da página, permitindo acessar o carrinho de compras ou categorias sem precisar voltar ao topo do site.
* **Hero Banner Imersivo:** Uma primeira dobra impactante com foto de estúdio de alta qualidade, tipografia imponente e botão de convite para explorar as novidades da coleção.
* **Vitrine com Microinterações de Hover:** Ao pousar o ponteiro sobre qualquer joia, a imagem realiza um leve efeito de ampliação (*smooth zoom*), simulando o gesto de aproximar uma lupa para conferir o trabalho de lapidação e acabamento do metal.
* **Carrinho de Compras Funcional:** Adição e remoção de produtos, atualização automática de valores e contagem de itens em tempo real no ícone do menu.
* **Design 100% Mobile First & Responsivo:** De monitores ultrawide de 27 polegadas até telas compactas de celulares, os tamanhos de fonte, espaçamentos e grids se reorganizam automaticamente para manter a sensação de conforto.

---

### 5. Principais Desafios e Lições Aprendidas

Desenvolver esse projeto foi um divisor de águas nos meus estudos de programação. Dentre os aprendizados mais marcantes, destaco:

1. **Equilíbrio entre Peso das Imagens e Qualidade Visual:** Peças de joalheria exigem fotos nítidas para mostrar brilho e detalhes de pedrarias. Aprendi na prática a comprimir e exportar imagens mantendo a nitidez sem prejudicar o tempo de carregamento da página (*Performance / First Contentful Paint*).
2. **Cálculo de Transições Suaves em CSS:** Entendi que o luxo mora nos milissegundos. Se uma transição acontece rápido demais, a interface parece dura; se demora muito, parece travada. Ajustar as curvas de *cubic-bezier* foi essencial para criar a sensação de deslize suave.
3. **Gerenciamento de Estado no DOM com JavaScript:** Gerenciar os itens adicionados ao carrinho, recalcular valores e garantir que a interface respondesse instantaneamente sem erros de re-renderização fortaleceu imensamente minha lógica e manipulação nativa do DOM.

---

### 6. Como Rodar o Projeto na Sua Máquina

Se você quiser baixar o projeto para estudar a estrutura de código ou testar alterações locais:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/stefanymazzei/L-U-N-N-A.git
   ```

2. **Navegue até a pasta do projeto:**
   ```bash
   cd L-U-N-N-A
   ```

3. **Abra o arquivo principal no navegador:**
   * Basta dar um duplo clique no arquivo `index.html`; ou
   * Abra a pasta no **VS Code** e execute com a extensão **Live Server** para recarregamento em tempo real enquanto edita o código.

---

### 7. Próximos Passos (Roadmap de Evolução)

Como este é um projeto vivo que acompanha meu crescimento profissional, pretendo implementar as seguintes melhorias em versões futuras:

* [ ] **Persistência em LocalStorage:** Salvar os itens do carrinho para que o cliente não perca suas escolhas caso atualize ou feche o navegador.
* [ ] **Modal de *Quick View* (Visualização Rápida):** Permitir abrir uma janela com mais fotos, peso em quilates e especificações do metal sem sair da página principal.
* [ ] **Simulador de Checkout:** Tela ilustrativa com cálculo de frete simulado e opções de parcelamento no cartão.
* [ ] **Suporte a Dark/Light Theme Alternativo:** Explorar uma variação clara luxuosa (*Alabaster White*) para que o usuário escolha como quer visualizar a boutique.

---

<div align="center">

### Feito com carinho e código por Stefany Mazzei

Se você gostou deste projeto, sinta-se à vontade para deixar uma ⭐️ no repositório!

[🌐 Acessar o Site L U N N A](https://stefanymazzei.github.io/L-U-N-N-A/) • [💼 Meu GitHub](https://github.com/stefanymazzei) • [⬅️ Voltar ao Início](https://github.com/stefanymazzei)

</div>
