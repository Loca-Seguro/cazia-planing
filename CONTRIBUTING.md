## 🤝 Guia de Contribuição

Bem-vindo(a) ao projeto\! Agradecemos seu interesse em contribuir.

Para manter nosso fluxo de trabalho organizado e alinhado com a metodologia Ágil, usamos um sistema hierárquico claro de Issues, que se reflete nos nossos templates de criação.

Nosso modelo de trabalho é:

$$
\text{Épico (Grande Meta)} \rightarrow \text{Feature (Funcionalidade)} \rightarrow \text{Task (Trabalho Acionável)}
$$

-----

## 1\. 📋 Visão Geral da Hierarquia

Para garantir a rastreabilidade e a organização do nosso quadro (Board), todas as Issues devem ser criadas seguindo a hierarquia abaixo:

| Tipo de Issue | Rótulo (Label) | Nível de Trabalho | Relação de Subtask |
| :--- | :--- | :--- | :--- |
| **✨ Épico** | `epic` | Alto (Meta de Longo Prazo) | Pai de **Features** |
| **🎯 Feature** | `feature` | Médio (Funcionalidade) | Subtask de um **Épico** e Pai de **Tasks** |
| **✅ Task** | `task` | Baixo (Unidade de Trabalho) | Subtask de uma **Feature** |

-----

## 2\. 📝 Como Criar uma Nova Issue

Ao criar uma nova Issue, você **DEVE** selecionar o template apropriado.

### A. Criando um Épico (`✨ Épico`)

Use o template **Épico** quando precisar iniciar uma nova meta grande, que levará tempo e englobará várias funcionalidades.

  * **Título:** Deve seguir o formato: `✨ Épico: [Nome da Grande Meta]`
  * **Conteúdo:** Liste as Features planejadas na seção **Features** usando as caixas de seleção (`- [ ]`).

### B. Criando uma Feature (`🎯 Feature`)

Use o template **Feature** para planejar e acompanhar a implementação de uma funcionalidade específica que ajudará a completar um Épico.

  * **Título:** Deve seguir o formato: `🎯 [FEATURE]: [Nome da Funcionalidade]`
  * **Hierarquia:** **Obrigatório** vincular a Issue a um **Épico** já existente na seção `🔗 Épico Pai`. (Exemplo: `#123`).
  * **Conteúdo:** Liste as Tasks necessárias na seção **Tarefas** usando as caixas de seleção.

### C. Criando uma Task (`✅ Task`)

Use o template **Task** para definir as unidades de trabalho mais granulares e acionáveis (codificação, testes, revisão de código, etc.).

  * **Título:** Deve seguir o formato: `✅ [TASK]: [O que precisa ser feito]`
  * **Hierarquia:** **Obrigatório** vincular a Issue a uma **Feature** já existente na seção `🔗 Feature Pai`. (Exemplo: `#456`).
  * **Conteúdo:** Seja claro na descrição e preencha a **Definição de Pronto (Definition of Done)**.

-----

## 3\. 🔄 Vincular a Hierarquia

Para manter a rastreabilidade visual, **sempre** use o seguinte método para vincular as Issues:

1.  Crie a Issue de nível inferior (ex: uma Task).
2.  Copie o número da Issue criada (ex: `#456`).
3.  Edite a Issue de nível superior (ex: a Feature) e cole o número na lista de caixas de seleção para que o link seja exibido no corpo do texto:

**Exemplo na Feature Pai:**

```markdown
## Tarefas (Tasks)

- [ ] ✅ [TASK] Task de Implementação (#456)
```

Seguindo este guia, garantimos que nosso quadro de Issues reflita o verdadeiro estado e progresso do projeto, facilitando a visualização e o gerenciamento\!

-----

Este `CONTRIBUTING.md` é completo, direciona o colaborador a usar os templates corretamente e explica a metodologia por trás do seu sistema de Issues.

Gostaria de ajuda para criar um primeiro Épico e algumas Features de exemplo para você testar e popular o seu novo sistema de Issues?