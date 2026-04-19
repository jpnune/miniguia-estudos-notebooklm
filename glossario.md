# Glossário Completo: O Caminho do Arquiteto (2026)

Este documento reúne os conceitos técnicos, arquitetônicos e pedagógicos essenciais para o currículo de Ciência da Computação autodidata focado na era da Inteligência Agêntica.

## 1. Fundamentos Técnicos e Arquitetura de Software

* **ADR (Architecture Decision Records):** Documentos que registram as decisões arquitetônicas cruciais e seus "porquês". Em 2026, assistentes de IA são integrados aos repositórios para sugerir ADRs automaticamente após mudanças significativas no código, mantendo o histórico transparente para a equipe [1].
* **AI-SDLC (Ciclo de Vida de Desenvolvimento com IA):** O novo modelo de desenvolvimento onde as fases tradicionais (planejamento, design, codificação, testes e implantação) são comprimidas de semanas para horas através da automação inteligente [2, 3].
* **Architect-in-the-Loop / Engenheiro Híbrido:** O papel do engenheiro de software moderno. Refere-se ao profissional que delega a escrita tática de código para a IA e foca na decomposição estratégica de problemas, na coordenação de agentes e na avaliação crítica da qualidade final do sistema [4, 5].
* **Complexidade Assintótica (Notação Big-O):** Avaliação matemática que mede como o tempo de execução e o uso de memória de um algoritmo crescem. É vital na era da IA para identificar se um agente gerou um código ineficiente (como exponencial $O(2^n)$ ao invés de linear $O(n)$), o que pode gerar altos custos de infraestrutura [6].
* **Data Mesh (Malha de Dados):** Arquitetura que resolve gargalos em data lakes centralizados através da propriedade de dados descentralizada por domínio [1].
* **Edge Computing / Edge AI:** Execução e processamento local de modelos de IA diretamente em dispositivos de borda. Exige do engenheiro um domínio profundo da hierarquia de memória da máquina [1, 7].
* **FinOps:** Prática arquitetônica focada na eficiência e otimização de custos na nuvem. Envolve usar modelos de IA menores e baratos para tarefas simples, reservando modelos de fronteira complexos apenas para raciocínios difíceis, podendo reduzir custos operacionais em até 70% [8].
* **Hierarquia de Memória:** Componentes de hardware (registradores, caches L1/L2/L3, RAM, disco) vitais para entender o fluxo de dados. Dominá-la é essencial para depurar latência em sistemas distribuídos [7].
* **Inteligência Agêntica:** O uso da IA não apenas como gerador de texto ou código, mas como uma força de trabalho produtiva autônoma que atua ativamente nas fases de desenvolvimento sob a supervisão humana [2].
* **RAG (Retrieval-Augmented Generation):** Padrão arquitetônico em que pipelines de dados recuperam informações em tempo real de bancos de dados vetoriais para contextualizar a IA, em vez de depender apenas do seu conhecimento estático interno [8].
* **Sistemas Multi-Agentes (MAS) / Swarms:** Arquitetura que substitui agentes monolíticos únicos por "enxames" (swarms) de micro-agentes especializados que colaboram entre si através de grafos de estado ou barramentos de mensagens [8].

## 2. Metodologia de Estudo e Interação com IA

* **Chain-of-Thought (CoT) e Padrão de Persona:** Técnicas avançadas de engenharia de prompt que permitem instruir a IA a raciocinar "passo a passo" e a assumir o papel de um professor emérito, guiando o aprendizado com perguntas estruturadas [9].
* **CRAFT e CO-STAR:** Frameworks estruturados de comunicação com IA (como *Context, Role, Action, Format, Target*). São utilizados para filtrar informações gratuitas na web e construir guias de estudo personalizados de alto nível [10].
* **Engenharia de Prompt:** Tratada como a "nova literacia funcional", é a habilidade primária de se comunicar de forma estruturada com modelos de linguagem para transformar a IA em um parceiro de estudos eficiente [9].
* **Esforço Produtivo:** Princípio educacional aplicado aos tutores de IA, onde a máquina retém as respostas diretas e exige tentativas múltiplas do aluno. Esse atrito proposital é essencial para garantir a retenção do conhecimento a longo prazo [10].
* **Ilusão de Competência:** O risco mais comum no estudo autodidata, onde o estudante acredita falsamente ter entendido um conceito complexo apenas por ter lido a resposta gerada pela IA, sem tê-la aplicado ou compreendido a fundo [10].
* **TDD (Test-Driven Development) com Agentes:** Metodologia onde o fluxo "Red-Green-Refactor" é acelerado pela IA. O engenheiro escreve o teste e especifica o comportamento num arquivo `spec.md` (Red), a IA tenta satisfazer o teste escrevendo o código mínimo (Green), e depois ambos melhoram a arquitetura juntos (Refactor) [4, 11].
* **Tutor Socrático:** Configuração na qual a ferramenta de IA age focando no "andaime" pedagógico. Em vez de entregar a solução pronta, ela interage guiando o aluno com dicas graduais e perguntas provocativas [9, 10].
Gostaria que eu utilizasse a nossa ferramenta nativa para gerar Flashcards (Cartões de 
