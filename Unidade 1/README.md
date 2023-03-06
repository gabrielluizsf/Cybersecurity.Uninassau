# **Segurança da Informação**
Conteúdo aprendido na cadeira de segurança de informação da Universidade Uninassau Caruaru :brazil:

## **Unidade 1**

### **Apresentação**

#### A disciplina tem como premissa permitir que o aluno possa desenvolver uma visão abrangente da área, compreendendo o papel dela nas organizações a partir dos aspectos que envolvem tal atividade, por meio de métodos, ferramentas e controles de acesso, permitindo a realização de análises de riscos, vulnerabilidades e ameaças nos sistemas de informação de uma organização.

#### Nos dias atuais, as organizações têm reconhecido a importância de haver obstáculos que protejam a informação privada de se tornar pública, especialmente quando essa informação é privilegiada. De fato, relatórios recentes têm revelado descobertas que expressam a necessidade de que haja pessoal de segurança de informações qualificado, com base nas previsões e preocupações em relação aos ataques cibernéticos.

#### A necessidade de se implementar recomendações a profissionais qualificados para a segurança das organizações é crescente: as empresas estão se esforçando para alocar mais recursos financeiros para a segurança.

#### Nesse contexto, a disciplina busca trazer ao aluno bases de conhecimento para que possa gerenciar recursos de infraestrutura física e lógica dos ambientes de sistemas de informação. Assim, poderá realizar análise de risco, e detectar ameaças e reduzir sua ocorrência, além de avaliar, analisar e implantar sistemas mais seguros, elaborando um plano de auditoria.

____ 

### **Segurança da informação e suas ameaças**

Professor Rafael Ramos Gomes

**OBJETIVO DA UNIDADE**

    Trazer ao aluno os conceitos de segurança da informação, do ponto de vista ético e profissional;

    Mostrar as ameaças e os riscos à informação;

    Abordar os tipos de malware e suas anatomias.


**TÓPICOS DE ESTUDO**

**Visão geral da segurança da informação**


        De 1960 à atualidade

        Conceitos de segurança da informação 

        Características da informação

        Política-base de segurança de TI

**Ameaças emergentes e análise de risco**

        Definição de risco e seus elementos

**Malware**

            Virus e worm

            Backdoor

            Adware, spyware e ransomware

____

### **Visão geral da segurança da informação**

Não devemos subestimar o impacto de incidentes de segurança, que podem levar à perda de dados, vazamentos de informações pessoais, desperdício de tempo e disseminação de vírus. Essa preocupação, porém, já existia em tempos remotos: a história da segurança da informação começa com a segurança do computador. 

A necessidade de proteger locais físicos, hardware e software contra ameaças surgiu ainda durante a Segunda Guerra Mundial, quando as primeiras máquinas desenvolvidas para auxiliar os cálculos de quebra de código em comunicação foram colocadas em uso.

Vários níveis de segurança foram implementados para proteger tais equipamentos e manter a integridade de seus dados. O acesso a informações sensíveis em zonas militares, por exemplo, era controlado por meio de crachás, chaves e reconhecimento do pessoal autorizado pelos guardas de segurança. A crescente necessidade de manter a proteção acabou levando a uma segurança informática mais complexa e tecnologicamente mais sofisticada. 

Durante aqueles primeiros anos, a segurança da informação era um processo direto composto predominantemente por segurança física e esquemas simples de classificação de documentos. As ameaças primárias à segurança consistiam no roubo físico de equipamentos, em espionagem contra os produtos dos sistemas e em sabotagem.

#### **EXPLICANDO:** 
Um dos primeiros problemas de segurança detectados e documentados ocorreu no ano de 1960, quando um administrador de sistemas estava trabalhando em um arquivo de “mensagem do dia”, e outro administrador estava editando a senha do arquivo. Um bug de software misturou os dois arquivos, e a senha do arquivo foi armazenada no arquivo final. 

Com a crescente ocorrência de problemas de tal natureza, foi possível segmentar a segurança da informação em períodos bem distintos.

**DE 1960 À ATUALIDADE**

Durante a Guerra Fria, vários computadores foram dispostos a operar on-line para realizar tarefas sofisticadas, como por exemplo o IBM 701 (conhecido como Calculadora da Defesa), que interligava centrais de defesa aérea continental a bunkers terrestres, nos EUA. Este computador não foi o primeiro adotado para realizar tais ações em um contexto de guerra. Durante a Segunda Guerra Mundial, uma máquina de criptografia denominada Enigma (Figura 1) já havia sido usada para (des)criptografar códigos de guerra.

A partir das décadas seguintes, foi necessário que esses computadores se comunicassem por meio de um processo menos complicado do que o envio de fitas magnéticas entre os centros de computação, até então usual. Em resposta a tal necessidade, a Agência de Projetos de Pesquisa Avançada (ARPA) começou a examinar a viabilidade de um sistema redundante de comunicação em rede para apoiar a troca de informações dos militares. Larry Roberts, conhecido como o fundador da Internet, concebeu e desenvolveu o projeto, que foi chamado de ARPANET. De certa forma, pode-se dizer que a ARPANET é a predecessora da internet. 

**CURIOSIDADE:**
Os britânicos e norte-americanos conseguiram, após a guerra, quebrar versões mais complexas da máquina. Como no caso da “submarino”, que causou constrangimento considerável às forças aliadas. A informação retirada após descriptografarem foi útil para antecipar ações das forças armadas alemãs. 

Na década seguinte, a ARPANET se tornou popular e mais amplamente utilizada, e seu uso indevido cresceu. Em dezembro de 1973, Robert M. “Bob” Metcalfe, a quem é creditado o desenvolvimento do padrão Ethernet, um dos mais populares protocolos de rede, identificou um problema significativo relacionado à segurança da ARPANET: sites remotos individuais não usavam controles, tampouco dispunham de proteções para preservar os dados de usuários remotos não autorizados. Após esse problema, outros foram encontrados:

    Vulnerabilidade de estrutura e formatos de senha;

    Ausência de procedimentos de segurança para conexões discadas;

    Identificação inexistente de usuário e autorização para o sistema.

Números de telefone foram amplamente distribuídos e publicamente divulgados nas paredes de cabines telefônicas, oferecendo aos hackers acesso fácil à ARPANET. Devido ao alcance e à frequência do computador, violações de segurança e à explosão no número de hosts e usuários na ARPANET, a rede foi rotulada como insegura. Em 1978, um famoso estudo intitulado “Relatório Final de Análise de Proteção” foi publicado, tendo como objetivo relatar, por iniciativa da própria ARPA, as vulnerabilidades da segurança da rede. 

O movimento em direção à segurança que alcançou resultados além da proteção de locais físicos começou com um único relatório patrocinado pelo Departamento de Defesa Norte-Americano, que tentou definir os múltiplos controles e mecanismos necessários à proteção de um sistema de computador multinível. O documento foi sigiloso por quase dez anos e agora é considerado o início do estudo da segurança informática.

A segurança dos sistemas, compartilhando recursos dentro do Departamento de Defesa, foi trazida à atenção dos pesquisadores na primavera e no verão de 1967. Àquela época, os sistemas estavam sendo adquiridos em um ritmo rápido, e assegurá-los era uma preocupação urgente para ambos os contratantes, militares e de defesa.

Em junho de 1967, a Agência de Projetos de Pesquisa Avançada formou uma força-tarefa para estudar o processo de garantia de sistemas de informação classificados. A força-tarefa foi montada em outubro de 1967 e se reuniu regularmente para formular recomendações, que acabaram se tornando o conteúdo do Relatório Rand R-609. Esse relatório foi o primeiro documento publicado amplamente reconhecido a identificar o papel das questões de gestão e política na segurança informática. Foi observado que a ampla utilização de componentes de rede em sistemas de informação nas forças armadas introduziu riscos de segurança que não poderiam ser mitigados pelas práticas de rotina usadas para proteger esses sistemas. 

