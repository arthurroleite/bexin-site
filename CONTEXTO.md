# BEXIN — Contexto do Projeto

## Empresa
- **Nome:** BEXIN
- **Tagline:** Consultoria e Inteligência pro Negócio
- **Conceito:** B = Batida · EX = Execução · IN = Inteligência
- **Produto/Ferramenta:** PULSO (plataforma de rastreamento da execução comercial)

## Repositório
- **GitHub:** https://github.com/arthurroleite/bexin-site
- **Conta GitHub:** arthurroleite
- **Branch principal:** master

## Hospedagem
- **Plataforma:** Vercel
- **Conta Vercel:** artroleite2015-gmailcoms-projects
- **Deploy automático:** qualquer push na branch master atualiza o site em produção

## Estrutura de arquivos
```
/
├── index.html       ← site principal (página pública)
├── site.html        ← cópia do index (pode remover futuramente)
├── branding.html    ← manual de marca (uso interno)
├── copy.html        ← deck de copy (uso interno)
└── images/
    ├── logo claro.jpeg    ← logo fundo branco (usar em fundos claros)
    ← logo escuro.jpeg   ← logo fundo verde escuro (usar em fundos escuros)
    ├── escritorio.jpeg    ← foto usada como fundo da seção mecanismo
    └── metodo.jpeg        ← foto usada na seção método
```

## Design system
- **Cor primária:** Jade `#00C896`
- **Verde profundo:** `#046A52`
- **Fundo escuro:** `#052E24`
- **Dourado (hover):** `#C9A24B`
- **Fontes:** Fraunces (títulos) + Inter (corpo) + JetBrains Mono (dados)

## Como atualizar o site
```bash
cd "C:/Users/arthu/Downloads/site_Copy_Branding_A3R Performar"
git add .
git commit -m "descrição da mudança"
git push
```
A Vercel detecta o push e publica automaticamente em segundos.

## Decisões tomadas
- `site.html` renomeado para `index.html` para Vercel servir como homepage
- Travessões (—) removidos do copy por decisão estética
- Ferramenta/plataforma chamada **PULSO**, consultoria chamada **BEXIN**
- Dourado `#C9A24B` usado exclusivamente em estados de hover
- Animações de scroll via IntersectionObserver (classe `.reveal`)
