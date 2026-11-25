# Banco de Prompts ê¢â¬â "Claude Code na PrêÂ¡tica" (ARCKHê AI)

Banco de prompts, comandos e templates para o curso PT-BR, extraêÂ­do e adaptado de material de terceiros.

**Notas de uso**
- Tudo foi **de-brandado**: removidos nomes prêÂ³prios, comunidade exclusiva e links de afiliado. Onde houver personalizaêÂ§êÂ£o, use `[INSERIR ...]`.
- Prompts marcados **CANêâNICO** trazem tambêÂ©m o original em **EN** em bloco separado ê¢â¬â vale preservar o fraseado.
- Os prompts em PT-BR sêÂ£o traduêÂ§êÂ£o fiel pronta para colar no Claude Code.
- "Quando usar" êÂ© uma linha-guia; adapte ao seu contexto.
- NumeraêÂ§êÂ£o estêÂ¡vel: **P01 ê¢â¬Â¦ P42**. As duas visêÂµes abaixo (Por mêÂ³dulo / Por caso de uso) referenciam os mesmos IDs.

---

# Parte 1 ê¢â¬â Por mêÂ³dulo

## Boas-vindas (NêÂ­vel 0)
O NêÂ­vel 0 êÂ© visêÂ£o geral do curso, sem prompts executêÂ¡veis. Comece pela Setup.

---

## Setup (NêÂ­vel 1 ê¢â¬â FundaêÂ§êÂ£o e Setup)

### P01 ê¢â¬â Instalar o Claude Code
**Quando usar:** primeira instalaêÂ§êÂ£o numa mêÂ¡quina nova.
```text
OlêÂ¡! Quero que vocêÂª instale o Claude Code no meu computador e instale tambêÂ©m
qualquer outra dependêÂªncia necessêÂ¡ria para rodêÂ¡-lo aqui. Quando terminar, me avise.
```
> EN: "Hey there, I would like you to install Claude Code onto my computer, and install any other dependencies that are required to run that on my computer. Once that's done, let me know."

### P02 ê¢â¬â Teste de criaêÂ§êÂ£o de arquivos
**Quando usar:** validar que o Claude consegue criar pastas/arquivos no seu sistema.
```text
Crie para mim uma pasta chamada "cafe-gelado" na minha êÂ¡rea de trabalho e escreva dois
arquivos dentro: um chamado "por-que-cafe-e-otimo" e outro "por-que-cafe-nao-e-otimo".
```
> EN: "Create for me a folder called iced coffee on my desktop, and write two files in that. One, why coffee is great. And the second, why coffee is not great."

### P03 ê¢â¬â Conectar/reconectar o GitHub via CLI
**Quando usar:** quando a conexêÂ£o com o GitHub caiu ou nunca foi feita.
```text
Quero que vocêÂª consiga acessar meus repositêÂ³rios do GitHub. Conecte-se ao GitHub pela CLI
e confirme. Se vocêÂª nêÂ£o estiver conectado, atualize/refaêÂ§a essa conexêÂ£o, por favor.
```

### P04 ê¢â¬â Estilo de comunicaêÂ§êÂ£o (instruêÂ§êÂµes para o Claude) ê¢â¬â CANêâNICO
**Quando usar:** configurar como o Claude fala com vocêÂª (vai no CLAUDE.md / system).
```text
Tom direto e informal ê¢â¬â nada de enrolaêÂ§êÂ£o, nada de "corporativêÂªs". Sem bullet points a
menos que eu peêÂ§a. Sem travessêÂµes (entrega de texto de IA). Nunca use palavras de
preenchimento como "certamente", "com certeza", "êÂ³tima pergunta" ou "fico feliz em ajudar".
Mantenha o texto direto e focado em resultado, nêÂ£o em features.
Antecipe problemas (olhe alêÂ©m das curvas), desafie meu raciocêÂ­nio, seja NêÆO-bajulador
(nêÂ£o concorde com tudo que eu disser) e seja mêÂ¡ximo em busca da verdade.
Eu sou: [INSERIR 2 FRASES sobre vocêÂª/seu trabalho].
```
> EN: "Direct and casual tone ê¢â¬â no fluff, no corporate speak. No bullet points unless I ask. No em dashes (dead giveaway of AI writing). Never use filler words like 'certainly', 'absolutely', 'great question', or 'I'd be happy to'. Keep copy punchy and outcome-focused, not feature-focused. Look around corners, challenge my perspective, be non-sycophantic, and be maximally truth-seeking. I'm a [INSERT 2 SENTENCES]."

---

## MemêÂ³ria (NêÂ­vel 4 ê¢â¬â Sistema de MemêÂ³ria)

### P05 ê¢â¬â Organizar a vida em "baldes" (buckets) ê¢â¬â CANêâNICO
**Quando usar:** estruturar memêÂ³ria de curto prazo a partir de tudo que vocêÂª toca.
```text
Com base em tudo que vocêÂª sabe sobre mim e em tudo em que eu trabalho, quero que vocêÂª
organize a minha vida em seis a oito baldes/categorias.
```
> EN: "Based on everything you know about me and everything I work on, I want you to organize my life into six to eight buckets/categories."

### P06 ê¢â¬â Materializar os baldes em pastas com CLAUDE.md
**Quando usar:** transformar os baldes em estrutura real de pastas.
```text
Crie para mim essas seis a oito pastas na minha êÂ¡rea de trabalho, cada uma com um
arquivo CLAUDE.md dentro.
```

