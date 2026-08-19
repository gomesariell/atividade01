# Prolintec - Soluções em Limpeza e Higiene

Projeto de website corporativo para a Prolintec, empresa especializada em soluções profissionais e domésticas em limpeza, higiene, papéis, descartáveis e equipamentos.

---

## 🚀 Como rodar o projeto

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Um servidor HTTP local (recomendado para evitar problemas com CORS)

### Opção 1: Abrir direto no navegador
1. Abra o arquivo `index.html` no seu navegador:
   - No Windows: Clique duas vezes no arquivo `index.html`
   - Ou arraste o arquivo para o navegador

### Opção 2: Usar um servidor HTTP local (Recomendado)

#### Com Python 3:
```bash
cd c:\Users\USER\Desktop\atividade01
python -m http.server 8000
```

#### Com Node.js (http-server):
```bash
npm install -g http-server
cd c:\Users\USER\Desktop\atividade01
http-server
```

#### Com Live Server (VS Code):
1. Instale a extensão "Live Server" no VS Code
2. Clique com botão direito no `index.html`
3. Selecione "Open with Live Server"

Acesse `http://localhost:8000` ou `http://127.0.0.1:5500` (dependendo do servidor)

---

## 🛠️ Tecnologias utilizadas

- **HTML5** - Estrutura semântica do projeto
- **CSS3** - Estilização com variáveis CSS customizadas, Grid e Flexbox
- **JavaScript Vanilla** - Interatividade (Menu mobile, carrinho, notificações)
- **Google Fonts** - Tipografia
  - DM Sans (400, 500, 700)
  - Plus Jakarta Sans (600, 700, 800)
- **Design Responsivo** - Mobile-first com breakpoints CSS

---

## 📁 Estrutura do projeto

```
atividade01/
├── index.html          # Página inicial com landing page
├── contato.html        # Página de contato com formulário
├── style.css           # Estilização global e componentes
└── README.md          # Este arquivo
```

---

## ✨ Funcionalidades implementadas

- ✅ Landing page responsiva com hero section
- ✅ Navegação com menu mobile
- ✅ Seções: Benefícios, Categorias, Produtos e Sobre
- ✅ Página de contato com formulário
- ✅ Carrinho de compras (UI)
- ✅ Design moderno com tema customizado
- ✅ Links de âncora para navegação suave
- ✅ Tipografia profissional

---

## 🔄 Recursos que faltam ser implementados

### Backend & Banco de dados
- [ ] Servidor backend para processar formulário de contato
- [ ] Banco de dados para armazenar mensagens de contato
- [ ] API REST para gerenciar produtos
- [ ] Sistema de autenticação/login

### Funcionalidades de E-commerce
- [ ] Adicionar produtos ao carrinho (apenas UI implementada)
- [ ] Remover itens do carrinho
- [ ] Cálculo de totais e frete
- [ ] Processo de checkout
- [ ] Pagamento online
- [ ] Histórico de pedidos

### Funcionalidades de Contato
- [ ] Validação avançada do formulário (lado cliente)
- [ ] Envio de e-mails (backend)
- [ ] Confirmação de envio com sucesso
- [ ] Sistema de tickets/suporte

### Conteúdo dinâmico
- [ ] Listagem dinâmica de produtos (atualmente hardcoded)
- [ ] Sistema de busca/filtro de produtos
- [ ] Avaliações e comentários de clientes
- [ ] Blog ou notícias

### Melhorias de UX/Performance
- [ ] Implementar JavaScript para interatividade completa
- [ ] Animações e transições suaves
- [ ] Otimização de imagens
- [ ] Lazy loading de imagens
- [ ] Progressive Web App (PWA)

### SEO & Analytics
- [ ] Sitemap XML
- [ ] Meta tags otimizadas para SEO
- [ ] Google Analytics
- [ ] Open Graph tags para redes sociais

### Deploy & Infraestrutura
- [ ] Configurar hospedagem (Vercel, Netlify, AWS, etc)
- [ ] Pipeline CI/CD
- [ ] HTTPS/SSL certificado
- [ ] CDN para distribuição de conteúdo

---

## 📝 Notas

- O projeto atualmente é uma página estática (HTML/CSS/JS básico)
- As funções JavaScript `toggleMenu()`, `showToast()` e `sendContact()` precisam ser implementadas
- O formulário de contato não envia dados para nenhum servidor
- As imagens usam placeholders do Unsplash

---

## 👨‍💻 Melhorias futuras sugeridas

1. Converter para uma arquitetura moderna (React, Vue.js ou Next.js)
2. Implementar CMS para gerenciar conteúdo
3. Adicionar integração com WhatsApp Business API
4. Implementar sistema de rastreamento de pedidos
5. Criar app mobile (React Native ou Flutter)

---

**Versão:** 1.0  
**Última atualização:** 2026-08-19