Esse relatório sinalizou um momento crucial no histórico de segurança do computador – quando o escopo de segurança expandiu significativamente a partir da segurança de locais físicos e hardware para incluir as seguintes premissas:

- Proteger os dados
- Limitar acesso aleatório e não autorizado a esses dados
- Envolver pessoal de vários níveis da organização em assuntos relacionados a segurança da informação

Grande parte da pesquisa inicial sobre segurança de computadores centrou-se em um sistema chamado Serviço de Informação e Computação Multiplexada (MULTICS). Embora seja obsoleto, hoje em dia, o MULTICS é digno de reconhecimento, porque foi o primeiro sistema operacional a integrar segurança em suas funções principais. Foi um mainframe (um computador de grande porte dedicado normalmente ao processamento de um volume enorme de informações), contendo um sistema operacional de compartilhamento de tempo desenvolvido no meio da década de 1960 por um consórcio da General Electric (GE), Bell Labs e do Massachusetts Institute of Technology (MIT).

Em meados de 1969, pouco após a reestruturação do projeto MULTICS, vários de seus desenvolvedores (Ken Thompson, Dennis Ritchie, Rudd Canaday e Doug McIlroy) criaram um sistema operacional chamado UNIX. Enquanto o sistema MULTICS implementou múltiplos níveis e senhas, o sistema UNIX não o fez. Sua função principal, processamento de texto, não exigia o mesmo nível de segurança que o de seu predecessor. Na verdade, só no início dos anos 1970 o componente mais simples de segurança, a função de senha, tornou-se um componente do UNIX.

Ao final dos anos 1970, o microprocessador trouxe o computador pessoal a uma nova era de computação. O PC tornou-se o cavalo de batalha da computação moderna, tirando-a da função de centro de dados. Essa descentralização dos sistemas de processamento de dados nos anos 1980 deu origem à interconexão em rede, ou seja, a interconexão de computadores pessoais e computadores servidores, o que permitiu que a comunidade global de computação fizesse todos os seus recursos funcionarem juntos.

Ao final do século XX, as redes de computadores se tornaram mais comuns, assim como a necessidade de conectar essas redes umas às outras. Isso deu origem à internet, a primeira rede global. A internet foi disponibilizada ao público geral nos anos 1990, tendo sido anteriormente um domínio do governo, da academia e da indústria dedicada a profissionais. Ela trouxe conectividade a praticamente todos os computadores que pudessem dispor de uma linha telefônica ou uma rede local (LAN) conectada à internet. 

Depois que a internet foi comercializada, a tecnologia foi difundida, alcançando quase todo o globo com uma variedade crescente de usuários. Desde a sua criação como uma ferramenta para compartilhar informações do Departamento de Defesa, a internet tem se tornado uma interconexão de milhões de redes. 

No início, essas conexões foram baseadas em normas de fato, porque os padrões da indústria para a interconexão de redes não existiam naquele momento. Esses padrões pouco fizeram para garantir a segurança da informação, embora essas tecnologias precursoras tenham sido amplamente adotadas e se tornado padrões da indústria, ao introduzirem um certo grau de segurança. No entanto, a segurança precoce da implantação da internet tratou o fenômeno como uma baixa prioridade. 

De fato, muitos dos problemas que afligem os e-mails na internet atualmente são o resultado dessa falta precoce de segurança. Naquela época, quando todos os usuários de internet e e-mail, teoricamente confiáveis, eram cientistas da computação, a autenticação de servidor e a criptografia de e-mail não pareciam necessárias. 

As abordagens iniciais de computação dependiam da segurança que foi construída no ambiente físico dos Data Centers, que abrigavam os computadores. Como a rede de computadores se tornou o estilo dominante de computação, a capacidade de proteger fisicamente uma rede foi se perdendo e as informações armazenadas ficaram mais expostas a ameaças de segurança.

Hoje, a internet é ampla, com possibilidade de haver diferentes dispositivos conectados com algum tipo de vulnerabilidade diferente que, se afetados, podem comprometer as redes de computadores. Atualmente, é vista uma consciência crescente da necessidade de melhorar a segurança da informação, a ponto de se afirmar que tal tópico de conhecimento é importante para a defesa nacional. 

A crescente ameaça de ataques cibernéticos tornou governos e empresas mais conscientes da necessidade de defender sistemas de comando e controle, e outras infraestruturas críticas. Há também crescente preocupação com os países envolvidos na guerra de informação e a possibilidade de os sistemas de informações pessoais e de negócios estarem expostos a ações indevidas.

### ***CONCEITOS DE SEGURANÇA DA INFORMAÇÃO***

Conforme deixa claro o autor Edison Fontes ao longo de seu livro Segurança da informação: o usuário faz a diferença, de 2006, segurança da informação é o conjunto de orientações, normas, procedimentos, políticas e demais ações que têm por objetivo proteger a informação, possibilitando que o negócio da organização seja realizado e sua missão seja alcançada.

Vários termos e conceitos são essenciais a qualquer discussão em segurança da informação, como:

**ACESSO**

Usuários autorizados têm acesso legal a um sistema; hackers, não. Controles de acesso regulam essa habilidade.

**ATIVO**

É o recurso organizacional que está sendo protegido. Um ativo pode ser físico, como um computador, ou objeto tangível ou lógico, como informações e dados. Ativos de informação são o foco dos esforços de segurança, ou seja, esforços que estão tentando proteger.

**ATAQUE**

Um ato intencional ou não intencional que pode causar danos ou comprometer informações e/ou os sistemas que o suportam. Os ataques podem ser ativos ou passivos, intencionais ou não intencionais, e diretos ou indiretos. A situação de alguém lendo casualmente informações não destinadas ao seu uso configura um ataque passivo. Um hacker tentando invadir um sistema de informação, por sua vez, diz respeito a um ataque intencional. Um relâmpago que causa um fogo em um prédio é um ataque não intencional. Em outro exemplo, um ataque direto é um hacker usando um computador para invadir um sistema; um ataque indireto é um hacker comprometer um sistema e usá-lo para invadir outros sistemas, por exemplo, como parte de uma botnet (gíria para “rede de robôs”). Este grupo de computadores comprometidos, executando software de escolha do atacante, pode operar de forma autônoma ou sob o controle direto do atacante para atacar sistemas e roubar informações do usuário ou realizar ataques distribuídos de negação de serviço. Ataques diretos se originam da ameaça em si. Os ataques indiretos se originam de um sistema comprometido ou recurso que está funcionando mal ou está sob o controle de uma ameaça.

**CONTROLE, SALVAGUARDA OU CONTRAMEDIDA**

Mecanismos, políticas ou procedimentos de segurança que podem combater ataques com sucesso, reduzir riscos, resolver vulnerabilidades e outras melhorias de segurança dentro de uma organização.

**EXPLOIT**

Trecho de software ou sequência de comandos ou dados usados para explorar potenciais vulnerabilidades de um sistema. Agentes de ameaças podem tentar explorar um sistema ou outro ativo de informação usando-o ilegalmente para seu ganho pessoal. Um exploit também pode ser um processo documentado para tirar vantagem de uma vulnerabilidade ou exposição, geralmente em software, que é inerente ao software ou é criado pelo atacante. Exploits fazem uso de ferramentas de software existentes ou componentes de software personalizados.

**EXPOSIÇÃO**

Uma condição ou estado de exposição. Em segurança da informação, a exposição existe quando uma vulnerabilidade conhecida de um invasor está presente.

**PERDA**

Uma única instância de um ativo de informação que sofreu danos ou modificação, ou ainda divulgação não autorizada. Quando as informações de uma organização são roubadas, há uma perda.

