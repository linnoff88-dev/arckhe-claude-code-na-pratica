# Banco de Prompts â€” "Claude Code na PrÃ¡tica" (ARCKHÉ AI)

Banco de prompts, comandos e templates para o curso PT-BR, extraÃ­do e adaptado de material de terceiros.

**Notas de uso**
- Tudo foi **de-brandado**: removidos nomes prÃ³prios, comunidade exclusiva e links de afiliado. Onde houver personalizaÃ§Ã£o, use `[INSERIR ...]`.
- Prompts marcados **CANÃ”NICO** trazem tambÃ©m o original em **EN** em bloco separado â€” vale preservar o fraseado.
- Os prompts em PT-BR sÃ£o traduÃ§Ã£o fiel pronta para colar no Claude Code.
- "Quando usar" Ã© uma linha-guia; adapte ao seu contexto.
- NumeraÃ§Ã£o estÃ¡vel: **P01 â€¦ P42**. As duas visÃµes abaixo (Por mÃ³dulo / Por caso de uso) referenciam os mesmos IDs.

---

# Parte 1 â€” Por mÃ³dulo

## Boas-vindas (NÃ­vel 0)
O NÃ­vel 0 Ã© visÃ£o geral do curso, sem prompts executÃ¡veis. Comece pela Setup.

---

## Setup (NÃ­vel 1 â€” FundaÃ§Ã£o e Setup)

### P01 â€” Instalar o Claude Code
**Quando usar:** primeira instalaÃ§Ã£o numa mÃ¡quina nova.
```text
OlÃ¡! Quero que vocÃª instale o Claude Code no meu computador e instale tambÃ©m
qualquer outra dependÃªncia necessÃ¡ria para rodÃ¡-lo aqui. Quando terminar, me avise.
```
> EN: "Hey there, I would like you to install Claude Code onto my computer, and install any other dependencies that are required to run that on my computer. Once that's done, let me know."

### P02 â€” Teste de criaÃ§Ã£o de arquivos
**Quando usar:** validar que o Claude consegue criar pastas/arquivos no seu sistema.
```text
Crie para mim uma pasta chamada "cafe-gelado" na minha Ã¡rea de trabalho e escreva dois
arquivos dentro: um chamado "por-que-cafe-e-otimo" e outro "por-que-cafe-nao-e-otimo".
```
> EN: "Create for me a folder called iced coffee on my desktop, and write two files in that. One, why coffee is great. And the second, why coffee is not great."

### P03 â€” Conectar/reconectar o GitHub via CLI
**Quando usar:** quando a conexÃ£o com o GitHub caiu ou nunca foi feita.
```text
Quero que vocÃª consiga acessar meus repositÃ³rios do GitHub. Conecte-se ao GitHub pela CLI
e confirme. Se vocÃª nÃ£o estiver conectado, atualize/refaÃ§a essa conexÃ£o, por favor.
```

### P04 â€” Estilo de comunicaÃ§Ã£o (instruÃ§Ãµes para o Claude) â€” CANÃ”NICO
**Quando usar:** configurar como o Claude fala com vocÃª (vai no CLAUDE.md / system).
```text
Tom direto e informal â€” nada de enrolaÃ§Ã£o, nada de "corporativÃªs". Sem bullet points a
menos que eu peÃ§a. Sem travessÃµes (entrega de texto de IA). Nunca use palavras de
preenchimento como "certamente", "com certeza", "Ã³tima pergunta" ou "fico feliz em ajudar".
Mantenha o texto direto e focado em resultado, nÃ£o em features.
Antecipe problemas (olhe alÃ©m das curvas), desafie meu raciocÃ­nio, seja NÃƒO-bajulador
(nÃ£o concorde com tudo que eu disser) e seja mÃ¡ximo em busca da verdade.
Eu sou: [INSERIR 2 FRASES sobre vocÃª/seu trabalho].
```
> EN: "Direct and casual tone â€” no fluff, no corporate speak. No bullet points unless I ask. No em dashes (dead giveaway of AI writing). Never use filler words like 'certainly', 'absolutely', 'great question', or 'I'd be happy to'. Keep copy punchy and outcome-focused, not feature-focused. Look around corners, challenge my perspective, be non-sycophantic, and be maximally truth-seeking. I'm a [INSERT 2 SENTENCES]."

---

## MemÃ³ria (NÃ­vel 4 â€” Sistema de MemÃ³ria)

### P05 â€” Organizar a vida em "baldes" (buckets) â€” CANÃ”NICO
**Quando usar:** estruturar memÃ³ria de curto prazo a partir de tudo que vocÃª toca.
```text
Com base em tudo que vocÃª sabe sobre mim e em tudo em que eu trabalho, quero que vocÃª
organize a minha vida em seis a oito baldes/categorias.
```
> EN: "Based on everything you know about me and everything I work on, I want you to organize my life into six to eight buckets/categories."

### P06 â€” Materializar os baldes em pastas com CLAUDE.md
**Quando usar:** transformar os baldes em estrutura real de pastas.
```text
Crie para mim essas seis a oito pastas na minha Ã¡rea de trabalho, cada uma com um
arquivo CLAUDE.md dentro.
```

