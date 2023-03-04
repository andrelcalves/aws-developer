### 1.  Quais das seguintes opções são benefícios da Nuvem AWS? (Selecione DUAS respostas.)

- [x] As depesas de capital são substituidas por despesas variáveis
- [x] As empreas ganham maior agilidade

### 2. Quais das opções a seguir são vantagens da Nuvem AWS? (Selecione DUAS respostas.)

- [x] A AWS gerencia a manutenção da infraestrutura
- [x] A AWS gerencia o planejamento de capacidade para servidores

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

Qual das seguintes opções é uma responsabilidade da AWS de acordo com o modelo de responsabilidade compartilhada da AWS?

* Projetar a aplicação do cliente para recuperação de desastres
* Atualizar os sistemas operacionais convidados em instâncias EC implementadas
* Configurar novos recursos em uma conta da AWS
* Proteger a infraestrutura fisica (correto)

Correto. A AWS mantém totalmente os controles físicos.

Para obter mais informações sobre o modelo de responsabilidade compartilhada, consulte [Modelo de responsabilidade compartilhada](https://aws.amazon.com/pt/compliance/shared-responsibility-model/).

Qual das opções a seguir descreve uma melhor prática de segurança que pode ser implementada usando o AWS Identity and Access Management (IAM)?

* A - Desativar o acesso ao Console de Gerenciamento da AWS para todos os usuários
* B - Gerar chaves secretas para cada usuário da IAM
* C - Conceder permissão a usuários que precisam executar apenas uma tarefa especifica. (correta)
* D - Amerzenar credências da AWS em instâncias Amazon EC2 

C - Por meio da recomendação de segurança de menor privilégio, uma prática recomendada do IAM é conceder permissões detalhadas aos usuários usando IAM roles.

Para obter mais informações sobre as melhores práticas do IAM e o menor privilégio, consulte [Conceder o menor privilégio](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege).

Para obter mais informações sobre as melhores práticas de proteção de uma conta da AWS, consulte [Quais são algumas das melhores práticas para proteger minha conta da AWS e seus recursos?](https://aws.amazon.com/pt/premiumsupport/knowledge-center/security-best-practices/)

8) Uma empresa precisa monitorar e receber alertas sobre eventos de login do Console de Gerenciamento da AWS que envolvem o usuário raiz da conta da AWS.

Qual produto da AWS a empresa pode usar para atender a esses requisitos?

A - Amaozon Cloud Front (correto)
B - AWS Config
C - AWS Truested Adivisor
D - AWS Identity and Access Managment (IAM)

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