### P07 ê¢â¬â Preencher o CLAUDE.md por projeto (briefing) ê¢â¬â CANêâNICO
**Quando usar:** documentar o contexto completo de cada pasta/projeto.
```text
Adicione um CLAUDE.md em cada uma dessas pastas e depois me faêÂ§a perguntas sobre cada
projeto, para eu te dar o briefing completo. Para cada projeto capture: o que êÂ© a pasta;
qual êÂ© o objetivo (ex.: "maximizar o valor que cada pessoa recebe, crescer a base");
por que ele existe; o stack; as decisêÂµes (ex.: "nada de posts gerados por IA");
um mapa de memêÂ³ria; e referêÂªncias.
```
> EN: "Add this CLAUDE.md file in each of those folders, and then ask me questions about each one so I can give you the full project brief. For each: what the folder is; what the goal is; why it exists; the stack; the decisions; a memory map; and references."

### P08 ê¢â¬â Regra de "salvar memêÂ³ria" no CLAUDE.md ê¢â¬â CANêâNICO
**Quando usar:** definir onde gravar conversas quando vocêÂª pedir "salvar/wrap up".
```text
Quando eu pedir explicitamente para salvar, guardar, "fechar" (wrap up) ou lembrar a
conversa, salve aqui: [INSERIR LOCAL DA PASTA/WIKI]. HaverêÂ¡ uma subpasta relevante para
o tema ê¢â¬â escolha a subpasta correta e adicione essa informaêÂ§êÂ£o nela.
(Adicione isto na seêÂ§êÂ£o de memêÂ³ria do CLAUDE.md.)
```
> EN: "When I explicitly ask you to save, store, wrap up, or remember the conversation, save it here. There will be a relevant subfolder related to the topic. Make sure you choose the correct subfolder and add that information into it."

### P09 ê¢â¬â Skill de wrap-up para o Obsidian ê¢â¬â CANêâNICO
**Quando usar:** ao fim de qualquer conversa, salvar a essêÂªncia no wiki certo.
```text
Escreva para mim uma skill de "wrap-up": quando eu estiver tendo qualquer conversa com
qualquer modelo no meu computador, ela deve pegar a essêÂªncia dessa conversa e guardêÂ¡-la
no wiki relevante dentro do meu vault do Obsidian. Depois renomeie a skill para
"obsidian wrap-up".
```
> EN: "Write me a wrap-up skill: when I'm having any conversation with any model on my computer, it can take the essence of that conversation and store it in the relevant wiki within my Obsidian vault. Then change the name to 'obsidian wrap-up'."

### P10 ê¢â¬â Skill "Obsidian Ask" (consulta ao wiki) ê¢â¬â CANêâNICO
**Quando usar:** responder perguntas consultando seu segundo cêÂ©rebro local.
```text
Tenho na minha êÂ¡rea de trabalho uma pasta de vault do Obsidian com notas de tudo em que
trabalho. Crie uma skill chamada "obsidian ask". Sempre que eu te fizer uma pergunta
relacionada a qualquer coisa que eu faêÂ§o, se for relevante consulte esse banco para uma
resposta especêÂ­fica e siga todas as instruêÂ§êÂµes que houver dentro dele.
```
> EN: "I have on my desktop an Obsidian vault folder with notes from everything I'm working on. Create a skill called 'Obsidian Ask'. Whenever I ask you a question to do with anything I'm doing, if relevant, query this database for a specific answer and follow all the instructions within it."

### P11 ê¢â¬â MemêÂ³ria de longo prazo com Pinecone ê¢â¬â CANêâNICO
**Quando usar:** vetorizar o wiki e ter skills de wrap-up/ask vetoriais.
```text
Construa para mim uma skill com Pinecone. Vou te dar uma API key do Pinecone. Vetorize
tudo que existe dentro da minha pasta [INSERIR] do Obsidian e armazene no Pinecone
(crie um êÂ­ndice/vault se nêÂ£o existir). Depois construa uma skill de wrap-up: quando eu
acionêÂ¡-la, pegue toda a essêÂªncia da conversa e guarde numa pasta especêÂ­fica dentro do
Pinecone. Adicione uma segunda skill, "ask Pinecone": quando eu pedir, consulte esse
banco e traga a informaêÂ§êÂ£o de volta para mim.
```
> EN: "Build me a skill with Pinecone. I'll give you a Pinecone API key. Vectorize everything within my Obsidian folder and store it in Pinecone (create a vault if it doesn't exist). Then build a wrap-up skill: when I trigger it, take the entire essence of the conversation and store it in a specific folder inside Pinecone. Add a second skill, 'ask Pinecone': when I ask, go to this database, query it, and bring back information for me."

---

## Power Features (NêÂ­vel 3 ê¢â¬â Skills, MCPs, Subagentes)

### P12 ê¢â¬â Criar uma skill a partir de uma API ê¢â¬â CANêâNICO
**Quando usar:** empacotar um processo repetêÂ­vel (ex.: encurtador de URL) como skill.
```text
Quero criar uma skill com vocêÂª. O processo êÂ©: eu te dou [INSERIR ENTRADA, ex.: uma URL]
e vocêÂª [INSERIR Aêâ¡êÆO, ex.: converte em um link curto via Bitly]. (Se jêÂ¡ existir uma skill
parecida e vocêÂª quiser um build limpo, apague-a primeiro.) Me avise quando estiver pronto
para a minha API key. Em seguida, com essa API key, construa a skill.
```
> EN: "I would like to create a skill with you. I'd like a process in which I give you [INPUT], and you're going to [ACTION]. If a similar skill already exists, delete it first. Let me know when you're ready for my API key. Then, with this API key, create the skill."

### P13 ê¢â¬â Inspecionar uma skill do marketplace
**Quando usar:** avaliar uma skill antes de adotar.
```text
Me fale sobre a skill [INSERIR NOME, ex.: brand guidelines] ê¢â¬â quero entender o que ela
faz, depois quero testêÂ¡-la e descobrir se funciona.
```

