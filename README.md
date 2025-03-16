README - Website EcoTrend
Visão Geral do Projeto
EcoTrend é um site de comércio eletrônico fictício desenvolvido como parte de um teste de faculdade para demonstrar habilidades em desenvolvimento web utilizando HTML, CSS e Bootstrap. O site simula uma loja online focada em roupas e acessórios sustentáveis e ecológicos, com ênfase em materiais orgânicos e práticas conscientes ambientalmente. O projeto apresenta uma interface front-end totalmente funcional com várias páginas, design responsivo e elementos interativos, refletindo funcionalidades típicas de um e-commerce real.

Os principais objetivos deste projeto são:

Projetar e implementar uma plataforma de e-commerce visualmente atraente e fácil de usar.
Aplicar princípios de design responsivo utilizando o Bootstrap 5.3.0.
Demonstrar compreensão da estrutura HTML, estilização CSS e integração de JavaScript.
Simular uma experiência realista de compras online com listagem de produtos, páginas detalhadas e documentação legal.
Estrutura do Projeto
O site EcoTrend é composto por vários arquivos HTML, cada um representando uma página distinta, estilizados com uma estrutura CSS compartilhada e aprimorados com componentes do Bootstrap. Abaixo está a estrutura de arquivos e a finalidade de cada página:

text

Collapse

Wrap

Copy
EcoTrend/
├── index.html                # Página inicial com produtos em destaque e carrossel
├── politicas.html            # Página de Políticas de Privacidade
├── termos.html               # Página de Termos e Condições
├── categorias.html           # Página de Categorias com listagem de produtos
├── Contato.html              # Página de formulário de contato
├── CamisetaBrancaFeminina.html      # Página do produto Camiseta Branca Feminina
├── CamisetaMasculinaListrada.html   # Página do produto Camiseta Masculina Listrada
├── CamisetaMangaLongaLaranjaInfantil.html  # Página do produto Camiseta Manga Longa Laranja Infantil
├── PijamaGaia.html           # Página do produto Pijama Gaia
├── CamisolaNatureCru.html    # Página do produto Camisola Nature Cru
├── CamisetaPreta.html        # Página do produto Camiseta Preta Masculina
├── Kit2Fronhas.html          # Página do produto Kit 2 Fronhas
├── src/
│   ├── assets/              # Pasta com imagens (banners, fotos de produtos, ícones de carrinho)
│   │   ├── Banner 1.jpg
│   │   ├── Banner 2.jpg
│   │   ├── Camiseta Branca Feminina.jpg
│   │   ├── Camiseta masculina listrada.jpg
│   │   ├── Camiseta preta.jpg
│   │   ├── Camiseta manga longa laranja infantil.jpg
│   │   ├── Pijama Gaia.jpg
│   │   ├── Camisola Nature Cru.jpg
│   │   ├── Fronha.jpg
│   │   ├── shopping-cart-black.webp
│   │   ├── shopping-cart-white.png

Descrição das Páginas
index.html: A página inicial é o ponto de entrada, apresentando um carrossel com banners promocionais e uma seção de "Produtos em Destaque" com sete itens, preços e botões "Adicionar ao Carrinho".
politicas.html: A página de Políticas de Privacidade descreve como os dados dos usuários são coletados, usados e protegidos, seguindo requisitos legais comuns em e-commerce.
termos.html: A página de Termos e Condições detalha as regras de uso do site, incluindo propriedade intelectual e cláusulas de responsabilidade.
categorias.html: A página de Categorias organiza os produtos em três seções: Camisetas, Pijamas e Camisolas, e Acessórios.
Contato.html: A página de Contato oferece um formulário para envio de mensagens, com campos para nome, e-mail, assunto e mensagem.
Páginas de Produto: Páginas individuais de produtos incluem:
CamisetaBrancaFeminina.html: Detalhes da camiseta branca feminina em algodão 100%.
CamisetaMasculinaListrada.html: Detalhes da camiseta masculina listrada.
CamisetaMangaLongaLaranjaInfantil.html: Detalhes da camiseta infantil laranja de manga longa.
PijamaGaia.html: Detalhes do pijama Gaia em algodão orgânico.
CamisolaNatureCru.html: Detalhes da camisola Nature Cru em algodão orgânico.
CamisetaPreta.html: Detalhes da camiseta preta masculina.
Kit2Fronhas.html: Detalhes do kit de duas fronhas em algodão orgânico.

