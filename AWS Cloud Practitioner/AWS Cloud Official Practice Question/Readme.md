### 1.  Quais das seguintes opções são benefícios da Nuvem AWS? (Selecione DUAS respostas.)
- [ ] As empresas precisam de uma equipe de TI maior
- [x] As depesas de capital são substituidas por despesas variáveis
- [ ] Os clientes recebem a mesma fatura mensal, idependente de quais recursos eles usam
- [x] As empreas ganham maior agilidade

### 2. Quais das opções a seguir são vantagens da Nuvem AWS? (Selecione DUAS respostas.)

- [x] A - A AWS gerencia a manutenção da infraestrutura
- [ ] B - A AWS gerencia a segurança de aplicações criadas na AWS
- [x] C - A AWS gerencia o planejamento de capacidade para servidores
- [ ] D - A AWS gerencia o desenvolvimento de aplicações na AWS
- [ ] E - A AWS gerencia o planejamento de custos para servidores virtuais

### 3. Uma empresa exige isolamento físico de suas instâncias Amazon EC2 das instâncias de outros clientes. Qual opção de compra de instâncias atende a esse requisito?

- [x] A - Host dedicados
- [ ] B - Intâncias reservadas
- [ ] C - Instâncias On-demand
- [ ] D - Instância Spot

### 4. Qual princípio da arquitetura da Nuvem AWS afirma que os sistemas devem reduzir as interdependências?

- [ ] A - Escalabilidade
- [ ] B - Serviços, não servidores
- [ ] C - Automação
- [x] D - Acomplamento fraco

### 5. Qual princípio de design da arquitetura da Nuvem AWS é compatível com a distribuição de cargas de trabalho em várias zonas de disponibilidade?

- [ ] A - Implementação de automação
- [ ] B - Design para agilidade
- [x] C - Design à prova de falhas
- [ ] D - Implementação de elasticidade 

C - A AWS recomenda que você distribua as cargas de trabalho em várias zonas de disponibilidade. Essa distribuição garantirá a disponibilidade contínua da aplicação, mesmo que ela não esteja disponível em uma única zona de disponibilidade.

### 6. Qual das seguintes opções é uma responsabilidade da AWS de acordo com o modelo de responsabilidade compartilhada da AWS?

- [ ] Projetar a aplicação do cliente para recuperação de desastres
- [ ] Atualizar os sistemas operacionais convidados em instâncias EC implementadas
- [ ] Configurar novos recursos em uma conta da AWS
- [x] Proteger a infraestrutura fisica

Correto. A AWS mantém totalmente os controles físicos.