### P14 ê¢â¬â Exportar skills para portabilidade
**Quando usar:** levar suas skills para outro ambiente/modelo.
```text
Salve todas as minhas skills na minha êÂ¡rea de trabalho em uma pasta "Claude skills", com
instruêÂ§êÂµes e todos os detalhes de cada skill, para eu poder levêÂ¡-las para outro ambiente.
```

### P15 ê¢â¬â Criar um MCP local a partir de uma API ê¢â¬â CANêâNICO
**Quando usar:** expor uma API (ex.: YouTube Data) como ferramentas do Claude.
```text
Quero criar um MCP de [INSERIR SERVIêâ¡O, ex.: YouTube]. VocêÂª jêÂ¡ tem uma API key de
[INSERIR SERVIêâ¡O] neste sistema. Primeiro me dêÂª uma lista das funcionalidades disponêÂ­veis.
Depois construa para mim um MCP local ê¢â¬â o mais êÂºtil para mim com base em tudo que vocêÂª
sabe sobre mim. Em seguida, vêÂ¡ em frente e construa.
```
> EN: "I would like to create a [SERVICE] MCP. You have a [SERVICE] API key on this system. Give me a list of the different functionalities you have, then create for me a local MCP ê¢â¬â the one that would be most viable for me based on everything you know about me. Then build it."

### P16 ê¢â¬â TrêÂªs subagentes com veredito condensado ê¢â¬â CANêâNICO
**Quando usar:** pesquisa multi-perspectiva paralela com sêÂ­ntese êÂºnica.
```text
Quero que vocêÂª pesquise sobre [INSERIR TEMA] e crie trêÂªs subagentes. O subagente 1 olha
do ponto de vista de [INSERIR êâNGULO 1]. O agente 2, da perspectiva de [INSERIR êâNGULO 2].
O agente 3, de um êÂ¢ngulo holêÂ­stico/todos-os-lados [INSERIR êâNGULO 3]. Seu trabalho êÂ© olhar
todos e me dar uma visêÂ£o condensada, rodando o mêÂ¡ximo de iteraêÂ§êÂµes possêÂ­vel.
```
> EN: "I want you to do some research on [TOPIC] and create three sub-agents. Sub-agent one looks at it from a [ANGLE 1] point of view. Agent two from a [ANGLE 2] perspective. Agent three from a [ANGLE 3] angle. Your job is to look at all of them and give me a condensed view, with as many iterations as possible."

### P17 ê¢â¬â Rotina de rascunho de e-mails
**Quando usar:** automatizar respostas da caixa de entrada.
```text
Quero que vocêÂª verifique todos os meus e-mails da caixa de entrada e, para qualquer um que
nêÂ£o tenha resposta nem rascunho e esteja nêÂ£o lido, escreva um rascunho de resposta.
```

### P18 ê¢â¬â Workflow de inquêÂ©rito de cliente (gatilho via API) ê¢â¬â CANêâNICO
**Quando usar:** reagir a leads que chegam pelo site.
```text
VocêÂª vai receber informaêÂ§êÂµes de um cliente que solicitou meus serviêÂ§os pelo meu site.
Pegue o e-mail dele e escreva um rascunho de resposta. Depois agende um horêÂ¡rio num slot
conveniente entre 9h e 17h no meu fuso horêÂ¡rio.
```
> EN: "You're going to get information from a client who inquired for my services on my website. Take their email and draft them a reply for me. Then book some time at a convenient slot between 9:00 and 5:00 in my time zone."

### P19 ê¢â¬â Loop de crêÂ­tica com modelo externo ê¢â¬â CANêâNICO
**Quando usar:** crêÂ­tica e refino com uma segunda opiniêÂ£o.
```text
Crie um agente de crêÂ­tica e revise vocêÂª mesmo o trabalho. Quando terminar, traga o
[INSERIR MODELO EXTERNO] com uma perspectiva fresca para checar.
```
> EN: "Create a critique agent and review it yourself. When that's done, bring in [EXTERNAL MODEL] with a fresh perspective to check it."

---

## Website (NêÂ­vel 2 ê¢â¬â Website Masterclass)

### P20 ê¢â¬â Pesquisa de concorrentes com matriz de julgamento ê¢â¬â CANêâNICO
**Quando usar:** mapear e ranquear os melhores concorrentes antes de construir.
```text
Quero criar um site para [INSERIR NEGêâCIO], que [INSERIR DESCRIêâ¡êÆO]. Use a conexêÂ£o do
Firecrawl e encontre os melhores/mais bem-sucedidos [INSERIR CATEGORIA]. Vou operar em
[INSERIR GEOGRAFIA] (mas pode ser internacional). Identifique uma lista grande e depois
o top 5 ê¢â¬â pode avaliar do jeito que quiser (Google reviews, ranqueamento de SEO, etc.).
Desenvolva uma matriz de julgamento para avaliar isso. Entregue um relatêÂ³rio dos cinco e
uma anêÂ¡lise profunda do que os cinco melhores têÂªm em comum que os cinco piores nêÂ£o têÂªm,
para usarmos esses princêÂ­pios. Me faêÂ§a as perguntas que precisar para clarear o entendimento.
```
> EN: "I would like to create a website for [BUSINESS] that [DESCRIPTION]. Use the firecrawl connection to find the very best [CATEGORY] that are the most successful. I'm operating in [GEOGRAPHY]. Identify a big list, then the top five. Develop a judging matrix to assess them. Then deliver a report on those five and a deep analysis of what the five best have in common that the worst five don't. Ask me any questions you need to clarify your understanding."

