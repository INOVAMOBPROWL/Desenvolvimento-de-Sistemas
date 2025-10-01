# Projeto INOVAMOB - Sistema Web para Recarga Digital de Passes de Ônibus

Este repositório contém a documentação e o código-fonte do projeto **INOVAMOB**, desenvolvido como parte do estudo da matéria **Desenvolvimento de Sistemas**. O objetivo do projeto é aplicar os conceitos aprendidos na matéria, utilizando como tema a modernização do processo de recarga de passes de ônibus em São José dos Campos, em colaboração com o Consórcio 123.

---

## Sumário

- [Estudo de Caso](#estudo-de-caso)
- [Diagrama de Uso](#diagrama-de-uso)
- [Diagrama de Classes](#diagrama-de-classes)
- [Diagrama de Atividade](#diagrama-de-atividade)
- [Diagrama de Sequência](#diagrama-de-sequência)
- [Diagrama de Pacote](#diagrama-de-pacote)
- [Lista de Requisitos Funcionais e Não Funcionais](#lista-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama UML](#diagrama-uml)
- [Caso de Teste](#caso-de-teste)
- [Kanban](#kanban)

---

## Estudo de Caso

Este estudo de caso tem como foco a melhoria e modernização do sistema de recarga de passes de ônibus do Consórcio 123. O serviço atual apresenta limitações, como filas e falta de acessibilidade. A proposta do projeto **INOVAMOB** é a criação de um sistema digital que permita aos usuários realizar a recarga de seus passes de forma rápida e prática, melhorando a experiência do usuário e a eficiência do processo.

---

## Diagrama de Uso

O diagrama de uso do sistema mostra como diferentes usuários interagem com a plataforma **INOVAMOB**. Ele descreve os principais casos de uso, como o processo de cadastro, recarga de passe, e visualização do histórico.

![Diagrama de Uso](caminho/para/imagem/diagrama_de_uso.png)

---

## Diagrama de Classes

Este diagrama apresenta a estrutura das classes no sistema **INOVAMOB**, destacando as principais entidades e seus relacionamentos, como as classes de **Usuário**, **Recarga** e **Administração**.

![Diagrama de Classes](caminho/para/imagem/diagrama_de_classes.png)

---

## Diagrama de Atividade

O diagrama de atividade ilustra o fluxo de trabalho dentro do sistema, representando as atividades executadas em processos específicos. No contexto do **INOVAMOB**, ele pode descrever como as operações de recarga de passe acontecem e como os dados fluem dentro do sistema.

![Diagrama de Atividade](caminho/para/imagem/diagrama_de_atividade.png)

---

## Diagrama de Sequência

O diagrama de sequência mostra a interação entre os objetos do sistema, destacando a ordem dos eventos e a troca de mensagens entre eles durante a execução de um processo. Esse diagrama é útil para visualizar a comunicação entre os componentes ao longo de uma operação, como a recarga de passe.

![Diagrama de Sequência](caminho/para/imagem/diagrama_de_sequencia.png)

---

## Diagrama de Pacote

O diagrama de pacote organiza o sistema em pacotes, que são grupos de classes ou componentes relacionados. Ele ajuda a entender a estrutura do sistema e como os módulos estão interconectados. No **INOVAMOB**, ele pode ser usado para representar a divisão entre funcionalidades como **Cadastro de Usuário**, **Recarga de Passe**, e **Administração**.

![Diagrama de Pacote](caminho/para/imagem/diagrama_de_pacote.png)

---

## Lista de Requisitos Funcionais e Não Funcionais

### Requisitos Funcionais

- **Cadastro de usuário**: O sistema deve permitir que novos usuários se cadastrem.
- **Recarga de passe**: O sistema deve permitir que os usuários realizem recargas de passes com diferentes formas de pagamento.
- **Visualização de histórico**: Os usuários devem ser capazes de visualizar o histórico de suas recargas.

### Requisitos Não Funcionais

- **Segurança**: O sistema deve garantir a criptografia das informações dos usuários.
- **Usabilidade**: A interface do sistema deve ser intuitiva e fácil de usar.
- **Desempenho**: O sistema deve ser capaz de realizar até 1000 recargas simultâneas sem degradação significativa de performance.

---

## Diagrama UML

O diagrama UML do sistema descreve a estrutura e os relacionamentos entre os componentes, proporcionando uma visão detalhada de como o sistema funciona em termos de objetos e interações.

![Diagrama UML](caminho/para/imagem/diagrama_uml.png)

---

## Caso de Teste

### Caso de Teste 1: Cadastro de Usuário

**Objetivo:** Validar se o sistema permite o cadastro de um novo usuário.

**Entrada:**
- Nome: João Silva
- Email: joao.silva@email.com
- Senha: 123456

**Ação:** O usuário preenche o formulário de cadastro e clica em "Cadastrar".

**Resultado Esperado:** O sistema exibe uma mensagem de sucesso e o novo usuário aparece na lista de usuários cadastrados.

---

## Kanban

Para gerenciar o progresso do projeto **INOVAMOB**, estamos utilizando a metodologia **Kanban**. Abaixo está a visão geral do quadro de tarefas do projeto, onde você pode acompanhar o progresso e o status das atividades.

### Tarefas

| Tarefa | Status | Responsável | Data de Entrega |
|--------|--------|-------------|-----------------|
| **Desenvolver tela de cadastro de usuário** | Em progresso | Willerson | 19/09/2025 |
| **Implementar funcionalidade de recarga de passe** | Pendente | Paulo | 22/09/2025 |
| **Criar página de relatórios de recargas** | Concluído | Otávio | 15/09/2025 |
| **Implementar autenticação e segurança de dados** | Pendente | Luís Gustavo | 25/09/2025 |
| **Desenvolver dashboard de administração** | Em progresso | Rikio | 18/09/2025 |

### Visualize o Quadro Kanban

O quadro Kanban é utilizado para gerenciar as tarefas do projeto de maneira visual e colaborativa. Clique abaixo para acessar o quadro no **Trello** e acompanhar o progresso:

[Trello - Quadro Kanban do Projeto INOVAMOB](https://trello.com/b/OT3Ox5vP/inovamob)

---

## Repositórios para Imagens dos Diagramas

Aqui estão os repositórios sugeridos para armazenar e gerenciar as imagens dos diagramas de seu projeto. Você pode criar pastas específicas para cada tipo de diagrama e fazer upload das imagens diretamente no GitHub.

- **Repositório de Diagramas**: [GitHub - INOVAMOB Diagramas](https://github.com/SEU-USER/INOVAMOB-Diagramas)
  - **Caso de Uso**: `diagrams/caso_de_uso/`
  - **Diagrama de Classes**: `diagrams/diagrama_de_classes/`
  - **Diagrama de Atividade**: `diagrams/diagrama_de_atividade/`
  - **Diagrama de Sequência**: `diagrams/diagrama_de_sequencia/`
  - **Diagrama de Pacote**: `diagrams/diagrama_de_pacote/`

Esse repositório pode ser usado para centralizar as imagens dos diagramas em pastas específicas e referenciar os links diretamente no README do projeto. Certifique-se de fazer o upload das imagens nesses repositórios e usar os links corretos nos lugares indicados no documento.

---

Essa versão do README agora inclui os diagramas adicionais que você mencionou, além de um link para um repositório onde as imagens dos diagramas podem ser armazenadas, mantendo tudo organizado e acessível no GitHub.
