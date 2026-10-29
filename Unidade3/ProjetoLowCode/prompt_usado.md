Desenvolva uma aplicação web chamada TaskFlow AI, um sistema simples de gerenciamento de tarefas com suporte de Inteligência Artificial, utilizando a plataforma Bubble.

O objetivo do projeto é demonstrar como ferramentas Low Code, No Code e Vibecode podem acelerar o desenvolvimento de software, simplificar a automação de processos e integrar serviços de Inteligência Artificial.

### 1. Interface da aplicação
Crie uma interface moderna, simples e intuitiva, com:
- Tela inicial com apresentação do sistema.
- Área para cadastro de tarefas.
- Painel para visualizar as tarefas cadastradas.
- Área de consulta à Inteligência Artificial.

Utilize um design minimalista, com cores azul, branco e cinza, priorizando a facilidade de uso e a organização visual.

### 2. Cadastro de tarefas
Permita que o usuário cadastre tarefas com os seguintes campos:
- Título.
- Descrição.
- Data de conclusão.
- Prioridade: baixa, média ou alta.
- Status: pendente, em andamento ou concluída.

Implemente um botão para salvar a tarefa e outro para cancelar o cadastro.

### 3. Gerenciamento de tarefas
Crie um painel que permita:
- Visualizar todas as tarefas cadastradas.
- Editar tarefas existentes.
- Excluir tarefas.
- Alterar o status das tarefas.
- Filtrar tarefas por status e prioridade.

### 4. Integração com Inteligência Artificial
Crie uma funcionalidade chamada "Assistente IA".

O usuário poderá informar suas tarefas e solicitar sugestões de organização.

A Inteligência Artificial deverá:
- Analisar a descrição das tarefas.
- Sugerir uma ordem de prioridade.
- Recomendar formas de organizar as atividades.
- Criar sugestões simples de planejamento.

A IA deverá apenas fornecer sugestões, sem alterar automaticamente as tarefas cadastradas.

Caso não exista uma API de IA configurada, crie a interface e deixe a integração preparada para configuração posterior.

### 5. Banco de dados
Configure um banco de dados no Bubble para armazenar as tarefas.

Cada tarefa deverá possuir:
- Identificador.
- Título.
- Descrição.
- Data de conclusão.
- Prioridade.
- Status.
- Data de criação.

### 6. Automação
Configure workflows no Bubble para:
- Salvar tarefas no banco de dados.
- Atualizar tarefas.
- Excluir tarefas.
- Alterar o status das tarefas.
- Atualizar o painel após cada operação.

###7. Validação e segurança

Implemente mecanismos básicos de validação e segurança para garantir o funcionamento correto da aplicação.

Validação de dados:

Não permitir o cadastro de tarefas sem título.

Não permitir descrições vazias.

Verificar se a data de conclusão é válida.

Impedir o envio de formulários com campos obrigatórios incompletos.

Limitar o tamanho dos campos de texto.

Exibir mensagens claras de erro ou confirmação para o usuário.

Segurança e controle de acesso:

Implementar autenticação de usuários, com cadastro, login e logout.

Cada usuário deverá visualizar e gerenciar exclusivamente suas próprias tarefas.

Configurar regras de privacidade (Privacy Rules) no banco de dados do Bubble.

Impedir que usuários não autenticados acessem páginas e funcionalidades protegidas.

Não expor chaves de API ou credenciais no navegador.

Realizar chamadas à API de Inteligência Artificial pelo backend do Bubble, mantendo as credenciais protegidas.

Validar os dados recebidos antes de armazená-los no banco de dados.

Não permitir que a IA execute operações de exclusão ou alteração de tarefas diretamente.
