# Copa 2026 - Tabela de Jogos

Projeto estático em HTML/CSS/JavaScript com a tabela consolidada da Copa do Mundo FIFA 2026.

## Arquivos

- `copa-2026-tabela.html`: página principal com jogos, transmissões, classificação dos grupos e layout responsivo.
- `index.html`: entrada usada pelo GitHub Pages, redirecionando para `copa-2026-tabela.html`.
- `images/`: imagens usadas na coluna de transmissão.
  - `cazetv-logo-848x477.webp`
  - `Globo-300-1024x576.png`
  - `SBT_2014.webp`
  - `channels4_profile.jpg`

## Como abrir

Abra o arquivo abaixo diretamente no navegador:

```text
/Users/gempe/copa-2026/index.html
```

Não é necessário servidor local.

No GitHub Pages, publique a raiz do repositório. O arquivo `index.html` será carregado automaticamente e abrirá a tabela.

## Conteúdo

A página inclui:

- 104 jogos da competição.
- Datas no formato `DD/MM Dia-da-semana`.
- Confrontos exibidos com bandeira e sigla da seleção.
- Fase de grupos com `Data`, `Hora`, `Grupo`, `Rodada`, `Confronto` e `Transmissão`.
- Mata-mata com `Data`, `Hora`, `Fase`, `Confronto` e `Transmissão`.
- Badges coloridos por grupo.
- Badges coloridos por rodada:
  - 1ª rodada: `#00ff00`
  - 2ª rodada: `#b86414`
  - 3ª rodada: `#2b1a3e`
- Jogos da seleção brasileira destacados.
- Jogos do dia atual destacados com a cor `#799fbf`.

## Transmissões

- CazéTV aparece em todos os jogos.
- Grupo Globo aparece nos jogos definidos, marcada com `*`.
- SBT e NSports aparecem nos jogos definidos.

Legenda do Grupo Globo:

```text
* Grupo Globo: Globo, ge tv, Globoplay e SporTV.
```

## Responsividade

Foram definidos breakpoints para:

- até `479px`, incluindo telas próximas de `320px`;
- `480px` a `767px`;
- `768px` a `1023px`;
- acima de `1024px`;
- refinamento acima de `1200px`.

No mobile, a tabela de jogos esconde `Jogo`, mantendo os campos essenciais.

## Fontes

Dados consolidados a partir de:

- FIFA
- Gazeta Esportiva
- ge/Globo
- ESPN