### P07 â€” Preencher o CLAUDE.md por projeto (briefing) â€” CANÃ”NICO
**Quando usar:** documentar o contexto completo de cada pasta/projeto.
```text
Adicione um CLAUDE.md em cada uma dessas pastas e depois me faÃ§a perguntas sobre cada
projeto, para eu te dar o briefing completo. Para cada projeto capture: o que Ã© a pasta;
qual Ã© o objetivo (ex.: "maximizar o valor que cada pessoa recebe, crescer a base");
por que ele existe; o stack; as decisÃµes (ex.: "nada de posts gerados por IA");
um mapa de memÃ³ria; e referÃªncias.
```
> EN: "Add this CLAUDE.md file in each of those folders, and then ask me questions about each one so I can give you the full project brief. For each: what the folder is; what the goal is; why it exists; the stack; the decisions; a memory map; and references."

### P08 â€” Regra de "salvar memÃ³ria" no CLAUDE.md â€” CANÃ”NICO
**Quando usar:** definir onde gravar conversas quando vocÃª pedir "salvar/wrap up".
```text
Quando eu pedir explicitamente para salvar, guardar, "fechar" (wrap up) ou lembrar a
conversa, salve aqui: [INSERIR LOCAL DA PASTA/WIKI]. HaverÃ¡ uma subpasta relevante para
o tema â€” escolha a subpasta correta e adicione essa informaÃ§Ã£o nela.
(Adicione isto na seÃ§Ã£o de memÃ³ria do CLAUDE.md.)
```
> EN: "When I explicitly ask you to save, store, wrap up, or remember the conversation, save it here. There will be a relevant subfolder related to the topic. Make sure you choose the correct subfolder and add that information into it."

### P09 â€” Skill de wrap-up para o Obsidian â€” CANÃ”NICO
**Quando usar:** ao fim de qualquer conversa, salvar a essÃªncia no wiki certo.
```text
Escreva para mim uma skill de "wrap-up": quando eu estiver tendo qualquer conversa com
qualquer modelo no meu computador, ela deve pegar a essÃªncia dessa conversa e guardÃ¡-la
no wiki relevante dentro do meu vault do Obsidian. Depois renomeie a skill para
"obsidian wrap-up".
```
> EN: "Write me a wrap-up skill: when I'm having any conversation with any model on my computer, it can take the essence of that conversation and store it in the relevant wiki within my Obsidian vault. Then change the name to 'obsidian wrap-up'."

### P10 â€” Skill "Obsidian Ask" (consulta ao wiki) â€” CANÃ”NICO
**Quando usar:** responder perguntas consultando seu segundo cÃ©rebro local.
```text
Tenho na minha Ã¡rea de trabalho uma pasta de vault do Obsidian com notas de tudo em que
trabalho. Crie uma skill chamada "obsidian ask". Sempre que eu te fizer uma pergunta
relacionada a qualquer coisa que eu faÃ§o, se for relevante consulte esse banco para uma
resposta especÃ­fica e siga todas as instruÃ§Ãµes que houver dentro dele.
```
> EN: "I have on my desktop an Obsidian vault folder with notes from everything I'm working on. Create a skill called 'Obsidian Ask'. Whenever I ask you a question to do with anything I'm doing, if relevant, query this database for a specific answer and follow all the instructions within it."

### P11 â€” MemÃ³ria de longo prazo com Pinecone â€” CANÃ”NICO
**Quando usar:** vetorizar o wiki e ter skills de wrap-up/ask vetoriais.
```text
Construa para mim uma skill com Pinecone. Vou te dar uma API key do Pinecone. Vetorize
tudo que existe dentro da minha pasta [INSERIR] do Obsidian e armazene no Pinecone
(crie um Ã­ndice/vault se nÃ£o existir). Depois construa uma skill de wrap-up: quando eu
acionÃ¡-la, pegue toda a essÃªncia da conversa e guarde numa pasta especÃ­fica dentro do
Pinecone. Adicione uma segunda skill, "ask Pinecone": quando eu pedir, consulte esse
banco e traga a informaÃ§Ã£o de volta para mim.
```
> EN: "Build me a skill with Pinecone. I'll give you a Pinecone API key. Vectorize everything within my Obsidian folder and store it in Pinecone (create a vault if it doesn't exist). Then build a wrap-up skill: when I trigger it, take the entire essence of the conversation and store it in a specific folder inside Pinecone. Add a second skill, 'ask Pinecone': when I ask, go to this database, query it, and bring back information for me."

---

## Power Features (NÃ­vel 3 â€” Skills, MCPs, Subagentes)

### P12 â€” Criar uma skill a partir de uma API â€” CANÃ”NICO
**Quando usar:** empacotar um processo repetÃ­vel (ex.: encurtador de URL) como skill.
```text
Quero criar uma skill com vocÃª. O processo Ã©: eu te dou [INSERIR ENTRADA, ex.: uma URL]
e vocÃª [INSERIR AÃ‡ÃƒO, ex.: converte em um link curto via Bitly]. (Se jÃ¡ existir uma skill
parecida e vocÃª quiser um build limpo, apague-a primeiro.) Me avise quando estiver pronto
para a minha API key. Em seguida, com essa API key, construa a skill.
```
> EN: "I would like to create a skill with you. I'd like a process in which I give you [INPUT], and you're going to [ACTION]. If a similar skill already exists, delete it first. Let me know when you're ready for my API key. Then, with this API key, create the skill."

