# TIC ClickSeguros
## 
### **CENTRO UNIVERSITÁRIO DE BRASÍLIA (CEUB)**
### **Curso:** Ciência da Computação
### **Disciplina:** Introdução à Computação
### **Estudantes:** 
Maria Clara Pedrosa Mendes Augusto

Marina da Conceição Souza Almeida

Renata Nunes Cotrim 

Lívia Pacheco Salomão Morais

Isabella Oliveira de Sousa Silva
### **RAs:**
**22504387**

**22500412**

**22501424**

**22507244**

**22505223**

## 1. Introdução
A ClickSeguro é uma empresa fictícia criada para ajudar pessoas a protegerem algo que hoje é essencial: seus dispositivos eletrônicos. De celulares e notebooks, a ideia é oferecer seguros simples, personalizados e acessíveis, voltados principalmente para quem quer evitar prejuízos com roubos, quebras ou acidentes.

Apesar de também oferecer suporte básico para questões digitais, o foco está no que realmente faz diferença para o cliente: garantir que ele não fique na mão caso algo aconteça com o aparelho.

A missão da ClickSeguro é cuidar do que conecta as pessoas com o mundo  de forma prática, confiável e sem burocracia.

Pensando nisso, este projeto tem como objetivo montar a estrutura de Tecnologia da Informação e Comunicação (TIC) necessária para o funcionamento eficiente da empresa. Nesta etapa, o foco está na definição da estrutura de hardware e software que atenderá os cinco departamentos: RH, Desenvolvimento Web, Marketing, Design e Diretoria.

Serão apresentados os equipamentos físicos e os softwares essenciais de cada setor, sempre com base nas necessidades específicas de uso. A proposta inclui a descrição das especificações técnicas, quantidades e valores médios, visando garantir que cada área tenha recursos compatíveis com suas demandas e atividades.

## 2. Estrutura da Empresa
### **1 – Diretoria (2 funcionários)**
#### CEO (Diretor Executivo)  
 Adaptado para realizar as tarefas de liderança e estratégia da empresa, tomando decisões práticas e lógicas para o bem da empresa, visando sempre visão, futuro e negócios.

#### CFO (Diretor Financeiro)  
 Adaptado para ser o executivo do financeiro da empresa, onde fica responsável pela parte do negócio, atuando em áreas como planejamento financeiro, gestão de riscos e elaboração de relatórios financeiros.
### **2 – Recursos Humanos (1 funcionário)**
#### Gestor de Recursos Humanos Estratégico 
Responsável por atrair, engajar e desenvolver talentos alinhados à estratégia do negócio. Atua desde a seleção e employer branding até a definição de metas (OKRs), treinamento, remuneração e rotinas do departamento pessoal, garantindo uma gestão de pessoas eficiente e estratégica. Pensando no bem estar do trabalhador e da empresa.
Utiliza ferramentas como sistemas de RH (como Gupy, Kenoby, Sólides ou Senior), plataformas de OKRs, ERPs, planilhas, softwares de folha de pagamento, além de apps de comunicação (Slack, Teams) e videoconferência (Zoom, Google Meet). E equipamentos tanto na empresa, como desktops quanto fora com notebook cuidando de manutenções, chamadas inesperadas ou trabalhos em casa (homeoffice).
### **3 – Desenvolvimento Web (5 funcionários)**
#### Desenvolvedores  
 Os desenvolvedores Full Stack são responsáveis por construir e manter toda a estrutura do site e do sistema de seguros da empresa. Atuam tanto na parte visual, que é acessada pelos usuários (front-end), quanto na parte que roda por trás do sistema, lidando com dados e lógica (back-end). Além disso, fazem atualizações frequentes, corrigem falhas e aplicam melhorias com base nos testes realizados e no feedback dos clientes e das demais equipes.
### **4 – Marketing (3 funcionários)**
#### Coordenação de Marketing  
 Define campanhas, promoções e divulgação da marca. Supervisiona redes sociais, anúncios e conteúdos sobre a marca.

#### Analista de Conteúdo  
 Cria textos para o site, redes sociais, propagandas e e-mails.  
 Analisa dados das campanhas.  
 Gera relatórios sobre o público.  
 Faz testes para melhorar resultados.
### **5 – Design (3 funcionários)**
#### Diretor de Arte  
Define a identidade visual da marca.  Supervisiona o trabalho dos designers.  Garante que esteja visualmente alinhado com a proposta da marca. 

