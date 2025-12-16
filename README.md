# 🛍️ E-Commerce PWA – Flutter Web

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)

## 📱 Sobre o Projeto

**E-Commerce PWA** é uma loja virtual mobile-first desenvolvida em Flutter Web, projetada para funcionar como Progressive Web App (PWA) – instalável em dispositivos móveis e com suporte básico a uso offline. O projeto oferece uma experiência de compra moderna, rápida e responsiva.

### ✨ Principais Funcionalidades

- 📱 **Mobile-First Design** – Interface otimizada para dispositivos móveis
- 📦 **Catálogo de Produtos** – Listagem com filtros, busca e categorização
- 🛍️ **Carrinho de Compras** – Adição, remoção e edição de quantidades
- 💳 **Checkout Completo** – Processo de pagamento intuitivo
- 🔐 **Área do Usuário** – Login, cadastro e gerenciamento de perfil
- 📊 **Histórico de Pedidos** – Visualização de compras anteriores
- 💵 **Integração de Pagamento** – Gateway de pagamento (mockado ou real)
- 📲 **PWA Instalável** – Pode ser instalado como app nativo
- 🔄 **Sincronização em Tempo Real** – Atualização automática de estoque e preços
- ⚡ **Performance Otimizada** – Carregamento rápido e navegação fluida
- 🌐 **Suporte Offline Básico** – Cache de produtos para visualização sem conexão

## 🛠️ Tecnologias Utilizadas

- **Flutter Web** – Framework para desenvolvimento web responsivo
- **Dart** – Linguagem de programação
- **Provider/Riverpod** – Gerenciamento de estado
- **Firebase** (opcional) – Backend, autenticação e banco de dados
- **Stripe/Mercado Pago** – Integração de pagamentos
- **Service Workers** – Cache e funcionalidade offline
- **Responsive Framework** – Layout adaptável

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Flutter SDK (versão 3.0 ou superior)
- Dart SDK
- Navegador web (Chrome recomendado para desenvolvimento)

### Instalação

```bash
# Clone o repositório
git clone https://github.com/gaio1812/ecommerce-pwa-flutter.git

# Entre no diretório
cd ecommerce-pwa-flutter

# Instale as dependências
flutter pub get

# Execute em modo de desenvolvimento
flutter run -d chrome
```

### Build para Produção

```bash
# Gerar build otimizado para web
flutter build web --release --web-renderer canvaskit

# Os arquivos estarão em build/web/
```

### Deploy

O projeto pode ser hospedado em:
- **Firebase Hosting**
- **Vercel**
- **Netlify**
- **GitHub Pages**

```bash
# Exemplo com Firebase
firebase deploy --only hosting
```

## 📂 Estrutura do Projeto

```
lib/
├── models/
│   ├── product.dart     # Modelo de produto
│   ├── cart_item.dart   # Item do carrinho
│   └── order.dart       # Pedido
├── screens/
│   ├── home_screen.dart
│   ├── product_list_screen.dart
│   ├── product_detail_screen.dart
│   ├── cart_screen.dart
│   ├── checkout_screen.dart
│   └── profile_screen.dart
├── widgets/
│   ├── product_card.dart
│   ├── cart_item_widget.dart
│   └── custom_app_bar.dart
├── providers/
│   ├── cart_provider.dart
│   ├── products_provider.dart
│   └── auth_provider.dart
├── services/
│   ├── api_service.dart
│   ├── payment_service.dart
│   └── auth_service.dart
└── main.dart
```

## 🔧 Funcionalidades Detalhadas

### Catálogo de Produtos
- Grid responsivo de produtos
- Filtros por categoria, preço e avaliação
- Busca em tempo real
- Ordenação (preço, popularidade, etc.)

### Carrinho de Compras
- Adição rápida de produtos
- Atualização de quantidades
- Cálculo automático de totais
- Persistência local (LocalStorage)

### Checkout
- Formulário de endereço de entrega
- Seleção de método de pagamento
- Resumo do pedido
- Confirmação de compra

### Área do Usuário
- Login e cadastro
- Gerenciamento de perfil
- Endereços salvos
- Histórico de pedidos

## 🎯 Roadmap

- [ ] Wishlist (lista de desejos)
- [ ] Avaliações e comentários de produtos
- [ ] Integração com APIs de frete (Correios, etc.)
- [ ] Notificações push para promoções
- [ ] Sistema de cupons de desconto
- [ ] Chat de suporte ao cliente
- [ ] Painel administrativo

## 📸 Screenshots

> Em desenvolvimento...

## 💡 Integrações de Pagamento

Exemplos de gateways suportados:
- **Stripe** – Cartões de crédito internacionais
- **Mercado Pago** – Métodos de pagamento brasileiros
- **PayPal** – Pagamento global
- **PagSeguro** – Mercado brasileiro

## 💼 Uso Profissional

Este projeto demonstra:
- Desenvolvimento de PWA com Flutter Web
- UI/UX focada em conversão de vendas
- Integração com APIs de pagamento
- Gerenciamento de estado complexo
- Performance e otimização para web
- Responsividade e mobile-first design
- Service Workers e funcionalidade offline

Ideal para portfólio demonstrando habilidades em desenvolvimento web moderno com Flutter e e-commerce.

## 📄 Licença

Este projeto está sob a licença MIT.

## 👨‍💻 Desenvolvedor

Desenvolvido por **Gabriel Gaio**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gaio1812)

---

⭐ Se este projeto foi útil, deixe uma estrela!