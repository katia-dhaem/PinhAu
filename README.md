Documentação do Projeto PinhAu
Equipe:
 Katia Dhaem
 Curso: Gestão da Tecnologia da Informação – IFPR Câmpus Pinhais

1. Identificação
a. Identidade visual do projeto
O projeto PinhAu possui identidade visual baseada em cores suaves e amigáveis, com predominância do amarelo (Bootstrap – bg-warning), transmitindo acolhimento e proximidade com o público-alvo. A interface prioriza simplicidade, clareza e fácil navegação.

b. Redes sociais do projeto
Atualmente o projeto encontra-se em fase acadêmica e está hospedado no GitHub como repositório de desenvolvimento.

c. Organização da Equipe
Responsável: Katia Dhaem


Função: Desenvolvimento backend, frontend, modelagem de banco de dados e documentação.


Forma de comunicação: WhatsApp (Daily), GitHub (versionamento) e Trello (organização Kanban).


d. Data de criação do projeto
2024 – Projeto Interdisciplinar I – IFPR Câmpus Pinhais
2026 – Projeto Interdisciplinar II – IFPR Câmpus Pinhais

2. Concepção
a. Descrição da visão geral do projeto
O projeto PinhAu consiste em uma plataforma web desenvolvida para facilitar a adoção responsável de cães no município de Pinhais.
O sistema conecta tutores que desejam disponibilizar cães para adoção e adotantes interessados em oferecer um novo lar aos animais.
A aplicação foi refatorada e reorganizada estruturalmente, visando maior manutenibilidade, organização modular e segurança.
b. Objetivo do projeto
Desenvolver uma plataforma digital simples e funcional que:
Permita o cadastro de tutores e adotantes;


Possibilite o cadastro e gerenciamento de cães;


Facilite a visualização pública dos animais disponíveis;


Promova a adoção responsável.


c. Escopo do produto
Descrição do produto:
 Sistema web desenvolvido em PHP e MySQL que permite gerenciamento de cães para adoção, autenticação de usuários e controle de perfil de tutor.
Principais entregas implementadas:
Sistema de cadastro e login com sessão;


CRUD completo de cães (inserção, alteração e remoção);


Perfil do tutor com gerenciamento de seus próprios animais;


Listagem pública de cães;


Organização modular do código em pastas separadas.


Critérios de aceite:
Usuário consegue cadastrar-se e realizar login;


Tutor consegue cadastrar e gerenciar seus cães;


Visitante consegue visualizar cães disponíveis;


Sistema mantém controle de acesso por sessão.


d. Matriz de Riscos
Id
Descrição
Impacto
Probabilidade
Resposta
R1
Falhas de segurança no login
Alto
Médio
Uso de sessões e prepared statements
R2
Inconsistência no banco de dados
Médio
Médio
Uso de chaves estrangeiras
R3
Código difícil de manter
Alto
Alto
Refatoração estrutural do projeto
R4
Falhas de autenticação
Alto
Médio
Validação de sessão em todas as telas restritas


3. Design do Software
a. Design Centrado no Usuário
O sistema foi desenvolvido priorizando simplicidade e facilidade de uso, com foco na navegação intuitiva e acesso rápido às principais funcionalidades.
b. Personas e mapa de empatia
Persona principal:
 Tutor que deseja disponibilizar um cão para adoção.
Persona secundária:
 Adotante que busca um animal para adoção responsável.
c. Storyboard (contexto de uso)
Usuário acessa a página inicial;


Visualiza cães disponíveis;


Realiza cadastro/login;


Tutor cadastra novo cão;


Tutor gerencia seus próprios registros.


d. UI Design (guia de estilo)
Interface baseada em Bootstrap;


Layout responsivo;


Uso de cards para organização de informações;


Separação de componentes (header e footer reutilizáveis).


e. Protótipação do MVP
O MVP contempla:
Autenticação funcional;


CRUD de cães;


Perfil do tutor;


Listagem pública.


4. Desenvolvimento
a. Processo de software
Metodologia utilizada:
 Kanban com organização em:
To Do


Doing


Done


Sprints quinzenais para desenvolvimento incremental.
b. Recursos utilizados
Frontend: HTML5, CSS3, Bootstrap
 Backend: PHP
 Banco de Dados: MySQL
 Controle de versão: GitHub
 Scripts: JavaScript (AJAX para gerenciamento de cães)
c. Resultados esperados
Plataforma funcional para adoção responsável;


Código organizado e modular;


Base estruturada para evolução futura.


d. Instruções para download e execução
Clonar o repositório:


git clone https://github.com/seuusuario/pinhau.git
Importar o script SQL disponível em:


banco_de_dados/script.sql
Configurar a conexão em:


conex_banco/conexao.php
Executar via XAMPP (htdocs).


e. Licença de uso e distribuição
Projeto acadêmico desenvolvido para fins educacionais no IFPR Câmpus Pinhais.
5. Estratégia de Marketing Digital
Como projeto acadêmico, a estratégia contempla:
Divulgação em redes sociais;


Parcerias futuras com ONGs locais;


Produção de conteúdo educativo sobre adoção responsável.