**PERFIL DE PROTEÇÃO OU POSTURA DE SEGURANÇA**

Todo conjunto de controles e salvaguardas, incluindo política, educação, treinamento, conscientização e tecnologia que a organização implementa (ou falha em implementar) para proteger o ativo. Às vezes, os termos são usados de forma intercambiável com o termo “programa de segurança”, embora esse programa geralmente inclua aspectos gerenciais de segurança, incluindo planejamento pessoal e programas subordinados.

**RISCO**

É a probabilidade de algo indesejado acontecer. As organizações devem minimizar o risco para corresponder à quantidade e à natureza do risco que estão dispostas a aceitar.

**ATACANTES E ALVOS**

Um computador pode ser o autor de um ataque, um agente usado para conduzir o ataque ou o alvo de um ataque. Um computador pode ser atacante e alvo de um ataque, quando, por exemplo, ele é comprometido por um ataque (alvo) e é usado para atacar outros sistemas (atacantes).
AMEAÇA

Risco ou possível perigo de que uma situação, objeto ou determinada circunstância possa levar para sua própria vida ou de terceiros. Ameaças estão sempre presentes e podem ser intencionais ou não direcionadas. Por exemplo, hackers intencionalmente ameaçam sistemas de informação desprotegidos, enquanto tempestades severas incidentalmente ameaçam edifícios e seu conteúdo.

**AGENTE DE AMEAÇA**

É a instância específica ou um componente de uma ameaça. Por exemplo, todos os hackers no mundo apresentam uma ameaça coletiva, enquanto Kevin Mitnick, que foi condenado por invadir sistemas de telefonia, é um agente de ameaça específica. Da mesma forma, um relâmpago, granizo, ou tornado é um agente de ameaça que faz parte da ameaça de tempestades severas.

**VULNERABILIDADE**

Deficiências ou falhas em um sistema ou mecanismo de proteção que o tornam vulnerável a ataques ou danos. Alguns exemplos de vulnerabilidades são uma falha em um pacote de software, uma porta do sistema desprotegida e uma porta destrancada. Algumas vulnerabilidades conhecidas foram examinadas, documentadas e publicadas, outras permanecem latentes ou não descobertas.

____

**CARACTERÍSTICAS DA INFORMAÇÃO**

O valor da informação vem das características que possui. Quando se observa uma característica de mudanças nas informações, o valor dessas informações aumenta ou, mais comumente, diminui. 

Algumas características afetam o valor da informação para alguns dos usuários mais do que para outros. Isso pode depender das circunstâncias: por exemplo, a pontualidade da informação pode ser um fator crítico, porque a informação perde muito ou todo o seu valor quando é entregue tarde demais. 

Embora os profissionais de segurança da informação e usuários finais compartilhem uma compreensão das características da informação, tensões podem surgir quando há necessidade de proteger as informações de conflitos de ameaças ao tempo em que haja necessidade dos usuários finais de possuir acesso irrestrito às informações. Por exemplo, usuários finais podem perceber um atraso de um décimo de segundo no cálculo de dados a ponto de isso se tornar um desnecessário aborrecimento. 

Os profissionais de segurança da informação, no entanto, podem perceber o décimo de segundo como um pequeno atraso que permite a realização de uma tarefa importante, como a criptografia de dados.

Autenticação, autorização e não repúdio são requisitos que projetistas de sistemas podem usar para manter a segurança do sistema com respeito à confidencialidade, integridade e disponibilidade (CID). Compreender cada um desses seis conceitos e como eles se relacionam uns com os outros ajuda os profissionais de segurança da informação a projetarem e implementarem sistemas seguros. 

Cada componente é crítico para a segurança geral, sendo a falha de qualquer componente isolado um potencial ponto de comprometimento do sistema. Assim, profissionais de segurança da informação devem ser dedicados a assegurar a proteção dos princípios da tríade CID, além da importância de compreenderem os conceitos de autenticação, autorização e não repúdio. 

A seguir, são explicados cada um desses conceitos e como eles se relacionam uns aos outros na área da segurança digital. Todas as definições foram extraídas do documento National Information Assurance Glossary (NIAG), glossário publicado pelo Comitê de Sistemas de Segurança Nacional (CNSS) dos Estados Unidos em 2010.

**Autenticação**

A autenticação é importante para qualquer sistema seguro e é a chave para se verificar a origem de uma mensagem ou qual indivíduo é reivindicado por ela. A edição de 2010 do NIAG define autenticação como uma “medida de segurança destinada a estabelecer a validade de uma transmissão, uma mensagem, originador ou um meio de verificar um indivíduo autorizado a receber categorias específicas de informação”.

Existem muitos métodos disponíveis para autenticar uma pessoa. Em cada método, o autenticador lança um desafio que uma pessoa deve responder. Esse desafio normalmente consiste em solicitar uma informação que apenas usuários autênticos podem fornecer. Essas informações caem nas três classificações conhecidas como fatores de autenticação.

<img src="https://sereduc.blackboard.com/bbcswebdav/library/Library%20Content/%28LMS%29%20-%20Do%20Not%20Delete/%28LMS%29%20DOL%20-%20Do%20Not%20Delete/SCORM/FUNDAMENTOS%20EM%20SEGURAN%C3%87A%20DA%20INFORMA%C3%87%C3%83O/UNIDADE%201/scormcontent/assets/cjMFKlJer-Oe32i0_BiWY7Nn7crVJfITs.png"/>

Quando um sistema de autenticação requer mais de um dos fatores do quadro 1, a comunidade de segurança classifica o evento como um sistema que requer autenticação em multifatores. Duas instâncias do mesmo fator, como uma senha combinada com o nome de solteira da mãe do usuário, por exemplo, não é autenticação em multifatores, mas a combinação de uma digitalização de impressões digitais e um número de identificação pessoal (PIN) não constitui, já que valida algo que o usuário é (o proprietário dessa impressão digital) e algo que o usuário sabe (um PIN).

A autenticação também se aplica à validação da origem de uma mensagem, como um pacote de rede ou e-mail. Em um nível baixo, a autenticação de sistemas de mensagens não pode confiar nos mesmos fatores que se aplicam à autenticação. Sistemas de autenticação de mensagens geralmente dependem de criptografia de assinaturas, que consistem em um resumo ou hash da mensagem, gerados com uma chave secreta. Como apenas uma pessoa tem acesso à chave que gera a assinatura, o destinatário é capaz de validar o remetente de uma mensagem.

Sem um sistema de autenticação de som, por exemplo, é impossível confiar que um usuário é quem diz ser, ou que uma mensagem é de quem afirma ser.

**Autorização**

Embora a autenticação esteja relacionada à verificação de identidades, a autorização se concentra em determinar o que um usuário tem permissão para fazer. De acordo com o NIAG, a definição de autorização é: “privilégios de acesso concedidos a um usuário, programa ou processo”.

Depois que um sistema seguro autentica usuários, ele também deve decidir privilégios que eles possuem. Por exemplo, um aplicativo bancário on-line autentica um usuário com base em suas credenciais, mas deve então determinar as contas às quais esse usuário tem acesso. Além disso, o sistema determina quais ações o usuário pode realizar em relação àquelas contas, como exibir saldos e fazer transferências.

**Não repúdio**

Imagine um cenário em que Marcos está comprando um carro de José e assina um contrato declarando que pagará R$ 40.000,00 pelo automóvel e se apropriará dele no próximo fim de semana. Se, posteriormente, Marcos decidir não comprar o carro, pode alegar que alguém forjou sua assinatura e que não é responsável pelo contrato.

