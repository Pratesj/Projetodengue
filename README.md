ENGENHARIA DE SOFTWARE I 

Profº Alciano G. Genovez de Oliveira 

 


LINS CONTRA A DENGUE 

Aplicativo de comunicação para o combate à Dengue. 

 
Artur Nakamura Merenda 

Daniel Fortunato da Silva 

Jhony Robson dos Santos Prates

Maykon Douglas dos Santos Cardozo 

 FATEC 

01/2025 

1- Tema 

Aplicativo de Comunicação para o Combate à Dengue. 

[Quebra da Disposição de Texto]  Desenvolvimento de um canal direto de comunicação entre a população e a prefeitura para monitoramento, denúncias e informações relacionadas à dengue. 

  

2 – Apresentação 

  

A prefeitura de Lins juntamente com a secretária de saúde planeja criar através de um aplicativo um canal direto de comunicação entre a população e a prefeitura destinado ao combate à dengue. 

O aplicativo deve conter informações sobre a dengue como: avisos sobre a situação atual da dengue na cidade, métodos de prevenção, sintomas da dengue e campanhas de vacinação, um canal de denúncia será criado onde será possível enviar mensagens de texto, fotos e vídeos com denúncias de possíveis focos de dengue. 

Será necessário a criação de dois mapas interativos mostrando os principais locais de foco da dengue na cidade e outro mostrando os postos de saúde. 

O aplicativo será gerenciado pela prefeitura onde será feita uma triagem das denúncias, e serão feitas publicações de notícias e relatórios para informar a população 

O desenvolvimento abrange o levantamento de requisitos funcionais e não funcionais, a definição dos atores envolvidos e a criação de user histories que guiarão o design e a implementação da aplicação. 

 

 

 

 

 

3 - Atores e suas Funções 

 

       População (Usuário Comum): 

o   Enviar denúncias (texto, foto, vídeo) de possíveis focos de dengue. 

o   Receber notificações, comunicados e orientações sobre prevenção, sintomas e vacinação. 

o   Consultar mapas interativos com focos de dengue e unidades de saúde. 

o   Histórico de Interações com o Aplicativo (histórico de status de denúncias). 

 

       Canal de Comunicação  

o   Publicações de Notícias e Boletins sobre a Dengue. 

o   Emitir notificações, comunicados e orientações sobre prevenção, sintomas e vacinação. 

o   Consultar mapas interativos com focos de dengue e unidades de saúde. 

 

       Agentes de Saúde / Equipes de Vigilância Sanitária: 

o   Receber e gerenciar as denúncias enviadas pela população. 

o   Atualizar o status das denúncias (ex.: "Em análise", "Foco confirmado", "Foco eliminado"). 

o   Executar ações de campo e registrar intervenções. 

 

 

       Administração Pública / Prefeitura: 

o   Enviar comunicados e alertas oficiais sobre a situação da dengue na cidade. 

o   Gerenciar campanhas de prevenção e vacinação. 

o   Monitorar estatísticas e gerar relatórios para tomada de decisão. 

       Desenvolvedores / Administradores do Sistema: 

o   Manter a infraestrutura do aplicativo, corrigir erros e implementar novas funcionalidades. 

o   Garantir a segurança dos dados e a estabilidade do sistema. 

       Órgãos de Saúde (Secretaria Municipal de Saúde): 

o   Fornecer informações oficiais, diretrizes e atualizações sobre o combate à dengue. 

o   Integrar dados e orientar as ações preventivas. 

  

 

 

 

 

 

 

 

 

 

 

 

4 - Requisitos Funcionais 

 

    Módulo de Denúncias: 

 

a.      Permitir que os usuários enviem denúncias de possíveis focos de dengue, inserindo localização, fotos, vídeos e descrição. 

b.      Permitir que agentes de saúde visualizem, gerenciem e atualizem o status das denúncias. 

c.      Enviar notificações aos usuários quando o status de sua denúncia for alterado. 

 

      Módulo de Informações e Prevenção: 

 

a.      Exibir conteúdo educativos sobre sintomas, prevenção e tratamento da dengue. 

b.      Disponibilizar mapas interativos com áreas de risco, focos confirmados e unidades de saúde. 