6. Gestão do Projeto
1. Backlog do Projeto
Principais funcionalidades priorizadas:
Sistema de autenticação


CRUD de cães


Perfil do tutor


Listagem pública


Melhorias de segurança


2. Métricas de acompanhamento
Número de funcionalidades entregues por sprint;


Registro de dailys;


Revisão quinzenal (Review).


3. Lições aprendidas
Importância da organização modular;


Necessidade de segurança em autenticação;


Relevância do versionamento contínuo.


7. Relatório Técnico
O sistema foi estruturado com:
Separação por camadas;


Controle de acesso por sessão;


Uso de prepared statements;


Estrutura organizada em pastas (autenticação, telas, componentes, banco_de_dados, etc.).


8. Plano de Negócio
Como projeto acadêmico, o plano prevê futura expansão com:
Upload de imagens reais;


Integração com API WhatsApp;


Sistema formal de solicitação de adoção;


Painel administrativo.


9. Artigo
O projeto contribui para a conscientização sobre adoção responsável, oferecendo uma solução digital que facilita a conexão entre tutores e adotantes.
10. Extras
a. Modelagem UML
Diagrama de casos de uso, classes e relacionamento entre entidades.
b. Modelagem de banco de dados
DER estruturado com chaves primárias e estrangeiras.
c. Resultados da Entrevista
Usuários indicaram necessidade de sistema simples, rápido e intuitivo.
d. Termo de Consentimento
Aplicável caso haja coleta de dados formal para extensão.

6. Versionamento (Git)
O desenvolvimento do projeto PinhAu utiliza controle de versionamento por meio do sistema Git, com hospedagem do repositório na plataforma GitHub. O uso do versionamento permite registrar todas as alterações realizadas no código-fonte ao longo do desenvolvimento, possibilitando acompanhar a evolução do projeto durante as sprints.
O versionamento também garante maior organização, rastreabilidade das modificações e segurança no desenvolvimento, permitindo identificar quando e por quem cada alteração foi realizada.

6.1 Organização dos Commits
Os commits foram realizados de forma incremental, acompanhando a evolução das sprints definidas no planejamento do projeto.
Sprint 1 – Estrutura e Autenticação
Principais commits realizados:
Organização inicial da estrutura de pastas do projeto


Criação das tabelas principais do banco de dados (usuarios e cao)


Implementação da conexão centralizada com o banco de dados


Criação da tela de login do sistema


Implementação do processamento de login com uso de sessões


Proteção das páginas restritas por meio de controle de sessão


Implementação da funcionalidade de logout


Testes de autenticação e redirecionamento de usuários


Sprint 2 – Interface e Usabilidade
Principais commits realizados:
Padronização do cabeçalho e rodapé do sistema


Criação de arquivo de estilos global (CSS)


Melhoria visual da tela de login


Ajuste de botões e navegação para maior clareza


Melhorias de layout visando facilitar o uso por usuários iniciantes


Ajustes de responsividade para acesso em dispositivos móveis


Sprint 3 – Integração e Persistência
Principais commits realizados:
Implementação da inserção de cães vinculados ao tutor


Criação da listagem pública de cães disponíveis para adoção


Implementação da listagem de cães no perfil do tutor


Implementação da funcionalidade de remoção de cães


Implementação da funcionalidade de atualização de dados dos cães


Validação de segurança nas operações de banco de dados


Testes de persistência e funcionamento completo do CRUD


6.2 Benefícios do Versionamento no Projeto
A utilização do Git trouxe diversos benefícios para o desenvolvimento do projeto, tais como:
Registro histórico de todas as alterações realizadas


Organização do desenvolvimento por etapas (sprints)


Facilidade de identificação de erros e correções


Controle da evolução do sistema ao longo do tempo


Possibilidade de colaboração e acompanhamento do progresso do projeto


6.3 Repositório do Projeto
O código-fonte do projeto PinhAu está hospedado em um repositório público na plataforma GitHub, permitindo o controle de versões do sistema e o acompanhamento da evolução do desenvolvimento ao longo das sprints. O repositório contém todos os arquivos necessários para execução do sistema, incluindo código-fonte, estilos, scripts e documentação do projeto.
Link do Repositório
GitHub:
https://github.com/Pinhau/Interdisciplinar_documenta-o

Link do Kanban

Trello:

https://trello.com/b/JMCkNwW3/pinhau-roadmap-e-sprint-1



Estrutura do Repositório
O projeto está organizado em uma estrutura de pastas que separa os diferentes componentes do sistema, facilitando a manutenção e o entendimento do código.
Exemplo de organização do repositório:
pinhau/
│
├── app/
│   └── config/
│       └── conexao.php
│
├── autenticacao/
│   ├── login.php
│   ├── logout.php
│   ├── processamento_login.php
│   └── processamento_cadastro.php
│
├── telas/
│   ├── perfil_tutor.php
│   ├── inserir_cao.php
│   └── alterar_cao.php
│
├── estilos/
│   └── global.css
│
├── js/
│
├── index.php
└── README.md

12. Pasta Extensão
Contempla documentação de ações futuras de extensão e aplicação prática do sistema na comunidade.