Para obter mais informações sobre o modelo de responsabilidade compartilhada, consulte [Modelo de responsabilidade compartilhada](https://aws.amazon.com/pt/compliance/shared-responsibility-model/).

### 7. Qual das opções a seguir descreve uma melhor prática de segurança que pode ser implementada usando o AWS Identity and Access Management (IAM)?

- [ ] A - Desativar o acesso ao Console de Gerenciamento da AWS para todos os usuários
- [ ] B - Gerar chaves secretas para cada usuário da IAM
- [x] C - Conceder permissão a usuários que precisam executar apenas uma tarefa especifica. 
- [ ] D - Amerzenar credências da AWS em instâncias Amazon EC2 

C - Por meio da recomendação de segurança de menor privilégio, uma prática recomendada do IAM é conceder permissões detalhadas aos usuários usando IAM roles.

Para obter mais informações sobre as melhores práticas do IAM e o menor privilégio, consulte [Conceder o menor privilégio](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege).

Para obter mais informações sobre as melhores práticas de proteção de uma conta da AWS, consulte [Quais são algumas das melhores práticas para proteger minha conta da AWS e seus recursos?](https://aws.amazon.com/pt/premiumsupport/knowledge-center/security-best-practices/)

### 8. Uma empresa precisa monitorar e receber alertas sobre eventos de login do Console de Gerenciamento da AWS que envolvem o usuário raiz da conta da AWS.

Qual produto da AWS a empresa pode usar para atender a esses requisitos?

- [x] A - Amaozon Cloud Watch
- [ ] B - AWS Config
- [ ] C - AWS Truested Adivisor
- [ ] D - AWS Identity and Access Managment (IAM)

O CloudWatch monitora os recursos da AWS e as aplicações executadas em tempo real na AWS. Você pode usar o CloudWatch para monitorar e receber alertas sobre eventos de login do console que envolvam o usuário raiz da conta da AWS.

Para obter mais informações sobre o CloudWatch, consulte O que é o Amazon CloudWatch?

Porque não é o Truested Adivsor. É possível usar o Trusted Advisor para fornecer orientações em tempo real para ajudar a provisionar seus recursos de acordo com as melhores práticas da AWS. O Trusted Advisor não pode alertar sobre eventos de login do console que envolvam o usuário raiz da conta da AWS

### 9) Uma empresa tem um servidor de aplicações em execução em uma instância Amazon EC2. O servidor de aplicações precisa acessar o conteúdo em um bucket privado do Amazon S3. Qual é a abordagem recomendada para atender a esse requisito?


- [x] A - Crie uma IAM role com as permissões apropriadas. Associe a role à instância EC2. 
- [ ] B - Configure uma conexão de peering de VPC para permitir a comunicação privada entre a instância EC2 e o bucket do S3.
- [ ] C - Crie uma chave de acesso compartilhada. Configure a instância EC2 para usar a chave codificada.
- [ ] D - Configure a aplicação para ler uma chave de acesso de uma fonte segura.

A -  As IAM roles são credenciais temporárias que expiram. As IAM roles são mais seguras do que as chaves de acesso de longo prazo porque reduzem o risco caso as credenciais sejam expostas acidentalmente.

Para obter mais informações sobre IAM roles, consulte Usar uma IAM role para [conceder permissões a aplicações executadas em instâncias Amazon EC2](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_use_switch-role-ec2.html).

### 10 ) Quais recursos ou serviços relacionados à segurança a AWS oferece? (Selecione DUAS respostas.)

- [ ] A - Compliance completa com PCI para aplicações do cliente executadas na AWS
- [x] B - Verificações de segurança do AWS Trusted Advisor
- [x] C - Criptografia dos dados 
- [ ] D - Teste de penetração automatizado
- [ ] B - Detecção de conteúdo protegido por direitos autorais do Amazon S3


B - Trusted Advisor baseia-se nas melhores práticas aprendidas ao atender centenas de milhares de clientes da AWS. Essas melhores práticas incluem verificações de segurança.

C -  Muitos produtos da AWS são compatíveis com a criptografia de dados, incluindo o Amazon Elastic Block Store (Amazon EBS) e o Amazon S3.

### 11) Quais recomendações estão incluídas nas verificações do AWS Trusted Advisor? (Selecione DUAS respostas.)

A
Permissões de bucket do Amazon S3 (correto)


B
Interrupções de produtos da AWS para serviços


C
Uso de autenticação multifator (MFA) no usuário raiz da conta da AWS (correto)


D
Patches de software disponíveis para instâncias Amazon EC2


E
Número de usuários na conta

A - O Trusted Advisor verifica permissões de bucket do S3 no Amazon S3 com permissões de acesso aberto. As permissões de bucket que concedem acesso de listagem a todos podem resultar em custos superiores aos esperados se os objetos do bucket forem acessados por usuários indesejados com alta frequência. As permissões de bucket que concedem acesso de upload e exclusão a todos os usuários criam possíveis vulnerabilidades de segurança, pois permitem que qualquer pessoa adicione, modifique ou remova itens em um bucket. Essa verificação do Trusted Advisor examina permissões explícitas de bucket e políticas de bucket associadas que podem substituir as permissões de bucket.

C - O Trusted Advisor confere a conta raiz e avisa se a MFA não está habilitada.


### Uma empresa quer uma conexão privada dedicada entre suas operações locais e a Nuvem AWS. Qual recurso ou produto da AWS fornecerá essa conexão?

A
AWS VPN


B
AWS PrivateLink


C
VPC endpoint


D
AWS Direct Connect (correto)

D -  O Direct Connect fornece uma conexão privada dedicada entre suas instalações locais e a Nuvem AWS. O Direct Connect é uma alternativa ao uso da Internet para acessar os serviços de nuvem da AWS.

 Você usa o PrivateLink quando deseja usar os serviços oferecidos por outra VPC com segurança na rede da AWS. Com o PrivateLink, todo o tráfego de rede permanece na estrutura global da AWS e nunca passa pela Internet pública. O PrivateLink não se conecta a operações locais.

 13) Qual aspecto da infraestrutura da AWS fornece implementação global de computação e armazenamento?

 
Várias zonas de disponibilidade em uma região da AWS


B
Várias regiões AWS (Correto)


C
Tags


D
Resource Groups

 B - Uma região é um local físico onde há clusters de datacenters da AWS. A AWS oferece muitas regiões diferentes nas quais é possível implantar infraestrutura em todo o mundo. Com o uso de várias regiões, você pode obter uma implementação global de computação, armazenamento e bancos de dados.

 ### 14) Quais recursos ou produtos da AWS são compatíveis com a replicação de dados em todas as regiões AWS? (Selecione DUAS respostas.)

 
Amazon S3 (correto)


B
Amazon Elastic Block Store (Amazon EBS)


C
Amazon EC2 instance store


D
AWS Storage Gateway


E
Amazon RDS (correto)

A -  O Amazon S3 é compatível com a replicação entre regiões. Com a replicação entre regiões, você designa um bucket do S3 de destino em outra região. Quando a replicação entre regiões estiver ativada, qualquer novo objeto carregado será replicado no bucket do S3 de destino.

E - Você pode usar o Amazon RDS para hospedar bancos de dados relacionais na AWS. Uma instância de banco de dados do RDS reside em uma única região. Com o Amazon RDS, você pode criar réplicas de leitura entre regiões. O Amazon RDS replica todos os dados da instância do banco de dados primário na réplica de leitura entre regiões.

### Uma empresa está hospedando um site estático por meio de um único bucket do Amazon S3.  Qual produto da AWS atingirá latência mais baixa e alta velocidade de transferência?

A
AWS Elastic Beanstalk


B
Amazon DynamoDB Accelerator (DAX)


C
Amazon Route 53


D
Amazon CloudFront (correto)

16) Qual produto da AWS fornece uma solução de armazenamento de arquivos compartilhado, simples e escalável para uso com servidores locais e instâncias Amazon EC2 baseadas em Linux?