Para refutar sua alegação, José poderia mostrar que um cartório de notas autenticou a identidade de Marcos e carimbou o documento para indicar essa verificação. Neste caso, o carimbo do cartório deu ao contrato a propriedade de não repúdio, que o NIAG define como “garantia de que o remetente dos dados tem prova de que o fez e o destinatário tem prova da identidade do remetente para que, mais tarde, nenhum dos dois possa negar que tenham processado os dados”.

No mundo das comunicações digitais, nenhum cartório pode carimbar cada mensagem transmitida, mas o não repúdio é ainda necessário. Para encontrar este requisito, sistemas seguros normalmente dependem de criptografia assimétrica (ou chave pública). Enquanto os sistemas de chave simétrica usam uma chave única para criptografar e descriptografar os dados, os sistemas assimétricos usam um par de chaves.

Estes sistemas usam uma chave (privada) para assinar dados e outra chave (pública) para verificar dados. Se a mesma chave pode assinar e verificar o conteúdo de uma mensagem, o remetente pode alegar que quem tem acesso à chave poderia facilmente tê-la forjado. Sistemas de chave assimétrica têm a propriedade de não repúdio, pois o signatário de uma mensagem pode manter sua chave privada em segredo

**Confidencialidade**

O termo confidencialidade é familiar à maioria das pessoas, mesmo àquelas que não atuam no setor de segurança da informação. O NIAG (2010) define confidencialidade como “garantia de que as informações não são divulgadas a indivíduos, processos ou dispositivos não autorizados”.

Assegurar que partes não autorizadas não tenham acesso a um pedaço da informação é uma tarefa complexa. É mais fácil entender quando o conceito é quebrado em três etapas principais. Primeiramente, a informação deve ter proteções capazes de impedir alguns usuários de acessá-lo. Em segundo lugar, limitações devem estar em vigor para restringir o acesso à informação apenas a quem tenha autorização para visualizá-la. Em terceiro lugar, um sistema de autenticação deve estar presente para verificar a identidade daqueles que tenham acesso aos dados.

As etapas de autenticação e autorização descritas anteriormente neste segmento são vitais para manter a confidencialidade, mas o conceito de confidencialidade se concentra, principalmente, em ocultar ou proteger a informação. Uma maneira de protegê-las é armazená-las em um local privado ou em uma rede privada que é limitada àqueles que tenham legítimo acesso à informação. Se um sistema deve transmitir os dados por meio de uma rede pública, as organizações devem usar uma chave que somente as partes conhecem para criptografar os dados. 

Para informações sobre viagens na internet, por exemplo, essa proteção pode significar o uso de uma rede privada virtual (VPN), que criptografa todo o tráfego entre os endpoints ou usa sistemas de e-mail criptografados, que restringem a exibição de uma mensagem ao destinatário pretendido. Se informações confidenciais deixam fisicamente um local protegido, como quando os funcionários transportam fisicamente fitas de backup entre departamentos, as organizações devem criptografar os dados, caso caiam nas mãos de usuários não autorizados.

A confidencialidade da informação digital também requer controles no mundo real. Shoulder surfing, a prática de olhar por sobre os ombros de uma pessoa enquanto ela está trabalhando no computador, é uma técnica usada por um invasor para coletar informações confidenciais. Ameaças físicas, como roubo simples, também ameaçam a confidencialidade. As consequências de uma quebra de confidencialidade variam dependendo da sensibilidade de dados protegidos. Uma quebra nos números de cartão de crédito, como no caso do Sistema de Processamento Heartland Payment Systems em 2008, poderia resultar em processos com indenizações de milhões de dólares.

**Integridade**

No campo da segurança da informação, “integridade” normalmente se refere à integridade dos dados, ou à garantia de que os dados armazenados sejam precisos e não contenham modificações não autorizadas

Esse princípio, que depende da autenticação, autorização e não repúdio como chaves para manter a integridade, impede que usuários sem autorização modifiquem dados. Ao ignorar um sistema de autenticação ou aumentar os privilégios, além daqueles normalmente concedidos a ele, um invasor pode ameaçar a integridade dos dados. 

Falhas e vulnerabilidades de softwares podem levar a perdas acidentais na integridade, podendo abrir um sistema para modificação não autorizada. Os programas tendem a ter um controle rígido quando um usuário lê, escreve ou acessa dados específicos, mas uma vulnerabilidade de software pode ir além desse controle. Por exemplo, um invasor pode explorar uma vulnerabilidade em um banco de dados por meio de um ataque do tipo injeção SQL para extrair, alterar ou adicionar informações a um banco de dados.

**CURIOSIDADE:**
Um dos ataques mais comuns que comprometem a integridade são as injeções SQL, que são muito exploradas, e os ataques acontecem devido a erros na programação dos sites, que permitem a realização de consultas na base de dados para retirada de informações confidenciais, como senhas e nome de usuários. 

Interromper a integridade dos dados em repouso ou em uma mensagem em trânsito pode trazer sérias consequências. Se for possível modificar uma mensagem de transferência de fundos entre um usuário e seu banco on-line, um invasor pode usar esse privilégio para sua vantagem. O atacante poderia interceptar a transferência e roubar os fundos, alterando o número da conta do destinatário para o número da conta bancária do invasor.

**Disponibilidade**

Sistemas de informação devem estar acessíveis aos usuários para que tragam algum valor. Se um sistema está inoperante ou respondendo em intervalos de tempo muito longos, não pode fornecer o serviço que deveria. O NIAG define a disponibilidade como “acesso oportuno e confiável a serviços de dados e informações para usuários autorizados. ”

Os ataques à disponibilidade são um pouco diferentes daqueles feitos à integridade e confidencialidade. O ataque mais conhecido que impacta o princípio da disponibilidade é um ataque de negação de serviço (DoS). Um ataque DoS pode acontecer de várias formas, pelo esgotamento de recursos pelo qual um invasor sobrecarrega um sistema a ponto de não responder a mais nenhum pedido de pacote. 

Os recursos em questão podem ser memória, tempo de unidade central de processamento (CPU), largura de banda de rede e/ou outro componente em que um atacante pode interferir. Um exemplo de um ataque DoS é o de inundação de rede: o atacante envia muito tráfego de rede para o sistema alvo, fazendo esse tráfego saturar a rede e mais nenhuma requisição legítima trafegar. 

A compreensão exata dos componentes da tríade CID e os conceitos por trás do objetivo de proteger tais princípios são importantes para que se realize de forma profissional a segurança da informação. Cada componente age como um pilar que sustenta a segurança de um sistema. Se um atacante violar qualquer um dos pilares, a segurança do sistema cairá. Autenticação, autorização e não repúdio são requisitos que os projetistas de sistemas devem observar para manter esses pilares. Entender como todos esses conceitos interagem uns com os outros é ponto necessário para usá-los efetivamente.

**Componentes de sistema da informação**

Os critérios anteriormente apresentados revelam a necessidade de se apresentar o que é exatamente um sistema de informação, em termos da descrição exata de seus componentes. Um sistema de informação (IS) é muito mais do que um hardware de computador: representa todo o conjunto de software, hardware, dados, pessoas, procedimentos e redes que tornam possível o uso de recursos de informação na organização. Esses seis componentes críticos permitem informações a serem inseridas, processadas, produzidas e armazenadas. Cada um desses componentes tem seus pontos fortes e fracos, bem como características e usos próprios. Cada componente do sistema de informação também tem seus próprios requisitos de segurança.

**Software**

O componente de software de um sistema de informação compreende aplicativos, sistemas operacionais e diversos utilitários de comando. O software é talvez o componente mais difícil de ser protegido. A exploração de erros na programação de software é responsável por uma parte substancial dos ataques em formação. A indústria de tecnologia da informação está repleta de relatórios alertando sobre brechas, bugs, pontos fracos ou outros problemas fundamentais no software. De fato, muitas facetas da vida cotidiana são afetadas por softwares que invadem sistemas.