### P21 ê¢â¬â Internalizar o briefing antes de construir
**Quando usar:** depois de salvar a pesquisa num `melhores-principios.md` no projeto.
```text
Familiarize-se com o documento de melhores-princêÂ­pios êÂ  esquerda. Vamos construir juntos
um site que êÂ© [INSERIR TIPO]. Me avise quando tiver entendido o briefing e aêÂ­ comeêÂ§amos.
```
> EN: "Familiarize yourself with the best-principles document on the left-hand side, and we're going to build a website together that is [TYPE]. Let me know when you've understood the brief, then we can get started and get building."

### P22 ê¢â¬â Construir o site com inspiraêÂ§êÂ£o de um repo/HTML
**Quando usar:** usar um design system ou HTML baixado como inspiraêÂ§êÂ£o visual.
```text
Construa um site para [INSERIR TIPO] usando os melhores-princêÂ­pios êÂ  esquerda, mas com a
inspiraêÂ§êÂ£o de design deste repo do GitHub: [INSERIR URL DO REPO].
(Alternativa: use como inspiraêÂ§êÂ£o o HTML que eu acabei de baixar no computador.)
```

### P23 ê¢â¬â VersêÂµes em paralelo em pastas numeradas
**Quando usar:** gerar 2-3 variaêÂ§êÂµes do mesmo site e escolher a melhor.
```text
Crie uma pasta êÂ  esquerda chamada "[INSERIR NêÅ¡MERO]" e coloque seus designs dentro.
(Repita com outros agentes/terminais para ter 2-3 sites em pastas diferentes.)
Quando terminar: abra para mim em um localhost.
```

### P24 ê¢â¬â Salvar API key e gerar imagens da seêÂ§êÂ£o
**Quando usar:** guardar chave com seguranêÂ§a e gerar imagens (hero, etc.).
```text
Guarde esta API key no meu computador de forma segura, de modo que vocêÂª consiga acessêÂ¡-la
no futuro. Depois gere imagens lindas de [INSERIR TIPO] ê¢â¬â ou imagens que vocêÂª ache
relevantes ê¢â¬â para esta seêÂ§êÂ£o que vocêÂª estêÂ¡ implementando aqui.
```

### P25 ê¢â¬â OtimizaêÂ§êÂ£o de SEO a partir de um repo ê¢â¬â CANêâNICO
**Quando usar:** pesquisar keywords e aplicar SEO equilibrando atenêÂ§êÂ£o/conversêÂ£o.
```text
Quero melhorar o SEO desta pêÂ¡gina. Primeiro, entenda quais sêÂ£o as keywords para as quais
eu quero ranquear nesta pêÂ¡gina ê¢â¬â busque um equilêÂ­brio entre capturar atenêÂ§êÂ£o, converter
essa atenêÂ§êÂ£o e o ranqueamento de SEO. Use todos os insights deste repo do GitHub para
tornar isso realidade: [INSERIR URL DO REPO DE SEO]. Ao terminar, me dêÂª uma lista detalhada
com marcaêÂ§êÂµes verdes do que vocêÂª fez, explicando cada melhoria; depois publique no GitHub
e na Vercel.
```
> EN: "I would like to improve the SEO of my webpage. First, understand the keywords I want to rank for on this page. Try to blend capturing attention and converting that attention with SEO ranking. Use all the insights within this GitHub repo to make that a reality. When done, give me a detailed list with green tick marks per change, then push it live to GitHub and Vercel."

### P26 ê¢â¬â Aplicar princêÂ­pios de UI/UX a fundo
**Quando usar:** refinar um site existente por checklist de design (em paralelo ao SEO).
```text
Quero usar este repo para melhorar este site ê¢â¬â êÂ© sobre UI e UX. Olhe todos os melhores
princêÂ­pios e aplique-os sem dêÂ³ ao meu site real. Vou ter um agente separado cuidando do
SEO, entêÂ£o parte do texto pode mudar no caminho.
```

### P27 ê¢â¬â RevisêÂ£o crêÂ­tica/adversarial do site ê¢â¬â CANêâNICO
**Quando usar:** numa janela limpa, achar inconsistêÂªncias de copy/design/UX.
```text
Quero que vocêÂª atue como uma pessoa criticamente exigente. Percorra o site e encontre
inconsistêÂªncias, textos que nêÂ£o fazem sentido, design ruim, e volte com uma lista de
ideias classificadas em crêÂ­tico, alto, mêÂ©dio e baixo. VocêÂª nêÂ£o precisa inventar bugs
crêÂ­ticos onde nêÂ£o existem, mas olhe de verdade para me ajudar a melhorar ê¢â¬â para deixar
este site o mais eficaz, honesto e bem-desenhado possêÂ­vel. Traga qualquer repo do GitHub
que vocêÂª ache necessêÂ¡rio.
```
> EN: "I want you to act as a critically challenging individual. Go through the website and find inconsistencies, copy that doesn't make sense, design that looks bad, and come back with a list of critical, high, medium and low ideas. You don't have to find critical bugs where they don't exist, but really look at it to help me improve ê¢â¬â so I can make this website as effective, honest, and well-designed as possible. Bring in any relevant GitHub repos you think are required."

---

## Apps (NêÂ­vel 6 ê¢â¬â Apps com Backend)