### P13 â€” Inspecionar uma skill do marketplace
**Quando usar:** avaliar uma skill antes de adotar.
```text
Me fale sobre a skill [INSERIR NOME, ex.: brand guidelines] â€” quero entender o que ela
faz, depois quero testÃ¡-la e descobrir se funciona.
```

### P14 â€” Exportar skills para portabilidade
**Quando usar:** levar suas skills para outro ambiente/modelo.
```text
Salve todas as minhas skills na minha Ã¡rea de trabalho em uma pasta "Claude skills", com
instruÃ§Ãµes e todos os detalhes de cada skill, para eu poder levÃ¡-las para outro ambiente.
```

### P15 â€” Criar um MCP local a partir de uma API â€” CANÃ”NICO
**Quando usar:** expor uma API (ex.: YouTube Data) como ferramentas do Claude.
```text
Quero criar um MCP de [INSERIR SERVIÃ‡O, ex.: YouTube]. VocÃª jÃ¡ tem uma API key de
[INSERIR SERVIÃ‡O] neste sistema. Primeiro me dÃª uma lista das funcionalidades disponÃ­veis.
Depois construa para mim um MCP local â€” o mais Ãºtil para mim com base em tudo que vocÃª
sabe sobre mim. Em seguida, vÃ¡ em frente e construa.
```
> EN: "I would like to create a [SERVICE] MCP. You have a [SERVICE] API key on this system. Give me a list of the different functionalities you have, then create for me a local MCP â€” the one that would be most viable for me based on everything you know about me. Then build it."

### P16 â€” TrÃªs subagentes com veredito condensado â€” CANÃ”NICO
**Quando usar:** pesquisa multi-perspectiva paralela com sÃ­ntese Ãºnica.
```text
Quero que vocÃª pesquise sobre [INSERIR TEMA] e crie trÃªs subagentes. O subagente 1 olha
do ponto de vista de [INSERIR Ã‚NGULO 1]. O agente 2, da perspectiva de [INSERIR Ã‚NGULO 2].
O agente 3, de um Ã¢ngulo holÃ­stico/todos-os-lados [INSERIR Ã‚NGULO 3]. Seu trabalho Ã© olhar
todos e me dar uma visÃ£o condensada, rodando o mÃ¡ximo de iteraÃ§Ãµes possÃ­vel.
```
> EN: "I want you to do some research on [TOPIC] and create three sub-agents. Sub-agent one looks at it from a [ANGLE 1] point of view. Agent two from a [ANGLE 2] perspective. Agent three from a [ANGLE 3] angle. Your job is to look at all of them and give me a condensed view, with as many iterations as possible."

### P17 â€” Rotina de rascunho de e-mails
**Quando usar:** automatizar respostas da caixa de entrada.
```text
Quero que vocÃª verifique todos os meus e-mails da caixa de entrada e, para qualquer um que
nÃ£o tenha resposta nem rascunho e esteja nÃ£o lido, escreva um rascunho de resposta.
```

### P18 â€” Workflow de inquÃ©rito de cliente (gatilho via API) â€” CANÃ”NICO
**Quando usar:** reagir a leads que chegam pelo site.
```text
VocÃª vai receber informaÃ§Ãµes de um cliente que solicitou meus serviÃ§os pelo meu site.
Pegue o e-mail dele e escreva um rascunho de resposta. Depois agende um horÃ¡rio num slot
conveniente entre 9h e 17h no meu fuso horÃ¡rio.
```
> EN: "You're going to get information from a client who inquired for my services on my website. Take their email and draft them a reply for me. Then book some time at a convenient slot between 9:00 and 5:00 in my time zone."

### P19 â€” Loop de crÃ­tica com modelo externo â€” CANÃ”NICO
**Quando usar:** crÃ­tica e refino com uma segunda opiniÃ£o.
```text
Crie um agente de crÃ­tica e revise vocÃª mesmo o trabalho. Quando terminar, traga o
[INSERIR MODELO EXTERNO] com uma perspectiva fresca para checar.
```
> EN: "Create a critique agent and review it yourself. When that's done, bring in [EXTERNAL MODEL] with a fresh perspective to check it."

---

## Website (NÃ­vel 2 â€” Website Masterclass)

### P20 â€” Pesquisa de concorrentes com matriz de julgamento â€” CANÃ”NICO
**Quando usar:** mapear e ranquear os melhores concorrentes antes de construir.
```text
Quero criar um site para [INSERIR NEGÃ“CIO], que [INSERIR DESCRIÃ‡ÃƒO]. Use a conexÃ£o do
Firecrawl e encontre os melhores/mais bem-sucedidos [INSERIR CATEGORIA]. Vou operar em
[INSERIR GEOGRAFIA] (mas pode ser internacional). Identifique uma lista grande e depois
o top 5 â€” pode avaliar do jeito que quiser (Google reviews, ranqueamento de SEO, etc.).
Desenvolva uma matriz de julgamento para avaliar isso. Entregue um relatÃ³rio dos cinco e
uma anÃ¡lise profunda do que os cinco melhores tÃªm em comum que os cinco piores nÃ£o tÃªm,
para usarmos esses princÃ­pios. Me faÃ§a as perguntas que precisar para clarear o entendimento.
```
> EN: "I would like to create a website for [BUSINESS] that [DESCRIPTION]. Use the firecrawl connection to find the very best [CATEGORY] that are the most successful. I'm operating in [GEOGRAPHY]. Identify a big list, then the top five. Develop a judging matrix to assess them. Then deliver a report on those five and a deep analysis of what the five best have in common that the worst five don't. Ask me any questions you need to clarify your understanding."

