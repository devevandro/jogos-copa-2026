# Copa 2026 - Tabela de Jogos

Projeto estático em HTML/CSS/JavaScript com a tabela consolidada da Copa do Mundo FIFA 2026.

## Arquivos

- `copa-2026-tabela.html`: página principal com jogos, transmissões, classificação dos grupos e layout responsivo.
- `images/`: imagens usadas na coluna de transmissão.
  - `cazetv-logo-848x477.webp`
  - `Globo-300-1024x576.png`
  - `SBT_2014.webp`
  - `channels4_profile.jpg`

## Como abrir

Abra o arquivo abaixo diretamente no navegador:

```text
/Users/gempe/copa-2026/copa-2026-tabela.html
```

Não é necessário servidor local.

## Conteúdo

A página inclui:

- 104 jogos da competição.
- Fase de grupos com `Data`, `Hora`, `Grupo`, `Rodada`, `Confronto`, `Cidade`, `Estádio` e `Transmissão`.
- Mata-mata com `Data`, `Hora`, `Fase`, `Confronto`, `Cidade`, `Estádio` e `Transmissão`.
- Badges coloridos por grupo.
- Badges coloridos por rodada:
  - 1ª rodada: `#00ff00`
  - 2ª rodada: `#b86414`
  - 3ª rodada: `#2b1a3e`
- Jogos da seleção brasileira destacados.
- Tabela de classificação dos 12 grupos, escondida por padrão e exibida pelo botão `Tabela`.

## Transmissões

- CazéTV aparece em todos os jogos.
- Plataforma Globo aparece nos jogos definidos, marcada com `*`.
- SBT e NSports aparecem nos jogos definidos.

Legenda da Plataforma Globo:

```text
* Plataforma Globo: Globo, ge tv, Globoplay e SporTV.
```

## Responsividade

Foram definidos breakpoints para:

- até `479px`, incluindo telas próximas de `320px`;
- `480px` a `767px`;
- `768px` a `1023px`;
- acima de `1024px`;
- refinamento acima de `1200px`.

No mobile, a tabela de jogos esconde `Jogo`, `Cidade` e `Estádio`, mantendo os campos essenciais.

## Fontes

Dados consolidados a partir de:

- FIFA
- Gazeta Esportiva
- ge/Globo
- ESPN