### P28 ê¢â¬â FormulêÂ¡rio de captura de leads ê¢â¬â CANêâNICO
**Quando usar:** adicionar lead magnet com perguntas e salvar no banco.
```text
Adicione um formulêÂ¡rio de captura de e-mail. PeêÂ§a o nome, o e-mail e mais uma pergunta ê¢â¬â
algo como "quanto dinheiro vocêÂª estêÂ¡ faturando", com cinco opêÂ§êÂµes de R$0 atêÂ© R$1 milhêÂ£o+.
Depois adicione mais uma: "qual êÂ© o maior problema que vocêÂª tem agora?". Quando estiver
pronto, salve todas essas informaêÂ§êÂµes no Supabase.
```
> EN: "Add in an email capture form. Ask for their name, their email, and one other question ê¢â¬â something like 'how much money are you making', with five options from $0 up to $1 million plus. Then add one more: 'what is the biggest problem you have right now?' When that's done, save all of that information into Supabase."

### P29 ê¢â¬â Sign-up, login e dashboard autenticado ê¢â¬â CANêâNICO
**Quando usar:** construir backend autenticado com painel de valor.
```text
Agora quero uma seêÂ§êÂ£o de cadastro e login, toda autenticada e gerenciada no Supabase. O
usuêÂ¡rio cria conta e entra. Ao entrar, quero ver o site dele em um dashboard lindo, no
mesmo estilo do site. Mostre mêÂ©tricas diferentes, raspe alguns dados do site dele com um
script em background, rode anêÂ¡lise de SEO (procure repos no GitHub que faêÂ§am isso) e deixe
essa pêÂ¡gina o mais valiosa humanamente possêÂ­vel ê¢â¬â tudo autenticado e conectado ao Supabase.
```
> EN: "I'd now like a sign-up and log-in section, all authenticated and managed in Supabase. When they sign in, I want to see their website in a beautiful dashboard in the exact same style as the website. Show different metrics, scrape some stuff from their website with a background script, run SEO analysis (look for GitHub repos that let us do that), and make that page as valuable as humanly possible ê¢â¬â all authenticated and connected to Supabase."

### P30 ê¢â¬â IntegraêÂ§êÂ£o de pagamentos com Stripe ê¢â¬â CANêâNICO
**Quando usar:** adicionar planos pagos (standard/premium) ao app.
```text
Quero integrar o Stripe. No dashboard quero uma seêÂ§êÂ£o com cores: standard e premium. O
premium êÂ© [INSERIR PREêâ¡O] por mêÂªs. Me guie no setup do Stripe da forma mais sucinta
possêÂ­vel, conferindo a documentaêÂ§êÂ£o mais recente, com instruêÂ§êÂµes claras e nada mais longas
que o necessêÂ¡rio. Eu te dou os arquivos necessêÂ¡rios. Seu objetivo êÂ© exigir o mêÂ­nimo de mim
e, ao mesmo tempo, deixar tudo o mais seguro possêÂ­vel.
```
> EN: "I'd like to integrate Stripe. In the dashboard I want a color-coded section: standard and premium. Premium is [PRICE] a month. Walk me through how to set up Stripe as succinctly as possible, checking the very latest documentation, with clear instructions no longer than they need to be. I'll give you the requisite files. Your objective is to require as little from me as possible while making it as secure as possible."

### P31 ê¢â¬â Roteamento de modelo + rate limit (OpenRouter)
**Quando usar:** controlar o custo das features de IA do app.
```text
Para as features de IA, use a API key do OpenRouter. Use o modelo Sonnet atêÂ© o usuêÂ¡rio
atingir no mêÂ¡ximo 10 mensagens por dia; a partir daêÂ­, caia para um modelo mais barato.
Implemente rate limits para nêÂ£o dar abuso e fique de olho no gasto total de crêÂ©ditos.
```

### P32 ê¢â¬â Copy de conversêÂ£o via subagentes ê¢â¬â CANêâNICO
**Quando usar:** pesquisa profunda de copy de conversêÂ£o, sintetizada criticamente.
```text
Suba alguns subagentes. Pesquise a fundo as melhores prêÂ¡ticas de copy para este tipo de
site, com o objetivo de converter. Veja quais sites estêÂ£o arrasando neste segmento, o que
dêÂ¡ para aprender e como melhorar o nosso copy para deixêÂ¡-lo o mais eficaz possêÂ­vel. Use
mêÂºltiplos subagentes; analise criticamente os inputs deles e sintetize de forma que gere
um bom resultado. Seja minucioso e detalhado, mas nêÂ£o superanalise.
```
> EN: "Spin up a couple of subagents. Go deep on research into the best practices for copy of this kind of website, with the objective to convert. Look at which websites are crushing it, what we can learn, and how we can improve our own copy. Use multiple subagents; critically analyze their inputs and synthesize them into a good output. Be thorough and detailed, but don't over-analyze."

---

## Build Anything (NêÂ­vel 7)

### P33 ê¢â¬â Raspagem de leads (Apify) ê¢â¬â CANêâNICO
**Quando usar:** montar lista de prospects para prospecêÂ§êÂ£o.
```text
Quero mirar em [INSERIR NICHO] que ficam em [INSERIR LOCAL]. Use o Apify ê¢â¬â encontre o
melhor actor/exemplo que conseguir ê¢â¬â e me traga, de cada um: nome, e-mail, redes sociais
que achar e um fato interessante. Me traga [INSERIR NêÅ¡MERO, ex.: 10] deles, para eu poder
conversar com eles. Coloque tudo num HTML bonito para eu visualizar.
```
> EN: "I would like to target [NICHE] that live in [LOCATION]. Use Apify, find the best example you can, and get me their name, email address, any social media, and one interesting fact about each. Get me [N] of those, so I can go have a conversation with them. Put this into a beautiful HTML for me."