c.      Fornecer informações sobre campanhas de vacinação e pontos de atendimento. 

 

      Módulo de Comunicação e Alertas: 

 

a.      Permitir à prefeitura o envio de comunicados e alertas sobre a situação atual da dengue. 

b.      Utilizar notificações push para alertar os usuários sobre emergências e campanhas. 

 

      Módulo Administrativo: 

a.      Gerenciar conteúdos, comunicados e estatísticas do aplicativo. 

b.      Gerar relatórios com dados sobre denúncias, áreas de risco e intervenções realizadas. 

 

 

      Módulo de Cadastro e Autenticação: 

a.      Permitir o cadastro de usuários por e-mail, telefone ou redes sociais. 

b.      Garantir autenticação segura para usuários e administradores. 

  

5 - Requisitos Não Funcionais 

       Desempenho: 

o   O aplicativo deve ser responsivo e compatível com diferentes dispositivos móveis (smartphones e tablets). 

o   Tempo de resposta inferior a 5 segundos para o envio e consulta de denúncias. 

o   O sistema deve suportar simultaneamente até 2 mil usuários ativos, considerando picos de uso (exemplo: período de campanhas intensas contra a dengue). 

 

 

       Segurança: 

o   Armazenar dados sensíveis de forma criptografada. 

o Implementar autenticação segura (ex.: Firebase Authentication). 

o Criptografia dos dados do usuário (denúncias, 			geolocalização, 	cadastro) em conformidade com a 	LGPD 	(Lei Geral de Proteção de Dados). 

o   Proteger o sistema contra-ataques cibernéticos (injeção de SQL, força bruta etc.). 

o Autenticação por meio de senha forte e/ou login via redes 	sociais confiáveis. 

 

       Usabilidade: 

o   Interface intuitiva e de fácil navegação, seguindo padrões de design modernos. 

o   O design deve ser simples e acessível para usuários de 		todas as idades e níveis de habilidade tecnológica. 

o   Conformidade com padrões de acessibilidade para garantir uso por pessoas com deficiência. 

 

       Escalabilidade: 

o   Estrutura que permita expansão para outras cidades e integração com novos módulos ou funcionalidades. 

o   Compatibilidade com Android e iOS. 

       Manutenibilidade: 

o   Código modular e bem documentado, facilitando futuras atualizações e correções. 

o  O aplicativo deve estar disponível 99,0% do tempo, com manutenção programada para horários de baixo pico de usabilidade. 

o Implementação de backups regulares das bases de dados 	para evitar 	perda de informações importantes. 

 

 

6 - User Histories 

 

      História de Denúncia: 

a.      Como um cidadão, quero enviar uma denúncia com foto, vídeo e localização para reportar um possível foco de dengue, para que as autoridades possam verificar e tomar providências. 

 

     História de Consulta de Informações: 

a.      Como um usuário, quero acessar um mapa interativo que mostre os focos de dengue e unidades de saúde, para me informar sobre a situação atual na minha região. 

 

     História de Recebimento de Alertas: 

a.      Como um cidadão, quero receber notificações push com alertas e comunicados oficiais da prefeitura, para me manter atualizado sobre as campanhas e medidas de prevenção. 

 

   História de Gestão Administrativa: 

 

a.      Como um agente de saúde, quero visualizar e atualizar o status das denúncias recebidas, para que eu possa monitorar e agir rapidamente nos focos identificados. 

     História de Autenticação: 

 

a.      Como um usuário, quero realizar o cadastro e login no aplicativo de forma segura, para acessar todas as funcionalidades e receber comunicações relevantes. 

 

7 – Ciclo de Vida do Projeto 

Para o desenvolvimento do aplicativo "Lins Contra a Dengue", optamos por adotar o modelo de ciclo de vida baseado em Prototipação. Essa escolha se alinha diretamente à natureza do projeto, que envolve interação constante com os usuários finais e ajustes frequentes baseados em feedback. Dado que o aplicativo precisa ser acessível, intuitivo e funcional para um público amplo — incluindo cidadãos de diferentes faixas etárias e níveis de familiaridade com tecnologia — o modelo de prototipação nos permitirá validar rapidamente funcionalidades, interfaces e fluxos de navegação com usuários reais. 

