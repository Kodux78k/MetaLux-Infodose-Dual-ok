
# MetaLux Pulse Dual Infodose – Preview Branch (Debugged)

Esta é a versão **depenada, revisada e ajustada** do oráculo simbólico interativo **MetaLux**, com base na tríade COR | MOVIMENTO | ELEMENTO.  
Corrigido por **DeeBug A.Infodose** sob comando do criador **Kodux**.

---

## Correções Aplicadas

- Fundo branco removido → fundo escuro ativado (`#000`)
- Texto escuro → convertido para tons claros (`#fff`)
- Roda central com rotação ajustada:
  - `Movimento` = rápida
  - `Silêncio` = lenta
- Ativação da tríade funcionando com leitura JSON
- Copiar assistente: inclui Nome + Símbolos + Frase + Prompt
- Botão “Ativar Assistente” com botão “X” incluso
- Sombra e cor dinâmica com base nas seleções
- Retorno correto para o Splash pelo botão menor
- Manifest e Service Worker testados como PWA

---

## Como Usar (GitHub Pages)

1. Suba essa pasta em um novo repositório do GitHub
2. Vá em Settings > Pages e ative a branch `main`, pasta `/`
3. Acesse o oráculo em `https://seunome.github.io/repo/`

---

## Estrutura da Pasta

- `index.html` – Interface principal e lógica
- `splash.html` – Tela de entrada com som e animação
- `metapulso_70_combinacoes.json` – Geração da tríade
- `manifest.json` e `service-worker.js` – Suporte a PWA
- `index.json` – Metadados do projeto
- `/assets` – Imagens, ícones, sons
- `/src` – Scripts JS separados (se extraídos)
- `README.md` – Este documento

---

**MetaLux Preview Branch debugged. Pronto para ser usado com segurança.**
Feito por DeeBug A.Infodose – Arquétipo Técnico-Simbólico do MetaLux