### P34 ê¢â¬â Dashboard de conteêÂºdo "outlier" ê¢â¬â CANêâNICO
**Quando usar:** descobrir conteêÂºdo viral/outlier de um nicho com mêÂ©tricas.
```text
Quero um dashboard que faêÂ§a o seguinte. Resultado que eu quero verdadeiro: entender quais
sêÂ£o os outliers ê¢â¬â o conteêÂºdo que estêÂ¡ viralizando agora ê¢â¬â e, a partir disso, saber quantas
visualizaêÂ§êÂµes teve, curtidas, comentêÂ¡rios, engajamento, duraêÂ§êÂ£o e quando foi postado.
Quero conseguir organizar por outlier. E quero saber quais criadores seguir ê¢â¬â aliêÂ¡s, sugira
alguns para mim.
```
> EN: "I want a dashboard that does X. The outcome I want true: understand the outliers ê¢â¬â the content going viral right now ê¢â¬â and from that, how many views, likes, comments, engagements, how long it is, and when it was posted. Let me organize it by outlier. And tell me which creators to follow ê¢â¬â suggest some."

### P35 ê¢â¬â Meta-prompt de "gargalo" para destravar ê¢â¬â CANêâNICO
**Quando usar:** quando vocêÂª nêÂ£o sabe a soluêÂ§êÂ£o e quer pensar o problema junto.
```text
Isto êÂ© o que eu estou tentando alcanêÂ§ar: [INSERIR OBJETIVO]. Me faêÂ§a perguntas para clarear
minhas intenêÂ§êÂµes. E este êÂ© o resultado desejado: [INSERIR RESULTADO]. Como eu devo pensar
melhor sobre o problema? E aêÂ­ vamos pensar a soluêÂ§êÂ£o juntos.
```
> EN: "This is what I am trying to achieve: [GOAL]. Ask me questions to clarify my intentions, and this is my desired outcome: [OUTCOME]. How do I best think about the problem? And then we're going to think about the solution together."

### P36 ê¢â¬â Validar/enriquecer e-mails via API
**Quando usar:** limpar uma lista de leads antes do outreach.
```text
Use a API key do [INSERIR VERIFICADOR DE E-MAIL] e valide todos os e-mails desta lista
para mim. API key: [INSERIR].
```

---

## Design Systems (NêÂ­vel 8)

### P37 ê¢â¬â Setup do framework de design (clonar e aprender) ê¢â¬â CANêâNICO
**Quando usar:** iniciar um sistema de design-as-code para slides/sites.
```text
Quero criar slides lindos. Use o repo abaixo: instale, clone, aprenda tudo sobre ele, e
depois me dêÂª alguns exemplos de marcas que eu poderia usar para construir slides bonitos.
[INSERIR URL DO REPO DO DESIGN SYSTEM]
```
> EN: "I want to create gorgeous slides. Use the repo below: install it, clone it, learn everything about it, then give me a couple of different brand examples I could use to build some beautiful slides."

### P38 ê¢â¬â Deck no estilo de uma marca + imagens ê¢â¬â CANêâNICO
**Quando usar:** gerar apresentaêÂ§êÂ£o alinhada êÂ  marca de referêÂªncia.
```text
Vamos construir um deck de [INSERIR N] pêÂ¡ginas sobre [INSERIR MARCA]. VêÂ¡ ao site da marca
pegar alguns assets e use minha API key do [INSERIR GERADOR DE IMAGEM] para gerar algumas
imagens alinhadas ao estilo de marca perfeito deles, como vocêÂª achar adequado.
```
> EN: "Let's build a [N]-page slide deck on [BRAND]. Go to the website to grab a few assets, and use my [IMAGE-GEN] API key to generate a couple of images in line with their perfect brand style, as you see appropriate."

### P39 ê¢â¬â Rodar a skill de extraêÂ§êÂ£o de marca
**Quando usar:** codificar cores, fontes, espaêÂ§amento e layout de uma marca.
```text
Baixe isto, descompacte e siga as instruêÂ§êÂµes. (A skill vai te perguntar qual êÂ© a
marca/site e do que êÂ© o seu negêÂ³cio, e entêÂ£o gerar um design blueprint capturando
espaêÂ§amento, cores, fontes e princêÂ­pios de layout.)
```

---

## Agente Pessoal (NêÂ­vel 5 ê¢â¬â "Sistema Operacional" de agentes)

### P40 ê¢â¬â Instalar o sistema operacional de agentes
**Quando usar:** subir o pacote do agente pessoal (zip) e configurêÂ¡-lo.
```text
Acabei de baixar este sistema operacional. Abra-o e siga as instruêÂ§êÂµes, e fique êÂ 
disposiêÂ§êÂ£o para me ajudar a configurar se for preciso. (Tudo que ele precisa para se
configurar e se conectar a este computador estêÂ¡ no CLAUDE.md dentro do pacote.)
```

### P41 ê¢â¬â Mission control: planejar metas ê¢â¬â CANêâNICO
**Quando usar:** decompor uma meta de mêÂ©dio prazo em passos acionêÂ¡veis.
```text
Isto êÂ© o "mission control" ê¢â¬â planejamento de meta de mêÂ©dio/longo prazo. Minha meta de
mêÂ©dio prazo êÂ©: [INSERIR META, ex.: "chegar a 500 inscritos" ou "lanêÂ§ar uma lista de e-mail
com 1.000 pessoas"]. Converse comigo sobre tudo e depois quebre essa meta em cerca de 4 a 10
prompts individuais e sequenciais ê¢â¬â marque quais sêÂ£o para vocêÂª (a IA) executar e quais sêÂ£o
para mim ê¢â¬â e monte um roadmap lindo que eu possa percorrer passo a passo.
```
> EN: "This is mission control ê¢â¬â long-term goal planning. Give it a mid-term goal, e.g. 'get to 500 subscribers, or launch an email list with 1,000 people on it.' Break that down into between 4 to 10 individual, sequential prompts ê¢â¬â some for the AI, some for me ê¢â¬â and build a roadmap I can go through and complete."