#### Designers Gráficos
Criam layouts para o site, app e redes sociais.  
Pensam na experiência do usuário.  
Trabalham junto com o time de desenvolvimento e marketing.
Quantidade total de funcionários**: 19 funcionários.**
## 3. Software
#### Necessidades comuns:
Sistema operacional desktops, notebooks e servidores: Nixos (De graça)
Desktops e notebooks usaram o gnome por padrão (De graça)
Funções básicas de negócios (reuniões, documentos, compartilhamento de arquivos, email) google workspace (varia de acordo com o plano escolhido. O plano mais básico, Business Starter, custa cerca de R$ 32,72 por mês por usuário. O plano Business Standard oferece mais recursos, como mais armazenamento e videochamadas com mais participantes, e custa cerca de R$ 81,80 por mês por usuário)
Navegador google chrome (de graça)
#### Software produzido na casa
##### Site de vendas:
Objetivo: ter um site onde clientes podem entrar em contrato para ativar ou contratar o seguro
Base de dados: MySQL
Backend e frontend: NextJs
##### Dashboard de análise de cliente:
Objetivo: Analisar dados históricos sobre comportamento de clientes para entender as melhores decisões de negócio e público alvo para nosso serviços
Base de dados: Cassandra
Backend: Python fastAPI
Frontend: NextJs
Por mais que NextJs seja tecnicamente um framework full stack, o único objetivo dele aqui vai ser renderizar as páginas mais completas enquanto se comunica com as APIs python. Python foi preferido quando comparado ao backend node (padrão do nextJS) por facilidade de integração com bibliotecas de análise de dados
##### Controle de funcionários:
Objetivo: Analisar comportamento de funcionários (horário de entrada e saída, tempo de uso do computador, etc...), além de controlar os acessos (computadores e crachás)
Base de dados: MySQL
Backend: Python fastAPI
Frontend: NextJs
O leitor de crachá da porta será afetado pela API
Os computadores terão que fazer uma consulta ao sistema ao iniciar pra checar a permissão do usuário
#### Por áreas:
##### RH
Controle de funcionários
##### Desenvolvimento Web
VsCode como editor de texto padrão

Autorização de alteração do sistema local permitindo instalar outros editores, linguagens e softwares necessários
##### Marketing
Business suite

Dashboard de análise de cliente
##### Design
Gimp para imagens
##### Diretoria
Dashboard de análise de cliente

Controle de funcionários
## 4. Hardware
Amazon RDS (MySQL) como banco de dados e backup pro site de vendas (preço varia com o uso)

Servidor vercel pro deploy do site de vendas (preço varia com o uso)

2 VPS para backup da base de dados do dashboard de análise de cliente e controle de funcionários Hostinger KVM2 (36,99 por mês plano de 2 anos)

### Servidor local:
para base de dados (MySQL e Cassandra), nextJs e Python do dashboard de análise de cliente e controle de funcionários. Além de ser usado como firewall e roteador
#### Especificações:
AMD Ryzen 9 5950X 16-core (R$ 2.749,99)

PLACA MÃE BIOSTAR A520MHP, CHIPSET A520, AMD AM4, MATX, DDR4 (R$ 515, 00 na Amazon)