O software carrega a força vital da informação dentro de uma organização. Infelizmente, programas são frequentemente criados sob as restrições do gerenciamento de projetos, como tempo, custo e mão de obra. A segurança da informação é muitas vezes implementada como uma reflexão tardia, em vez de desenvolvida como um componente integral desde o início do projeto. Nesse caminho, programas de software se tornam um alvo fácil de ataques acidentais ou intencionais.

**Hardware**

Hardware é a tecnologia física que hospeda e executa o software, armazena e transporta os dados e fornece interfaces para a entrada e remoção de informações do sistema. As políticas de segurança física lidam com o hardware como um ativo físico e com a proteção de ativos físicos de danos ou roubo.

Aplicando as ferramentas tradicionais de segurança física, como bloqueios e chaves, restringe-se o acesso e a interação com os componentes de hardware de um sistema. Proteger a localização física dos computadores e dos próprios usuários é importante, pois uma violação de segurança física pode resultar em perda de informações. Infelizmente, a maioria dos sistemas de informação é construída em plataformas de hardware que não podem garantir qualquer nível de segurança da informação, se o acesso irrestrito ao hardware for possível.

**Dados**

Os dados armazenados, processados e transmitidos por um sistema de computador devem ser protegidos e são, muitas vezes, o bem mais valioso possuído por uma organização, além de serem o principal alvo de ataques intencionais. Sistemas desenvolvidos nos últimos anos provavelmente usarão sistemas de gerenciamento de banco de dados que, se concebidos corretamente, melhoram a segurança dos dados e das aplicações. 

Infelizmente, muitos projetos de desenvolvimento de sistemas não fazem uso dos recursos de segurança do sistema de gerenciamento de banco de dados e, em alguns casos, o banco de dados é implementado de maneira menos segura que os sistemas de arquivos tradicionais.

**Pessoas**

Embora muitas vezes negligenciadas em considerações de segurança do computador, as pessoas sempre foram ameaça à segurança da informação. Diz a lenda que por volta de 200 a.C., um grande exército ameaçava a segurança e a estabilidade do Império Chinês. Os invasores eram tão ferozes que o imperador chinês comandou a construção de uma grande muralha que se bloquearia contra os invasores hunos. 

Por volta de 1275 d.C., Kublai Khan finalmente conseguiu o que os hunos haviam tentado por milhares de anos. Inicialmente, o exército de Khan tentou escalar, escavar e romper a parede. No fim, Khan simplesmente subornou o porteiro – e o resto é história. Se esse evento realmente ocorreu ou não, a moral da história é que as pessoas podem ser o elo mais fraco no programa de segurança de informação de uma organização. 

A menos que política, educação, treinamento, conscientização e tecnologia sejam empregados para evitar danos acidentais ou intencionais ou a perda de informações, pessoas permanecerão como o elo mais fraco. A engenharia social pode atuar no sentido de manipular as ações das pessoas e obter acesso às informações sobre um sistema.

**Procedimentos**

Outro componente frequentemente negligenciado de um sistema de informação é o procedimento. Procedimentos são instruções escritas para realizar uma tarefa específica. Quando um usuário não autorizado obtém os procedimentos de uma organização, isso representa uma ameaça à integridade das informações. Por exemplo, um consultor de um banco aprendeu a transferir fundos usando os procedimentos do centro de computação, que estavam prontamente disponíveis. Aproveitando-se de uma falha de segurança (falta de autenticação), esse consultor bancário ordenou que milhões de reais fossem transferidos para sua própria conta, até que a situação fosse corrigida.

A maioria das organizações distribui procedimentos para seus funcionários legítimos para que possam acessar o sistema de informação, mas muitas dessas empresas geralmente não fornecem educação adequada sobre a proteção dos procedimentos. 

Educar os funcionários sobre os procedimentos de salvaguarda é tão importante quanto fisicamente proteger o sistema de informação. Afinal, os procedimentos são informações por direito próprio. Portanto, o conhecimento dos procedimentos, como o de toda a informação crítica, deve ser divulgado entre os membros da organização apenas com base na necessidade de conhecimento.

**Redes**

O componente de um sistema de informação que elevou a necessidade do uso de computadores e da segurança da informação é a rede. Quando os sistemas de informação estão conectados uns aos outros para formar redes locais (LANs), e essas LANs estão conectadas a outras redes, como a internet, novos desafios de segurança emergem rapidamente. A tecnologia física que permite funções de rede está se tornando cada vez mais acessível às organizações. 

Aplicar ferramentas tradicionais de segurança física, como bloqueios e chaves, para restringir o acesso e a interação com os componentes de hardware de um sistema de informação ainda é uma ação importante. Todavia, quando sistemas computacionais estão interligados em rede, essa abordagem já não é suficiente. Etapas para fornecer segurança de rede são essenciais, assim como a implementação de sistemas de alarme e intrusão para tornar os proprietários de sistemas conscientes dos compromissos de segurança que estejam em curso.

Um dos preceitos fundamentais da análise de segurança (reforçado por observações e estatísticas) é que, à medida que as ações de segurança se tornam mais eficazes, as pessoas se tornam o elo mais fraco de um sistema de segurança. Por exemplo, quando se trata da fronteira dos EUA com o México, à medida que os muros foram ampliados e os controles nos pontos de entrada se tornaram mais sofisticados, os contrabandistas recorreram ao suborno para contornar a segurança mais rígida. 

**Segurança, ética e internet**

Criminosos que visam locais de trabalho descobriram maneiras de contornar os controles de acesso mais restritos e outras medidas físicas instituídas pelas empresas. Talvez os invasores entrem por uma porta bloqueada que tenha sido aberta por um trabalhador fazendo uma pausa para fumar, ou sigam um funcionário legítimo por uma entrada segura, fingindo ter perdido suas credenciais. Esse mesmo princípio se aplica à segurança cibernética: à medida que maiores barreiras técnicas são impostas para proteger as redes de computadores contra invasões externas, seus usuários se tornam o elo mais fraco da segurança cibernética.

Em primeiro lugar, cabe sempre um aviso: esses sistemas de informação atacantes sempre selecionaram as pessoas com acesso aos seus alvos. Desde a época dos phreakers, que faziam chamadas de longa distância gratuitas, e dos primeiros hackers de computador, as pessoas com acesso às informações sobre telefone e sistemas de computador têm sido alvo de ataques de engenharia social. Essas abordagens se baseiam em uma combinação de charme, psicologia e sociologia para obter as informações necessárias, em vez de hacking técnico. Em uma metáfora usada com frequência, em vez de abrir a fechadura de uma porta, os engenheiros sociais entram no prédio ou convencem alguém a dizer onde a chave reserva está escondida.

Há muitas maneiras de realizar um ataque de engenharia social. Alguns golpes fazem os usuários de computador fornecerem seus nomes de usuários e suas senhas ou convencerem os administradores de sistemas a redefinir as senhas. Engenheiros sociais se tornaram adeptos da exploração da natureza humana, das normas sociais e do respeito pela autoridade em seus esforços para levar as pessoas a cumprir suas ordens. Sua capacidade contínua de obter informações de lo-gin confirma a viabilidade dessa abordagem. Novas formas de golpes de engenharia social, como a “fraude do presidente”, continuam surgindo. Nesse esquema, os golpistas se passam pelo CEO, ou por outro executivo sênior da empresa, e enviam um e-mail para um executivo de contas a pagar, solicitando a transferência urgente e secreta de fundos.

Muitos esquemas de fraudes on-line, como os de uma pessoa que afirma ser do IRS ou do FBI, dependem mais da engenharia social do que da habilidade técnica de hacking. A esse respeito, nada mudou muito desde os dias dos phreakers. Muitos dos chamados hackers são realmente trapaceiros de confiança usando engenharia social, em vez de codificadores que escrevem malware. Atualmente, há muito menos pessoas escrevendo código para ferramentas de hacking do que as pessoas que as usam.

