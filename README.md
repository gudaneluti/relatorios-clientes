# Relatórios para clientes

Hospedagem estática (GitHub Pages) de relatórios e análises individuais para compartilhar com clientes e parceiros.

## Estrutura

Cada relatório fica em uma pasta própria, com `index.html` como ponto de entrada:

```
relatorios-clientes/
├── <slug-do-relatorio>/
│   └── index.html
└── outro-slug/
    └── index.html
```

URL pública de cada relatório:
`https://gudaneluti.github.io/relatorios-clientes/<slug-do-relatorio>/`

## Como adicionar um relatório novo

1. Criar pasta com slug descritivo: `<cliente>-<assunto>-<mes-ano>`
   - Exemplo: `dra-nathalia-meta-mai-2026`
2. Colocar o HTML como `index.html` dentro da pasta
3. Se o relatório tiver imagens/CSS adicional, colocar tudo dentro da mesma pasta (caminhos relativos)
4. Commit + push para `main` — GitHub Pages publica automaticamente em ~1 minuto

## Privacidade

Repositório **público** (requisito do GitHub Pages no plano gratuito). Para conteúdos sensíveis:

- Use slug não óbvio (sem nome do cliente) caso queira reduzir descoberta
- Remova a pasta após uso quando aplicável (`git rm -r <pasta> && git push`)
- Para proteção real (senha/autenticação), considere alternativas como Vercel com Password Protection

## Relatórios ativos

| Slug | Cliente / Assunto | Data | URL |
|---|---|---|---|
| `dra-nathalia-meta-mai-2026` | Dra Nathalia Teófilo — Situação Meta Ads pré-reunião com agência | 19/05/2026 | [abrir](https://gudaneluti.github.io/relatorios-clientes/dra-nathalia-meta-mai-2026/) |
| `dra-nathalia-guia-produtos` | Dra Nathalia Teófilo — Guia de Produtos da clínica | — | [abrir](https://gudaneluti.github.io/relatorios-clientes/dra-nathalia-guia-produtos/) |
