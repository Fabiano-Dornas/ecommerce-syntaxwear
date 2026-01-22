# 👟 SyntaxWear - E-commerce de Tênis e Sneakers

Uma plataforma moderna de e-commerce especializada em venda de tênis e sneakers online. O projeto é uma aplicação web responsiva desenvolvida com HTML, CSS e uma arquitetura componentizada.

## 📋 Visão Geral

**SyntaxWear** é um site de e-commerce focado em vender tênis e sneakers com estilo urbano e futurista. A plataforma oferece uma experiência de compra intuitiva com navegação responsiva, categorização de produtos e interface moderna.

## 🎯 Funcionalidades Principais

- **Navegação Principal**: Menu com categorias (Masculino, Feminino, Outlet)
- **Seção Hero**: Banner destacado com call-to-action para conversão
- **Categorização de Produtos**: 4 categorias principais
  - Casual
  - Esporte
  - Moderno
  - Futurista
- **Grid de Produtos**: Exibição em destaque de produtos selecionados
- **Newsletter**: Inscrição para e-mail marketing
- **Redes Sociais**: Links para Instagram, WhatsApp, TikTok e Facebook
- **Menu Responsivo**: Hamburguer menu para dispositivos móveis
- **Ícones de Acesso Rápido**: Conta, Ajuda e Carrinho de compras

## 📁 Estrutura do Projeto

```
ecommerce-syntaxwear/
├── index.html                 # Arquivo principal da aplicação
├── README.md                  # Documentação
├── css/                       # Estilos da aplicação
│   ├── reset.css             # Reset de estilos padrão
│   ├── variables.css         # Variáveis CSS e tipografia
│   ├── base.css              # Estilos base e componentes globais
│   └── components/           # Estilos de componentes específicos
│       ├── header.css        # Estilos do cabeçalho
│       ├── hero.css          # Estilos da seção hero
│       ├── product-category.css  # Estilos de categorias
│       ├── product-grid.css  # Estilos do grid de produtos
│       └── footer.css        # Estilos do rodapé
├── images/                   # Recursos visuais
│   ├── banners/             # Imagens de banners
│   ├── favicons/            # Ícones do navegador
│   ├── icons/               # Ícones do site (menu, conta, etc)
│   ├── logo/                # Logo da marca
│   └── products/            # Imagens dos produtos
└── .git/                    # Repositório Git
```

## 🎨 Design e Estilo

### Tipografia
- **Principal**: Ubuntu (variações de peso: 300, 400, 500, 700)
- **Secundárias**: Oswald, Roboto
- Importadas do Google Fonts

### Componentes CSS
- **Reset**: Normalização de estilos padrão do navegador
- **Variables**: Variáveis CSS para manutenção de temas
- **Base**: Estilos globais e componentes reutilizáveis
- **Components**: Estilos modularizados por seção

### Botões
- Dois estilos: `btn-outline` e `btn-filled`
- Dimensões padronizadas: 161px × 48px
- Transições suaves (0.3s) para hover

## 📱 Responsividade

- **Design Mobile-First**
- **Breakpoint**: 1200px para ajustes em tablets/desktops
- **Menu Hamburger**: Ativado em dispositivos menores
- **Layout Fluido**: Adapta-se a diferentes tamanhos de tela

## 🔗 Seções da Página

### Header
- Logo da marca
- Menu de navegação responsivo
- Ícones de acesso rápido (Conta, Ajuda, Carrinho)
- Menu hamburguer para dispositivos móveis

### Hero Section
- Subtítulo destacado: "Krypton One"
- Título principal: "Transforme qualquer passo em presença"
- Dois botões de call-to-action
- Background image com overlay

### Categories Section
- 4 cards de categorias com hover effect
- Cada categoria tem link para seus produtos
- Overlay para melhor legibilidade do nome

### Product Grid
- Card destacado com produto "Krypton One"
- 5 produtos adicionais em grid
- Diferentes estilos visuais para cada card

### Footer
- **Newsletter**: Inscrição por email
- **Redes Sociais**: Links para principais plataformas
- **Menu de Navegação**: Organizado por categorias
  - Masculino (4 categorias)
  - Feminino (4 categorias)
  - Outlet (Masculino e Feminino)
  - Nossas Lojas (Loja física e online)
  - Sobre (Quem somos, Missão)
- **Copyright**: Informação de direitos reservados

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização com media queries e flexbox/grid
- **SVG**: Ícones e logo em formato vetorial
- **Responsive Design**: Mobile-first approach

## 📊 SEO e Metadados

- **Título**: "SyntaxWear - Tênis e Sneakers Online"
- **Description**: Descrição otimizada para mecanismos de busca
- **Charset**: UTF-8
- **Viewport**: Meta tag para responsividade
- **Linguagem**: Portuguese (pt-br)

## 🎯 Próximos Passos para Desenvolvimento

- [ ] Integração com backend para gerenciamento de produtos
- [ ] Sistema de carrinho de compras funcional
- [ ] Página de detalhes do produto
- [ ] Sistema de autenticação de usuários
- [ ] Integração com gateway de pagamento
- [ ] Filtros e busca avançada de produtos
- [ ] Sistema de avaliações e comentários
- [ ] Rastreamento de pedidos
- [ ] Chat de atendimento ao cliente

## 📝 Notas de Desenvolvimento

- Todos os links (#) devem ser conectados às páginas correspondentes
- Formulário de newsletter precisa ser integrado com serviço de email
- Cards de produtos precisam de dados dinâmicos
- Sistema de carrinho deve ser implementado com JavaScript
- Icones SVG com dupla extensão (.svg.svg) devem ser revistos

## 👤 Informações do Projeto

**Nome**: SyntaxWear E-commerce
**Tipo**: Plataforma de Vendas de Tênis e Sneakers
**Status**: Em Desenvolvimento
**Versão**: 1.0