Outro tipo de ataque cibernético focado na pessoa é o phishing: a tentativa de persuadir um usuário a clicar em um hiperlink ou a abrir um anexo de e-mail que acabaria instalando malware em seu dispositivo. Em muitos casos, o software maligno pode migrar de um computador individual para outros sistemas conectados à mesma rede. O malware permite que hackers acessem os arquivos em um computador infectado, usem os sistemas infectados como parte de uma botnet ou, cada vez mais, forneçam ransomware, software que criptografa os dados em um sistema infectado, permitindo que os hackers exijam pagamento antes de entregarem a chave de software para desbloquear a criptografia.

Embora muitas tentativas de phishing sejam um pouco estranhas e difíceis de detectar quando alguém é avisado sobre a tática, uma técnica mais refinada, chamada spear-phishing é muito mais insidiosa. Essa forma altamente segmentada de phishing usa uma abordagem avançada de engenharia social para entregar malware. O e-mail de spear-phishing se refere ao seu alvo pelo nome e pretende ser de um amigo, colega de trabalho ou superior, alguém em quem o alvo confie.

Recentemente, um sofisticado esquema de spear-phishing veio à tona envolvendo um grupo de hackers baseado no Irã, que estabeleceu uma falsa conta de mídia social na persona de uma mulher atraente. Os invasores usaram a conta para se conectar a um funcionário de uma empresa-alvo e acabaram criando uma amizade on-line. Usando a conta falsa, os hackers convenceram o funcionário a criar um site para os negócios da mulher. Quando os hackers, sob o disfarce de “amiga” feminina, enviaram um arquivo para sua conta de e-mail de trabalho, ele abriu o anexo. O malware se espalhou dentro da rede de sua empresa, permitindo que os hackers coletassem informações confidenciais de pelo menos seis clientes. Essa operação demonstra a variedade de abordagens de engenharia social que podem ser usadas para enganar as pessoas, para que comprometam inadvertidamente a segurança cibernética.

Nem todas as ameaças à segurança cibernética envolvem vítimas involuntárias. Os casos de despejos maciços de dados envolvendo Chelsea Manning, Edward Snowden e outros são lembretes de que insiders maliciosos também representam um risco significativo à segurança. De fato, a tecnologia atual torna fácil para alguém sair pela porta carregando uma grande quantidade de dados. Um pen drive de 8 gigabytes pode conter mais de 15.000 documentos de 100 páginas do Microsoft Word, e sites de hospedagem externos, como o DropBox, podem conter múltiplas vezes essa quantidade. 

A ideologia pode motivar ameaças internas. Esses insiders poderiam se opor a algum aspecto de uma empresa ou organização durante o seu emprego, ou poderiam se unir intencionalmente a uma empresa ou grupo que vise prejudicá-la. Isso vale para pessoas de dentro do mercado muito mais comuns do que aquelas movidas pela ideologia. Houveram muitos casos de funcionários tentando vender informações proprietárias para ganho pessoal ou fornecendo essas informações a um concorrente em troca de um emprego.

Mas nem todas as ameaças internas são automotivadas. Como já observado anteriormente, um operador de inteligência humana teria pouca dificuldade em recrutar agentes internos para auxiliar na obtenção de dados ou no acesso a uma rede de computadores. Usando abordagens tradicionais de inteligência humana, envolvendo dinheiro, ideologia, compromisso ou ego, seria fácil encontrar um parceiro disposto na maioria das empresas ou organizações. 

Obviamente, os funcionários de TI não são os únicos alvos. Outros funcionários podem ser recrutados para fazer um clique aparentemente inocente em um e-mail de phishing ou para conectar uma unidade flash infectada com malware ao computador corporativo. Mais tarde, eles poderiam alegar que encontraram o caminho no andar da sala de descanso. Os insiders também podem fornecer aos hackers uma compreensão detalhada da cultura e dos relacionamentos da empresa, incluindo cópias de e‑mails anteriores que podem ser usados para criar tentativas convincentes de spear-phishing. Embora a maioria dos usuários de downloads em massa represente uma ameaça única, uma verba recrutada pode comprometer a segurança cibernética durante um período prolongado.

Infelizmente, em vários hacks recentes, redes de dados foram comprometidas simplesmente porque alguém não teve tempo e esforço para instalar atualizações destinadas a consertar pontos fracos no software operacional. Embora alguns hackers sofisticados possam acessar vulnerabilidades exclusivas, desconhecidas do fornecedor do software e não consertadas, na maioria das vezes, as ferramentas de hacking são projetadas para explorar os pontos fracos identificados, o que limita o prazo de validade do software atualizado. No final, a falha em aplicar patches é simplesmente mais uma maneira de os humanos deixarem as redes abertas para ataques cibernéticos.

A maioria dos assaltos às redes de computadores explora negligências ou falhas de segurança, mas à medida que essas brechas são fechadas e os alvos se tornam mais difíceis de se explorar tecnicamente, os invasores se concentram nas muitas vulnerabilidades apresentadas pelo elemento humano.

### **POLÍTICA-BASE DE SEGURANÇA DE TI**

        Alguns dos elementos comentados no tópico anterior são retomados no diagrama formulado pela autora Claudete Aurora da Silva em sua dissertação de mestrado Gestão da segurança da informação: um olhar a partir da Ciência da Informação, defendida em 2009 no Centro de Ciências Humanas e Sociais Aplicadas da PUC de Campinas. A autora afirma que a qualidade do processo de gestão de Segurança da Informação deve contemplar os três principais recursos da organização, que seriam:
        Mesmo com o melhor planejamento e implementação, é impossível obter informações com absoluta segurança, pois há a necessidade de equilibrar segurança e acesso. A segurança da informação não pode ser absoluta: é um processo, não um objetivo.

        É possível disponibilizar um sistema a qualquer pessoa, em qualquer lugar, a qualquer hora, através de qualquer meio. Contudo, tal acesso irrestrito representa um perigo para a segurança da informação. Por outro lado, um sistema de informação completamente seguro não permitiria alguém acessá-lo. Por exemplo, quando desafiada a obter uma certificação de segurança do nível TCSEC C-2 para o seu sistema operacional Windows, a Microsoft teve que remover todos os componentes de rede e operar o computador apenas a partir do console em uma sala segura.

Para alcançar o equilíbrio, isto é, operar um sistema de informação que satisfaça o usuário e o profissional de segurança, o nível de segurança deve permitir acesso razoável, mas se proteger contra ameaças. 

Por causa das preocupações e dos problemas de segurança, um sistema de informações ou departamento de processamento de dados pode ficar muito arraigado na gestão e proteção de sistemas. Um desequilíbrio pode ocorrer quando as necessidades do usuário final são prejudicadas por um foco muito pesado de proteger e administrar os sistemas de informação. Ambos os técnicos de segurança da informação e os usuários finais devem reconhecer que compartilham os mesmos objetivos gerais da organização: garantir que os dados estejam disponíveis quando, onde e como forem necessários, com atrasos ou obstáculos mínimos. Em um mundo ideal, esse nível de disponibilidade pode ser alcançado mesmo após preocupações com perda, dano, interceptação ou destruição.

A implementação da segurança da informação em uma organização deve começar em algum lugar, e não pode acontecer durante a noite. Proteger os ativos de informação é, na verdade, um processo incremental que requer coordenação, tempo e paciência. 