### P21 â€” Internalizar o briefing antes de construir
**Quando usar:** depois de salvar a pesquisa num `melhores-principios.md` no projeto.
```text
Familiarize-se com o documento de melhores-princÃ­pios Ã  esquerda. Vamos construir juntos
um site que Ã© [INSERIR TIPO]. Me avise quando tiver entendido o briefing e aÃ­ comeÃ§amos.
```
> EN: "Familiarize yourself with the best-principles document on the left-hand side, and we're going to build a website together that is [TYPE]. Let me know when you've understood the brief, then we can get started and get building."

### P22 â€” Construir o site com inspiraÃ§Ã£o de um repo/HTML
**Quando usar:** usar um design system ou HTML baixado como inspiraÃ§Ã£o visual.
```text
Construa um site para [INSERIR TIPO] usando os melhores-princÃ­pios Ã  esquerda, mas com a
inspiraÃ§Ã£o de design deste repo do GitHub: [INSERIR URL DO REPO].
(Alternativa: use como inspiraÃ§Ã£o o HTML que eu acabei de baixar no computador.)
```

### P23 â€” VersÃµes em paralelo em pastas numeradas
**Quando usar:** gerar 2-3 variaÃ§Ãµes do mesmo site e escolher a melhor.
```text
Crie uma pasta Ã  esquerda chamada "[INSERIR NÃšMERO]" e coloque seus designs dentro.
(Repita com outros agentes/terminais para ter 2-3 sites em pastas diferentes.)
Quando terminar: abra para mim em um localhost.
```

### P24 â€” Salvar API key e gerar imagens da seÃ§Ã£o
**Quando usar:** guardar chave com seguranÃ§a e gerar imagens (hero, etc.).
```text
Guarde esta API key no meu computador de forma segura, de modo que vocÃª consiga acessÃ¡-la
no futuro. Depois gere imagens lindas de [INSERIR TIPO] â€” ou imagens que vocÃª ache
relevantes â€” para esta seÃ§Ã£o que vocÃª estÃ¡ implementando aqui.
```

### P25 â€” OtimizaÃ§Ã£o de SEO a partir de um repo â€” CANÃ”NICO
**Quando usar:** pesquisar keywords e aplicar SEO equilibrando atenÃ§Ã£o/conversÃ£o.
```text
Quero melhorar o SEO desta pÃ¡gina. Primeiro, entenda quais sÃ£o as keywords para as quais
eu quero ranquear nesta pÃ¡gina â€” busque um equilÃ­brio entre capturar atenÃ§Ã£o, converter
essa atenÃ§Ã£o e o ranqueamento de SEO. Use todos os insights deste repo do GitHub para
tornar isso realidade: [INSERIR URL DO REPO DE SEO]. Ao terminar, me dÃª uma lista detalhada
com marcaÃ§Ãµes verdes do que vocÃª fez, explicando cada melhoria; depois publique no GitHub
e na Vercel.
```
> EN: "I would like to improve the SEO of my webpage. First, understand the keywords I want to rank for on this page. Try to blend capturing attention and converting that attention with SEO ranking. Use all the insights within this GitHub repo to make that a reality. When done, give me a detailed list with green tick marks per change, then push it live to GitHub and Vercel."

### P26 â€” Aplicar princÃ­pios de UI/UX a fundo
**Quando usar:** refinar um site existente por checklist de design (em paralelo ao SEO).
```text
Quero usar este repo para melhorar este site â€” Ã© sobre UI e UX. Olhe todos os melhores
princÃ­pios e aplique-os sem dÃ³ ao meu site real. Vou ter um agente separado cuidando do
SEO, entÃ£o parte do texto pode mudar no caminho.
```

### P27 â€” RevisÃ£o crÃ­tica/adversarial do site â€” CANÃ”NICO
**Quando usar:** numa janela limpa, achar inconsistÃªncias de copy/design/UX.
```text
Quero que vocÃª atue como uma pessoa criticamente exigente. Percorra o site e encontre
inconsistÃªncias, textos que nÃ£o fazem sentido, design ruim, e volte com uma lista de
ideias classificadas em crÃ­tico, alto, mÃ©dio e baixo. VocÃª nÃ£o precisa inventar bugs
crÃ­ticos onde nÃ£o existem, mas olhe de verdade para me ajudar a melhorar â€” para deixar
este site o mais eficaz, honesto e bem-desenhado possÃ­vel. Traga qualquer repo do GitHub
que vocÃª ache necessÃ¡rio.
```
> EN: "I want you to act as a critically challenging individual. Go through the website and find inconsistencies, copy that doesn't make sense, design that looks bad, and come back with a list of critical, high, medium and low ideas. You don't have to find critical bugs where they don't exist, but really look at it to help me improve â€” so I can make this website as effective, honest, and well-designed as possible. Bring in any relevant GitHub repos you think are required."

---

## Apps (NÃ­vel 6 â€” Apps com Backend)

