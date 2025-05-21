# Engenharia de Prompts: Conceitos Essenciais para Interação com IAs Generativas

## Introdução

A Engenharia de Prompts é a arte e ciência de criar entradas (prompts) eficazes para modelos de linguagem de Inteligência Artificial (IA) generativa, como o GPT-3, GPT-4, Gemini, entre outros. Um prompt bem elaborado é crucial para obter respostas precisas, relevantes e úteis, maximizando o potencial dessas tecnologias. Esta habilidade está se tornando cada vez mais valorizada em diversas áreas profissionais.

## Componentes Essenciais de um Prompt Eficaz

Um prompt bem estruturado geralmente inclui um ou mais dos seguintes componentes:

1.  **🎯 Instrução (Tarefa):**
    * Define a ação específica que se espera que o modelo execute.
    * Deve ser clara, concisa e direta.
    * Exemplo: "Resuma o seguinte texto em três frases."

2.  **🎭 Contexto ou Configuração (Persona/Cenário):**
    * Fornece informações de fundo ou define um papel para o modelo.
    * Ajuda o modelo a entender a perspectiva e o tom desejados.
    * Exemplo: "Você é um assistente virtual especializado em história medieval. Explique as causas da Guerra dos Cem Anos."

3.  **📄 Dados de Entrada ou Conteúdo de Suporte:**
    * Informações que o modelo deve usar para processar a instrução.
    * Pode ser um texto, dados, exemplos ou preferências.
    * Exemplo: "[Cole aqui o texto para ser resumido]"

4.  **📝 Formato de Saída:**
    * Especifica como a resposta deve ser apresentada.
    * Garante que a saída seja estruturada e fácil de usar.
    * Exemplo: "Liste os resultados em formato JSON." ou "Apresente os pontos principais em tópicos."

5.  **💡 Exemplos (Few-shot Learning):**
    * Fornecer pares de entrada e saída esperada para guiar o modelo sobre o formato ou tipo de resposta desejada.
    * Exemplo:
        * Entrada: "Traduza 'Olá' para o francês." Saída: "Bonjour."
        * Entrada: "Traduza 'Adeus' para o francês." Saída: (o modelo deve gerar "Au revoir.")

## Técnicas Fundamentais de Engenharia de Prompts

1.  **Clareza e Especificidade:**
    * Seja o mais explícito possível sobre o que você quer. Evite ambiguidades.
    * Quanto mais detalhes relevantes você fornecer, melhor será o resultado.

2.  **Zero-shot Prompting:**
    * Dar uma instrução direta ao modelo sem exemplos prévios. Funciona bem para tarefas que o modelo já foi treinado extensivamente.
    * Exemplo: "Qual é a capital da França?"

3.  **Few-shot Prompting:**
    * Fornecer alguns exemplos (shots) de entradas e saídas desejadas para guiar o modelo. Útil para tarefas mais complexas ou quando se deseja um formato específico.
    * Exemplo:
        * "Cliente: Preciso de ajuda com minha senha. Assistente: Posso ajudar a redefinir sua senha. Qual é o seu email?"
        * "Cliente: O produto chegou quebrado. Assistente: [Peça ao modelo para gerar uma resposta empática e uma solução]"

4.  **Chain-of-Thought (CoT) Prompting:**
    * Incentivar o modelo a "pensar passo a passo" antes de dar a resposta final, especialmente para problemas que exigem raciocínio.
    * Exemplo: "Some 5 + 8. Explique o seu raciocínio passo a passo antes de dar o resultado final."

5.  **Definição de Persona/Papel:**
    * Instruir o modelo a atuar como um especialista ou assumir uma determinada personalidade.
    * Exemplo: "Aja como um revisor de textos experiente e corrija os erros gramaticais no texto a seguir."

6.  **Uso de Delimitadores:**
    * Utilizar caracteres como `"""`, `---`, `<tag>`, `##` para separar claramente diferentes partes do prompt (instrução, contexto, dados).
    * Exemplo:
        ```
        Contexto: """Você é um bot de atendimento ao cliente."""
        Instrução: """Responda à seguinte pergunta do cliente:"""
        Pergunta do Cliente: """Como posso rastrear meu pedido?"""
        ```

7.  **Restrições e Limitações:**
    * Especificar o que o modelo *não* deve fazer ou quais limites deve respeitar (ex: "Não use jargões técnicos", "Limite a resposta a 100 palavras").

8.  **Iteração e Refinamento:**
    * A engenharia de prompts é um processo iterativo. Teste diferentes abordagens, analise as respostas e refine seus prompts para obter melhores resultados.

## Boas Práticas

* **Teste Variações:** Experimente diferentes formas de perguntar a mesma coisa.
* **Seja Explícito sobre Negativas:** Se há algo que o modelo não deve fazer, diga explicitamente.
* **Divida Tarefas Complexas:** Para problemas muito grandes, divida-os em sub-tarefas menores com prompts específicos para cada uma.
* **Peça para Citar Fontes (quando aplicável):** Se a precisão factual é crítica, peça ao modelo para justificar ou citar fontes (embora a capacidade de fazer isso com precisão varie).
* **Controle a Extensão da Resposta:** Peça respostas curtas, médias ou longas conforme necessário.

## Por que incluir Engenharia de Prompts no seu Currículo?

Dominar a engenharia de prompts demonstra:

* **Habilidade de Comunicação Efetiva:** Capacidade de se comunicar claramente com sistemas complexos.
* **Pensamento Analítico e Resolução de Problemas:** Habilidade para decompor problemas e guiar a IA para soluções.
* **Adaptabilidade Tecnológica:** Proatividade em aprender e utilizar novas tecnologias de IA.
* **Eficiência e Produtividade:** Capacidade de extrair o máximo valor de ferramentas de IA para otimizar tarefas.

A engenharia de prompts é uma competência chave na era da IA, permitindo que profissionais de diversas áreas interajam de forma mais inteligente e produtiva com as tecnologias generativas.
# Prompt Engineering
Here is gonna be a talk about LLM and PLN of prompts


Search connections on tokenization in OpenAI, Copilot, and Gemini
# Mapa mental DIO
<img src="src/imagem_2025-05-19_163649455.png" alt="Diagrama UML" width="1000"/>

# 1. Clear Instruction
- You need to set a text that you don`t have a roll of lake of information, going into the target already
  
# 2. Set an adequate context


# 3. Give PLN or LMM an example of what you want

# 4. Data in, information, or a problem that you needed

# 5. The format Out
- Specifies what you wanna from the answer 

# 6. Set a structure on the data in, set in the problem that you wanna resolve

# 7. Envious Prompts
- The prompts can be biased
- Or partial on the prompt

# 8. Privacy and Safety 
- Don`t put on the prompt information data that is private to the company or person