A segurança da informação pode começar como um esforço de base em que os administradores de sistemas tentam melhorar a segurança. Isto é frequentemente referido como uma abordagem ascendente. A principal vantagem da abordagem ascendente é a perícia técnica dos administradores individuais, trabalhando com sistemas de informação no dia a dia. Esses administradores possuem um conhecimento profundo que pode acelerar o desenvolvimento de um sistema de segurança da informação. Eles conhecem e entendem as ameaças aos seus sistemas e os mecanismos necessários para protegê-los com sucesso. Infelizmente, essa abordagem raramente funciona, já que não possui vários recursos críticos, como suporte aos participantes e poder de permanência organizacional.

A abordagem descendente, ou de cima para baixo, na qual o projeto é iniciado por gerentes de nível superior que emitem políticas, procedimentos e processos, dita as metas e os resultados esperados, e determinam responsabilidade por cada ação requerida, além de ter probabilidade maior de sucesso. Essa abordagem tem um forte apoio da alta gerência, geralmente um financiamento dedicado, um claro processo de planejamento e implementação, e meios de influenciar a cultura.

Para que qualquer esforço em toda a organização seja bem-sucedido, a Alta Administração deve aceitá-lo e apoiá-lo totalmente. O papel desempenhado nesse esforço pelo chefe não pode ser exagerado. Normalmente, esse chefe é um executivo, como um diretor de informações (CIO) ou o vice‑presidente de tecnologia da informação (VP-IT), que move o projeto para frente, garante que ele seja gerenciado adequadamente e aceito em toda a organização. Sem esse suporte de alto nível, administradores de vários níveis falham na seleção do tempo para o projeto ou o descartam como sendo de baixa prioridade. 

Também é crítico para o sucesso desse tipo de projeto o envolvimento e o apoio dos usuários finais. Essas pessoas são mais diretamente afetadas pelo processo e pelo resultado do projeto, e devem ser incluídas nos processos de informações de segurança. 

Para ter sucesso, o JAD deve ter poder de permanência, sendo capaz de sobreviver à rotatividade de funcionários e não devendo ser vulnerável às mudanças na equipe de pessoas que está desenvolvendo o sistema de segurança da informação. Isso significa que os processos e procedimentos devem ser documentados e integrados à cultura organizacional, sendo adotados e promovidos pela gerência da organização.

### **Ameaças emergentes e análise de risco**

A análise de risco em segurança da informação é usada para identificar, estimar e priorizar riscos para operações e ativos organizacionais resultantes da operação e uso de sistemas de informação.

A avaliação de risco é basicamente um conceito de negócio centrado em recursos financeiros. É preciso, primeiramente, pensar em como uma organização lucra, como os funcionários e os ativos afetam a lucratividade do negócio e quais riscos podem resultar em grandes perdas monetárias para a empresa. Na sequência, deve-se pensar em como melhorar a infraestrutura de TI para reduzir os riscos que podem levar às maiores perdas financeiras para a organização.

No entanto, deve-se lembrar que tudo vezes zero é igual a zero, de modo que se o fator de ameaça for alto, assim como o nível de vulnerabilidade, mas a importância do ativo for zero (em outras palavras, não vale dinheiro para a empresa), o risco de se perder dinheiro será zero.

Existem várias maneiras de coletar as informações necessárias para avaliar o risco. Por exemplo:

- Entrevistar gerentes e propietários de dados e outros funcionários
- Analisar sistemas e infraestrutura da empresa
- Revisar documentação

Uma vez analisado o risco, é preciso estabelecer estratégias de gerenciamento, a fim de que os elementos de risco sejam minimamente controlados.

A análise básica de riscos envolve apenas três fatores: a importância dos ativos em risco, o nível de ameaça e a vulnerabilidade do sistema a essa ameaça. Usando esses fatores, pode-se avaliar o risco, ou seja, a probabilidade de perda de dinheiro da organização. Embora a avaliação de risco se baseie em construções lógicas, não números, é útil representá-la como uma fórmula:

```go

Risco = Ativo x Ameaça x Vulnerabilidade

```

Caso queiramos posicionar a vulnerabilidade dentro de um esquema que considere os demais elementos do processo aqui tratado, poderemos adotar a seguinte representação , que a considera o início dos riscos que, por sua vez, levam a consequências indesejáveis.

<img src="https://sereduc.blackboard.com/bbcswebdav/library/Library%20Content/%28LMS%29%20-%20Do%20Not%20Delete/%28LMS%29%20DOL%20-%20Do%20Not%20Delete/SCORM/FUNDAMENTOS%20EM%20SEGURAN%C3%87A%20DA%20INFORMA%C3%87%C3%83O/UNIDADE%201/scormcontent/assets/5NwwYXB8H2oqJWOb_7kBmZVlAVZTRVz79.png" />

**DEFINIÇÃO DE RISCO E SEUS ELEMENTOS**

Antes de iniciar um processo de gerenciamento de risco em segurança da informação, é necessário conceituar o termo “risco”: é qualquer evento capaz de causar impacto na capacidade das empresas alcançarem os objetivos em seu negócio, e também a probabilidade de uma fonte de ameaça se aproveitar de uma vulnerabilidade da empresa, o que pode gerar um impacto para seu negócio. No entanto, diferentemente das ameaças, os riscos podem ser controlados (mitigados ou minimizados). 

Para dar início ao gerenciamento de riscos dentro da segurança da informação de uma organização, devem ser adotados os seguintes passos:

Localizar todos os ativos valiosos na organização que possam ser prejudicados por ameaças, de forma que resulte em uma perda financeira. São exemplos:


    servidores;
    sites web;
    informações de contato dos clientes;
    documentos de parceiros;
    segredos comerciais;
    dados de cartões de crédito dos clientes.

Identificar possíveis consequências, determinando quais as perdas financeiras que a organização sofreria se um determinado ativo fosse danificado. São exemplos de consequências que merecem atenção:


    perda de dados;
    tempo de inatividade do sistema ou aplicativo;
    consequências legais.

Identificar ameaças e seu nível. Uma ameaça é qualquer coisa que possa explorar uma vulnerabilidade para violar sua segurança e causar danos a seus ativos. São exemplos de ameaças comuns:


    desastres naturais;
    falha de sistema;
    interferência humana acidental;
    ações humanas maliciosas (interferência, interceptação ou representação).

Identificar vulnerabilidades e avaliar a probabilidade de sua exploração. Uma vulnerabilidade é uma fraqueza que permite que alguma ameaça viole sua segurança e cause danos a um ativo. Deve-se pensar no que protege os sistemas contra uma determinada ameaça, se a ameaça realmente ocorrer, e questionar quais são as chances de que isso realmente danifique seus ativos. As vulnerabilidades podem ser físicas (como equipamentos antigos), problemas com design ou configuração de software (como permissões de acesso excessivas ou estações de trabalho sem patches) ou fatores humanos (como membros da equipe não treinados ou descuidados).

Avaliar o risco. Risco, isto é, o potencial de determinada ameaça para explorar as vulnerabilidades do ambiente e causar danos a um ou mais ativos, levando à perda monetária. Deve-se avaliar o risco de acordo com a fórmula lógica indicada anteriormente e atribuir a ele um valor (alto, moderado ou baixo). Em seguida, é desenvolvida uma solução para cada risco alto e moderado com uma estimativa de seu custo.

Criar um plano de gerenciamento de risco usando os dados coletados.

Criar uma estratégia para aprimoramentos de infraestrutura de TI para atenuar as vulnerabilidades mais importantes e obter a aprovação do gerenciamento.

Definir processos de mitigação. Pode-se melhorar a infraestrutura de segurança de TI, mas não se pode eliminar todos os riscos. Quando há um desastre, o que aconteceu deve ser consertado, o motivo investigado e se deve impedir que isso aconteça novamente, ou pelo menos que tornar as consequências menos prejudiciais. Por exemplo, uma falha em um servidor pode conduzir a um processo de mitigação de amostra.

### **Malware**