Diferentemente de modelos mais rígidos como o Cascata, a prototipação foca na construção de versões simplificadas (protótipos) do sistema, que podem ser avaliadas e ajustadas iterativamente. Esse processo torna-se especialmente valioso em projetos com forte componente de usabilidade, como este, pois permite refinar a experiência do usuário com base em testes práticos e reais, antes do desenvolvimento completo. 

Além disso, a prototipação facilita a comunicação entre os envolvidos — desenvolvedores, agentes da prefeitura, equipes de saúde e cidadãos — possibilitando uma compreensão mais clara do que será entregue, reduzindo erros de interpretação de requisitos e aumentando a chance de sucesso do projeto. 

 

8 – Requisitos de Segurança 

A segurança da informação no sistema "Lins Contra a Dengue" será estruturada com base nos três pilares fundamentais: Confidencialidade, Integridade e Disponibilidade. A seguir, detalha-se cada um desses pilares e as estratégias adotadas para garantir sua implementação no projeto. 

 

8.1 – Confidencialidade 

A confidencialidade diz respeito à proteção dos dados contra acessos não autorizados. Para assegurar esse aspecto, será utilizado o algoritmo de criptografia AES (Advanced Encryption Standard), na versão AES-256. 

O AES é um algoritmo de criptografia simétrica, amplamente adotado por instituições governamentais e organizações internacionais devido à sua robustez e eficiência. No projeto, ele será utilizado para proteger informações sensíveis como: 

Dados de cadastro e autenticação dos usuários; 

Conteúdo das denúncias enviadas (texto, foto, vídeo e geolocalização); 

Registros de status e interações entre usuários e agentes públicos. 

Vantagens do AES-256: 

Alta segurança: chave de 256 bits resistente a ataques de força bruta; 

Desempenho eficiente: adequado ao uso em dispositivos móveis e web; 

Padrão consolidado: aprovado por órgãos como o NIST e compatível com as exigências da LGPD. 

Desvantagens do AES-256: 

Gerenciamento de chaves: exige um sistema seguro para o armazenamento e distribuição das chaves criptográficas; 

A escolha do AES-256 proporciona uma camada sólida de proteção aos dados dos usuários, especialmente em contextos onde a denúncia de focos de dengue envolve informações pessoais e sensíveis. Assim, garante-se que somente pessoas autorizadas possam acessar ou manipular esses dados, cumprindo os critérios legais e éticos do projeto. 

 

8.2 – Integridade 

Imagem 2, Imagem 

O campo Usuário é um campo do tipo caractere que aceita no maximo 30 caracteres. 

O campo Senha também é um campo do tipo caractere, com algumas regras de uso, tamanho mínimo de caractere de 8 dígitos, com a inserção de ao menos um caractere maiúsculo, um caractere especial e um número. 

 

Capturar, Imagem 

O campo nome completo é do tipo campo que aceita no máximo 50 dígitos. 

O campo E-mail é do tipo caractere que aceita no máximo 30 dígitos. 

O campo Senha também é um campo do tipo caractere, com algumas regras de uso, tamanho mínimo de caractere de 8 dígitos, com a inserção de ao menos um caractere maiúsculo, um caractere especial e um número. 

O campo confirmação de senha, deve atender aos mesmos requisitos do campo senha e obviamente os campos devem ser iguais para a validação. 

 

Capturar1, Imagem 

O campo imagem deve receber imagens no formato de arquivo JPEG/PDF/PNG. 

O campo endereço é do tipo caractere e aceita no máximo 50 dígitos. 

O campo descrição do local é do tipo texto e recebe no máximo 256 caracteres. 

Forma 

8.3 – Disponibilidade 

A disponibilidade refere-se à capacidade do sistema de estar acessível e operacional sempre que necessário, especialmente em situações de emergência ou aumento de demanda, como surtos de dengue. 

Para garantir a alta disponibilidade do aplicativo, serão adotadas as seguintes estratégias: 

Uso de serviços em nuvem (cloud computing): como Firebase, AWS ou Google Cloud, que oferecem escalabilidade automática e balanceamento de carga. 

