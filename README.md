# Consultor YouTube — Do Zero à Monetização

**Skill para ChatGPT em português do Brasil** que atua como consultor especializado em criação, produção, crescimento e monetização de canais do YouTube.

Ajuda usuários iniciantes ou experientes a trabalhar de forma organizada, **do planejamento do nicho à candidatura ao Programa de Parcerias do YouTube (YPP)**. Serve para canais **com apresentador**, **sem aparecer (faceless/dark)** ou híbridos.

> **Importante:** este projeto distribui uma *Skill do ChatGPT* (um conjunto de instruções e recursos). Não é um programa executável, extensão do navegador, conexão oficial com o YouTube, aplicativo publicado automaticamente no catálogo de Plugins, nem serviço que monetiza um canal sozinho. O ChatGPT pode orientar e preparar materiais; ações em contas e canais dependem dos acessos e ferramentas autorizados pelo usuário.

## O que a Skill faz

| Etapa | Principais atividades |
| --- | --- |
| 0 — Diagnóstico | Entender objetivo, recursos, experiência, nicho, país e formato do canal |
| 1 — Nicho e público | Comparar oportunidades e definir proposta de valor |
| 2 — Concorrência | Pesquisar canais comparáveis, padrões e lacunas de conteúdo |
| 3 — Canal e marca | Orientar nome, identidade visual, descrição, configurações e segurança |
| 4 — Planejamento | Criar pautas, pilares editoriais e cronograma de 30, 60 e 90 dias |
| 5 — Pré-produção | Roteiros completos, cenas, narração, títulos e conceitos de thumbnails |
| 6 — Produção | Orientar gravação, edição, legendas, licenças e publicação |
| 7 — Distribuição | Trabalhar Shorts, playlists, comunidade, colaboração e testes |
| 8 — YouTube Analytics | Interpretar CTR, retenção, horas de exibição, fontes de tráfego e evolução |
| 9 — Monetização | Conferir exigências oficiais, preparar candidatura ao YPP e estudar outras receitas |

O conteúdo foi estruturado a partir de **sete fluxos de trabalho**: análise de concorrentes, ideias originais, análise de roteiros, roteiros completos, thumbnails, títulos e análise de métricas. Os fluxos foram ampliados para cobrir o ciclo integral do canal.

## Instalação no ChatGPT

1. Baixe o arquivo [`skill.zip`](./skill.zip) disponível na raiz deste repositório. No GitHub, abra o arquivo e use a opção de baixar o arquivo bruto, quando disponível.
2. No ChatGPT, abra a seção de **Skills / Habilidades** (a localização exata pode variar conforme a interface e o plano).
3. Se estiver disponível a opção de **criar/importar/carregar uma Skill**, selecione o arquivo `skill.zip` e conclua as etapas indicadas.
4. Após a instalação, peça no chat algo como: **“Quero criar um canal do zero no YouTube. Use o Consultor YouTube e me oriente passo a passo.”**

**Se sua conta não oferecer importação de Skills**, consulte as opções de criação disponíveis nela. O arquivo `SKILL.md` documenta o comportamento da Skill, mas simplesmente publicar ou baixar o repositório **não instala automaticamente** um plugin no catálogo do ChatGPT.

## Como usar

A Skill pode atuar em duas modalidades:

**Acompanhamento completo:** parte do diagnóstico, apresenta um plano com marcos verificáveis e orienta a próxima ação sem obrigar o usuário a dominar termos técnicos.

**Pedido pontual:** entrega diretamente o material solicitado, sem exigir o cumprimento de todas as fases anteriores.

### Exemplos para copiar no chat

**1. Canal do zero**

> Quero criar um canal no YouTube sobre [tema], para [público], com [X] horas semanais e orçamento de [valor]. Quero [aparecer / não aparecer]. Prepare meu plano inicial e a primeira ação prática.

**2. Escolha de nicho**

> Compare três subnichos de [assunto] para um canal em português. Considere demanda, concorrência verificável, dificuldade de produção e monetização. Não invente números.

**3. Pesquisa de concorrentes**

> Analise dez canais do nicho [nicho], com referências verificáveis, e identifique padrões, formatos, lacunas e oportunidades originais.

**4. Calendário editorial**

> Crie 20 ideias de vídeos e um calendário de 90 dias para meu canal de [nicho], com vídeos longos e Shorts adequados à minha disponibilidade.

**5. Roteiro completo**

> Escreva um roteiro completo de oito minutos sobre [tema], com gancho inicial, narração, sugestões de cenas, transições, fontes a conferir e chamada para ação.

**6. Thumbnails e títulos**

> Para este roteiro [cole roteiro], desenvolva cinco conceitos de thumbnails e quinze títulos. Explique o público e a hipótese editorial de cada alternativa.

**7. Diagnóstico de desempenho**

> Vou informar os dados do meu YouTube Studio. Analise CTR, retenção, tempo de exibição, fontes de tráfego e inscritos. Priorize três testes para os próximos vídeos.

**8. Monetização**

> Avalie minha preparação para o Programa de Parcerias do YouTube no Brasil. Use as regras oficiais mais recentes, diferencie as modalidades de monetização e me dê um checklist de candidatura.

## Arquivos do projeto

```text
.
├── README.md                         # apresentação, instalação e exemplos
├── PUBLICACAO-GITHUB.md              # instruções para manter o projeto público
├── skill.zip                         # Skill pronta para importação
└── consultor-youtube-crescimento/
    ├── SKILL.md                      # instruções centrais da Skill
    ├── agents/openai.yaml            # nome e descrição na interface
    ├── references/
    │   ├── diagnostico-analytics.md
    │   ├── monetizacao-politicas.md
    │   ├── roteiro-operacional.md
    │   ├── roteiros-e-embalagem.md
    │   └── sete-fluxos-ia.md
    └── assets/
        ├── briefing-canal.md
        ├── calendario-90-dias.csv
        ├── checklist-publicacao.md
        └── controle-videos.csv
```

Os arquivos `.csv` podem ser abertos em planilhas para adaptação ao cronograma e aos dados reais de cada canal. O `skill.zip` contém somente os arquivos necessários para executar a Skill; os arquivos `README.md` e `PUBLICACAO-GITHUB.md` documentam o projeto no GitHub.

## Critérios de qualidade e limites

- Priorizar fontes oficiais do YouTube para **regras do YPP, direitos autorais, conteúdo sintético, requisitos e menus**. Revalidar requisitos antes de recomendar uma candidatura: números e políticas podem mudar.
- Não prometer inscritos, visualizações, renda ou aprovação na monetização.
- Não solicitar senhas, códigos de verificação ou tokens. Dados do YouTube Studio são opcionais e devem ser compartilhados conscientemente.
- Recomendar criação original, respeito a direitos autorais, uso responsável de IA e identificação adequada de conteúdo alterado quando exigido.
- Reconhecer dados indisponíveis; nunca apresentar estimativas como métricas observadas.

## Atualizações

Para modificar a Skill, edite os arquivos em `consultor-youtube-crescimento/`, valide a estrutura do `SKILL.md` e gere um novo `skill.zip` contendo apenas a pasta da Skill. Mantenha o pacote e as fontes na mesma versão.

## Direitos e licença

Este repositório é destinado à **consulta pública**, mas **não inclui, nesta versão, uma licença aberta de redistribuição ou modificação**. A visibilidade pública no GitHub não equivale à concessão de licença de uso. O responsável pelo repositório poderá adicionar uma licença posteriormente, se desejar.

O YouTube e o Google são marcas de seus respectivos titulares; este projeto não é afiliado, patrocinado nem endossado por eles.
