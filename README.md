<div align="center">

# 🍔 Gordo Lanches

### *O verdadeiro sabor em porções generosas!*

Plataforma moderna de cardápio digital e sistema de pedidos online desenvolvida para proporcionar a melhor experiência gastronômica aos clientes da **Gordo Lanches**.

---

[![Status do Projeto](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge&logo=git)](https://github.com/)
[![Versão](https://img.shields.io/badge/Versão-0.1.0-blue?style=for-the-badge)](https://github.com/)
[![Licença](https://img.shields.io/badge/Licença-MIT-green?style=for-the-badge)](LICENSE)
[![PRs Bem-vindos](https://img.shields.io/badge/PRs-Bem--vindos-brightgreen?style=for-the-badge&logo=github)](CONTRIBUTING.md)

[Visão Geral](#-visão-geral) •
[Funcionalidades](#-funcionalidades) •
[Cardápio](#-categorias-do-cardápio) •
[Tecnologias](#-tecnologias) •
[Estrutura](#-estrutura-do-projeto) •
[Como Executar](#-como-executar-o-projeto) •
[Roadmap](#-roadmap-de-desenvolvimento) •
[Autor](#-autor)

</div>

---

## 📖 Visão Geral

O projeto **Gordo Lanches** nasceu com o objetivo de revolucionar o atendimento e a gestão de pedidos da lanchonete. Através de uma interface intuitiva, rápida e focada em dispositivos móveis (*Mobile First*), os clientes podem navegar pelo catálogo completo de produtos, montar seus lanches com ingredientes adicionais e fechar seus pedidos em poucos cliques.

Além de valorizar a apresentação dos pratos com fotos em alta qualidade e descrições apetitosas, o sistema visa cortar custos operacionais com taxas abusivas de aplicativos de entrega tradicionais, direcionando os pedidos formatados de maneira ágil diretamente para o atendimento via **WhatsApp** e integrando pagamentos instantâneos via **PIX**.

---

## ✨ Funcionalidades

### 📱 Para os Clientes
- **Cardápio Digital Interativo:** Navegação fluida por categorias (artesanais, tradicionais, porções, bebidas e sobremesas).
- **Personalização de Pedidos:** Adição de adicionais (bacon, queijo extra, molhos artesanais) e remoção de ingredientes (sem cebola, sem picles, etc.).
- **Carrinho de Compras em Tempo Real:** Atualização automática de valores, quantidade e observações do pedido.
- **Opções de Entrega:**
  - 🛵 **Delivery:** Cálculo automático de taxa de entrega baseado no bairro/endereço informado.
  - 🏬 **Retirada no Balcão:** Opção rápida para o cliente retirar o pedido no local.
- **Checkout Inteligente via WhatsApp:** Geração de mensagem estruturada e padronizada enviada automaticamente para o atendente.
- **Pagamento Integrado:**
  - Chave Pix com geração de QR Code e código "Copia e Cola".
  - Opções para pagamento na entrega (Cartão de Débito/Crédito ou Dinheiro com troco).

### ⚙️ Para a Gestão (Previsto no Roadmap)
- **Painel Administrativo:** Controle de abertura/fechamento da loja e horários de funcionamento.
- **Gestão de Cardápio:** Edição rápida de preços, promoções e marcação de itens esgotados.
- **Gestor de Pedidos (KDS):** Visualização em tempo real das comandas (Pendente ➔ Em Preparo ➔ Saiu para Entrega ➔ Concluído).

---

## 🍟 Categorias do Cardápio

| Categoria | Destaques |
| :--- | :--- |
| 🍔 **Hambúrgueres Artesanais** | Blends especiais de carne bovina, pão brioche selado na manteiga e queijo derretido. |
| 🥪 **Lanches Tradicionais** | X-Tudo, X-Bacon, X-Salada, Misto Quente e os clássicos da chapa prensada. |
| 🌭 **Hot Dogs Especiais** | Prensados com purê caseiro, batata palha crocante e molhos da casa. |
| 🍟 **Porções & Petiscos** | Batata frita com cheddar e bacon, nuggets, anéis de cebola e calabresa acebolada. |
| 🥤 **Bebidas** | Refrigerantes, sucos naturais, cervejas artesanais e água mineral. |
| 🍦 **Sobremesas & Shakes** | Milk-shakes cremosos, churros e sobremesas artesanais. |

---

## 🛠️ Tecnologias

O projeto está sendo estruturado com tecnologias modernas da web para garantir velocidade de carregamento, ótima indexação (SEO) e alta escalabilidade:

- **Linguagens & Frameworks:** [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML), [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS), [JavaScript (ES6+)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- **Estilização & UI:** Design Responsivo com foco em *Mobile-First*, animações suaves e paleta de cores acolhedora voltada ao setor alimentício (tons de vermelho, amarelo e preto).
- **Ícones & Tipografia:** [Lucide Icons](https://lucide.dev/) / [FontAwesome](https://fontawesome.com/) e [Google Fonts](https://fonts.google.com/) (Poppin/Inter).
- **Integrações:** API oficial do WhatsApp (`wa.me`) para redirecionamento direto de comandas.

---

## 📂 Estrutura do Projeto

Abaixo, a arquitetura sugerida para a organização dos arquivos do projeto:

```bash
gordolanches/
├── 📁 assets/
│   ├── 📁 css/              # Folhas de estilo (variáveis, layout, componentes)
│   ├── 📁 js/               # Lógica da aplicação (carrinho, menu, checkout)
│   ├── 📁 images/           # Imagens de lanches, logos e ícones
│   │   ├── 📁 lanches/
│   │   ├── 📁 bebidas/
│   │   └── 📁 porcoes/
│   └── 📁 fonts/            # Tipografias locais (se aplicável)
├── 📄 index.html            # Página principal com o catálogo e carrinho
├── 📄 .gitignore            # Arquivos ignorados pelo Git
├── 📄 LICENSE               # Licença do projeto
└── 📄 README.md             # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Para visualizar e testar o projeto localmente, você precisa apenas de um navegador moderno (Google Chrome, Firefox, Edge ou Safari) e do Git instalado em seu computador.

### Passo a Passo

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/Michel-S2/gordolanches.git
   ```

2. **Acesse o diretório do projeto:**
   ```bash
   cd gordolanches
   ```

3. **Abra o projeto:**
   - **Opção 1:** Dê dois cliques no arquivo `index.html` para abrir diretamente no navegador.
   - **Opção 2 (Recomendada):** Utilize a extensão **Live Server** no VS Code para hot-reload e melhor simulação de servidor local:
     - Clique com o botão direito no `index.html` ➔ **Open with Live Server**.

---

## 🗺️ Roadmap de Desenvolvimento

- [x] Concepção da ideia e estrutura inicial do repositório
- [ ] Criação do design visual e prototipagem da interface
- [ ] Implementação da página principal com catálogo de produtos
- [ ] Desenvolvimento da lógica do carrinho de compras (adicionar, remover, alterar quantidade)
- [ ] Sistema de customização de ingredientes por item
- [ ] Integração com WhatsApp para disparo da comanda formatada
- [ ] Cálculo dinâmico de taxa de entrega e opção de retirada
- [ ] Sistema de pagamento via QR Code Pix
- [ ] Painel administrativo para acompanhamento de pedidos

---

## 🤝 Como Contribuir

Contribuições são muito bem-vindas! Se você deseja colaborar com novas funcionalidades, melhorias no design ou correções:

1. Faça um **Fork** do projeto.
2. Crie uma **Branch** para sua funcionalidade:
   ```bash
   git checkout -b feature/NovaFuncionalidade
   ```
3. Realize o **Commit** de suas alterações com mensagens claras:
   ```bash
   git commit -m 'feat: adiciona filtro por categoria no cardapio'
   ```
4. Envie para o repositório remoto (**Push**):
   ```bash
   git push origin feature/NovaFuncionalidade
   ```
5. Abra um **Pull Request** explicando detalhadamente as mudanças propostas.

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para obter mais informações.

---

## 👤 Autor

Desenvolvido com dedicação por **Michel Freitas**.

- **GitHub:** [@Michel-S2](https://github.com/Michel-S2)

---

<div align="center">
  <sub>Gordo Lanches © Todos os direitos reservados. Feito com ❤️ e fome de hambúrguer!</sub>
</div>
