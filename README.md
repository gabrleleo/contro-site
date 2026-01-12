# Gabriel - Espaço Pessoal

Um site minimalista e reflexivo que reage à presença do visitante. Espaço onde código, texto e experiência se encontram.

## 🎨 Características

- **Saudação Dinâmica**: O site cumprimenta o visitante baseado na hora do dia
- **Pesquisa Inteligente**: Busca por termos gera frases personalizadas relacionadas
- **Gerador de Frases**: 40+ citações em 5 categorias (Reflexão, Criatividade, Existência, Tecnologia, Todas)
- **Mural Interativo**: Deixe suas mensagens que ficam persistidas
- **Contador de Visitas**: Rastreie quantas vezes você visitou este espaço
- **Filtro Velho Oeste**: Foto com estilo vintage sepia
- **Design Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Persistência Local**: Todos os dados são salvos no localStorage

## 🚀 Como Usar

### Opção 1: GitHub Pages

1. Faça fork deste repositório
2. Vá para **Settings** → **Pages**
3. Selecione **Deploy from a branch**
4. Escolha a branch `main` e pasta `/ (root)`
5. Clique em **Save**
6. Seu site estará disponível em `https://seu-usuario.github.io/gabriel-site`

### Opção 2: Servidor Local

```bash
# Se tiver Python instalado
python -m http.server 8000

# Ou com Node.js
npx http-server
```

Acesse `http://localhost:8000`

## 📁 Estrutura

```
gabriel-site-github/
├── index.html           # Página principal
├── assets/
│   ├── index-*.css     # Estilos compilados
│   └── index-*.js      # JavaScript compilado
├── images/
│   └── gabriel.jpg     # Foto com filtro velho oeste
├── .nojekyll           # Desabilita Jekyll no GitHub Pages
└── README.md           # Este arquivo
```

## 🎯 Funcionalidades Principais

### Hub (Menu Principal)
- Pesquisar por palavras-chave
- Acessar diferentes seções
- Ver contador de visitas

### Gerador de Frases
- Selecione uma categoria
- Gere frases aleatórias
- Cada categoria tem seu próprio conjunto de reflexões

### Pesquisa Personalizada
Busque por qualquer termo e receba uma frase relacionada:
- Termos mapeados: amor, medo, sucesso, fracasso, tempo, mudança, sonho, morte, beleza, liberdade, conhecimento, silêncio, luz, escuridão, força, fraqueza, esperança, desespero, verdade, mentira
- Termos genéricos: recebem frases personalizadas automaticamente

### Mural
Deixe suas reflexões e mensagens que ficarão persistidas durante sua sessão

### Contador
Acompanhe quantas vezes você visitou este espaço

## 🎨 Design

- **Tema**: Minimalismo Reflexivo
- **Paleta**: Escuro (#0a0a0a) com tons neutros
- **Tipografia**: Playfair Display (títulos) + Segoe UI (corpo)
- **Interatividade**: Sutil e responsiva

## 📱 Responsividade

O site se adapta perfeitamente para:
- Desktop (1024px+)
- Tablet (768px - 1023px)
- Mobile (até 767px)

## 🔧 Tecnologias

- React 19
- Tailwind CSS 4
- Vite
- TypeScript
- shadcn/ui

## 💾 Dados Persistentes

Todos os dados são armazenados localmente no navegador:
- Nome do visitante
- Mensagens do mural
- Contador de visitas
- Estado da navegação

## 📝 Assinatura

— controversys

## 📄 Licença

Livre para usar e modificar conforme necessário.

---

**Criado com ❤️ como um espaço para reflexão e criatividade.**
