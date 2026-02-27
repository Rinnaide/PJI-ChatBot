# PJI-ChatBot

Nosso ChatBot é uma aplicação de atendimento automatizado que permite aos usuários esclarecer dúvidas sobre a instituição. O sistema processa as mensagens enviadas, identifica palavras-chave relevantes e retorna respostas pré-definidas, seja a solução direta para o problema ou orientações para especificar melhor a dúvida.

### Exemplo de Fluxo

**Mensagem do usuário:**

> "Tenho interesse em estudar no SENAC."

**Palavra-chave identificada:** `estudar`

**Resposta do Bot:**

> "O SENAC oferece diversos cursos. Em qual área de conhecimento você tem interesse?"

---

**Mensagem do usuário:**

> "Eu tenho interesse em tecnologia."

**Palavra-chave identificada:** `tecnologia`

**Resposta do Bot:**

> "O SENAC oferece os seguintes cursos na área de Tecnologia:
>
> - Análise e Desenvolvimento de Sistemas
> - (outros cursos...)"

---

## Estrutura do Banco de Dados

| Tabela                  | Descrição                                                    |
| ----------------------- | -------------------------------------------------------------- |
| **Usuário**      | Armazena os dados dos usuários que interagem com o chatbot    |
| **Palavra-Chave** | Contém os termos-chave para identificação de intents        |
| **Respostas**     | Armazena as respostas associadas a cada palavra-chave          |
| **Cursos**        | Mantém a maioria do catálogo de cursos oferecidos pelo SENAC |

---

## Destaques Técnicos

### Arquitetura e Tecnologias

- **Backend:** Implementação de chatbot com respostas fixasbaseadas em filtro de palavras-chave
- **Segurança:** Utilização do Spring Security para autenticação e controle de acesso
- **Frontend:** Interface de chat desenvolvida em React Native, com caixa de texto para envio de mensagens
- **Cadastro:** Registro de usuários interessados para futuras ações de marketing e relacionamento

### Funcionalidades Principais

| Tecnologia                 | Funcionalidade                                                                  |
| -------------------------- | ------------------------------------------------------------------------------- |
| **Spring Framework** | Filtros avançados para processamento de mensagens e identificação de intents |
| **React Native**     | Interface responsiva para visualização do chat e interação do usuário      |
|                            |                                                                                 |

---