### P28 â€” FormulÃ¡rio de captura de leads â€” CANÃ”NICO
**Quando usar:** adicionar lead magnet com perguntas e salvar no banco.
```text
Adicione um formulÃ¡rio de captura de e-mail. PeÃ§a o nome, o e-mail e mais uma pergunta â€”
algo como "quanto dinheiro vocÃª estÃ¡ faturando", com cinco opÃ§Ãµes de R$0 atÃ© R$1 milhÃ£o+.
Depois adicione mais uma: "qual Ã© o maior problema que vocÃª tem agora?". Quando estiver
pronto, salve todas essas informaÃ§Ãµes no Supabase.
```
> EN: "Add in an email capture form. Ask for their name, their email, and one other question â€” something like 'how much money are you making', with five options from $0 up to $1 million plus. Then add one more: 'what is the biggest problem you have right now?' When that's done, save all of that information into Supabase."

### P29 â€” Sign-up, login e dashboard autenticado â€” CANÃ”NICO
**Quando usar:** construir backend autenticado com painel de valor.
```text
Agora quero uma seÃ§Ã£o de cadastro e login, toda autenticada e gerenciada no Supabase. O
usuÃ¡rio cria conta e entra. Ao entrar, quero ver o site dele em um dashboard lindo, no
mesmo estilo do site. Mostre mÃ©tricas diferentes, raspe alguns dados do site dele com um
script em background, rode anÃ¡lise de SEO (procure repos no GitHub que faÃ§am isso) e deixe
essa pÃ¡gina o mais valiosa humanamente possÃ­vel â€” tudo autenticado e conectado ao Supabase.
```
> EN: "I'd now like a sign-up and log-in section, all authenticated and managed in Supabase. When they sign in, I want to see their website in a beautiful dashboard in the exact same style as the website. Show different metrics, scrape some stuff from their website with a background script, run SEO analysis (look for GitHub repos that let us do that), and make that page as valuable as humanly possible â€” all authenticated and connected to Supabase."

### P30 â€” IntegraÃ§Ã£o de pagamentos com Stripe â€” CANÃ”NICO
**Quando usar:** adicionar planos pagos (standard/premium) ao app.
```text
Quero integrar o Stripe. No dashboard quero uma seÃ§Ã£o com cores: standard e premium. O
premium Ã© [INSERIR PREÃ‡O] por mÃªs. Me guie no setup do Stripe da forma mais sucinta
possÃ­vel, conferindo a documentaÃ§Ã£o mais recente, com instruÃ§Ãµes claras e nada mais longas
que o necessÃ¡rio. Eu te dou os arquivos necessÃ¡rios. Seu objetivo Ã© exigir o mÃ­nimo de mim
e, ao mesmo tempo, deixar tudo o mais seguro possÃ­vel.
```
> EN: "I'd like to integrate Stripe. In the dashboard I want a color-coded section: standard and premium. Premium is [PRICE] a month. Walk me through how to set up Stripe as succinctly as possible, checking the very latest documentation, with clear instructions no longer than they need to be. I'll give you the requisite files. Your objective is to require as little from me as possible while making it as secure as possible."

### P31 â€” Roteamento de modelo + rate limit (OpenRouter)
**Quando usar:** controlar o custo das features de IA do app.
```text
Para as features de IA, use a API key do OpenRouter. Use o modelo Sonnet atÃ© o usuÃ¡rio
atingir no mÃ¡ximo 10 mensagens por dia; a partir daÃ­, caia para um modelo mais barato.
Implemente rate limits para nÃ£o dar abuso e fique de olho no gasto total de crÃ©ditos.
```

### P32 â€” Copy de conversÃ£o via subagentes â€” CANÃ”NICO
**Quando usar:** pesquisa profunda de copy de conversÃ£o, sintetizada criticamente.
```text
Suba alguns subagentes. Pesquise a fundo as melhores prÃ¡ticas de copy para este tipo de
site, com o objetivo de converter. Veja quais sites estÃ£o arrasando neste segmento, o que
dÃ¡ para aprender e como melhorar o nosso copy para deixÃ¡-lo o mais eficaz possÃ­vel. Use
mÃºltiplos subagentes; analise criticamente os inputs deles e sintetize de forma que gere
um bom resultado. Seja minucioso e detalhado, mas nÃ£o superanalise.
```
> EN: "Spin up a couple of subagents. Go deep on research into the best practices for copy of this kind of website, with the objective to convert. Look at which websites are crushing it, what we can learn, and how we can improve our own copy. Use multiple subagents; critically analyze their inputs and synthesize them into a good output. Be thorough and detailed, but don't over-analyze."

---

## Build Anything (NÃ­vel 7)

### P33 â€” Raspagem de leads (Apify) â€” CANÃ”NICO
**Quando usar:** montar lista de prospects para prospecÃ§Ã£o.
```text
Quero mirar em [INSERIR NICHO] que ficam em [INSERIR LOCAL]. Use o Apify â€” encontre o
melhor actor/exemplo que conseguir â€” e me traga, de cada um: nome, e-mail, redes sociais
que achar e um fato interessante. Me traga [INSERIR NÃšMERO, ex.: 10] deles, para eu poder
conversar com eles. Coloque tudo num HTML bonito para eu visualizar.
```
> EN: "I would like to target [NICHE] that live in [LOCATION]. Use Apify, find the best example you can, and get me their name, email address, any social media, and one interesting fact about each. Get me [N] of those, so I can go have a conversation with them. Put this into a beautiful HTML for me."