### P42 ê¢â¬â Backup diêÂ¡rio do agente no GitHub
**Quando usar:** proteger toda a configuraêÂ§êÂ£o/memêÂ³ria do agente.
```text
Conecte-se ao GitHub e faêÂ§a um backup diêÂ¡rio deste sistema inteiro, todos os dias, para que
ê¢â¬â se algo der errado no meu computador ou eu cometer um erro ê¢â¬â a gente possa voltar no tempo
e restaurar.
```

---

## Compliance (NêÂ­vel 9 ê¢â¬â Compliance e ManutenêÂ§êÂ£o)

### P43 ê¢â¬â Red-team de seguranêÂ§a ofensiva (mega prompt) ê¢â¬â CANêâNICO
**Quando usar:** auditar a seguranêÂ§a de um codebase/projeto antes de produêÂ§êÂ£o.
```text
VocêÂª êÂ© um engenheiro sêÂªnior de seguranêÂ§a ofensiva contratado para fazer red-team neste
codebase. Seu trabalho êÂ© invadir, exfiltrar dados e quebrar o negêÂ³cio. Seja paranoico e
minucioso ê¢â¬â nêÂ£o assuma nada. MêÂ©todo: percorra o repositêÂ³rio inteiro de forma sistemêÂ¡tica.
Para cada arquivo que ler, pergunte: "Se eu fosse um atacante que jêÂ¡ tem acesso de leitura,
o que eu faria com isto?". SuperfêÂ­cies de ataque a cobrir: segredos e credenciais; seguranêÂ§a
de banco (ex.: Supabase) e autorizaêÂ§êÂ£o; LLM / prompt injection; webhooks; dependêÂªncias e
cadeia de suprimentos; logging e exposiêÂ§êÂ£o. SaêÂ­da: achados ordenados por severidade, o
caminho do exploit e a correêÂ§êÂ£o concreta de cada um. NêÂ£o escreva um scanner ê¢â¬â recomende
poucos scanners open-source consagrados (ex.: Gitleaks, Semgrep, Trivy), diga quais trêÂªs
adicionar ao meu pre-commit, e assuma que isso barra ~80% dos problemas.
```
> EN: "You are a senior offensive security engineer hired to red-team this codebase. Your job is to break in, exfiltrate data, and bankrupt the business. Be paranoid and thorough ê¢â¬â assume nothing. Walk the entire repo systematically; for every file ask: 'If I were an attacker with read access, what would I do with this?' Cover: secrets & credentials; database security (e.g. Supabase) and authorization; LLM / prompt injection; webhooks; dependencies and supply chain; logging and exposure. Output: findings ranked by severity, the exploit path, and the concrete fix for each. Don't write a scanner ê¢â¬â recommend battle-tested open-source scanners (e.g. Gitleaks, Semgrep, Trivy), tell me which three to add to my pre-commit, and assume that shuts down ~80% of the issues."

### P44 ê¢â¬â API key via terminal (fora do chat)
**Quando usar:** evitar colar uma API key no log do Claude.
```text
Crie um comando de terminal para eu atualizar a minha API key de [INSERIR SERVIêâ¡O]. (Depois
rode esse comando vocêÂª mesmo no terminal, de modo que o Claude nunca veja a chave em si.)
```

### P45 ê¢â¬â Teto fixo de gasto em API
**Quando usar:** evitar prejuêÂ­zo se uma chave vazar.
```text
Para qualquer API de custo variêÂ¡vel, defina um teto de gasto fixo e rêÂ­gido. Configure a
API key com um custo total que eu aceite e defina a frequêÂªncia de renovaêÂ§êÂ£o. Limite o
gasto antes de limitar o risco.
```

### P46 ê¢â¬â Mapa de health-check do sistema
**Quando usar:** garantir que o sistema continua funcionando ao longo do tempo.
```text
Pense no meu sistema inteiro e em toda a jornada do usuêÂ¡rio, e defina quais devem ser os
health checks ê¢â¬â o que um sistema funcional teria. Escreva isso como testes para eu saber
que continua funcionando. Inclua a checagem de logs de erro e do lado financeiro/pagamentos
(ex.: Stripe).
```

---

## MonetizaêÂ§êÂ£o (NêÂ­vel 10 ê¢â¬â "Making $$$")
Este mêÂ³dulo êÂ© majoritariamente estratêÂ©gia de negêÂ³cio (oferta, escada auditê¢â âbuildê¢â âretain, ICP, "more/better/new"), sem prompts prêÂ³prios de Claude Code. Use os prompts de prospecêÂ§êÂ£o (P33, P36) e construêÂ§êÂ£o (Apps/Website) aplicados ao seu funil.

---

## Painel / OS (NêÂ­vel 11 ê¢â¬â Claude Code + Sistema Operacional de Agentes)

### P47 ê¢â¬â Adicionar uma ferramenta desconhecida ao OS
**Quando usar:** quando uma ferramenta sua nêÂ£o foi detectada pelo agente pessoal.
```text
Eu uso [INSERIR FERRAMENTA/SISTEMA] e nêÂ£o vejo isso no sistema operacional. VocêÂª pode
adicionêÂ¡-lo aqui para mim?
```

### P48 ê¢â¬â Consultar o NotebookLM via agente
**Quando usar:** o agente busca/cria notebooks no Google NotebookLM.
```text
VocêÂª tem a skill do NotebookLM no "pantheon" ê¢â¬â fique totalmente atualizado com ela. VêÂ¡ ao
meu NotebookLM, encontre o êÂºltimo infogrêÂ¡fico que gerei e depois crie um notebook novo
sobre [INSERIR TEMA].
```

