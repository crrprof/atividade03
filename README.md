
# SPA Modular — ONG Exemplo

Projeto didático de **Single Page Application (SPA)** com **JavaScript modular** e **templates em strings**, organizado por funcionalidades.

## Estrutura
```
spa-modular/
├─ index.html          # HTML principal (imports dos módulos)
├─ css/
│  └─ style.css        # Estilos (layout e utilitários)
├─ js/
│  ├─ templates.js     # Templates/views e componentes simples
│  ├─ store.js         # Estado/dados de exemplo (mock)
│  ├─ router.js        # Roteamento por hash + pós-render
│  └─ app.js           # Bootstrap: listeners globais e init
└─ img/
   └─ README.txt       # Pasta para imagens
```

## Como rodar
1. Abra `index.html` no navegador (duplo clique).
2. Navegue: `#/home`, `#/projetos`, `#/cadastro` (sem recarregar a página).

## Objetivos atendidos
- **SPA básica:** troca de conteúdo dinâmica no `<main id="app">` via JS, sem reload.
- **Templates JS:** `Templates.*` e `Components.*` retornam HTML (strings) para cada view.
- **Código modular:** JS separado por responsabilidade (templates, store, router, app).
- **Estrutura organizada:** pastas para `css`, `js` e `img`.

## Próximos passos (opcionais)
- `validators.js` e `masks.js` como módulos separados (CPF/CEP/telefone).
- `history.pushState` em vez de hash (`#/rota` → `/rota`).
- Carregar projetos com `fetch()` de um `projects.json` (mock API).
- Componentização mais avançada (montar/desmontar eventos por view).
```