### P34 â€” Dashboard de conteÃºdo "outlier" â€” CANÃ”NICO
**Quando usar:** descobrir conteÃºdo viral/outlier de um nicho com mÃ©tricas.
```text
Quero um dashboard que faÃ§a o seguinte. Resultado que eu quero verdadeiro: entender quais
sÃ£o os outliers â€” o conteÃºdo que estÃ¡ viralizando agora â€” e, a partir disso, saber quantas
visualizaÃ§Ãµes teve, curtidas, comentÃ¡rios, engajamento, duraÃ§Ã£o e quando foi postado.
Quero conseguir organizar por outlier. E quero saber quais criadores seguir â€” aliÃ¡s, sugira
alguns para mim.
```
> EN: "I want a dashboard that does X. The outcome I want true: understand the outliers â€” the content going viral right now â€” and from that, how many views, likes, comments, engagements, how long it is, and when it was posted. Let me organize it by outlier. And tell me which creators to follow â€” suggest some."

### P35 â€” Meta-prompt de "gargalo" para destravar â€” CANÃ”NICO
**Quando usar:** quando vocÃª nÃ£o sabe a soluÃ§Ã£o e quer pensar o problema junto.
```text
Isto Ã© o que eu estou tentando alcanÃ§ar: [INSERIR OBJETIVO]. Me faÃ§a perguntas para clarear
minhas intenÃ§Ãµes. E este Ã© o resultado desejado: [INSERIR RESULTADO]. Como eu devo pensar
melhor sobre o problema? E aÃ­ vamos pensar a soluÃ§Ã£o juntos.
```
> EN: "This is what I am trying to achieve: [GOAL]. Ask me questions to clarify my intentions, and this is my desired outcome: [OUTCOME]. How do I best think about the problem? And then we're going to think about the solution together."

### P36 â€” Validar/enriquecer e-mails via API
**Quando usar:** limpar uma lista de leads antes do outreach.
```text
Use a API key do [INSERIR VERIFICADOR DE E-MAIL] e valide todos os e-mails desta lista
para mim. API key: [INSERIR].
```

---

## Design Systems (NÃ­vel 8)

### P37 â€” Setup do framework de design (clonar e aprender) â€” CANÃ”NICO
**Quando usar:** iniciar um sistema de design-as-code para slides/sites.
```text
Quero criar slides lindos. Use o repo abaixo: instale, clone, aprenda tudo sobre ele, e
depois me dÃª alguns exemplos de marcas que eu poderia usar para construir slides bonitos.
[INSERIR URL DO REPO DO DESIGN SYSTEM]
```
> EN: "I want to create gorgeous slides. Use the repo below: install it, clone it, learn everything about it, then give me a couple of different brand examples I could use to build some beautiful slides."

### P38 â€” Deck no estilo de uma marca + imagens â€” CANÃ”NICO
**Quando usar:** gerar apresentaÃ§Ã£o alinhada Ã  marca de referÃªncia.
```text
Vamos construir um deck de [INSERIR N] pÃ¡ginas sobre [INSERIR MARCA]. VÃ¡ ao site da marca
pegar alguns assets e use minha API key do [INSERIR GERADOR DE IMAGEM] para gerar algumas
imagens alinhadas ao estilo de marca perfeito deles, como vocÃª achar adequado.
```
> EN: "Let's build a [N]-page slide deck on [BRAND]. Go to the website to grab a few assets, and use my [IMAGE-GEN] API key to generate a couple of images in line with their perfect brand style, as you see appropriate."

### P39 â€” Rodar a skill de extraÃ§Ã£o de marca
**Quando usar:** codificar cores, fontes, espaÃ§amento e layout de uma marca.
```text
Baixe isto, descompacte e siga as instruÃ§Ãµes. (A skill vai te perguntar qual Ã© a
marca/site e do que Ã© o seu negÃ³cio, e entÃ£o gerar um design blueprint capturando
espaÃ§amento, cores, fontes e princÃ­pios de layout.)
```

---

## Agente Pessoal (NÃ­vel 5 â€” "Sistema Operacional" de agentes)

### P40 â€” Instalar o sistema operacional de agentes
**Quando usar:** subir o pacote do agente pessoal (zip) e configurÃ¡-lo.
```text
Acabei de baixar este sistema operacional. Abra-o e siga as instruÃ§Ãµes, e fique Ã 
disposiÃ§Ã£o para me ajudar a configurar se for preciso. (Tudo que ele precisa para se
configurar e se conectar a este computador estÃ¡ no CLAUDE.md dentro do pacote.)
```