---

## Slash commands e comandos triviais (transversais)

NêÂ£o sêÂ£o prompts, mas fazem parte do fluxo de trabalho:
- `/init` (com effort alto) ê¢â¬â fazer o Claude entender o codebase inteiro.
- `/clear` ê¢â¬â resetar a conversa (evitar "context rot").
- `/context` ê¢â¬â inspecionar o uso da janela de contexto.
- `/compact` ê¢â¬â comprimir o contexto mantendo o essencial.
- `/model` ê¢â¬â trocar entre Opus / Sonnet / Haiku.
- `/cost` ê¢â¬â ver o gasto de tokens da sessêÂ£o.
- `/agents` ê¢â¬â gerenciar subagentes.
- `/memory` ê¢â¬â abrir/editar os arquivos de memêÂ³ria (CLAUDE.md).
- Invocar skills com `/<nome-da-skill>`.
- `/newbot` (no BotFather do Telegram) ê¢â¬â criar um bot para o agente pessoal.

---

# Parte 2 ê¢â¬â Por caso de uso

> Os mesmos prompts, agrupados pela tarefa. IDs cruzados com a Parte 1.

### Pesquisa / concorrêÂªncia
- **P16** ê¢â¬â TrêÂªs subagentes com veredito condensado
- **P20** ê¢â¬â Pesquisa de concorrentes com matriz de julgamento
- **P32** ê¢â¬â Copy de conversêÂ£o via subagentes
- **P34** ê¢â¬â Dashboard de conteêÂºdo "outlier"

### Briefing
- **P07** ê¢â¬â Preencher o CLAUDE.md por projeto
- **P21** ê¢â¬â Internalizar o briefing antes de construir
- **P35** ê¢â¬â Meta-prompt de "gargalo" para destravar

### ConstruêÂ§êÂ£o
- **P02** ê¢â¬â Teste de criaêÂ§êÂ£o de arquivos
- **P22** ê¢â¬â Construir o site com inspiraêÂ§êÂ£o de repo/HTML
- **P23** ê¢â¬â VersêÂµes em paralelo em pastas numeradas
- **P24** ê¢â¬â Salvar API key e gerar imagens
- **P28** ê¢â¬â FormulêÂ¡rio de captura de leads
- **P29** ê¢â¬â Sign-up, login e dashboard autenticado
- **P30** ê¢â¬â IntegraêÂ§êÂ£o de pagamentos com Stripe
- **P31** ê¢â¬â Roteamento de modelo + rate limit (OpenRouter)

### Debugging
- **P19** ê¢â¬â Loop de crêÂ­tica com modelo externo
- **P35** ê¢â¬â Meta-prompt de "gargalo" para destravar
- **P46** ê¢â¬â Mapa de health-check do sistema

### Design
- **P26** ê¢â¬â Aplicar princêÂ­pios de UI/UX a fundo
- **P37** ê¢â¬â Setup do framework de design (clonar e aprender)
- **P38** ê¢â¬â Deck no estilo de uma marca + imagens
- **P39** ê¢â¬â Rodar a skill de extraêÂ§êÂ£o de marca

### SEO
- **P25** ê¢â¬â OtimizaêÂ§êÂ£o de SEO a partir de um repo
- **P29** ê¢â¬â Dashboard com anêÂ¡lise de SEO (componente)

### AutomaêÂ§êÂ£o
- **P12** ê¢â¬â Criar uma skill a partir de uma API
- **P15** ê¢â¬â Criar um MCP local a partir de uma API
- **P17** ê¢â¬â Rotina de rascunho de e-mails
- **P18** ê¢â¬â Workflow de inquêÂ©rito de cliente
- **P41** ê¢â¬â Mission control: planejar metas
- **P42** ê¢â¬â Backup diêÂ¡rio do agente no GitHub
- **P48** ê¢â¬â Consultar o NotebookLM via agente

### MemêÂ³ria / CLAUDE.md
- **P04** ê¢â¬â Estilo de comunicaêÂ§êÂ£o (instruêÂ§êÂµes para o Claude)
- **P05** ê¢â¬â Organizar a vida em baldes
- **P06** ê¢â¬â Materializar os baldes em pastas
- **P07** ê¢â¬â Preencher o CLAUDE.md por projeto
- **P08** ê¢â¬â Regra de "salvar memêÂ³ria" no CLAUDE.md
- **P09** ê¢â¬â Skill de wrap-up para o Obsidian
- **P10** ê¢â¬â Skill "Obsidian Ask"
- **P11** ê¢â¬â MemêÂ³ria de longo prazo com Pinecone

### ProspecêÂ§êÂ£o / vendas
- **P18** ê¢â¬â Workflow de inquêÂ©rito de cliente
- **P33** ê¢â¬â Raspagem de leads (Apify)
- **P36** ê¢â¬â Validar/enriquecer e-mails via API

### Red-team
- **P27** ê¢â¬â RevisêÂ£o crêÂ­tica/adversarial do site
- **P43** ê¢â¬â Red-team de seguranêÂ§a ofensiva (mega prompt)

### Setup
- **P01** ê¢â¬â Instalar o Claude Code
- **P03** ê¢â¬â Conectar/reconectar o GitHub via CLI
- **P13** ê¢â¬â Inspecionar uma skill do marketplace
- **P14** ê¢â¬â Exportar skills para portabilidade
- **P40** ê¢â¬â Instalar o sistema operacional de agentes
- **P44** ê¢â¬â API key via terminal (fora do chat)
- **P45** ê¢â¬â Teto fixo de gasto em API
- **P47** ê¢â¬â Adicionar uma ferramenta desconhecida ao OS