Malwares ou códigos maliciosos são programas criados com o intuito de causar danos ao seu computador. Esses códigos podem infectar seu computador e sua rede por meio de vulnerabilidades de programas instalados, da execução de mídias (CD/DVD) ou pen drives, por acessos a páginas web, e pela execução de arquivos previamente infectados obtidos através de mensagens de e-mail. O malware é conhecido como contaminante de computador, sendo disfarçado ou escondido dentro de arquivos não maliciosos.

Assim que instalados, os códigos maliciosos passam a ter acesso aos dados armazenados em seu computador, podendo executar ações em seu nome de acordo com as permissões de cada usuário da máquina.

Malware é aplicado somente a softwares mal-intencionados que causem dano. Software que cause algum dano devido a erros não é considerado um malware, por exemplo, alguns softwares que são escritos para executar algum tipo de serviço sob demanda e que causem danos por conta de algum código subscrito errado não são malwares.

Comumente os malwares são utilizados contra sites de governo e empresas para coleta de informações ou perturbação de seu funcionamento geral, mas também são utilizados contra algum indivíduo para coleta de informações pessoais, como número de identificação, números bancários, senhas, etc.

**VÍRUS E WORM**

O vírus infecta os computadores por meio de programas na função de hospedeiro. Após instalado na máquina, ele altera o início do programa com um código malicioso, podendo afetar não só computadores, mas também toda uma rede, por meio do compartilhamento de arquivos, criando novos executáveis.

Podemos definir um vírus como um segmento de código de computador malicioso, que se multiplica de modo a se tornar parte de demais arquivos e programas. Os programas infectados pelo vírus acabam se tornando um ponto de partida para sua manifestação.

Diferentemente do vírus, o worm não necessita de um programa hospedeiro. Ele se propaga pela rede, infectando computadores através de uma falha de segurança denominada exploit. Ele é muito mais perigoso do que o vírus, pois age de maneira rápida e sem que a vítima saiba. Assim que entra no microcomputador, cria cópias de si mesmo em diversos locais do sistema e se espalha para os demais micros da rede. 

O worm oferece mais riscos porque é autônomo. Dessa forma, não precisa de interação com o usuário para ser ativado no computador e se multiplicar. Os worms infectam o computador através de brechas já existentes no sistema e podem ser transmitidos através de acessos a páginas da internet. A brecha mais comum é quando o instalador de um programa é executado, incorrendo em uma porta aberta que facilita a instalação do software malicioso. A partir daí, o worm se propaga pela rede.

Alguns worms são tão sofisticados que conseguem fechar todas as portas de segurança, impedindo a infiltração de outros tipos de malwares. Assim esse worm terá exclusividade no roubo de informações.

**BACKDOOR**

O backdoor permite o comando do computador de forma remota e a execução de determinadas ações, como o download de outros tipos de malwares, envios de dados, spam, além de ataques de navegação e serviços.

Ele pode assumir diversas formas, podendo, por exemplo, ser um software que realiza a criação de outras portas, para que malwares possam invadir o sistema. Como padrão de segurança, é necessário que todo o sistema seja monitorado regularmente em busca de vulnerabilidades.

Diversos recursos podem ser utilizados para evitar esse tipo de ataque. Um deles é o firewall, que, se mal configurado, pode se tornar uma dessas vulnerabilidades. O firewall de aplicação também previne a presença do backdoor, impedindo a instalação de aplicativos indesejados.

Nem todos os backdoors presentes no sistema são perigosos; alguns são ou estão instalados no sistema para a realização de tarefas de manutenção ou atualização de um dispositivo. Por exemplo, atualmente, com a internet das coisas, dispomos de vários equipamentos conectados à internet, e alguns deles recebem atualizações sem que haja interação do usuário. Até técnicos podem realizar acessos para solucionar problemas. Isso se torna possível por causa de um backdoor instalado.

**ADWARE, SPYWARE E RANSONWARE**

O adware exibe vários tipos de anúncios indesejados e sem a autorização do usuário, principalmente quando navegadores são abertos e sites de anúncios são acessados. Normalmente, assumem um formato de pop-up, e saltam aos olhos exibindo mensagens persuasivas, como oferecendo prêmios ou recompensas.

Já o spyware, software espião, rouba informações do seu computador, de sites visitados na internet, e todas as informações coletadas são enviadas para um hacker.

Há também o spyware, que é o roubo de senhas. Para que seja realizado o roubo de senhas, os hackers utilizam o keylogger, que é um programa que captura senhas a partir do que é digitado pelo usuário. Esse tipo de malware restringe o seu acesso ao computador ou arquivos, e o hacker exige resgaste para liberar o seu acesso.


**SINTETIZANDO O QUE FOI APRENDIDO**

Segurança da informação tem sido crucial em nossas vidas desde os primórdios. Em tempos de guerra, por exemplo, a informação, bem como a forma como ela iria chegar aos companheiros que estavam no campo de batalha, era determinante. Por isso é importante, antes de tudo, ter uma visão geral acerca da necessidade de uma boa gestão da informação. Informação pessoais, por exemplo, não devem chegar a pessoas que não nos conhecem. O valor da informação deve ser levado a sério, pois ela é valiosa e pode conter dados da sua vida e da sua organização que, quando em mãos erradas, podem comprometer e colocar pessoas em risco. Por esses motivos, foram criadas políticas de segurança que possam ajudar na sua prevenção.

Há no mundo muitas ameaças que têm por finalidade o roubo de informações, para posteriormente utilizá-las contra pessoas ou organizações. Algumas empresas utilizam a análise de risco para saber se existem gargalos e brechas que podem vir a ameaçar o bem ativo da organização. Muitas ferramentas podem ser aplicadas e facilitam essa descoberta.

Para que uma análise de risco seja bem-feita é importante conhecer o que são malwares e seus diferentes tipos, bem como cada um deles age diante das brechas e vulnerabilidades sistêmicas.

A proteção do seu bem maior deve ter um cuidado especial. A proteção deve existir desde a conscientização pessoal até a organizacional. Por conseguinte, as empresas estão cada vez mais se organizando e mantendo seu público conscientes dos riscos à informação.

Para proteger um bem valioso como a informação, portanto, deve-se ter entendimento das ameaças, o que se inicia efetivamente com um levantamento dos aspectos sistêmicos da sua organização sob a perspectiva das políticas de segurança. Tal análise exige que brechas encontradas sejam imediatamente reparadas.

**REFERÊNCIAS BIBLIOGRÁFICAS**

CNSS – Committee on National Security Systems. National information assurance (IA) glossary. CNSS instruction no. 4009. Fort Meade, MD: CNSS, 2010. Disponível em: <https://www.hsdl.org/?view&did=7447>. Acesso em: 15 jul. 2019

FONTES, E. Segurança da informação: o usuário faz a diferença. São Paulo: Saraiva, 2006.

NSA – National Security Agency. The enigma Machine. Disponível em: <https://www.nsa.gov/News-Features/Photo-Gallery/igphoto/2002054065/>. Acesso em: 8 jul. 2019

SILVA, C. A. Gestão de segurança da informação: um olhar a partir da Ciência da Informação. 2009. 99 f. Dissertação (Mestrado) – Centro de Ciências e Sociais Aplicadas, Pontifícia Universidade Católica, Campinas, SP, 2009. Disponível em: <http://tede.bibliotecadigital.puc-campinas.edu.br:8080/jspui/bitstream/tede/819/1/Claudete%20Aurora%20da%20Silva.pdf>. Acesso em: 20 ago. 2019.

SILVA, N. O poder da vulnerabilidade. Exame, 24 fev. 2017. Disponível em: <https://exame.abril.com.br/blog/gestao-fora-da-caixa/o-poder-da-vulnerabilidade/>. Acesso em: 9 jul. 2019