### P41 â€” Mission control: planejar metas â€” CANÃ”NICO
**Quando usar:** decompor uma meta de mÃ©dio prazo em passos acionÃ¡veis.
```text
Isto Ã© o "mission control" â€” planejamento de meta de mÃ©dio/longo prazo. Minha meta de
mÃ©dio prazo Ã©: [INSERIR META, ex.: "chegar a 500 inscritos" ou "lanÃ§ar uma lista de e-mail
com 1.000 pessoas"]. Converse comigo sobre tudo e depois quebre essa meta em cerca de 4 a 10
prompts individuais e sequenciais â€” marque quais sÃ£o para vocÃª (a IA) executar e quais sÃ£o
para mim â€” e monte um roadmap lindo que eu possa percorrer passo a passo.
```
> EN: "This is mission control â€” long-term goal planning. Give it a mid-term goal, e.g. 'get to 500 subscribers, or launch an email list with 1,000 people on it.' Break that down into between 4 to 10 individual, sequential prompts â€” some for the AI, some for me â€” and build a roadmap I can go through and complete."

### P42 â€” Backup diÃ¡rio do agente no GitHub
**Quando usar:** proteger toda a configuraÃ§Ã£o/memÃ³ria do agente.
```text
Conecte-se ao GitHub e faÃ§a um backup diÃ¡rio deste sistema inteiro, todos os dias, para que
â€” se algo der errado no meu computador ou eu cometer um erro â€” a gente possa voltar no tempo
e restaurar.
```

---

## Compliance (NÃ­vel 9 â€” Compliance e ManutenÃ§Ã£o)

### P43 â€” Red-team de seguranÃ§a ofensiva (mega prompt) â€” CANÃ”NICO
**Quando usar:** auditar a seguranÃ§a de um codebase/projeto antes de produÃ§Ã£o.
```text
VocÃª Ã© um engenheiro sÃªnior de seguranÃ§a ofensiva contratado para fazer red-team neste
codebase. Seu trabalho Ã© invadir, exfiltrar dados e quebrar o negÃ³cio. Seja paranoico e
minucioso â€” nÃ£o assuma nada. MÃ©todo: percorra o repositÃ³rio inteiro de forma sistemÃ¡tica.
Para cada arquivo que ler, pergunte: "Se eu fosse um atacante que jÃ¡ tem acesso de leitura,
o que eu faria com isto?". SuperfÃ­cies de ataque a cobrir: segredos e credenciais; seguranÃ§a
de banco (ex.: Supabase) e autorizaÃ§Ã£o; LLM / prompt injection; webhooks; dependÃªncias e
cadeia de suprimentos; logging e exposiÃ§Ã£o. SaÃ­da: achados ordenados por severidade, o
caminho do exploit e a correÃ§Ã£o concreta de cada um. NÃ£o escreva um scanner â€” recomende
poucos scanners open-source consagrados (ex.: Gitleaks, Semgrep, Trivy), diga quais trÃªs
adicionar ao meu pre-commit, e assuma que isso barra ~80% dos problemas.
```
> EN: "You are a senior offensive security engineer hired to red-team this codebase. Your job is to break in, exfiltrate data, and bankrupt the business. Be paranoid and thorough â€” assume nothing. Walk the entire repo systematically; for every file ask: 'If I were an attacker with read access, what would I do with this?' Cover: secrets & credentials; database security (e.g. Supabase) and authorization; LLM / prompt injection; webhooks; dependencies and supply chain; logging and exposure. Output: findings ranked by severity, the exploit path, and the concrete fix for each. Don't write a scanner â€” recommend battle-tested open-source scanners (e.g. Gitleaks, Semgrep, Trivy), tell me which three to add to my pre-commit, and assume that shuts down ~80% of the issues."

### P44 â€” API key via terminal (fora do chat)
**Quando usar:** evitar colar uma API key no log do Claude.
```text
Crie um comando de terminal para eu atualizar a minha API key de [INSERIR SERVIÃ‡O]. (Depois
rode esse comando vocÃª mesmo no terminal, de modo que o Claude nunca veja a chave em si.)
```

### P45 â€” Teto fixo de gasto em API
**Quando usar:** evitar prejuÃ­zo se uma chave vazar.
```text
Para qualquer API de custo variÃ¡vel, defina um teto de gasto fixo e rÃ­gido. Configure a
API key com um custo total que eu aceite e defina a frequÃªncia de renovaÃ§Ã£o. Limite o
gasto antes de limitar o risco.
```

### P46 â€” Mapa de health-check do sistema
**Quando usar:** garantir que o sistema continua funcionando ao longo do tempo.
```text
Pense no meu sistema inteiro e em toda a jornada do usuÃ¡rio, e defina quais devem ser os
health checks â€” o que um sistema funcional teria. Escreva isso como testes para eu saber
que continua funcionando. Inclua a checagem de logs de erro e do lado financeiro/pagamentos
(ex.: Stripe).
```

---

## MonetizaÃ§Ã£o (NÃ­vel 10 â€” "Making $$$")
Este mÃ³dulo Ã© majoritariamente estratÃ©gia de negÃ³cio (oferta, escada auditâ†’buildâ†’retain, ICP, "more/better/new"), sem prompts prÃ³prios de Claude Code. Use os prompts de prospecÃ§Ã£o (P33, P36) e construÃ§Ã£o (Apps/Website) aplicados ao seu funil.

---

## Painel / OS (NÃ­vel 11 â€” Claude Code + Sistema Operacional de Agentes)

### P47 â€” Adicionar uma ferramenta desconhecida ao OS
**Quando usar:** quando uma ferramenta sua nÃ£o foi detectada pelo agente pessoal.
```text
Eu uso [INSERIR FERRAMENTA/SISTEMA] e nÃ£o vejo isso no sistema operacional. VocÃª pode
adicionÃ¡-lo aqui para mim?
```