Memória RAM Corsair Vengeance LPX, 64GB (2x32GB), 3200MHz, DDR4, CL16, Preto \- CMK64GX4M2E3200C16 (R$ 799,99 na [kabum](https://www.kabum.com.br/produto/110856/memoria-ram-corsair-vengeance-lpx-64gb-2x32gb-3200mhz-ddr4-cl16-preto-cmk64gx4m2e3200c16?utm_id=22429436051&gad_source=1&gad_campaignid=22429436051&gclid=CjwKCAjw24vBBhABEiwANFG7y6R0be2dLG60uqC4Bm5YNnlejr_6gpWnaX3Xxm545AxwHt7AM0N4LBoChtcQAvD_BwE))

SSD Kingston KC3000, 4TB, M.2 2280 (R$ 2728,99 na kabum)

Fonte: Corsair CX Series CX750 (R$ 509,99 na kabum)

Gabinete Office Husky 100 (R$ 79,90 na [kabum](https://www.kabum.com.br/produto/643716/gabinete-office-husky-100-micro-atx-mini-atx-preto-hgo100pt?utm_id=22446425993&gad_source=1&gad_campaignid=22446425993&gclid=CjwKCAjw_pDBBhBMEiwAmY02Nq99897YVHXZjC3pNz5iqohStP83Bla9_LE5h8Ak-o-kCYaf2lY40hoCzToQAvD_BwE))
### Telas maiores para sala da diretoria e sala de reunião:
Dois cabos HDMI pra conectar os notebooks às televisões quando necessário (R$ 18,90 cada um na Amazon)

Duas telas maiores (uma pro diretor e uma pra sala de reunião), Samsung Smart TV 65" Crystal UHD 4K 65DU8000 (R$ 3419,00 cada uma na Magazine Luiza)

Um leitor de crachá com API pra configuração iDTouch Prox (R$ 251,54 na Magazine Luiza)
### Redes:
4 TP Link Archer C7 Como pontos de acesso em cada sala (uma sala de reunião, uma sala para diretoria, uma pra RH e desenvolvimento web, uma pra marketing e design)(R$ 598,00 cada um no mercado livre)

5 cabos de rede de 20 metros para conectar os APs ao switch (R$ 19,35 cada um na Amazon)

Um dumb switch conectando todos os Aps ao servidor. tp link ls1008g (R$ 141,52 na kabum)
**Para os funcionários:**
Notebook Lenovo Thinkpad E14 AMD Ryzen 3 7330U 8GB 256GB SSD pra cada pessoa da empresa (R$ 4003,99 na lenovo)

Crucial 8GB DDR4-3200 SODIMM para cada notebook dos setores de marketing, design e diretoria (R$ 139,99 na kabum)

Crucial P3 Plus 2TB PCIe M.2 2280 SSD para cada notebook do setor de design (R$ 935,00 na amazon)
## 5. Considerações Finais
### Custos totais:
#### Custos mensais
Google workspace: R$ 1554.20 (R$ 81,80 \* 19 funcionários)

VPS: R$: 36.99

Cloud (AWS, Vercel) custos variam com a utilização

total: 1591.19
#### Custos iniciais
Servidor local: R$ 7.379,00

TVs e cabos HDMI: R$ 6876

Leitor de crachá: R$ 251,54

Redes: R$ 2620,27

Notebooks: R$ 76.057,00

Melhoria de ram para diretoria, marketing e design: R$ 1119,92

Melhoria de ssd pro time de design: 2.805,00

Total: 94.303,73

### Justificativa das escolhas feitas
#### Notebooks
Escolhemos os **thinkpads** pela possibilidade de melhoria para RAM e SSD, o que significa que a empresa pode usar o mesmo modelo de notebook com os setores necessários recebendo upgrades. Funcionários utilizando o mesmo modelo facilita a integração de hardware (para as TVs das salas de apresentação, por exemplo). 
#### Sistema Operacional
Utilizamos **NixOS** pois as configurações declarativas significam que os computadores podem ser facilmente reproduzidos do ponto de vista software. Na maioria das empresas isso geraria possíveis problemas de compatibilidade, no nosso caso todo software utilizado (tanto os desenvolvidos internamente ou externamente) são baseados na web ou estão disponíveis para Linux. O usuário não ser capaz de instalar outros softwares (privilégio reservado para a equipe de desenvolvimento) nesse caso é uma feature, não um bug. Garantindo sistemas mais seguros com todas as funcionalidades necessárias.
#### Navegador
**Chrome:** Escolhido por ter uma boa integração com o Google Workspace, que fornece ótimo software de negócio Web-Based, não precisando se preocupar com a escolha de software compatível com Linux.
#### Editor de imagens
**Gimp:** escolhido por ser compatível com Linux, além de ser gratuito e oferecer todas as capacidades necessárias para a equipe de design.
#### Editor de texto
**Visual Studio Code:** editor padrão dos programadores, pois é o mais comum, porém os desenvolvedores têm autorização para mexer nas configurações do sistema, podendo trocar de editor e baixar outras dependências, caso necessário.
#### Servidor interno
por questão de segurança. Nossos sistemas internos, roteador e firewall são executados no nosso servidor interno enquanto nossos sistemas externos tem um deploy em cloud.
##### Processador:
O alto número de cores é necessário pela grande quantidade de programas simultâneos
##### Placa-mãe:
suporta 64GB de RAM, que vão ser necessários pela quantidade de processos e é compatível com o processador. Possui também uma entrada M.2, permitindo o uso de SSDs rápidos, essencial para bases de dados.
##### Fonte:
escolhida pelo alto potencial de consumo do processador (até 400 watts em alguns testes) e da placa-mãe (até 100 watts) o uso da memória RAM e do SSD são ignoráveis nessa proporção.
##### Gabinete
Custo benefício.
#### Roteadores
fáceis de configurar como Dumb APs, permitindo que o controle (roteamento e firewall) seja feito pelo nosso servidor
#### Swtitches
**Dumb Switch:** escolhido para conectar os roteadores ao nosso servidor.
#### Deploy do app externo
A escolha de um serviço cloud é importante pela facilidade de acesso e distribuição pelo mundo. Escolhemos **vercel** pela compatibilidade com Next.Js
#### Banco de dados
O banco de dadosfica na **AWS** por ser uma das opções mais baratas e práticas para esse tipo de serviço. além de oferecer backup off site por padrão
#### VPS
Escolhemos usar um vps para manter um backup offsite das bases de dados internas, evitando perder os dados caso tenha algum problema com nosso servidor, ele pode ser bem menos potente do que nossa máquina local, já que ele não vai rodar os bancos de dados, apenas para guardar o backup.
#### Leitor de crachá:
escolhido pois tem integração com API, permitindo o controle da entrada e saída de funcionários pelo nosso sistema de RH internamente desenvolvido.
