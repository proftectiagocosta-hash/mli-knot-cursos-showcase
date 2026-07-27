# Security Policy / Política de Segurança

[English](#english) | [Português](#português)

---

## English

### Scope

This repository is a public, sanitized showcase of the private MLI-Knot-Cursos project.

It contains documentation, fictional examples, conceptual flows, public-safe screenshots, and roadmap material. It is not the production platform and must not receive direct copies of private source code, real user records, production configuration, or unrevised internal material.

### Sensitive material that must not be published

Do not publish:

- real student, teacher, guardian, staff, or user data;
- names, email addresses, phone numbers, addresses, identifiers, enrollment numbers, attendance records, grades, progress records, or account details tied to real people;
- real screenshots containing accounts, dashboards, messages, certificates, payments, personal profiles, or browser/session information;
- credentials, passwords, tokens, API keys, cookies, secrets, environment files, or authentication data;
- payment details, billing records, bank information, transaction identifiers, invoices, or financial credentials;
- production backend details, database contents, internal endpoints, access-control rules, deployment secrets, or infrastructure identifiers;
- private course content, licensed instructional material, unreleased classes, assessments, answer keys, or copyrighted assets without publication rights;
- official certificates, validation codes, signatures, QR codes, serial numbers, or records that could be mistaken for an issued credential;
- raw logs, exports, backups, database dumps, support conversations, or unrevised internal notes;
- private source code or history copied from the main MLI-Knot-Cursos repository.

When examples are necessary, use fictional names, synthetic values, placeholder identifiers, generic screenshots, and clearly non-production data.

### Screenshots and visual material

Before publishing an image, video, PDF, diagram, or screen recording:

1. remove or replace real names and identifiers;
2. remove profile photos and personal images;
3. remove browser tabs, paths, notifications, account menus, and session details;
4. remove payment, certificate, enrollment, and progress records tied to real people;
5. confirm that metadata and filenames do not reveal private context;
6. verify that the material cannot be combined with other public information to identify a person or reconstruct a private environment.

Blurring is not always sufficient. Prefer recreating the image with fictional data.

### Security-relevant reports

A report is security-relevant when it concerns:

- accidental exposure of personal, educational, financial, authentication, or private project data;
- a public file that reveals private source material, internal architecture, credentials, secrets, or production details;
- a screenshot, example, certificate, or document that can identify a real person;
- a link or artifact that grants unintended access to private content;
- repository history that still contains removed sensitive material;
- impersonation, misleading official-certificate claims, or misuse of the MLI-Knot/Tendoshk identity to suggest endorsement.

Typos, broken links, formatting errors, translation issues, and purely conceptual inaccuracies are usually documentation issues rather than security vulnerabilities, unless they expose or direct users to sensitive material.

### Reporting a vulnerability or accidental exposure

Do not reproduce sensitive material in a public issue, discussion, pull request, review comment, or screenshot.

Use GitHub private vulnerability reporting when available. If it is unavailable, contact the maintainer through a private channel listed on the maintainer's GitHub profile.

Provide only the minimum information required for safe investigation:

- affected file, path, commit, release, or page;
- general type of exposed data;
- whether the material is still publicly accessible;
- steps needed to locate the issue without repeating the sensitive value;
- potential impact;
- sanitized screenshots or logs, when necessary.

Do not send real passwords, complete tokens, full payment data, private student records, private course material, or unredacted personal documents.

### Incident response

When sensitive material is confirmed, the maintainer should evaluate the need to:

1. stop further publication;
2. remove the content from the current public tree;
3. assess affected commits, branches, releases, artifacts, caches, and forks;
4. rotate or revoke exposed credentials and secrets;
5. notify affected people or services when appropriate;
6. rewrite or purge public history when deletion from the latest commit is insufficient;
7. replace examples with fictional, sanitized material;
8. document the correction without repeating the exposed content.

Deleting a file from the latest commit does not remove it from earlier history.

### Public showcase limitation

This repository does not provide a production student-management system, payment platform, official certification service, authentication service, or data-processing environment.

Security guarantees for the private project, future deployments, third-party integrations, or systems inspired by this documentation are outside this repository's public scope.

---

## Português

### Escopo

Este repositório é uma vitrine pública e sanitizada do projeto privado MLI-Knot-Cursos.

Ele contém documentação, exemplos fictícios, fluxos conceituais, capturas seguras para publicação e material de roadmap. Ele não é a plataforma de produção e não deve receber cópias diretas de código-fonte privado, registros reais de usuários, configuração de produção ou material interno não revisado.

### Material sensível que não deve ser publicado

Não publique:

- dados reais de alunos, professores, responsáveis, funcionários ou usuários;
- nomes, endereços de e-mail, telefones, endereços físicos, identificadores, números de matrícula, registros de frequência, notas, progresso ou dados de contas vinculados a pessoas reais;
- capturas reais contendo contas, painéis, mensagens, certificados, pagamentos, perfis pessoais ou informações de navegador e sessão;
- credenciais, senhas, tokens, chaves de API, cookies, segredos, arquivos de ambiente ou dados de autenticação;
- informações de pagamento, registros de cobrança, dados bancários, identificadores de transação, faturas ou credenciais financeiras;
- detalhes do backend de produção, conteúdo de banco de dados, endpoints internos, regras de controle de acesso, segredos de implantação ou identificadores de infraestrutura;
- conteúdo privado de cursos, material didático licenciado, aulas ainda não publicadas, avaliações, gabaritos ou ativos protegidos sem direito de publicação;
- certificados oficiais, códigos de validação, assinaturas, QR codes, números de série ou registros que possam ser confundidos com uma credencial emitida;
- logs brutos, exportações, backups, dumps de banco, conversas de suporte ou notas internas não revisadas;
- código-fonte privado ou histórico copiado do repositório principal MLI-Knot-Cursos.

Quando exemplos forem necessários, utilize nomes fictícios, valores sintéticos, identificadores placeholder, capturas genéricas e dados claramente não produtivos.

### Capturas e material visual

Antes de publicar imagem, vídeo, PDF, diagrama ou gravação de tela:

1. remova ou substitua nomes e identificadores reais;
2. remova fotografias de perfil e imagens pessoais;
3. remova abas do navegador, caminhos, notificações, menus de conta e detalhes de sessão;
4. remova registros de pagamento, certificado, matrícula e progresso vinculados a pessoas reais;
5. confirme que metadados e nomes de arquivos não revelem contexto privado;
6. verifique se o material não pode ser combinado com outras informações públicas para identificar uma pessoa ou reconstruir um ambiente privado.

Desfocar informações nem sempre é suficiente. Prefira recriar a imagem com dados fictícios.

### Relatos relevantes para segurança

Um relato é relevante para segurança quando envolve:

- exposição acidental de dados pessoais, educacionais, financeiros, de autenticação ou do projeto privado;
- arquivo público que revele código privado, arquitetura interna, credenciais, segredos ou detalhes de produção;
- captura, exemplo, certificado ou documento capaz de identificar uma pessoa real;
- link ou artefato que conceda acesso não intencional a conteúdo privado;
- histórico do repositório que ainda contenha material sensível removido da árvore atual;
- falsificação, alegação enganosa de certificado oficial ou uso indevido da identidade MLI-Knot/Tendoshk para sugerir endosso.

Erros de digitação, links quebrados, problemas de formatação, tradução e imprecisões puramente conceituais normalmente são problemas de documentação, e não vulnerabilidades, exceto quando expõem ou direcionam para material sensível.

### Como relatar vulnerabilidade ou exposição acidental

Não reproduza material sensível em issue, discussão, Pull Request, comentário de revisão ou captura pública.

Utilize o relato privado de vulnerabilidade do GitHub quando estiver disponível. Caso não esteja, contate o mantenedor por um canal privado indicado no perfil do mantenedor no GitHub.

Forneça somente o mínimo necessário para uma investigação segura:

- arquivo, caminho, commit, release ou página afetada;
- tipo geral de dado exposto;
- indicação se o material ainda está acessível publicamente;
- passos para localizar o problema sem repetir o valor sensível;
- impacto potencial;
- capturas ou logs sanitizados, quando necessários.

Não envie senhas reais, tokens completos, dados integrais de pagamento, registros privados de alunos, conteúdo privado de cursos ou documentos pessoais sem ocultação.

### Resposta a incidentes

Quando material sensível for confirmado, o mantenedor deverá avaliar a necessidade de:

1. interromper novas publicações;
2. remover o conteúdo da árvore pública atual;
3. avaliar commits, branches, releases, artefatos, caches e forks afetados;
4. revogar ou substituir credenciais e segredos expostos;
5. notificar pessoas ou serviços afetados quando apropriado;
6. reescrever ou limpar o histórico público quando a exclusão no commit mais recente for insuficiente;
7. substituir exemplos por material fictício e sanitizado;
8. documentar a correção sem repetir o conteúdo exposto.

Excluir um arquivo no commit mais recente não o remove do histórico anterior.

### Limitação da vitrine pública

Este repositório não fornece um sistema de produção para gestão de alunos, plataforma de pagamentos, serviço oficial de certificação, serviço de autenticação ou ambiente de processamento de dados.

Garantias de segurança do projeto privado, de implantações futuras, de integrações de terceiros ou de sistemas inspirados nesta documentação estão fora do escopo público deste repositório.