A - AWS Managed Services (AMS)
B - Amazon S3 Glacier
C - Amazon Elastic Block Store (Amazon EBS)
D - Amazon Elastic File System (Amazon EFS)

O Amazon EFS fornece um sistema de arquivos elástico que permite compartilhar dados de arquivos sem a necessidade de provisionar e gerenciar o armazenamento. Ele pode ser usado com os serviços de nuvem da AWS e recursos locais, e foi criado visando dimensionar sob demanda para petabytes sem interromper as aplicações. Com o Amazon EFS, é possível aumentar e reduzir seus sistemas de arquivos automaticamente à medida que adiciona e remove arquivos, eliminando a necessidade de provisionar e gerenciar a capacidade para acomodar o crescimento.

Para obter mais informações sobre como usar o Amazon EFS, consulte Passo a passo: Crie e monte um sistema de arquivos no local com o AWS Direct Connect e a VPN.


### Uma empresa precisa de acesso ininterrupto por telefone, e-mail e chat. O tempo de resposta deverá ser inferior a uma hora se um sistema de produção tiver uma interrupção de serviço. Qual plano do AWS Support atende a esses requisitos pelo MENOR custo?


A AWS Basic Support 
B AWS Developer Support
C AWS Business Support (correto)
D AWS Enterprise Support

O plano Business Support fornece acesso ininterrupto por telefone, e-mail e chat. O plano Business Support tem um tempo de resposta inferior a um hora caso um sistema de produção sofra uma interrupção de serviço

O plano Enterprise Support fornece acesso ininterrupto por telefone, e-mail e chat. O plano Enterprise Support tem um tempo de resposta inferior a 15 minutos caso um sistema de produção sofra uma interrupção de serviço. No entanto, o plano Enterprise Support é mais caro do que o Business Support.

### Qual modelo de preço do Amazon EC2 se ajusta com base na oferta e na demanda de instâncias EC2?

Instâncias On-Demand


B
Instâncias reservadas


C
Instâncias Spot (correto)


D
Instâncias reservadas conversíveis

Correto. As instâncias spot são descontadas mais intensamente quando há mais capacidade disponível nas zonas de disponibilidade.

 As instâncias On-Demand são oferecidas a um preço definido de acordo com a região da AWS.

 ### 19) Qual das opções a seguir é uma vantagem do faturamento consolidado na AWS?

 A
Qualificação de preços por volume (correto)


B
Permissões de acesso compartilhado


C
Várias faturas para cada conta


D
Eliminação da necessidade de marcar recursos

A - O faturamento consolidado é um recurso do AWS Organizations. É possível combinar o uso em todas as contas na organização para compartilhar os descontos de preços por volume, os descontos de instância reservada e os Savings Plans. Essa solução pode resultar em uma carga menor em comparação com o uso de contas individuais independentes.

### Qual produto da AWS pode criar um alarme que envia uma notificação quando um limite de faturamento é excedido?

A
AWS Trusted Advisor


B
AWS CloudTrail


C
Amazon CloudWatch (correto)


D
Amazon QuickSight


. Você pode monitorar suas cobranças estimadas da AWS usando o CloudWatch. Quando você ativa o monitoramento de cobranças estimadas em sua conta da AWS, elas são calculadas e enviadas várias vezes ao dia para o CloudWatch como dados de métrica.

Para obter mais informações sobre o CloudWatch, consulte [Criação de um alarme de faturamento para monitorar as cobranças estimadas da AWS.](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html)