# Livia Cardoso — Portfólio

Portfólio pessoal de Livia Cardoso, estudante de Administração na PUC-Campinas, construído para o processo AI Builder. O site reúne projetos de IA, dados e produto em uma página única, com visual inspirado no Ramp Design.

## O que tem no site

- **Abertura:** os projetos desfilam em 3D como telas das apresentações. Clicar abre a apresentação completa.
- **Projetos:** grade com RankUP, Aresta, BEES PRO, logic, Vênus e o artigo sobre poder na rede de IA. Cada projeto abre os slides, a stack e as habilidades desenvolvidas.
- **Pesquisa ao vivo (Graph RAG):** o ecossistema de IA do artigo como grafo interativo em D3.js. Perguntas em português disparam buscas no grafo (entidades, vizinhos, caminhos, rankings), acendem o subgrafo usado e geram uma resposta que cita cada relação com a fonte.
- **Sobre** e **Por onde ando:** resumo e fotos de eventos, palcos e hackathons.

## Estrutura

```
index.html      página única (HTML, CSS e JS inline; dados do grafo embutidos)
img/            slides dos projetos, fotos e imagens
vercel.json     configuração de deploy
```

## Rodar localmente

Abra o `index.html` com um servidor estático. Por exemplo:

```
npx serve .
```

## Deploy

Hospedado na Vercel. Cada push na branch `main` gera um novo deploy no mesmo endereço.

## Dados do grafo

Amostra de 31 relações extraída da base do artigo "Poder, dependência e intermediação no ecossistema global de IA" (PUC-Campinas, 2026). Grau, intermediação e comunidades (Louvain) são calculados sobre essa amostra.