Funcionalidades
1. Design Responsivo
Utiliza o Bootstrap 5.3.0 para um layout responsivo, priorizando dispositivos móveis e adaptando-se a diferentes tamanhos de tela.
Cartões de produtos e navegação escalam dinamicamente com transições CSS (transform: scale(1.05) ao passar o mouse).
2. Navegação
Um cabeçalho consistente em todas as páginas inclui links para "Home", "Categorias", "Contato" e um ícone de carrinho com efeito de troca ao passar o mouse (de preto para branco).
O rodapé contém links para "Contato", "Termos e Condições" e "Políticas de Privacidade", com efeitos de escala ao passar o mouse.
3. Carrossel na Página Inicial
Um carrossel Bootstrap exibe dois banners promocionais (Banner 1.jpg e Banner 2.jpg) com intervalo de 3 segundos, navegável por controles de anterior/próximo.
4. Listagem de Produtos
A página inicial e a página de categorias exibem cartões de produtos com imagens, títulos, preços e botões de ação ("Ver Mais" e "+ Carrinho").
Páginas detalhadas de produtos incluem imagens maiores, descrições, preços e botões de seleção de tamanho (ex.: PP, P, M, G, GG).
5. Estilização
CSS personalizado complementa o Bootstrap com um cabeçalho em gradiente verde (linear-gradient(#006600, green)), animações de hover e uma paleta de cores coesa (verde para botões, texto branco em fundos escuros).
Cartões de produtos e botões escalam ao passar o mouse para maior interatividade.
6. Páginas Legais
As Políticas de Privacidade e os Termos e Condições são estruturados com títulos e parágrafos justificados, simulando documentação legal padrão.

Detalhes Técnicos

Tecnologias Utilizadas
HTML5: Estrutura semântica das páginas, com seções, cabeçalhos e formulários.
CSS3: Estilização personalizada, incluindo transições, gradientes e hover effects.
Bootstrap 5.3.0: Framework para design responsivo, componentes como carrossel, cartões e navegação.
JavaScript: Integração via Bootstrap para funcionalidades interativas (carrossel, botões) e script adicional de validação (Cloudflare).

Dependências Externas
Bootstrap CSS: https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css
Bootstrap JS: https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js
Script Cloudflare para segurança (incluso nos arquivos HTML).

Paleta de Cores
Verde escuro (#006600): Cabeçalho e botões em hover.
Verde médio (green): Gradiente do cabeçalho e botões principais.
Preto (#000000): Fundo do carrossel e texto em cartões.
Branco (#FFFFFF): Texto no cabeçalho e rodapé.
Cinza escuro (#00000080): Fundo da legenda do carrossel.

Instruções de Uso
Executando o Projeto:
Clone o repositório ou copie os arquivos para um diretório local.
Abra o arquivo index.html em um navegador web moderno (Chrome, Firefox, etc.).
Navegue entre as páginas usando os links no cabeçalho ou rodapé.
Testando Responsividade:
Redimensione a janela do navegador ou use as ferramentas de desenvolvedor (F12) para simular diferentes tamanhos de tela.
Interatividade:
Passe o mouse sobre os itens de navegação, cartões de produtos e botões para ver os efeitos de hover.
Clique nos controles do carrossel para navegar entre os banners.

Pontos de Aprendizado

Este projeto permitiu o desenvolvimento das seguintes competências:

-Estruturação de um site multi-página com navegação consistente.
-Uso de frameworks CSS para acelerar o desenvolvimento e garantir responsividade.
-Aplicação de técnicas de design visual para melhorar a experiência do usuário.
-Simulação de um ambiente de e-commerce com foco em usabilidade e estética.

Considerações Finais

O EcoTrend é um exemplo funcional de um site de e-commerce básico, projetado para atender aos requisitos de um teste de faculdade. Embora seja um projeto front-end estático, ele reflete práticas reais de desenvolvimento web e poderia ser expandido com back-end (ex.: Node.js, PHP) para funcionalidades como carrinho de compras dinâmico e processamento de formulários. O foco em sustentabilidade também adiciona um toque contemporâneo, alinhando-se às tendências atuais do mercado.

Data: 16 de março de 2025

Desenvolvido por: Leonardo Fernandes Mesquita, RM:559623; Guilherme Augusto Caseiro, RM:559765; Marco Antonio Caires, RM:559256; alunos da turma 1ESPA de Engenharia de Software

Instituição: Faculdade de Informática e Administração Paulista - FIAP

Disciplina: Front-End

Localização: https://github.com/leoGitFiap/frontEndCP4_2025 -- https://leogitfiap.github.io/frontEndCP4_2025/ 