Backups regulares e automáticos: com políticas de retenção adequadas, protegendo contra falhas e perdas acidentais de dados. 

Monitoramento contínuo do sistema: para detectar falhas ou instabilidades com antecedência e tomar ações corretivas. 

Infraestrutura redundante: para garantir funcionamento mesmo em caso de falhas pontuais (failover). 

Vantagens dessa abordagem: 

Alta escalabilidade: adapta-se automaticamente a picos de uso, como em campanhas de vacinação ou alertas de surto; 

Confiabilidade: minimiza interrupções e mantém o serviço ativo na maior parte do tempo; 

Recuperação rápida: em caso de falha, os backups e a redundância garantem retomada ágil do sistema. 

Desvantagens: 

Custo operacional: serviços em nuvem e infraestrutura robusta podem gerar custos contínuos de operação; 

Complexidade técnica: exige uma equipe de desenvolvimento preparada para lidar com cloud, automação de backups e monitoramento. 

Ao priorizar a disponibilidade, o sistema garante que a população possa registrar denúncias e acessar informações críticas sobre a dengue a qualquer momento, reforçando a confiança no aplicativo e contribuindo para ações rápidas e eficazes de combate à doença. 

 

8.4 - Autenticação 

A autenticação será baseada em login com e-mail e senha, exigido para todos os usuários que interagirem com funcionalidades que envolvam envio ou acesso a dados sensíveis (denúncias, notificações, etc.).  

 

Política de Autenticação: 

Usuários obrigados a se autenticar: 

Cidadãos (usuários da população) que desejarem registrar denúncias, acompanhar status ou acessar comunicados exclusivos. 

Agentes da prefeitura (como profissionais da saúde e equipe de TI). 

Formato de login: e-mail + senha. 

Padrões de segurança: 

Senhas devem ter no mínimo 8 caracteres, conter letras e números. 

As senhas serão armazenadas utilizando algoritmo de hash seguro (ex: bcrypt). 

A autenticação de sessão será gerenciada por tokens JWT, com expiração automática e renovação controlada. 

 

8.5 - Autorização 

O sistema possuirá níveis de acesso diferenciados de acordo com o perfil do usuário: 

1. Cidadão (usuário comum) 

Pode: 

Enviar denúncias com foto, localização e descrição. 

Consultar o status das denúncias enviadas. 

Acessar comunicados públicos da prefeitura. 

Ler materiais educativos e campanhas. 

Não pode: 

Visualizar denúncias de outros usuários. 

Editar ou apagar conteúdos do sistema. 

2. Agente Público / Moderador 

Pode: 

Visualizar e moderar denúncias recebidas (aprovar, classificar, encaminhar). 

Publicar comunicados. 

Marcar focos como resolvidos. 

Gerar relatórios simples com base em denúncias por bairro e data. 

Não pode: 

Editar dados do perfil de outros usuários. 

3. Administrador do Sistema (Prefeitura / TI) 

Pode: 

Gerenciar usuários (ativar, desativar contas). 

Visualizar todos os dados e relatórios do sistema. 

Acompanhar logs e auditorias. 

Editar conteúdos de comunicação pública. 

Configurar parâmetros técnicos (ex: tempo de expiração de tokens, upload de imagens, etc). 

 

8.6 - Auditoria 

Para garantir transparência e rastreabilidade, o sistema armazenará os seguintes dados para fins de auditoria: 

Dados auditáveis: 

Ações administrativas realizadas, como: 

Criação, edição ou exclusão de comunicados. 

Aprovação ou recusa de denúncias. 

Atividades dos usuários, como: 

Data e hora do envio de denúncias. 

Localização e imagem anexada na denúncia. 

Histórico de status das denúncias (em análise, em andamento, resolvido). 

Acesso ao sistema: 

Data e hora do login e logout dos usuários. 

IP aproximado e dispositivo utilizado no acesso. 

Alterações críticas no sistema: 

Modificações na base de dados por parte de administradores. 

Objetivo: 

Permitir a geração de relatórios em caso de fiscalização ou inconsistência. 

Ajudar a identificar falhas operacionais ou uso indevido do sistema. 
