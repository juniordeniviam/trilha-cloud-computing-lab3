### Computação em nuvem - Laboratório DIO <br/><br/>

**Resumo sobre como configurar uma instância de Banco de Dados via Azure**
<br/>

A Azure oferece vários serviços gerenciados para diferentes tipos de bancos de dados, como:<br/>
- Azure SQL Database: Banco de dados relacional compatível com SQL Server.
- Azure Database for MySQL: Gerenciamento de bancos de dados MySQL.
- Azure Database for PostgreSQL: Banco de dados gerenciado para PostgreSQL.
- Azure Cosmos DB: Banco de dados NoSQL multimodelo.
________________________________________________________________________________________________________________________________________________________________________________________

**Configuração Básica**
- Nome do Banco de Dados: Definir um nome único para a instância.
- Região: Escolher a região onde o banco de dados será hospedado para otimizar a latência e conformidade.
- Recursos (CPU, memória, armazenamento): Escolha das especificações técnicas de computação e armazenamento, ajustando conforme a carga esperada.
- Backup e Redundância: Configurar políticas de backup automático e redundância de dados (local, zona de disponibilidade ou geograficamente redundante).
________________________________________________________________________________________________________________________________________________________________________________________

**Segurança e Acesso**
- Firewall: Configurar as regras de firewall para permitir o acesso ao banco de dados apenas a partir de IPs ou redes específicas.
- Autenticação: Escolher o método de autenticação (SQL Authentication ou Azure AD Authentication).
- Criação de Usuários e Permissões: Gerenciar usuários do banco de dados e atribuir permissões apropriadas para cada um, garantindo controle de acesso baseado em papéis.
________________________________________________________________________________________________________________________________________________________________________________________

**Escalabilidade Dinâmica**
- Aumentar ou diminuir a capacidade de processamento e armazenamento sem interrupção de serviço.
- Backup Automático e Recuperação: Backups regulares e opções de restauração de ponto no tempo garantem a proteção dos dados.
________________________________________________________________________________________________________________________________________________________________________________________

**Segurança Gerenciada**
- A Azure oferece criptografia de dados, firewall, autenticação baseada em Azure AD, e monitoramento de ameaças.
________________________________________________________________________________________________________________________________________________________________________________________
<br/>

Com esse processo simplificado e gerenciado pela Azure, o usuário pode focar na administração e otimização de seus dados, sem se preocupar com a infraestrutura subjacente.