### P48 â€” Consultar o NotebookLM via agente
**Quando usar:** o agente busca/cria notebooks no Google NotebookLM.
```text
VocÃª tem a skill do NotebookLM no "pantheon" â€” fique totalmente atualizado com ela. VÃ¡ ao
meu NotebookLM, encontre o Ãºltimo infogrÃ¡fico que gerei e depois crie um notebook novo
sobre [INSERIR TEMA].
```

---

## Slash commands e comandos triviais (transversais)

NÃ£o sÃ£o prompts, mas fazem parte do fluxo de trabalho:
- `/init` (com effort alto) â€” fazer o Claude entender o codebase inteiro.
- `/clear` â€” resetar a conversa (evitar "context rot").
- `/context` â€” inspecionar o uso da janela de contexto.
- `/compact` â€” comprimir o contexto mantendo o essencial.
- `/model` â€” trocar entre Opus / Sonnet / Haiku.
- `/cost` â€” ver o gasto de tokens da sessÃ£o.
- `/agents` â€” gerenciar subagentes.
- `/memory` â€” abrir/editar os arquivos de memÃ³ria (CLAUDE.md).
- Invocar skills com `/<nome-da-skill>`.
- `/newbot` (no BotFather do Telegram) â€” criar um bot para o agente pessoal.

---

# Parte 2 â€” Por caso de uso

> Os mesmos prompts, agrupados pela tarefa. IDs cruzados com a Parte 1.

### Pesquisa / concorrÃªncia
- **P16** â€” TrÃªs subagentes com veredito condensado
- **P20** â€” Pesquisa de concorrentes com matriz de julgamento
- **P32** â€” Copy de conversÃ£o via subagentes
- **P34** â€” Dashboard de conteÃºdo "outlier"

### Briefing
- **P07** â€” Preencher o CLAUDE.md por projeto
- **P21** â€” Internalizar o briefing antes de construir
- **P35** â€” Meta-prompt de "gargalo" para destravar

### ConstruÃ§Ã£o
- **P02** â€” Teste de criaÃ§Ã£o de arquivos
- **P22** â€” Construir o site com inspiraÃ§Ã£o de repo/HTML
- **P23** â€” VersÃµes em paralelo em pastas numeradas
- **P24** â€” Salvar API key e gerar imagens
- **P28** â€” FormulÃ¡rio de captura de leads
- **P29** â€” Sign-up, login e dashboard autenticado
- **P30** â€” IntegraÃ§Ã£o de pagamentos com Stripe
- **P31** â€” Roteamento de modelo + rate limit (OpenRouter)

### Debugging
- **P19** â€” Loop de crÃ­tica com modelo externo
- **P35** â€” Meta-prompt de "gargalo" para destravar
- **P46** â€” Mapa de health-check do sistema

### Design
- **P26** â€” Aplicar princÃ­pios de UI/UX a fundo
- **P37** â€” Setup do framework de design (clonar e aprender)
- **P38** â€” Deck no estilo de uma marca + imagens
- **P39** â€” Rodar a skill de extraÃ§Ã£o de marca

### SEO
- **P25** â€” OtimizaÃ§Ã£o de SEO a partir de um repo
- **P29** â€” Dashboard com anÃ¡lise de SEO (componente)

### AutomaÃ§Ã£o
- **P12** â€” Criar uma skill a partir de uma API
- **P15** â€” Criar um MCP local a partir de uma API
- **P17** â€” Rotina de rascunho de e-mails
- **P18** â€” Workflow de inquÃ©rito de cliente
- **P41** â€” Mission control: planejar metas
- **P42** â€” Backup diÃ¡rio do agente no GitHub
- **P48** â€” Consultar o NotebookLM via agente

### MemÃ³ria / CLAUDE.md
- **P04** â€” Estilo de comunicaÃ§Ã£o (instruÃ§Ãµes para o Claude)
- **P05** â€” Organizar a vida em baldes
- **P06** â€” Materializar os baldes em pastas
- **P07** â€” Preencher o CLAUDE.md por projeto
- **P08** â€” Regra de "salvar memÃ³ria" no CLAUDE.md
- **P09** â€” Skill de wrap-up para o Obsidian
- **P10** â€” Skill "Obsidian Ask"
- **P11** â€” MemÃ³ria de longo prazo com Pinecone

### ProspecÃ§Ã£o / vendas
- **P18** â€” Workflow de inquÃ©rito de cliente
- **P33** â€” Raspagem de leads (Apify)
- **P36** â€” Validar/enriquecer e-mails via API

### Red-team
- **P27** â€” RevisÃ£o crÃ­tica/adversarial do site
- **P43** â€” Red-team de seguranÃ§a ofensiva (mega prompt)

### Setup
- **P01** â€” Instalar o Claude Code
- **P03** â€” Conectar/reconectar o GitHub via CLI
- **P13** â€” Inspecionar uma skill do marketplace
- **P14** â€” Exportar skills para portabilidade
- **P40** â€” Instalar o sistema operacional de agentes
- **P44** â€” API key via terminal (fora do chat)
- **P45** â€” Teto fixo de gasto em API
- **P47** â€” Adicionar uma ferramenta desconhecida ao OS
