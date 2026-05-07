# -miniguia-estudos-notebooklm

Este repositório foi desenvolvido como um caderno temático sobre Agentes de Inteligência Artificial. O objetivo principal é compreender como agentes de IA funcionam, quais são suas arquiteturas, aplicações práticas e desafios atuais.

# Objetivos de estudo

Entender os componentes fundamentais de um agente de IA;
Aprender como agentes utilizam ferramentas externas;
Explorar exemplos práticos de automação inteligente;
Desenvolver capacidade de engenharia de prompts;
Criar um material reutilizável para estudos futuros.

# Fontes

https://www.youtube.com/watch?v=wxD8MaD0xXk

https://www.youtube.com/watch?v=7C0k8wsYeV0

https://www.youtube.com/watch?v=k6x3FuBPMiE

https://www.youtube.com/watch?v=I3jGUKBaxBo

https://www.youtube.com/watch?v=-Ka4YKW7RwM

https://www.youtube.com/watch?v=iFDukMTw4Go

# Perguntas Estratégicas Utilizadas

Prompt
“Explique o que é um agente de IA de forma simples e depois aprofunde tecnicamente.”

Resultado:
A IA forneceu uma boa introdução e depois explicou conceitos como memória, planejamento e ferramentas.

Dificuldade encontrada:
As respostas iniciais ficaram muito genéricas.

Solução:
Adicionar:

“mais fontes para que a base dela fosse mais ampla."

# Resumo

Guia de Estudo: Agentes de IA e Sistemas Autônomos
1. Conceitos Fundamentais

    Definição: Diferente de chatbots tradicionais baseados em regras rígidas, os Agentes de IA são softwares que tomam decisões e agem de forma autônoma para cumprir tarefas complexas.
    Ciclo Operacional: O agente planeja, executa através de ferramentas e aprende com os resultados (memória).
    Estratégias de Raciocínio:
        Chain of Thought (Cadeia de Pensamento): O modelo gera etapas lógicas antes da resposta final.
        ReAct: Combina raciocínio com a execução de ações em ciclos.
        Tree of Thoughts: Explora múltiplos caminhos de decisão como uma árvore.

2. Arquitetura e Ferramentas (n8n)

    Componentes: Consistem em um cérebro (LLM), ferramentas (Skills), memória e guardrails (segurança).
    n8n: Uma das melhores ferramentas no-code para criar esses agentes devido aos seus nós avançados e opção de auto-hospedagem (self-hosting) para reduzir custos.
    Memória: A de curto prazo armazena o histórico imediato (volátil), enquanto a de longo prazo usa bancos de dados vetoriais (como Pinecone ou Supabase) para persistência.

3. Mercado e Implementação

    Oportunidade: Projetos de implementação podem variar de R$3.000 R$70.000.
    Desafios: Alucinações, latência, custos e a dificuldade de governança em sistemas multiagentes.

# Glossario

API: Interface que permite a comunicação entre dois sistemas.

Cadeia de Pensamento (CoT): Método de raciocínio passo a passo da IA.

Guardrails: Regras de segurança e comportamento para a IA.

LLM: O modelo de linguagem (ex: GPT-4, Claude) que serve como o "cérebro".

MCP (Model Context Protocol): Protocolo para padronizar o uso de ferramentas por IAs.

RAG: Técnica de alimentar a IA com dados privados sem precisar de retreinamento.

Self-hosting: Hospedar o software em servidores próprios para maior controle e menor custo.

Token: Unidade básica de texto processada por modelos de IA.

Vector Database: Banco de dados especializado em armazenar memórias para agentes de IA.

Webhook: Gatilho que envia dados em tempo real quando um evento ocorre.

# Prompts

1. Explique o que são agentes de IA de forma simples e didática. Depois, aprofunde tecnicamente mostrando como funcionam componentes como memória, planejamento, tomada de decisão e uso de ferramentas externas. Inclua exemplos reais de aplicações atuais.

2. Compare chatbots tradicionais, assistentes virtuais e agentes de IA autônomos. Organize a resposta em tabela, destacando diferenças de autonomia, memória, capacidade de executar tarefas e exemplos práticos de cada tecnologia.

# link do caderno:

https://notebooklm.google.com/notebook/fa55048a-b996-4981-a058-b631296e6e9d
