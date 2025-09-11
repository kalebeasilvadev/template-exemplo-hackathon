# Angular Website Example - Template para Hackathon

Este repositório contém um website Angular convertido de um template HTML, ideal para uso como base em hackathons e projetos rápidos.

## 🚀 Deploy Automático

O projeto está configurado para deploy automático no **GitHub Pages** via **GitHub Actions**.

### URL do Projeto

```
https://kalebeandrade.github.io/template-exemplo-hackathon/
```

## 📋 Funcionalidades

- **Angular 17** com TypeScript
- **Responsive Design** 
- Múltiplas páginas (Home, About, Services, Gallery, Pricing, Testimonials)
- Navegação SPA (Single Page Application)
- Deploy automático no GitHub Pages
- Configuração de fallback para 404.html (suporte a rotas)

## 🛠️ Desenvolvimento Local

### Pré-requisitos

- Node.js 20+
- npm

### Instalação

```bash
# Clone o repositório
git clone https://github.com/kalebeandrade/template-exemplo-hackathon.git
cd template-exemplo-hackathon

# Instale as dependências
npm install

# Execute o servidor de desenvolvimento
npm start
```

O projeto estará disponível em `http://localhost:4200`

### Build de Produção

```bash
# Build para produção
npm run build

# Build para GitHub Pages (com base-href correto)
npm run build -- --configuration=production --base-href "/template-exemplo-hackathon/"
```

## 🔧 Configuração do GitHub Pages

Para usar este template em seu próprio repositório:

1. **Fork/Clone** este repositório
2. Vá para **Settings → Pages** no GitHub
3. Em **Build and deployment**, selecione **Source: GitHub Actions**
4. O workflow já está configurado em `.github/workflows/deploy.yml`
5. Faça um push para `main` - o deploy será automático

### Personalizando para seu Repositório

Se você mudou o nome do repositório, atualize a URL no README:

```
https://<seu-usuario>.github.io/<seu-repositorio>/
```

## 📁 Estrutura do Projeto

```
src/
├── app/
│   ├── about/          # Página Sobre
│   ├── clients/        # Página Clientes
│   ├── gallery/        # Galeria de imagens
│   ├── home/           # Página inicial
│   ├── pricing/        # Página de preços
│   ├── services/       # Página de serviços
│   ├── testimonial/    # Depoimentos
│   └── shared/         # Serviços compartilhados
├── assets/
│   ├── css/           # Estilos CSS
│   ├── images/        # Imagens do projeto
│   ├── fonts/         # Fontes personalizadas
│   └── js/            # Scripts JavaScript
└── environments/      # Configurações de ambiente
```

## 🎨 Personalização

### Cores e Estilos

- Edite `src/assets/css/namari-color.css` para personalizar cores
- Modifique `src/styles.css` para estilos globais

### Conteúdo

- Configure os dados em `src/app/shared/services/configuration.ts`
- Personalize os componentes de cada seção
- Substitua as imagens em `src/assets/images/`

### Logo e Favicon

- Substitua `src/assets/images/logo.png`
- Atualize `src/favicon.ico`

## 🚀 Pronto para Hackathon

Este template está otimizado para desenvolvimento rápido:

- ✅ Estrutura modular e organizade
- ✅ Deploy automático configurado
- ✅ Responsivo e acessível
- ✅ Múltiplas seções já implementadas
- ✅ Fácil personalização de conteúdo

---

**Código original:** [AndrewJBateman/angular-website-example](https://github.com/AndrewJBateman/angular-website-example)

**Adaptado para template de hackathon** com deploy automático no GitHub Pages.