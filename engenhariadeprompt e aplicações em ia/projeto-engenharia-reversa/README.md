[README.md](https://github.com/user-attachments/files/27616389/README.md)

Este documento final detalha a atividade de **Engenharia Reversa e Vibecoding**, onde o usuário atua como um Desenvolvedor de Software assistido por IA para reconstruir aplicações funcionais baseando-se apenas na interface externa[cite: 4].

---

# # Laboratório de Reconstrução: Engenharia Reversa e Vibecoding

Este repositório descreve o fluxo de trabalho para clonagem de WebApps utilizando o **Google AI Studio** e o modelo **Gemini**, focando em *Clean Code* e componentização[cite: 4].

## ## 🎯 Fluxo de Trabalho (3 Passos)

1.  **Analisa:** Exploração do WebApp de referência para mapear componentes visuais e regras de lógica de negócio sem acessar o código-fonte[cite: 4].
2.  **Configura:** Definição das *System Instructions* no Google AI Studio, posicionando a IA como um desenvolvedor Full-Stack Senior[cite: 4].
3.  **Constrói e Valida:** Geração do código, execução em ambiente de teste e ajuste de instruções por contraste até atingir a fidelidade estética e funcional[cite: 4].

---

## ## 🛠️ Estrutura de Inicialização (`vibecoding`)

A atividade utiliza uma estrutura de prompt organizada para definir o contexto do projeto[cite: 4]:

*   **Role Definition:** Desenvolvedor Full-Stack Senior especializado em *Rapid Prototyping*[cite: 4].
*   **Project Context:** Definição do nome do app, descrição da referência e estética da UI (ex: Minimalista, Glassmorphism)[cite: 4].
*   **Tech Stack:** Escolha de frameworks (React/Vite), bibliotecas de estilo (Tailwind CSS) e gerenciamento de estado[cite: 4].
*   **Reverse Engineering Map:** Mapeamento da estrutura de layout e funcionalidades principais (*core features*)[cite: 4].

---

## ## 🧠 Técnicas de Refinamento e Correção

Para garantir a precisão do código gerado, são aplicadas quatro técnicas fundamentais de prompt[cite: 4]:

| Técnica | Descrição | Exemplo de Aplicação[cite: 4] |
| :--- | :--- | :--- |
| **Erro e Contraste** | Apontar a falha exata e fornecer o contra-exemplo. | "No último output você usou X, mas eu solicitei Y." |
| **Negative Prompting** | Uso de comandos de negação explícitos para evitar excessos. | "Não utilize a biblioteca X, use apenas a biblioteca Y." |
| **Few-Shot Prompting** | Fornecer exemplos do que é considerado "correto". | "Use o exemplo abaixo como guia de estilo e profundidade." |
| **Chain of Thought** | Pedir para a IA explicar o passo a passo lógico. | Utilizado para identificar desvios em tarefas complexas. |

---

## ## ⚖️ Princípios de Desenvolvimento
*   **Curadoria Ética:** O desenvolvedor deve garantir que, embora a IA gere a "casca", a criatividade humana seja a "alma" do software[cite: 4].
*   **Letramento em IA:** Foco no pensamento crítico e na resolução de problemas complexos através da engenharia de prompt[cite: 4].
