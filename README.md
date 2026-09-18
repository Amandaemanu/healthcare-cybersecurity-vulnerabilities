Sobre o projeto

Este repositório apresenta um estudo sobre vulnerabilidades e riscos de segurança cibernética presentes em sistemas de informação em saúde.

O objetivo é analisar como falhas técnicas, problemas de configuração, vulnerabilidades de software e fatores humanos podem afetar:

confidencialidade dos dados dos pacientes;
integridade das informações clínicas;
disponibilidade dos serviços de saúde;
segurança de sistemas hospitalares;
segurança de dispositivos médicos;
continuidade dos serviços assistenciais.

O projeto combina conceitos de cibersegurança, sistemas de informação em saúde, gestão de riscos e proteção de dados.

Por que cibersegurança em saúde?

Os sistemas de saúde concentram informações altamente sensíveis e dependem cada vez mais de infraestrutura digital.

Um incidente de segurança pode afetar não apenas dados pessoais, mas também a disponibilidade de sistemas utilizados na assistência ao paciente.

Entre os ambientes analisados neste projeto estão:

Prontuários Eletrônicos do Paciente (PEP/EHR);
Sistemas de Informação Hospitalar (HIS);
Sistemas laboratoriais;
Sistemas de farmácia;
APIs de sistemas de saúde;
dispositivos médicos conectados;
infraestrutura de redes hospitalares;
sistemas de telemedicina.
Principais categorias de vulnerabilidades
1. Autenticação

Falhas relacionadas à identificação e autenticação dos usuários.

Exemplos:

senhas fracas;
ausência de MFA;
gerenciamento inadequado de sessões;
políticas inadequadas de senha.
2. Controle de acesso

Falhas que permitem que um usuário acesse informações ou funcionalidades além das suas permissões.

Exemplos:

privilégios excessivos;
ausência de segregação de funções;
IDOR/BOLA;
controles de autorização inadequados.
3. APIs

APIs são componentes importantes da integração entre sistemas de saúde.

Possíveis problemas:

autenticação inadequada;
autorização inadequada;
exposição excessiva de dados;
ausência de rate limiting;
validação insuficiente de entradas.
4. Sistemas legados

Hospitais podem depender de sistemas antigos que apresentam dificuldades de atualização, integração ou substituição.

Serão analisados:

software desatualizado;
dependências antigas;
sistemas sem suporte;
dificuldades de aplicação de patches;
integração com sistemas modernos.
5. Dispositivos médicos

Dispositivos conectados podem ampliar a superfície de ataque de uma organização de saúde.

O projeto abordará questões como:

comunicação insegura;
credenciais padrão;
firmware desatualizado;
interfaces de administração;
integração com redes hospitalares.
Metodologia

As análises serão realizadas utilizando referências públicas, documentação técnica, padrões de segurança e ambientes controlados.

Quando forem utilizados exemplos práticos, eles serão executados exclusivamente em:

aplicações desenvolvidas para laboratório;
ambientes locais;
máquinas virtuais;
sistemas explicitamente destinados a testes de segurança.

Não serão realizados testes não autorizados contra sistemas reais de saúde.

Estrutura do projeto
01-fundamentals/             Fundamentos de segurança em saúde
02-vulnerabilities/          Categorias de vulnerabilidades
03-healthcare-systems/       Análise dos sistemas de saúde
04-case-studies/             Estudos de casos reais
05-standards-and-regulations/ Normas e regulamentações
06-risk-analysis/            Análise e modelagem de riscos
07-labs/                     Ambientes práticos controlados
references/                  Referências bibliográficas
Objetivos
Identificar vulnerabilidades comuns em sistemas de informação em saúde.
Compreender os riscos associados a essas vulnerabilidades.
Relacionar vulnerabilidades técnicas aos impactos para organizações de saúde e pacientes.
Estudar estratégias de prevenção e mitigação.
Desenvolver conhecimentos práticos em cibersegurança aplicada à saúde.
Construir uma base de estudos para futuras pesquisas acadêmicas e profissionais.
Tecnologias e conceitos
Cybersecurity
Information Security
Healthcare Information Systems
OWASP
API Security
Threat Modeling
Risk Assessment
Network Security
Data Protection
Incident Response
Vulnerability Management
Digital Health
Status

🚧 Projeto em desenvolvimento.

Novos estudos de caso, análises técnicas e laboratórios serão adicionados progressivamente.

Aviso ético

Este projeto possui finalidade educacional e de pesquisa.

Todas as atividades práticas devem ser realizadas somente em sistemas próprios, ambientes de laboratório ou sistemas para os quais exista autorização explícita para testes de segurança.

Nenhuma vulnerabilidade será explorada contra sistemas reais sem autorização.
