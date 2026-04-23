# Missão Seatrade Cruise Global 2026 — Miami

Relatório executivo da missão institucional de Itajaí à **Seatrade Cruise Global 2026** em Miami, EUA — principal feira mundial do setor de cruzeiros.

## Publicação

- **URL pública (após deploy):** https://cadeodiego.github.io/setur-seatrade-miami-2026/
- **Arquivo principal:** [`relatorio.html`](relatorio.html)
- **Versão atual:** v1.0 · abril de 2026

## Estrutura

```
setur-seatrade-miami-2026/
├── relatorio.html              ← peça principal (espelho da versão pública atual)
├── relatorio-v1.html           ← histórico (criado ao subir v2)
├── README.md
└── assets/
    ├── itajai-turismo-branco.svg
    ├── fotos/                  ← registro fotográfico da missão
    └── materiais/
        └── terminal-cruzeiros.pdf
```

## Padrão de versionamento

Segue o mesmo padrão do dashboard da temporada de cruzeiros:

- `relatorio.html` = espelho da versão pública atual (link estável)
- `relatorio-vN.html` = histórico de iterações preservado
- Para publicar nova versão: renomear `relatorio.html` antigo → `relatorio-vN.html`, subir novo `relatorio.html`, commit + push

## Stack

- HTML/CSS single-file, zero framework
- Fontes: Fraunces (display) + Inter (body) via Google Fonts
- Paleta institucional Itajaí — A Maix Quirida
- SVG hand-crafted para ícones e gráficos
- Mobile-first responsivo
- Print stylesheet com quebras otimizadas

## Produção

Secretaria de Turismo e Eventos de Itajaí
Diretoria Executiva de Turismo e Eventos
Diego Oliveira · Diretor Executivo
cadeodiego@gmail.com

## Referência

Relatório da Temporada de Cruzeiros 2025/26: https://cadeodiego.github.io/setur-cruzeiros-2026/dashboard.html
