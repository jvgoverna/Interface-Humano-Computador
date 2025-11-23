
# **Projeto de IHC**

## **Aprendizado de máquina aplicado na construção de carteiras de investimento adaptadas ao perfil de investimento**

**Membros de Equipe:** <br>
Felipe Orlando Lanzara R.A: 22.225.015-1 <br>
João Vitor Governatore R.A: 22.225.012-8 <br>
Pedro Henrique Legra Kramer Costa R.A: 22.125.091-3 <br>


## **Entrega 1 (concluído)**
**1) Conhecendo o Problema** 

1.1) Membros de Equipe (nome completo e número de matrícula): <br>
Felipe Orlando Lanzara R.A: 22.225.015-1 <br>
João Vitor Governatore R.A: 22.225.012-8 <br>
Pedro Henrique Legra Kramer Costa R.A: 22.125.091-3 <br>


1.2) Título Original do TCC: <br> Aprendizado de máquina aplicado na construção de carteiras de investimento adaptadas ao perfil de investimento

1.3) Nome do orientador:<br> Profa. Dra. Gabriela Oliveira Biondi

1.4) Previsto desenvolver Interface? ( X ) Sim     (   ) Não

1.5) Objetivo do trabalho? <br> Desenvolver um sistema capaz de prever o comportamento futuro de ações na bolsa de valores utilizando modelos de redes neurais recorrentes do tipo LSTM, integrando os resultados a um questionário de suitability para adequar as recomendações de ativos ao perfil de investidor.

1.6) Qual o produto final? <br> Uma página web interativa (InvestMind) com backend para comunicação com o banco de dados, treinamento apartado do machine learning, permitindo previsão de ações e recomendação personalizada de acordo com o perfil de risco.

1.7) Quem é o usuário final deste produto? <br> Investidores individuais, iniciantes ou experientes, que desejam suporte na análise de ações alinhada ao seu perfil de risco.

1.8) O que o usuário recebe de benefício ao usar esse produto? <br> 
•	Previsões personalizadas de preços de ações com base em dados históricos e indicadores econômicos. <br>
•	Recomendações de ativos alinhadas ao perfil de risco do investidor. <br>
•	Interface amigável para consulta e acompanhamento de resultados. 

1.9) Quais as funcionalidades da ferramenta (visão do usuário)? <br>
•	Cadastro e login de usuário. <br>
•	Questionário de perfil de investidor (suitability). <br>
•	Exibição do perfil de risco e pontuação. <br>
•	Consulta a previsões de preços para ativos selecionados. <br>
•	Visualização de gráficos comparativos entre preços reais e previstos.<br>
•	Histórico de previsões realizadas.

1.10) Quais tecnologias e ferramentas computacionais que pretendem usar neste projeto (TCC)? <br> 
•	Frontend: React.js, HTML5, CSS3, JavaScript. <br>
•	Backend: Node.js, Express. <br>
•	Banco de Dados: CockroachDB (compatível com PostgreSQL). <br>
•	Machine Learning: Python, TensorFlow/Keras, Pandas, NumPy, Matplotlib. <br>
•	Integração e APIs: Yahoo Finance, Banco Central do Brasil (SGS API). <br>
•	Controle de versão: Git/GitHub.

1.11) Qual é o contexto de uso dessa aplicação? (esse já é um conceito de IHC que professor explicou na sala) <br>
O sistema será utilizado em ambiente web por investidores que buscam suporte para tomada de decisão no mercado de ações. O contexto envolve análise de dados financeiros, aplicação de modelos preditivos e adequação das recomendações ao perfil de risco, permitindo acesso tanto em computadores quanto em dispositivos móveis, priorizando clareza de informações e usabilidade na navegação.

# **Entrega 2  (data) \[concluído]**

**\[1 solução completa por pessoa da equipe\]**

**Dica: fator mais importante desta entrega é a equipe conseguir identificar e documentar prints de telas de interfaces concorrentes (ou interfaces representativas para o público alvo). Esses prints serão usados na fase de caracterização de padrões, affordances, heurísticas, etc.**

1) **Público Alvo** <br>

Nosso público-alvo são pessoas que são responsáveis legais por si mesmas e têm interesse em investir seu dinheiro

1.1) 	***Perfil do público alvo segundo o Mercado**

1.1.1) Segmentação demográfica:

•	Idade: 25 a 55 anos (maior interesse em investimentos, potencial para uso de computador).
•	Escolaridade: Ensino superior e técnico (maior familiaridade com tecnologia e investimentos).
•	Renda: Média a alta (capacidade financeira para investir em ações).

1.1.2) Segmentação geográfica:
•	Usuários em áreas urbanas, com acesso estável à internet e computador.

1.1.3) Segmentação psicográfica:

•	Perfil de investidor iniciante, buscando orientação e segurança.
•	Investidor intermediário que deseja otimizar sua carteira com recomendações inteligentes.
•	Pessoas com interesse em finanças pessoais e busca por autonomia no investimento.

1.1.4) Segmentação comportamental:

•	Usuários que buscam recomendações rápidas e fáceis.
•	Usuários que valorizam transparência e explicação das sugestões.
•	Pessoas que utilizam computador como principal dispositivo para acessar serviços financeiros.


2) **Análise de Concorrência (quando identificado concorrência \- ATENÇÃO: CONCORRENTE NÃO É IDÊNTICO E SIM ATUANDO NA MESMA ÁREA)**  
**Principais concorrentes mais utilizados pelo seu público-alvo (link, descrição e imagens de ilustração):** <br>

• **Investidor10 [https://investidor10.com.br/]**

- Plataforma digital de informações financeiras que oferece dados detalhados sobre empresas listadas na bolsa, incluindo cotações, indicadores fundamentalistas e análises de mercado. O Investidor10 organiza as informações de forma clara e acessível, permitindo ao usuário acompanhar o desempenho das ações, comparar múltiplas empresas e avaliar tendências de crescimento no curto, médio e longo prazo.

![Investidor10](https://github.com/user-attachments/assets/4ec51129-8b1b-4afa-8904-809a6eee98d1)

• **StatusInvest [https://statusinvest.com.br/]**

- Plataforma digital de análise e monitoramento de ativos financeiros, que fornece indicadores e projeções sobre a tendência de crescimento das ações em diferentes horizontes temporais.

![StatusInvest](https://github.com/user-attachments/assets/d3429ebe-9b55-41df-9372-6186b673f8a3)

• **Corretora Rico [https://www.rico.com.vc/]**
- Corretora digital que fornece uma plataforma de compra e venda de ativos financeiros e acompanhamento do portfólio de ativos do usuário
  
![AppRico](https://github.com/user-attachments/assets/27566076-b192-40bc-b3ac-4c22eed8c8a9)

3) **Características e funcionalidades dos concorrentes:**

**Investidor10** <br>
- **Características** <br>
	- Plataforma de análise e monitoramento de ativos financeiros. <br>
	- Oferece dados completos sobre ações, FIIs, ETFs e BDRs, com foco em empresas listadas na bolsa brasileira. <br>
	- Gráficos interativos e indicadores fundamentais para análise de investimentos. <br>
- **Funcionalidades** <br>
	- Criação de listas personalizadas de ativos, com a possibilidade de acompanhar o desempenho ao longo do tempo.
	- Acompanhamento das cotações da B3 em tempo real.
	- Projeções e indicadores que ajudam a avaliar o potencial de crescimento de ações e outros ativos.
	- Comparação entre diferentes ativos e geração de relatórios detalhados.

**StatusInvest** <br>
- **Características** <br>
	- Foco em informações detalhadas sobre ativos da bolsa brasileira (ações, FIIs, ETFs, BDRs). <br>
	- Possui gráficos interativos e dashboards personalizados. <br>
- **Funcionalidades** <br>
	- Criação de listas personalizadas de ativos financeiros, com a possibilidade de acompanhamento da ação ao longo de um horizonte temporal. <br>
	- Acompanhamento em tempo real das cotações da B3. <br>
 
 **Corretora Rico**
 - **Características** <br>
	- Plataforma voltada para iniciantes e investidores experientes. <br>
	- Integração com produtos financeiros, permitindo compra e venda de ativos na própria corretora. <br>
- **Funcionalidades** <br>
	- Home broker para negociação de ações, FIIs, ETFs e derivativos. <br>
	- Simuladores e ferramentas de planejamento de investimentos. <br>
 	- Acesso a fundos de investimento, renda fixa, previdência e produtos estruturados. <br>

4) **Experiência do usuário (UX) e pesquisa de satisfação do cliente e opiniões:**

**Investidor10** <br>
	- Navegação clara, com informações financeiras detalhadas, proporcionando uma boa compreensão das ações e indicadores de mercado. <br>
	- Algumas informações podem ser mais complexas para iniciantes, mas o layout facilita o aprendizado gradual. <br>

**StatusInvest** <br>
	- Dashboards de fácil acesso e entendimento sobre os ativos da bolsa brasileira. <br>
 	- Navegação intuitiva, porém o site apresenta informações em excesso, podendo gerar dúvidas e confusões de informações para usuários iniciantes. <br>

**Corretora Rico** <br>
	- Navegação rápida, acessível a várias plataformas e com um design simplificado. <br>
 	- Execução de ordem de compra ou venda dos ativos com apenas um clique. <br>



5) **Padrões e tendências no mercado:**

Atualmente, observa-se uma tendência no uso de aplicações móveis e web que oferecem uma interface de fácil uso e entendimento ao investidor. Além da utilização de diversos perguntas para a construção do questionário de suitability e identificar o perfil de investimento do usuário. E encontra-se também o uso da Inteligência artificial para ajudar a instruir o investidor, principalmente os iniciantes na compra e venda de seus ativos financeiros.

# **Entrega 3 (data) \[concluído\]**

**1\) Personas**   

# Persona Pedro

![Pedro](https://github.com/user-attachments/assets/54fc361a-cfa2-4d81-af23-389da7c8cef4)


Atores: Pedro 


Pedro Henrique tem 21 anos, é estudante de Ciência da Computação e trabalha pela manhã, estudando à tarde-noite. Solteiro, mora com os pais e tem renda de estagiário/trainee, o que o torna atento a custos e sensível a riscos. Vive em um grande centro urbano no Brasil, desloca-se de transporte público e alterna entre notebook (para tarefas longas) e celular (para consultas rápidas).

Seus pais sempre enfatizaram a importância de investir para garantir um futuro financeiro tranquilo. No entanto, devido à sua rotina cheia, trabalhando pela manhã e estudando à tarde-noite, ele tem pouco tempo para se dedicar ao estudo de investimentos. Mesmo aos finais de semana, ele precisa se concentrar nas tarefas da faculdade, no TCC e na iniciação didática. Embora tenha o desejo de investir em ações, ele se sente inseguro e tem medo de perder dinheiro por falta de conhecimento.

Durante uma pesquisa no GitHub, Pedro encontrou o repositório do InvestMind, que oferece sugestões de ações com base em previsões de um modelo de machine learning. Com sua formação em ciência da computação, ele se sentiu mais seguro para arriscar, confiando no fato de que o modelo poderia fazer uma análise temporal dos preços das ações e recomendar o melhor momento para investir. Embora não soubesse exatamente qual modelo foi utilizado, ele confiava na ideia de que o sistema de IA seria mais preciso do que suas próprias decisões.

Pedro clonou o repositório, subiu a aplicação, preencheu o questionário de suitability e, por já ter experiência em navegar por sites, teve facilidade em interagir com a plataforma. Após preencher o formulário, ele utilizou um gráfico de timesplot para identificar o melhor momento para vender a ação. Alguns dias depois, ele seguiu a recomendação, vendeu as ações e obteve lucro.


# Persona Primária João Vitor

![João](https://github.com/user-attachments/assets/5cc5dbb9-6d51-4605-a9c9-2fa3b9d6d192)

João Vitor é um senhor com 65 anos de idade, pai de dois filhos, professor da rede pública do estado de São Paulo e está muito próximo de se aposentar. Ele passou muitos anos guardando dinheiro em sua poupança, e ouvindo rumores a respeito do mercado financeiro, especificamente em ações e em sua maior rentabilidade em comparação com uma poupança. Ao conhecer uma plataforma, ele criou sua conta e respondeu ao questionário de Suitability disponibilizado, e foi classificado como investidor conservador.

Após o preenchimento foi apresentado a João gráficos e dashboards com letras muito pequenas, cores de fácil confusão, trazendo uma maior dificuldade para a interpretação dos dados mostrados em relação as ações recomendadas. Além disso na apresentação dos gráficos e dashboards foram exibidos termos técnicos e indicadores complexos, como volatilidade. O que pode gerar um conflito aos usuários iniciantes.

Essas dificuldades geraram frustrações e insegurança, levando a João abandonar o uso da plataforma. Esse cenário revela falhas relacionadas à usabilidade e acessibilidade à plataforma. Podendo oferecer recursos como ajuste de tamanho de fonte e uma linguagem mais clara e apresentável para esses públicos.

Para João, o mais importante não é acessar métricas complexas ou acompanhar gráficos avançados em tempo real, mas sim ter clareza e segurança sobre onde seu dinheiro pode ser aplicado. Ele valoriza informações apresentadas de forma simples, que deixem claro o nível de risco e o potencial de retorno de cada ação, sem a utilização de termos técnicos.

# Persona Primária Felipe Orlando

![Felipe](https://github.com/user-attachments/assets/d4b94eb8-7cbd-4340-b2df-ca5b57b85624)


Atores: Felipe Orlando - "Busca por mais conhecimento"

Felipe Orlando tem 42 anos, é engenheiro civil e investe em ações há mais de 10 anos. Ele já possui uma carteira diversificada, acompanha o mercado diariamente e entende bem conceitos como volatilidade, dividend yield e valuation. Apesar da experiência, Felipe busca principalmente ganhar dinheiro de forma mais rápida e aceita os riscos e possíveis consequências de estratégias mais arrojadas. Ao conhecer a nossa plataforma, criou sua conta, respondeu ao questionário de Suitability e foi classificado como investidor agressivo.

Após o preenchimento, Felipe teve acesso a dashboards avançados com gráficos preditivos baseados em modelos de deep learning (LSTM). Mesmo com seu bom conhecimento, percebeu que alguns relatórios apresentavam informações redundantes ou pouco customizáveis, o que dificultava integrar os dados da plataforma com suas próprias planilhas e rotinas. Além disso, notou que, em alguns momentos, os gráficos não deixavam explícitos os gatilhos de mercado que embasam as projeções — como movimentos de commodities, variações do dólar ou decisões de política monetária nem traduziam essas previsões em pontos objetivos de entrada, stop e alvo para operações rápidas.

Essas limitações não o fizeram abandonar a plataforma, mas mostraram oportunidades de melhoria: oferecer filtros realmente personalizáveis voltados à agilidade (presets para day/swing trade, janelas intradiárias, latência/atualização em tempo quase real), maior transparência sobre os fatores externos que influenciam as previsões com faixas de confiança, e exportação simples para as ferramentas que ele já usa (Excel/Google Sheets, API/webhook e integração direta com o home broker).

Para Felipe, o mais importante é transformar sinais em resultado financeiro com rapidez, assumindo os riscos inerentes. Ele valoriza ter, em um só lugar, dashboards claros com os gráficos de previsão da plataforma que mostram, para cada ação, a estimativa de crescimento projetada para os próximos dois anos, além de uma leitura objetiva da tendência e da faixa de confiança. Com isso, consegue comparar rapidamente oportunidades, definir pontos de entrada com base no potencial de alta indicado e ajustar sua exposição conforme o risco que topa correr, usando a plataforma como um atalho prático para capturar movimentos de mercado.


**2\) Mapa de Empatia \[1 por equipe\]**

A persona João Vitor foi escolhida como principal para o mapa de empatia por representar o perfil mais próximo do público que deve utilizar a plataforma: investidores iniciantes ou conservadores que buscam sair da poupança, mas ainda sentem insegurança diante de informações complexas.

Nome: João Vitor | Idade: 65 anos


- O que ve: <br>
  - Oportunidade de retirar o dinheiro em sua poupança e investir em alguma ação com maior lucratividade.
  - Gráficos e dashboards com termos técnicos e letras pequenas.
  - Dificuldade na interpretação dos dados recomendados.
---

- O que ouve: <br>
  - Rumores sobre a maior rentabilidade do mercado financeiro em comparação à poupança.
  - Ouve termos técnicos sem explicações claras, aumentando sua insegurança no mercado financeiro.
  - Notícias sobre oportunidades diferentes de investimento.
---

- O que pensa e sente: <br>
  - Desconfiança no investimento de seu dinheiro no mercado financeiro.
  - Preocupação de que seu investimento poderia estar rendendo mais em outro lugar.
  - Confuso com as recomendações de investimento.
---

- O que fala e faz: <br>
  - Reclama que os gráficos e termos técnicos são difíceis de entender.
  - Acessa a plataforma para conferir recomendações, mas demonstra hesitação antes de tomar decisões de investimento.
  - Comenta com amigos ou familiares sobre a dificuldade de interpretar os dados e pede ajuda para confirmar se está fazendo a escolha certa.
---

- Dores (frustrações e obstáculos) <br>
  - Falta de usabilidade e acessbilidade à plataforma.
  - Preocupação de que seu investimento poderia estar rendendo mais em outro lugar.
---

- Necessidades <br>
  - Melhoria na acessibilidade e usabilidade da plataforma à pessoas com prioridades.
  - Garantir que seu capital esteja alocado nas oportunidades mais rentáveis do mercado financeiro, de acordo com seu perfil conservador.
---

**3\) Contexto de Uso \[1 por equipe\]**
- **Ambiente:**
	- Local: em casa, geralmente na sala ou escritório.
	- Aparelho: computador/desktop com tela maior, usando mouse e teclado.
	- Horário: no período da noite, após retornar do trabalho e organizar suas tarefas pessoais.
---
- **Aspectos Sociais**
	- Usuários podendo ser influenciados por amigos, familiares ou colegas de trabalho que também investem.
 	- Informações sobre investimentos compartilhadas em redes sociais ou grupos de amigos, podendo impactar o investidor na escolha das ações a serem investidas.
  	- Usuários com maior experiência ou conhecimento financeiro tendem a lidar melhor com oscilações de mercado.
  	- Usuários com perfil conservador podem se sentir ansiosos e evitar investimentos com uma alta volatilidade.
---
- **Dados que precisam ser armazenados previamente pelo sistema**
	- Perfil do investidor: resultado do questionário de Suitability (ex.: conservador, moderado ou arrojado) para personalizar recomendações.
 	- Dados pessoais de cada usuário: nome, e-mail e credenciais necessárias para autenticação e personalização da experiência.
 	- Valores previstos para cada ação no futuro: projeções calculadas pelo modelo de previsão a serem exibidas em gráficos.
  	- Valores históricos de cada ação no passado: dados reais que serão apresentados em formato de gráfico para comparação com as previsões.
---

**4\) Jornada do Usuário \[1 por equipe\]**

 1. **Antes de usar (início do uso)**
	- Chega em casa após o trabalho como professor e procura um momento de tranquilidade.
	- Decide acessar o site para buscar alternativas mais rentáveis que a poupança.
	- Liga o computador e entra na plataforma com expectativa de clareza e segurança.

 2. Durante o uso (experiência na plataforma)
	- Responde ao questionário de Suitability e descobre seu perfil de investidor.
	- Explora os dashboards de previsões de ações, mas encontra dificuldade em interpretar gráficos e termos técnicos.
	- Consulta informações sobre rentabilidade e riscos, tentando comparar opções de investimento.
	- Demonstra interesse, mas também insegurança ao tomar decisões baseadas nos dados apresentados.

 3. Depois de usar (encerramento da experiência)
	- Faz anotações simples sobre as informações consultadas.
	- Conversa com familiares para confirmar suas impressões e buscar opiniões.
	- Encerra o acesso sentindo necessidade de maior clareza e acessibilidade, mas com esperança de continuar usando o site como apoio.

# **Entrega 4  (data) \[concluído\]**

**\[1 solução completa por pessoa da equipe\]**

**Dica: Cada membro de equipe deve pensar em cenários existentes na atualidade (que causam problemas para os usuários) e que a interface prevista ajudará a resolver o problema. Cenário de Análise/Problema é uma história triste. Não descreve a solução. Descreve somente o problema.**

## 1) **Cenário de Análise/Problema**

### Cenário de Análise/Problema - João Vitor
### Clareza e Simplicidade: A Necessidade de Usabilidade para Investidores Iniciantes
Atores: João Vitor (investidor iniciante)

João Vitor, é um senhor de 65 anos de idade professor da rede pública do estado de São Paulo, ele passou muitos anos guardando dinheiro em sua poupança, após ouvir rumores a respeito do mercado de investimento sobre maior rentabilidade de seu patrimônio em comparação com a poupança. Então decide retirar seu investimento aplicado e comprar ações.

Após um longo dia de trabalho, João está em sua casa à frente de seu computador pessoal com o objetivo de explorar, entender e encontrar investimentos além da poupança. Seu plano mental é que ao navegar pelas ações recomendadas para seu perfil a plataforma apresente informações claras e com uma linguagem condizente ao seu perfil. Então João cria uma conta em uma plataforma de recomendação de ações e preenche o questionário de suitability, onde o classifica como perfil conservador.

Após a classificação é recomendado diversas ações para investir, porém essas recomendações apresentam uma linguagem de difícil entendimento, com gráficos e dashboards com letras pequenas, linguagem técnica e cores de fácil confusão, não entendendo o significado de termos como volatilidade e não encontrando explicação simples no site.

João avalia a plataforma de forma negativa, concluindo que o site é útil para pessoas que apresentam um conhecimento prévio sobre investimento financeiro, não sendo o caso dele e se sentindo frustado e inseguro se realmente vale a pena retirar seu investimento na poupança, por sua incapacidade de interpretar as informações e gráficos oferecidos a ele. Sua ação final foi de fechar a plataforma, abandonar o uso e continuar pesquisando sobre esse universo com amigos.

### Cenário de Análise/Problema - Felipe
### Busca por Mais Conhecimento: A Necessidade de Ferramentas Avançadas para Investidores Experientes
Atores: Felipe Orlando (Investidor Agressivo)

Felipe Orlando tem 42 anos, é engenheiro civil e investe em ações há mais de 10 anos. Ele já possui uma carteira diversificada, acompanha o mercado diariamente e entende bem conceitos como volatilidade, dividend yield e valuation. Apesar da experiência, Felipe busca principalmente ganhar dinheiro de forma mais rápida e aceita os riscos e possíveis consequências de estratégias mais arrojadas. Ao conhecer a nossa plataforma, criou sua conta, respondeu ao questionário de Suitability e foi classificado como investidor agressivo.

Após o preenchimento, Felipe teve acesso a dashboards avançados com gráficos preditivos baseados em modelos de deep learning (LSTM). Mesmo com seu bom conhecimento, percebeu que alguns relatórios apresentavam informações redundantes ou pouco customizáveis, o que dificultava integrar os dados da plataforma com suas próprias planilhas e rotinas. Além disso, notou que, em alguns momentos, os gráficos não deixavam explícitos os gatilhos de mercado que embasam as projeções — como movimentos de commodities, variações do dólar ou decisões de política monetária nem traduziam essas previsões em pontos objetivos de entrada, stop e alvo para operações rápidas.

Essas limitações não o fizeram abandonar a plataforma, mas mostraram oportunidades de melhoria: oferecer filtros realmente personalizáveis voltados à agilidade (presets para day/swing trade, janelas intradiárias, latência/atualização em tempo quase real), maior transparência sobre os fatores externos que influenciam as previsões com faixas de confiança, e exportação simples para as ferramentas que ele já usa (Excel/Google Sheets, API/webhook e integração direta com o home broker).

Para Felipe, o mais importante é transformar sinais em resultado financeiro com rapidez, assumindo os riscos inerentes. Ele valoriza ter, em um só lugar, dashboards claros com os gráficos de previsão da plataforma que mostram, para cada ação, a estimativa de crescimento projetada para os próximos dois anos, além de uma leitura objetiva da tendência e da faixa de confiança. Com isso, consegue comparar rapidamente oportunidades, definir pontos de entrada com base no potencial de alta indicado e ajustar sua exposição conforme o risco que topa correr, usando a plataforma como um atalho prático para capturar movimentos de mercado.

### Cenário de Análise/Problema - Pedro
### Frustação: A Necessidade de reavaliação do perfil de investidor
Atores: Pedro

Pedro começou a investir no ano passado utilizando o software InvestMind [1]. [5] ao criar sua conta, ele logou e respondeu ao questionário de Suitability e foi classificado como um investidor agressivo, perfil que condizia com seu comportamento naquele momento. Com isso, o sistema passou a recomendar ativos de maior risco e alta volatilidade, compatíveis com essa classificação.

Com o passar do tempo (1 ano), Pedro modificou seu comportamento de investimento. Ele passou a se interessar por ações mais estáveis, de menor risco e volatilidade, adotando assim uma postura mais conservadora. O problema é que o software não possuía qualquer mecanismo automático para identificar essa mudança de comportamento ou sugerir uma reavaliação do perfil. Dessa forma, as recomendações continuaram sendo voltadas a um investidor agressivo.

Pedro, sem perceber que seu perfil ainda estava configurado como agressivo, seguiu aplicando seu dinheiro nos ativos sugeridos pela plataforma. Ao final do período planejado, constatou que havia sofrido perdas financeiras em razão da alta volatilidade das ações escolhidas. Apenas após esse prejuízo, ele verificou manualmente seu perfil no sistema, refez o questionário de Suitability e, então, foi corretamente reclassificado como conservador.

Esse cenário revela falhas de interface humano-computador relacionadas à falta de feedback e de prevenção de erros. O sistema poderia ter um indicativo melhor, mais visual sobre o tipo de perfil atual de Pedro e poderia se mostrar mais adaptável às mudanças do usuário ao longo do tempo. De tempos em tempos o sistema deveria realizar uma reavaliação periódica do perfil de investidor para verificar se o mesmo se manteve. Após seis meses de uso, o aplicativo poderia ter solicitado automaticamente a Pedro que refizesse o questionário, o que teria evitado a recomendação de investimentos incompatíveis.

2) ## **Questões de Refinamento**

# Questões de refinamento (João Vitor):

| Indice | Elemento |Pergunta | Resposta |
| -- | -- | -- | -- |
| 	[1]   |   objetivo       | De que informações ou conhecimento João precisa para explorar, entender e encontrar investimentos além da poupança?  |  |
| 	[2]   |   ambiente       | Em que situação João decide decide aplicar seu investimento em ações (quando, onde e por quê)?                       |  |
| 	[3]   |   ator(es)		 | Quais características de João auxiliou a atrapalhar o alcance do objetivo?                                           |  |
| 	[4]   |   planejamento	 | Em que ordem João precisam realizar as ações? Poderia realizá-la de outra maneira?                            	    |  |
| 	[5]   |   ação       	 | Quais erros podem ser cometidos ao utilizar a plataforma? Como podem ser desfeitos? Quais são suas consequências?    |  |
| 	[6]   |   evento		 | Quais eventos disparam a necessidade de João alcançar o objetivo?    											    |  |
| 	[7]   |   avaliação		 | Qual é o resultado do alcance do objetivo?     																	    |  |

# Refinamento do Cenário Análise/Problema (João Vitor)
### Clareza e Simplicidade: A Necessidade de Usabilidade para Investidores Iniciantes
Atores: João Vitor (investidor iniciante)

João Vitor, é um senhor de 65 anos de idade professor da rede pública do estado de São Paulo, ele passou muitos anos guardando dinheiro em sua poupança, após ouvir rumores a respeito do mercado de investimento sobre maior rentabilidade de seu patrimônio em comparação com a poupança [6]. Então decide retirar seu investimento aplicado e comprar ações. [2]

Após um longo dia de trabalho, João está em sua casa à frente de seu computador pessoal em um momento de tranquilidade após um longo dia de trabalho [2], com o objetivo de explorar, entender e encontrar investimentos além da poupança, porém com moderação por ser iniciante no universo digital e financeiro [3]. Seu plano mental é que ao navegar pelas ações recomendadas para seu perfil a plataforma apresente informações claras e com uma linguagem condizente ao seu perfil, com frases como "baixo risco" ou "recomendado para iniciantes", além do potencial de retorno relacionado a cada investimento [1]. Então João cria uma conta em uma plataforma de recomendação de ações e preenche o questionário de suitability, onde o classifica como perfil conservador [4]. O principal erro que João pode cometer é preenchê-lo de forma imprecisa por não compreender as perguntas, ocasionando uma classificação de perfil incorreta. O erro mais crítico, no entanto, é da própria plataforma, que ao classificá-lo corretamente como conservador, ainda assim apresenta a ele informações complexas com gráficos e termos técnicos. A consequência disso é a recomendação de ações inadequadas e a frustração imediata de João, que se sente inseguro e incapaz de prosseguir. Para desfazer esses erros a plataforma poderia oferecer uma forma de mostrar informações simplificadas mas ainda assim transmitindo todos as informações diferenciais e úteis para a realização do investimento. [5]

Após a classificação é recomendado diversas ações para investir, porém essas recomendações apresentam uma linguagem de difícil entendimento, com gráficos e dashboards com letras pequenas, linguagem técnica e cores de fácil confusão, não entendendo o significado de termos como volatilidade e não encontrando explicação simples no site.

João avalia a plataforma de forma negativa, concluindo que o site é útil para pessoas que apresentam um conhecimento prévio sobre investimento financeiro, não sendo o caso dele e se sentindo frustado e inseguro se realmente vale a pena retirar seu investimento na poupança, por sua incapacidade de interpretar as informações e gráficos oferecidos a ele. Sua ação final foi de fechar a plataforma, abandonar o uso e continuar pesquisando sobre esse universo com amigos [7].


# Questões de refinamento (Felipe):

| Indice | Elemento |Pergunta | Resposta |
| -- | -- | -- | -- |
| 	[1]   |   objetivo       | Quais funcionalidades avançadas são necessárias para que Felipe sinta que a plataforma realmente agrega valor às suas análises?                   |  |
| 	[2]   |   ambiente       | Como o contexto de investidor experiente influencia a forma como Felipe interage com a plataforma?                                                |  |
| 	[3]   |   ator(es)		 | De que maneira o alto nível de conhecimento de Felipe pode se tornar uma barreira, levando-o a considerar a plataforma simplista ou insuficiente? |  |
| 	[4]   |   planejamento	 | Como Felipe organiza suas etapas de análise e de que forma a plataforma poderia apoiar melhor esse fluxo?                        	             |  |
| 	[5]   |   ação       	 | O que acontece quando Felipe tenta personalizar relatórios ou cruzar informações externas com os dashboards oferecidos pela plataforma?           |  |
| 	[6]   |   evento		 | Que situações do mercado despertam em Felipe a necessidade de recorrer a previsões mais claras e detalhadas? 						     	     |  |
| 	[7]   |   avaliação		 | Como Felipe percebe o equilíbrio entre inovação tecnológica e usabilidade prática na plataforma?												     |  |

# Refinamento do Cenário Análise/Problema (Felipe)
### Busca por Mais Conhecimento: A Necessidade de Ferramentas Avançadas para Investidores Experientes
Atores: Felipe (investidor Agressivo)

Felipe Orlando, engenheiro civil de 42 anos, possui mais de 10 anos de experiência no mercado de ações. Ao longo de sua trajetória, desenvolveu amplo domínio de conceitos técnicos como volatilidade, dividend yield e valuation. Apesar de sua vivência, Felipe busca constantemente ferramentas que ampliem sua capacidade analítica e tragam previsões mais precisas para suas decisões de investimento. Nesse contexto, funcionalidades avançadas como filtros técnicos, maior transparência sobre variáveis externas (ex.: dólar, commodities) e a possibilidade de ver previsões sobre ações tornam-se essenciais para que ele perceba valor real na plataforma [1].

O cenário ocorre em seu cotidiano de investidor ativo, que dedica tempo diariamente à análise de relatórios de corretoras e ao acompanhamento do mercado [2]. Nesse ambiente, a plataforma surge como complemento às ferramentas já utilizadas, mas enfrenta o desafio de atender a um usuário que possui alto nível de conhecimento. Tal expertise, embora positiva, pode transformar-se em barreira: Felipe percebe limitações mais facilmente e tende a considerar simplistas as soluções que não oferecem profundidade ou flexibilidade suficientes [3].

Ao utilizar a plataforma, Felipe segue uma sequência de etapas: cria sua conta, realiza o questionário de suitability, acessa dashboards avançados e recebe sua recomendação de ações. Esse fluxo é funcional, mas poderia ser otimizado se houvesse, por exemplo, filtros técnicos disponíveis já no início da análise, permitindo maior personalização [4]. Durante suas interações, Felipe se depara com dificuldades ao tentar personalizar relatórios ou cruzar dados da plataforma com informações externas. A falta de flexibilidade limita sua capacidade de análise comparativa, gerando frustração e a percepção de que a ferramenta ainda não está pronta para seu perfil avançado [5].

A necessidade de previsões mais claras e detalhadas torna-se ainda mais evidente em situações de alta volatilidade do mercado, como oscilações do dólar, impacto das commodities ou a divulgação de balanços trimestrais de grandes empresas. Esses eventos disparam sua busca por relatórios mais transparentes e detalhados, que lhe permitam validar de forma independente as informações fornecidas pelo sistema [6].

Ao final, Felipe reconhece a plataforma como uma iniciativa inovadora, principalmente pelo uso de técnicas modernas de deep learning (LSTM). Contudo, sua avaliação mostra que ainda há desequilíbrio entre inovação tecnológica e usabilidade prática. Para ele, a ausência de flexibilidade, clareza metodológica e opções de integração compromete o potencial de a plataforma se consolidar como diferencial em sua tomada de decisão [7].


# Questões de refinamento (Pedro):


| Indice | Elemento       | Pergunta                                                    | Resposta |
|---|---|---|---|
| [1] ok | objetivo         | Qual é o objetivo principal do Pedro ao usar o InvestMind?  | Seu objetivo ao usar o InvestMind é converter janelas curtas em decisões seguras e objetivas, evitando dinheiro parado e minimizando decisões leigas. |
| [2] ok | ambiente         | Em que contexto por trás do descobrimento da plataforme?     | Pedro utiliza seu notebook para realizar suas tarefas acadêmicas , para aprender e programar e para realizar investimentos no portal do Banco, enquanto usa seu celular para lazer como escutar música, assistir videos no youtube ou jogar jogos mobile. Durante uma de suas sesão de estudo de IA pedro descobriu um repositório do Github chamado InvestMind.  |
| [3] ok | ator(es)         | Quais atores foram impactados pela perda | Pedro ficou abatido ao perceber que as ações em que havia investido caíram, em vez de subir como esperava. Chorou, contou aos pais a perda de R$ 500 e, no calor do momento, culpou o InvestMind, chamou o software de “péssimo” e afirmou que a responsabilidade não era dele, a notícia logo se espalhou pela vizinhança e os vizinhos passaram a conhecer o software como ínutil |
| [4] | planejamento     	| Quais metas, critérios e configurações Pedro define antes de usar o aplicativo?      | Após ler o README, Pedro entende que o InvestMind apenas sugere oportunidades a decisão de utilizar ou não é dele. Por isso, define metas SMART: alcançar R$ 1.000 de lucro em 12 meses, desembolsando R$ 200/mês. |
| [5] ok | ação            	| Quais ações realiza na interface para poder acessar o core (carteira de investimentos) do aplicativo?                         | Ao abrir o aplicativo Pedro se deparou com uma interface escrita login, ele não possuia login, então interagiu com o botão cadastro, inseriu as credenciais solicitadas (CPF, nome, sobrenome, celular, idade) e em seguida submeteu as credenciais fornecidas. |
| [6]  | evento           | Quais eventos (de mercado, do sistema e pessoais) levaram Pedro a mudar seu comportamento de investidor?           | Pedro começou a presenciar que seus amigos proximos começaram a utilizar seus dinheiros ganhos com esforços em apostas e cassinos, alegando que iria aumentar sua renda, mas, pelo contrário, os levou a perder dinheiro, Pedro, que não é bobo, começou a repensar suas próprias ações de investimento. |
| [7]  ok| avaliação        | Como o usuário avalia o uso do aplicativo                |	Durante o uso do aplicativo, Pedro teve facilidade em utilizá-lo, pois o mesmo apresentava uma interface limpa e objetiva. Ele conseguiu navegar facilmente pelos gráficos, simular ações e realizar operações de compra e venda de forma rápida, o que lhe permitiu economizar tempo. Sentindo-se mais confiante, Pedro decidiu seguir as recomendações baseadas na classificação do seu perfil de investidor.

Ele avaliou positivamente essa experiência inicial, destacando que a clareza visual e a fluidez da navegação foram essenciais para que se sentisse confortável com a plataforma. A organização das informações e a simplicidade no acesso às funcionalidades deram a ele uma sensação de controle, mesmo sendo um investidor relativamente novo.  |



# Refinamento do Cenário Análise/Problema (Pedro)
### Frustação: A Necessidade de reavaliação do perfil de investidor
Atores: Pedro

[2] Pedro utiliza seu notebook para realizar suas tarefas acadêmicas, para aprender e programar e para realizar investimentos no portal do Banco, enquanto usa seu celular para lazer como escutar música, assistir vídeos no YouTube ou jogar jogos mobile. Durante uma de suas sessão de estudo de IA Pedro descobriu um repositório do Github chamado InvestMind. [1] Seu objetivo ao usar o InvestMind é converter janelas curtas em decisões seguras e objetivas, evitando dinheiro parado e minimizando decisões leigas.

[5] Ao abrir o aplicativo Pedro se deparou com uma interface escrita login, ele não possuía login, então interagiu com o botão cadastro, inseriu as credenciais solicitadas (CPF, nome, sobrenome, celular, idade) e em seguida submeteu as credenciais fornecidas. Em seguida respondeu ao questionário de suitability e foi classificado como um investidor agressivo, um perfil que combinava com seu comportamento na época.

[6] Com o passar do tempo, Pedro começou a presenciar que seus amigos próximos começaram a utilizar seus dinheiros ganhos com esforços em apostas e cassinos, alegando que iria aumentar sua renda, mas, pelo contrário, os levou a perder dinheiro; Pedro, que não é bobo, começou a repensar suas próprias ações de investimento. Ele passou a se interessar por ações mais estáveis, de menor risco e volatilidade, adotando uma postura mais conservadora. O problema é que o software não possuía qualquer mecanismo automático para identificar essa mudança de comportamento ou para sugerir uma reavaliação do perfil.

[4] Após ler o README, Pedro entende que o InvestMind apenas sugere oportunidades — a decisão de utilizar ou não é dele. Por isso, define metas SMART: alcançar R$ 1.000 de lucro em 12 meses, desembolsando R$ 200/mês. Ainda assim, como as recomendações continuavam orientadas ao perfil agressivo original, houve descompasso entre as metas e o tipo de ativo recomendado.

Ao final do período planejado, [3] Pedro ficou abatido ao perceber que as ações em que havia investido caíram, em vez de subir como esperava. Chorou, contou aos pais a perda de R$ 500 e, no calor do momento, culpou o InvestMind, chamou o software de “péssimo” e afirmou que a responsabilidade não era dele; a notícia logo se espalhou pela vizinhança e os vizinhos passaram a conhecer o software como inútil. Foi somente após o prejuízo que ele verificou manualmente seu perfil no sistema, refez o questionário de suitability e, então, foi corretamente reclassificado como conservador.

[7] Durante o uso do aplicativo, Pedro teve facilidade em utilizá-lo, pois o mesmo apresentava uma interface limpa e objetiva. Ele conseguiu navegar facilmente pelos gráficos, simular ações e realizar operações de compra e venda de forma rápida, o que lhe permitiu economizar tempo. Sentindo-se mais confiante, decidiu seguir as recomendações baseadas na classificação do seu perfil de investidor. Ele avaliou positivamente essa experiência inicial, destacando que a clareza visual e a fluidez da navegação foram essenciais para que se sentisse confortável com a plataforma. A organização das informações e a simplicidade no acesso às funcionalidades deram a ele uma sensação de controle, mesmo sendo um investidor relativamente novo.


# **Entrega 5  (data) \[concluído\]**

**\[1 solução por pessoa\]**

**DICA: nesta entrega a equipe deve descrever as funcionalidades mais importantes da interface/produto. Dividir pelo número de integrantes. Cada um se responsabiliza pela modelagem de 1 bloco. Cada aluno deve modelar pelo menos 1 HTA, 1 GOMS e 1 CTT (de funcionalidade diferentes ou da mesma \- escolha de cada um). Cada diagrama deve ter um texto explicando a funcionalidade.**

**Análise de Tarefas**

# Cadastro de Usuários na plataforma

**1\) HTA**
![HTA Cadastro](https://github.com/user-attachments/assets/47c3b87b-068e-4487-8292-bbb6960ec473)



| Objetivos/Operações | Problemas e Recomendações | 
| --      | -- | 
| 	0. Cadastrar usuáro na plataforma 1>2   |Input: formulário de cadastro com dados pessoais, dados de acesso e aceite dos termos. <br> Feedback: cadastro aparece como pendente até a validação do sistema.<br> Plano: informar dados e depois validar os dados preenchidos para liberar acesso. <br> Recomendação: permitir que o usuário faça o cadastro online de forma simples e intuitiva.| 
| 	1. Coletar informações do usuáro (1+2) > 3|Plano: coletar dados pessoais, credenciais de acesso e confirmação do aceite dos termos obrigatórios.| 
| 	1.1 Solicitar dados pessois   |Problema: risco de informações incompletas ou inválidas (ex: CPF incorreto).<br> Recomendação: implementar máscaras de entrada e validação automática de campos.| 
| 	1.2 Solicitar dados de acesso à plataforma   |Problema: senhas fracas ou repetidas.<br>Recomendação: exigir senha forte (mínimo de caracteres, números, letras e símbolos) e validar formato de e-mail.   	 | 
| 	1.3 Confirmar a leitura e aceitação dos termos de uso e política de privacidade |Problema: usuários podem não ler os termos.<br> Recomendação: destacar pontos críticos antes do aceite (ex: uso de dados pessoais) e exigir confirmação obrigatória para prosseguir.|
| 	2. Validar informações preenchidas 1+2  |Ação: verificar consistência e autenticidade dos dados.<br> Recomendação: usar validações automáticas para reduzir erros manuais.|
| 	2.1 Verificar e-mail e senha preenchida   |Problema: e-mail inválido ou duplicado.<br> Recomendação: checagem em tempo real do e-mail preenchido.|
| 	2.2 Checar se o CPF já foi cadastrado anteriormente no sistema 1>2   |Problema: cadastro duplicado.<br> Recomendação: bloquear duplicidade e exibir mensagem clara ao usuário.|
| 	2.2.1 Cadastrar dados pessoais e de acesso ao banco de dados se corretos   |Plano: salvar dados somente após validação de unicidade (e-mail e CPF).|
| 	2.2.2 Redirecionar à página de login 1>2>3   |Ação: após validação, redirecionar automaticamente para login.|
| 	2.2.2.1 Solicitar e-mail e senha cadastrados   |Problema: usuários podem tentar acessar com credenciais válidas, mas em dispositivos públicos ou compartilhados (ex.: lan houses, computadores de faculdade).<br>Recomendação: oferecer opção de “Não manter conectado” por padrão e alertar sobre riscos de salvar senha em dispositivos não pessoais.|
| 	2.2.2.2 Verificar e-mal e senha preenchidos   |Problema: login falho após cadastro.<br>Recomendação: exibir mensagens claras de erro (“E-mail ou senha incorretos”).|
| 	2.2.2.3 Redirecionamento para a página inicial da plataforma se corretos   |Plano: acesso concedido somente após validação correta.<br>Recomendação: exibir mensagem de boas-vindas ou tutorial inicial.|

**2\) GOMS**

GOAL 0: Cadastrar usuáro na plataforma

- GOAL 1: Coletar informações do usuáro
	 - METHOD 1.A: preencher os dados pessoais manualmente <br>
 	(SEL.RULE: todos os campos obrigatórios devem ser preenchidos)
  
	   	- OP.1.A.1: preencher os dados pessoais (nome, CPF, data de nascimento,...)
		- OP.1.A.2: preencher os dados de aceso (e-mail e senha)
	   	- OP.1.A.3: marcar checkbox de aceite dos termos de uso e política de privacidade
	  	- OP.1.A.4: planejar a sequência de preenchimento (dados pessoais → acesso → termos)
    	- OP.1.A.5: verificar se os dados foram preenchidos corretamnente
      
    - METHOD 1.B: Preencher os dados pessoais utilizando comando por voz <br>
    (SEL.RULE: todos os campos obrigatórios devem ser preenchidos)
		- OP.1.B.1: clicar ou tocar no ícone de microfone ao lado do campo.
    	- OP.1.B.2: ditar os dados pessoais (nome, CPF, data de nascimento,...)
     	- OP.1.B.3: ditar os dados de acesso (e-mail e senha)
      	- OP.1.B.4: marcar checkbox de aceite dos termos de uso e política de privacidade 
     	- OP.1.B.5: verificar se os dados foram preenchidos corretamnente
     
- GOAL 2: Validar informações preenchidas
	<!-- - METHOD 2.A: validar informações dos dados do usuário <br>
 	(SEL.RULE: ocorre sempre após o envio do formulário de cadastro) -->

  	- OP.2.A.1: verificar campos do formulário
  	- OP.2.A.2: preencher campos do formulário
	- OP.2.A.3: clicar no botão “Cadastrar” <br>


	- GOAL 2.A.3.A: validar dados pessoais
  		- OP.2.A.3.A.1: interpretar mensagens de erro
	   	- OP.2.A.3.A.2: corrigir campos e clicar novamente no botão de cadastrar <br>
	- GOAL 2.A.3.B: validar dados de acesso da plataforma
   		- OP.2.A.3.B.1: validar rejeição do e-mail ou senha
   	  	- OP.2.A.3.B.2:	interpretar mensagens de erro e realizar a correção
		- OP.2.A.3.B.3: corrigir campos e clicar novamente no botão de cadastrar	 	 
  		- OP.2.A.3.B.4: aguardar e verificar a exibição da mensagem de sucesso do cadastro dos dados pessoais
	 	

- GOAL 3: Checar se o CPF já foi cadastrado anteriormente no sistema
  
  <!-- - METHOD 2.A: validar CPF preenchido <br>
	(SEL.RULE: se o sistema exibir alerta de CPF já cadastrado anteriormente) -->

	- OP.2.A.1: clicar em “Logar” ou mudar dados de cadastro do usuário e preencher os campos novamente
	- OP.2.A.2: decidir continuar para login ou cadastrar novo usuário com outro CPF


- GOAL 4: Redirecionar à página de login
	- GOAL 4.A: acessar a tela de login exibida pelo sistema
		- OP 4.A.1: reconhecer a mensagem de feedback (“Cadastro realizado com sucesso” ou “CPF já cadastrado”)
  		- OP 4.A.2: clicar no botão/link “Ir para login”
    	- OP 4.A.3: identificar os campos de e-mail e senha na tela de login
		- OP 4.A.4: focar o cursor no campo de e-mail para iniciar autenticação
  		- OP 4.A.5: clicar no botão Logar e aguardar o redirecionamento para a página inicial, caso o usuário já esteja previamente cadastrado.
    	- OP 4.A.6: aguardar e verificar se a página inicial foi carregada
    
	- GOAL 4.B: validar dados de acesso da plataforma (tela login) <br>
		- OP 4.B.1: validar rejeição do e-mail ou senha
   		- OP 4.B.2:	interpretar mensagens de erro e realizar a correção
		- OP 4.B.3: corrigir campos e clicar novamente no botão de logar
  		- OP 4.B.4: aguardar e verificar se a página de login foi carregada	

**3\) CTT**

![CTT Cadastro](https://github.com/user-attachments/assets/957d9a26-90eb-488d-8def-4ddbcc329f30)

# Login de Usuários na plataforma

**1\) HTA**

![HTA Login](https://github.com/user-attachments/assets/e3b451f9-cdad-44d4-88db-31d0e7875e38)


| Objetivos/Operações                                          | Problemas e Recomendações                                                                                                                                                                                                                                                                                                                                                                                                         |
| ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **0. Logar no aplicativo (1/2/3)**                           | **Input:** tela com três opções de login (Google, Facebook, credenciais próprias).<br>**Plano:** escolher um método de autenticação e concluir o login. <br>**Problema:** escolha confusa entre métodos; retorno de erro pouco claro. <br>**Recomendações:** destacar o método recomendado; mensagens de erro específicas; indicador de progresso/carregamento; link “Ajuda para entrar”.                                         |
| **1. Logar com Conta Google**                                | **Ação:** iniciar fluxo OAuth do Google. <br>**Problemas:** troca de contas, permissão negada, bloqueio de pop-up. <br>**Recomendações:** botão padrão “Continuar com Google” e explicitar os dados solicitados; lidar com pop-ups bloqueados; permitir trocar de conta; feedback de sucesso/fracasso e retorno automático à app.                                                                                                 |
| **2. Logar com Conta Facebook**                              | **Ação:** iniciar fluxo OAuth do Facebook. <br>**Problemas:** sessão expirada/conta desativada; desconfiança sobre privacidade. <br>**Recomendações:** usar rótulo oficial “Continuar com Facebook”; tela de permissões clara; link “Saiba mais sobre privacidade”; fallback para login por e-mail.                                                                                                                               |
| **3. Logar com credenciais do aplicativo ( (1/2) > 3 > 4 )** | **Plano:** inserir credenciais (manualmente/salvas), confirmar login e seguir ao questionário de suitability. <br>**Problemas:** e-mail inválido, senha incorreta, teclado móvel atrapalhando campos. <br>**Recomendações:** validação em tempo real de e-mail; mostrar/ocultar senha; lembrar do usuário apenas em dispositivo confiável; suporte a 2FA; opção “Esqueci minha senha”.                                            |
| **3.1 Inserir credenciais manualmente**                      | **Ação:** campos de e-mail e senha. <br>**Problemas:** erros de digitação, senha fraca. <br>**Recomendações:** máscaras/autoformatação do e-mail; indicador de força de senha; colar desabilitado apenas em campos sensíveis quando exigido pela política; dica de usar gerenciador de senhas.                                                                                                                                   |
| **3.1.1 Digitando credenciais**                              | **Ação:** digitar e-mail e senha. <br>**Problemas:** erro invisível (qual campo falhou). <br>**Recomendações:** validação campo-a-campo; mensagens junto ao campo; foco automático no primeiro erro; acessibilidade (labels e aria-describedby).                                                                                                                                                                                  |
| **3.1.2 Copiando credenciais**                               | **Ação:** colar dados de um gerenciador. <br>**Problemas:** espaços acidentais, caracteres invisíveis. <br>**Recomendações:** `trim()` automático; prevenir espaços no fim; dica “verifique espaços extras ao colar”.                                                                                                                                                                                                             |
| **3.2 Inserir credenciais salvas**                           | **Ação:** usar auto-preenchimento do navegador/gerenciador. <br>**Problemas:** credenciais desatualizadas; múltiplas contas salvas. <br>**Recomendações:** sugerir contas detectadas; permitir trocar rapidamente; mensagem clara quando a senha estiver incorreta; CTA “Atualizar senha salva”.                                                                                                                                  |
| **3.3 Selecionar a opção logar**                             | **Ação:** acionar o botão **Logar**. <br>**Problemas:** clique duplo gerando requisições repetidas; ausência de estado de carregamento. <br>**Recomendações:** desabilitar botão após clique; spinner com rótulo (“Verificando credenciais…”); tempo limite e tratamento de rede offline; atalho teclado **Enter**.                                                                                                               |
| **3.4 Preencher questionário de suitability (4)**            | **Plano:** após autenticação, direcionar ao questionário inicial (ou revisão, se já existir). <br>**Problemas:** abandono no meio; falta de clareza sobre impacto nas recomendações. <br>**Recomendações:** **progress bar** e salvamento automático; textos curtos e exemplos; resumo final com perfil estimado e como isso afeta sugestões; permitir pausar e retomar; lembrete periódico para reavaliar (ex.: a cada 90 dias). |


**2\) GOMS**

- **GOAL 0: Logar no aplicativo**

	- **GOAL 1: Selecionar método de autenticação**

		- **METHOD 1.A: Entrar com credenciais (e-mail e senha)** <br>
		(SEL.RULE: usar quando não houver/querer login federado)

			- OP.1.A.1: identificar campos de e-mail e senha  
			- OP.1.A.2: focar campo de e-mail e digitar e-mail  
			- OP.1.A.3: focar campo de senha e digitar senha  
			- OP.1.A.4: clicar no botão “Logar” (ou pressionar Enter)  
			- OP.1.A.5: aguardar validação/autenticação do sistema  

		- **METHOD 1.B: Entrar com Google (OAuth)** <br>
		(SEL.RULE: usar quando houver conta Google ativa no dispositivo)

			- OP.1.B.1: clicar em “Continuar com Google”  
			- OP.1.B.2: selecionar a conta (ou autenticar-se)  
			- OP.1.B.3: conceder permissões solicitadas  
			- OP.1.B.4: aguardar redirecionamento autenticado  

		- **METHOD 1.C: Entrar com Facebook (OAuth)** <br>
		(SEL.RULE: usar quando preferir conta Facebook conectada)

			- OP.1.C.1: clicar em “Continuar com Facebook”  
			- OP.1.C.2: selecionar a conta (ou autenticar-se)  
			- OP.1.C.3: conceder permissões solicitadas  
			- OP.1.C.4: aguardar redirecionamento autenticado  

	- **GOAL 2: Validar credenciais e tratar falhas**
		- OP.2.A.1: interpretar mensagens de erro (e-mail inválido/senha incorreta)  
		- OP.2.A.2: corrigir campo(s) indicado(s)  
		- OP.2.A.3: clicar novamente em “Logar” e aguardar validação <br>

	- **GOAL 3: Direcionar ao questionário de suitability (condicional)**
		- OP.3.A.1: reconhecer aviso “Complete/Revise seu perfil”  
		- OP.3.A.2: clicar em “Iniciar questionário”  
		- OP.3.A.3: responder perguntas e confirmar envio  
		- OP.3.A.4: aguardar confirmação do perfil e retorno à aplicação <br>

	- **GOAL 4: Acessar a carteira (página inicial pós-login)**
		- OP.4.A.1: reconhecer mensagem de feedback (“Login realizado com sucesso”)  
		- OP.4.A.2: verificar exibição da carteira e do chip de perfil  
		- OP.4.A.3: prosseguir para ações de simulação/operacional  



- **GOAL 0: Realizar Simulação de investimentos**

	- **GOAL 1: Definir/ajustar budget (R$)**

		- **METHOD 1.A: Digitar orçamento manualmente** <br>
		(SEL.RULE: usar quando o usuário souber o valor a simular)

			- OP.1.A.1: localizar campo “Budget (R$)”  
			- OP.1.A.2: focar campo e digitar o valor em R$  
			- OP.1.A.3: confirmar entrada (Enter ou clicar fora)  
			- OP.1.A.4: verificar barra/resumo de orçamento atualizado  

		- **METHOD 1.B: Ajustar orçamento por controles de incremento** <br>
		(SEL.RULE: usar quando preferir aumentar/diminuir gradualmente)

			- OP.1.B.1: clicar em “+” ou “−” para ajustar o valor  
			- OP.1.B.2: observar orçamento restante/consumido  
			- OP.1.B.3: confirmar valor final do budget  <br>

	- **GOAL 2: Selecionar Ações (CRUD) para compor a carteira**

		- **METHOD 2.A: Adicionar ação à carteira** <br>
		(SEL.RULE: usar quando incluir novo ativo)

			- OP.2.A.1: focar busca/autocomplete de ativo  
			- OP.2.A.2: digitar ticker ou nome e selecionar na lista  
			- OP.2.A.3: informar valor a alocar (R$) ou percentual (%)  
			- OP.2.A.4: clicar em “Adicionar”  
			- OP.2.A.5: verificar atualização de orçamento e distribuição  

		- **METHOD 2.B: Remover ação da carteira** <br>
		(SEL.RULE: usar quando ativo não deve permanecer)

			- OP.2.B.1: localizar ativo na lista da carteira  
			- OP.2.B.2: clicar em “Remover”  
			- OP.2.B.3: confirmar remoção (se solicitado) e observar “Undo” (toast)  

		- **METHOD 2.C: Editar ação da carteira** <br>
		(SEL.RULE: usar quando desejar alterar valor ou trocar ativo)

			- OP.2.C.1: focar campo de valor (R$ ou %) do ativo  
			- OP.2.C.2: digitar novo valor e confirmar  
			- OP.2.C.3: *(opcional)* trocar ticker mantendo alocação  
			- OP.2.C.4: verificar recálculo de orçamento e alertas (excesso/concentração)  <br>

	- **GOAL 3: Validar orçamento e consistência da carteira**
		- OP.3.A.1: checar se valor investido ≤ orçamento  
		- OP.3.A.2: identificar alertas (ex.: concentração > limite, ativo incompatível com perfil)  
		- OP.3.A.3: decidir reduzir/redistribuir (METHOD 2.C) ou remover (METHOD 2.B)  
		- OP.3.A.4: confirmar ajustes até eliminar alertas  <br>

	- **GOAL 4: Finalizar simulação e registrar resultado**

		- **METHOD 4.A: Salvar/exportar simulação** <br>
		(SEL.RULE: usar para reutilizar ou compartilhar)

			- OP.4.A.1: clicar em “Salvar” ou “Exportar”  
			- OP.4.A.2: escolher formato (CSV/PNG/JSON)  
			- OP.4.A.3: confirmar e verificar mensagem de sucesso  

		- **METHOD 4.B: Resetar e recomeçar a simulação** <br>
		(SEL.RULE: usar quando desejar iniciar do zero)

			- OP.4.B.1: clicar em “Resetar simulação”  
			- OP.4.B.2: confirmar ação  
			- OP.4.B.3: verificar limpeza da carteira e do orçamento  <br>

	- **GOAL 5: Revisar/atualizar suitability (condicional)**
		- OP.5.A.1: ao detectar incompatibilidade de risco, abrir “Revisar perfil”  
		- OP.5.A.2: responder questionário curto de reavaliação  
		- OP.5.A.3: salvar novo perfil e retornar à simulação com recomendações ajustadas <br>

**3\) CTT**

![CTT Login](https://github.com/user-attachments/assets/eac9947c-90de-45f5-a6c3-d20206a1d928)


# Simulação de investimentos na plataforma

**1\) HTA**

![HTA Simulacao](https://github.com/user-attachments/assets/8f423daa-3fc4-4c53-9e30-8864623128a2)


| Objetivos/Operações                                   | Problemas e Recomendações                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ----------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Realizar Simulação de investimentos (1 > 2)**    | **Input:** tela de simulação com orçamento (R$) e carteira simulada. <br>**Plano:** definir **budget** e **selecionar/ajustar ações** (CRUD) até fechar a carteira. <br>**Problemas:** usuário não percebe limite do orçamento; falta de feedback sobre risco/diversificação. <br>**Recomendações:** barra de progresso do orçamento (usado/restante), **resumo em tempo real** (nº de ativos, alocação %, risco estimado), botão **“Resetar simulação”** e **desfazer/refazer**. |
| **2. Selecionar budget (R$) (1/2)**                   | **Ação:** informar quanto será usado na simulação. <br>**Problemas:** valores fora do padrão (vírgula/ponto), orçamento negativo ou muito baixo. <br>**Recomendações:** máscara monetária (`R$ 0.000,00`), limites mínimo/máximo, tooltip com **exemplos**, validação imediata e **teclas de incremento** (+/−).                                                                                                                                                                  |
| **2.1 Adicionar budget**                              | **Plano:** inserir um novo valor de orçamento. <br>**Problemas:** usuário não sabe impacto do aumento/diminuição. <br>**Recomendações:** **impacto previsto** (ex.: “+R$ 500 permite +2 compras médias”), confirmação suave e **salvamento automático**.                                                                                                                                                                                                                          |
| **2.2 Editar budget atual**                           | **Ação:** alterar orçamento já definido. <br>**Problemas:** carteira pode exceder o novo orçamento. <br>**Recomendações:** aviso “orçamento excedido em R$ X”, CTA “**Rebalancear automaticamente**” (proporcional) ou “**Ajustar manualmente**”.                                                                                                                                                                                                                                 |
| **3. Selecionar Ações (CRUD) (1/2/3)**                | **Plano:** adicionar, remover e editar ativos até fechar a alocação. <br>**Problemas:** digitação de ticker incorreto, liquidez mínima/lote, taxas ignoradas. <br>**Recomendações:** **autocomplete de ticker/nome**, checagem de existência, alerta de lote mínimo (se aplicável), campo de **taxas opcionais**, e **badge** de volatilidade/risco.                                                                                                                              |
| **3.1 Adicionar ação à carteira (1 > 2)**             | **Ação:** nome/ticker + valor a investir (R$). <br>**Problemas:** ultrapassar orçamento; concentração excessiva em um único ativo. <br>**Recomendações:** **bloqueio/alerta** ao exceder orçamento; **alerta de concentração** (>X%) com sugestão de diversificação; opção “**alocar por %**” além de R$.                                                                                                                                                                        |
| **3.1.1 Adicionar nome da ação**                      | **Ação:** selecionar via busca/autocomplete. <br>**Problemas:** homônimos (units, ON/PN), confusão com BDR/ETF. <br>**Recomendações:** ficha curta no dropdown (ticker, tipo, setor), **ícone** de classe (Ação/ETF/BDR) e link “detalhes”.                                                                                                                                                                                                                                       |
| **3.1.2 Adicionar quantidade investida na ação (R$)** | **Ação:** informar valor em R$ (ou %) para o ativo. <br>**Problemas:** arredondamentos, valor zero/negativo. <br>**Recomendações:** alternar **R$ ↔ %**, validação de mínimo, **sugestões rápidas** (5%, 10%, 15%) e **mensagem** “restam R$ X”.                                                                                                                                                                                                                                  |
| **3.2 Remover ação da carteira**                      | **Ação:** excluir um ativo da simulação. <br>**Problemas:** remoção acidental. <br>**Recomendações:** **Undo** 5–10s (toast “Ativo removido — Desfazer”), atualização imediata do orçamento e da distribuição.                                                                                                                                                                                                                                                                    |
| **3.3 Editar ação da carteira (1/2)**                 | **Plano:** alterar nome/ticker ou valor investido. <br>**Problemas:** perder histórico do que mudou; inconsistência com orçamento após edição. <br>**Recomendações:** **modo edição inline** com preview do impacto, **controle de versão leve** (ícone “alterado”), recálculo do orçamento e **validação ao sair do campo**.                                                                                                                                                     |
| **3.3.1 Editar quantidade investida (R$)**            | **Ação:** ajustar o valor alocado naquele ativo. <br>**Problemas:** ultrapassar orçamento ou ficar com centavos residuais. <br>**Recomendações:** **snap** para valores válidos, aviso de excesso, botão “**Rebalancear**” proporcional.                                                                                                                                                                                                                                          |
| **3.3.2 Editar nome da ação (R$)**                    | **Ação:** trocar o ativo mantendo (opcionalmente) a mesma alocação. <br>**Problemas:** trocar para ativo incompatível com perfil/suitability. <br>**Recomendações:** **cheque de compatibilidade** com perfil (badge “Compatível/Alto risco”), confirmação antes de substituir e sugestão de **ativos equivalentes** (mesmo setor/volatilidade menor).                                                                                                                            |
**2\) GOMS**

- **GOAL 0: Realizar Simulação de investimentos na plataforma**

	- **GOAL 1: Definir/ajustar budget (R$)**

		- **METHOD 1.A: Digitar orçamento manualmente** <br>
		(SEL.RULE: usar quando o usuário souber exatamente o valor a simular)
			- OP.1.A.1: localizar o campo “Budget (R$)”
			- OP.1.A.2: focar o campo e digitar o valor em R$
			- OP.1.A.3: confirmar entrada (Enter ou clicar fora)
			- OP.1.A.4: verificar barra/resumo do orçamento atualizado

		- **METHOD 1.B: Ajustar orçamento por controles de incremento** <br>
		(SEL.RULE: usar quando preferir ajustar gradualmente)
			- OP.1.B.1: clicar nos botões “+” ou “−” para ajustar o valor
			- OP.1.B.2: observar orçamento restante/consumido em tempo real
			- OP.1.B.3: confirmar o valor final do budget

	- **GOAL 2: Selecionar Ações (CRUD) para compor a carteira**

		- **METHOD 2.A: Adicionar ação à carteira** <br>
		(SEL.RULE: usar para incluir novo ativo)
			- OP.2.A.1: focar o campo de busca/autocomplete de ativos
			- OP.2.A.2: digitar ticker ou nome e selecionar na lista sugerida
			- OP.2.A.3: informar o valor a alocar (R$) ou percentual (%)
			- OP.2.A.4: clicar em “Adicionar”
			- OP.2.A.5: verificar atualização do orçamento e da distribuição

		- **METHOD 2.B: Remover ação da carteira** <br>
		(SEL.RULE: usar quando um ativo não deve permanecer)
			- OP.2.B.1: localizar o ativo na lista da carteira
			- OP.2.B.2: clicar em “Remover”
			- OP.2.B.3: confirmar remoção (se solicitado) e observar opção de “Desfazer” (toast)

		- **METHOD 2.C: Editar ação da carteira** <br>
		(SEL.RULE: usar quando precisar alterar valor ou trocar ativo)
			- OP.2.C.1: focar o campo de valor (R$ ou %) do ativo
			- OP.2.C.2: digitar o novo valor e confirmar
			- OP.2.C.3: *(opcional)* trocar o ticker mantendo a alocação
			- OP.2.C.4: verificar recálculo de orçamento e alertas (excesso/concentração)

	- **GOAL 3: Validar orçamento e consistência da carteira**

		- OP.3.A.1: checar se o valor investido ≤ orçamento
		- OP.3.A.2: identificar alertas (ex.: concentração > limite, ativo incompatível com perfil/suitability)
		- OP.3.A.3: decidir reduzir/redistribuir (**METHOD 2.C**) ou remover (**METHOD 2.B**)
		- OP.3.A.4: confirmar ajustes até eliminar alertas

		- **GOAL 3.A: Resolver orçamento excedido**  
			- OP.3.A.1: revisar alocações que causaram excesso
			- OP.3.A.2: diminuir valores (**METHOD 2.C**) ou excluir ativos (**METHOD 2.B**)
			- OP.3.A.3: confirmar que o orçamento voltou ao limite

		- **GOAL 3.B: Resolver concentração/risco incompatível**  
			- OP.3.B.1: identificar ativos acima do limite de concentração
			- OP.3.B.2: reduzir percentual do(s) ativo(s) ou diversificar adicionando novos (**METHOD 2.A/2.C**)
			- OP.3.B.3: confirmar que a carteira atende aos limites de risco e perfil

	- **GOAL 4: Finalizar simulação e registrar resultado**

		- **METHOD 4.A: Salvar/exportar simulação** <br>
		(SEL.RULE: usar para reutilizar, comparar cenários ou compartilhar)
			- OP.4.A.1: clicar em “Salvar” ou “Exportar”
			- OP.4.A.2: escolher o formato (CSV/PNG/JSON)
			- OP.4.A.3: confirmar e verificar mensagem de sucesso

		- **METHOD 4.B: Resetar e recomeçar a simulação** <br>
		(SEL.RULE: usar quando desejar iniciar do zero)
			- OP.4.B.1: clicar em “Resetar simulação”
			- OP.4.B.2: confirmar a ação
			- OP.4.B.3: verificar limpeza da carteira e do orçamento

	- **GOAL 5: Revisar/atualizar suitability (condicional)**

		- OP.5.A.1: ao detectar incompatibilidade de risco, abrir “Revisar perfil”
		- OP.5.A.2: responder questionário curto de reavaliação
		- OP.5.A.3: salvar o novo perfil e retornar à simulação com recomendações ajustadas
**3\) CTT**

![CTT Simulacao](https://github.com/user-attachments/assets/91ee7a15-717b-4bbe-99ea-1a62e438b098)


# **Entrega 6  (data) \[em andamento/concluído\]**

## Primeira Parte da Prototipação em Papel
Essa primeira parte apresenta as primeiras 4 telas que podem ser vistas no site antes do usuário efetuar o seu login, sendo elas, pela ordem da numeração: Página de Login, Página de Cadastro, Página de Políticas da Empresa e Página de Política de Privacidade.

![Prototipação em Papel 1](https://github.com/user-attachments/assets/2cf97ab5-3a46-4861-a937-94648d956f11)



## Segunda Parte da Prototipação em Papel
Essa segunda parte mostra as 4 últimas telas que podem ser vistas após o usuário efetuar o seu login dentro do site, sendo elas, pela ordem da numeração: Página de Perfil de Investidor, Página de Simulação de Investimentos, Página de Gráficos das Ações, Página do Questionário de Suitability.

![Prototipação em Papel 2](https://github.com/user-attachments/assets/9cfbad7b-2f8e-4103-ba37-e05086ec8679)


## Fluxograma da Prototipação em Papel
As setas do fluxograma mostram para onde cada página pode levar a depender da escolha do usuário. Uma legenda de cada página é mostrada à esquerda da imagem. É bom ressaltar que após realizar o cadastro, o usuário já é redirecioando para a Página do Questionário de Suitability, não sendo necessário realizar o login.

![Prototipação em Papel Fluxograma](https://github.com/user-attachments/assets/54486147-4477-430f-bae1-42ed0d812d6a)


## Simulação de Teste de Usuário
Durante o teste com a prototipação em papel, um usuário qualquer conseguiu entender a proposta geral do site, mas relatou problemas na parte de cadastro, ficando confuso o acesso e o retorno nas telas de “Políticas da Empresa” e “Política de Privacidade” a partir do cadastro: os links não estavam evidentes, não ficou claro se eram obrigatórios antes de prosseguir e também não identificando para onde o botão de “voltar” levava. A sensação foi de “perder-se” nessas páginas auxiliares.

Outro ponto levantado foi o botão de Menu presente nas telas de Gráficos, Simulação de Investimentos e Perfil do Investidor. Como as opções só aparecem após clicar, o controle passou despercebido em um primeiro momento, reduzindo a descoberta das funcionalidades. A pessoa sugeriu deixar as opções de navegação sempre visíveis (por exemplo, uma barra lateral fixa ou abas), ou ao menos tornar o botão mais destacado e autoexplicativo, para facilitar a orientação no site.


# **Entrega 7  (data) \[concluído\]**

**\[PARTE A: 1 solução completa por pessoa da equipe\]**

**1\)	Identificação de Necessidades dos Usuários e Requisitos de IHC: exercício de perguntas**

* **Que dados coletar?**

  Para embasar a definição de requisitos de IHC em uma plataforma de recomendação de ações, é essencial levantar informações do usuário (a respeito do perfil demográfico, conhecimento digital e financeiro e limitações de acessibilidade) , sua relação com a tecnologia
(habilidade com computadores, apps financeiros já utilizados, dificuldades recorrentes de navegação, contexto e frequência de uso), seu conhecimento e domínio em investimentos (objetivos, tolerância a riscos, explicações sobre o assunto) e por fim suas tarefas e metas dentro do sistema (receber recomendações de ações com seu perfil, simular carteira de investimento, ter um perfil de investimento traçado).


* **De quem coletar?**

  A coleta dessas informações serão destinadas aos usuários finais do nosso sistema, abrangendo perfis com diferentes níveis de familiaridade digital, financeira e contextos de usos. Utilizando como bases usuários iniciantes e experientes no meio financeiro com diferentes faixas etárias, rotinas e objetivos em nossa plataforma.
	

**2\)	Aspectos Éticos**

* **Seu projeto deverá considerar aspectos éticos? Justifique usando os conceitos da aula.**

	Sim, o projeto deve necessariamente considerar aspectos éticos, pois envolve pessoas e o tratamento de dados pessoais e financeiros. Os dados dos usuário ( Dados pessoais, de login e questionário de suitability) seguirá os princípios de autonomia, beneficência, não maleficência e justiça e equidade, com consentimento informado claro e possibilidade de retirada a qualquer momento.

	- Autonomia: Explicar o uso dos dados coletados e possibilidade de de recusar/desistir e pedir permissão para gravações.
 	- Beneficiência: Ponderar riscos/benefícios e maximizar benefícios (ex.: explicar limitações das recomendações, destacar que não é aconselhamento personalizado)
  	- Não Maleficiência: Minimizar danos previsíveis (ex.: evitar que uma interface induza interpretações erradas de risco/retorno de alguma ação).
  	- Justiça e equidade: assegurar relevância social e evitar ônus indevido a grupos vulneráveis (ex.: linguagem acessível, acessibilidade digital).
	

**\[PARTE B: 1 solução completa por pessoa da equipe \- e com técnicas diferente; questionário deve ser uma das técnicas escolhidas\]**

**3\)	Ferramentas de Coleta de Dados (João) **  

# Classificação de Cartões

**3.1) nome do instrumento e objetivo de aplicação**

**Instrumento:** Classificação de Cartões

**Objetivo:** Permite identificar como os usuários nomeiam conteúdos da plataforma (suitability, recomendações, simulações, acompanhamento), como os descrevem e quais informações pertencem a quais categorias



**3.2) explicar como aplicar (serve para normalizar o processo de aplicação quando pessoas distintas aplicam o instrumento)** 

- Selecione e convite os participantes
- Prepare em torno de 30 - 40 cartões, explique a tarefa que o usuário deverá realizar e peça para agrupar e nomear cada cartão, não guiando a decisão apenas obeservando e registrando as tomadas de decisão do usuário.
- Durante o processo, os participantes formarão clusters (agrupamentos) de cartões que consideram relacionados, refletindo como percebem a organização natural das informações.
- Registro: Capture os agrupamentos finais, nomes dos grupos, cartões e comentários do participante.
- Análise dos dados: Identifique padrões e semelhanças entre os clusters criados pelos diferentes usuários.
- Resultado: um esqueleto de navegação e rótulos coerentes com o modelo mental dos usuários, reduzindo esforço cognitivo e erros de navegação.

**3.3) instrumento (por exemplo, link do questionário no Google Forms, roteiro de entrevista, roteiro do Grupo Focal, etc)**

- Preparação dos cartões: listar 30–40 tópicos centrais da plataforma (Ex: Questionário Suitability, Login, Cadastro, Simulação, Recomendação)

- Execução das sessões: agendar encontros individuais (presenciais ou remotos), usar um quadro digital compartilhado (ou mesa com cartões físicos) aplicar o roteiro acima sem variações entre aplicadores.

- Coleta e organização: ao final de cada sessão, capturar a configuração dos grupos e os rótulos criados do perfil resumido do participante e observações.

<!--
# Grupo Focal

**3.1) nome do instrumento e objetivo de aplicação**

**Instrumento:** Grupo Focal

**Objetivo:** Permite obter, em pouco tempo, múltiplos pontos de vista de um determninado grupo de pessoas sobre a plataforma

**3.2) explicar como aplicar (serve para normalizar o processo de aplicação quando pessoas distintas aplicam o instrumento)** 

- Grupos de 3 - 10 pessoas
- Duração: 1-2 horas
- 1 moderador para conduzir a reunião
- O moderador explica os objetivos da reunião e após isso faz algumas perguntas para os integrantes dessa renunião e se permitido documenta todas as informações importantes que obteve

**3.3) instrumento (por exemplo, link do questionário no Google Forms, roteiro de entrevista, roteiro do Grupo Focal, etc)**

- Preparação: Defina um roteiro único com os temas a serem debatidos e, se necessário, inclua imagens para ilustrar.
  
- Execução: recrutar, agendar sessões de 1-2 horas, aplicar exatamente o mesmo roteiro e documente todas as informações importantes que obteve

- Pós-sessão: transcrever pontos-chave, extrair citações que exemplifiquem necessidades e confusões, sintetizar temas, priorizar com a equipe e refletir no próximo protótipo e no plano de teste de usabilidade.
-->
# Brainstorming de Necessidades e Desejos dos Usuários

**3.1) nome do instrumento e objetivo de aplicação**

**Instrumento:** Brainstorming de Necessidades e Desejos dos Usuários

**Objetivo:** Busca levantar de forma bastante livre um conjunto grande e abrangente de opiniões dos participantes em relação à plataforma

**3.2) explicar como aplicar (serve para normalizar o processo de aplicação quando pessoas distintas aplicam o instrumento)** 

- Participantes: Cada sessão geralmente envolve de 8 a 12 usuários orientados por um moderador
- O moderador introduz o tema do brainstorming, orienta uma parte individual e depois uma coletiva. Os participantes não devem censurar uns aos outros
- O moderador documenta as ideias debatidas

**3.3) instrumento (por exemplo, link do questionário no Google Forms, roteiro de entrevista, roteiro do Grupo Focal, etc)**

- Preparação: definir 2–3 perguntas-gatilho (p.ex.: “O que você precisa ver para confiar na recomendação?”, “Que explicações eliminariam suas dúvidas?”).

- Execução: aplicar exatamente as mesmas regras e perguntas para todos os grupos; moderador registra todas as ideias, sem filtrar ao final, agrupar e votar.

- Pós-sessão: documentar melhores ideias debatidas


# Questionário

**3.1) nome do instrumento e objetivo de aplicação**

**Instrumento:** Questionário

**Objetivo:** Coletar rapidamente dados padronizados de muitos usuários sobre perfil, hábitos e necessidades, gerando insumos objetivos para a plataforma.

**3.2) explicar como aplicar (serve para normalizar o processo de aplicação quando pessoas distintas aplicam o instrumento)** 

Participantes: Entre 30 a 50 usuários sendo iniciantes ou avançados em relação ao tema
- O moderador cria as perguntas e as alternativas de acordo com o que for de seu interesse saber
- Os usuários irão responder as perguntas via link do google forms
- O moderador coleta as respostas para realizar uma análise posteriormente

**3.3) instrumento (por exemplo, link do questionário no Google Forms, roteiro de entrevista, roteiro do Grupo Focal, etc)**

- Preparação: Criar o Google Forms com seções padrão (Perfil → Dispositivo de acesso → Uso de apps financeiros → Experiência em investimentos → Metas & horizonte). Incluir termo de consentimento no início, estimar 3–5 min, marcar perguntas-chave como obrigatórias, ativar “1 resposta por pessoa” quando possível e fazer um piloto com 5–10 usuários. (Link do formulário: https://forms.gle/utgqWhXwafFhRpPF7).

- Execução: Divulgar o link com instruções iguais para todos, mantendo autoaplicado (sem orientar respostas), priorizando questões de múltipla escolha e deixando o forms aberto por 7-10 dias.

- Pós-coleta: Exportar as respostas para Excel, fazer gráficos de cada pergunta, criar cruzamentos (ex.: perfil × horizonte de investimento), anotar as decisões de design e incluir os gráficos no relatório.



# **Entrega 8  (data) \[concluído\]**

**\[1 solução por equipe\]**

**CICLO DE VIDA DE ENGENHARIA DE USABILIDADE**

**![][image1]**

1. **Características da Plataforma**  
   

| Característica | Descrição |
| :---- | :---- |
| Descrição do Software | Para o desenvolvimento da plataforma, utilizamos React e o CockroachDB para o armazenamento dos dados pessoais, de login e de suitability (perfil encontrado) dos investidores. Para a previsão das ações, aplicamos uma rede neural LSTM (Long Short-Term Memory), que auxilia na recomendação personalizada da carteira de investimentos em um horizonte de tempo de 1, 6 e 24 meses. |
| Descrição do Hardware | A plataforma é acessada através de um navegador web, podendo ser executada em computadores com acesso à internet.|
| LISTA DE Capacidades da Plataforma (com explicação) | - Cadastro e autenticação dos usuários na plataforma: Permite que usuários criem uma conta e tenham acesso a plataforma apartir de seu login. <br> - Coleta de perfil de investimento: Apartir de um questionário de suitability disponibilizado na plataforma é possível identificar o perfil de investimento do usuário. <br> - Previsão de ações com LSTM: Utilizando uma rede neural (LSTM) conseguimos prever a tendência das ações com base em dados históricos do mercado em um período de 1, 6 e 24 meses. <br> - Carteira de investimento personalizada: Carteira de ações adaptada ao perfil de investimento do usuário, auxiliando em sua tomada de decisão. <br> - Interface Web responsiva: Interface web com acesso via navegador com boa usabilidade e desempenho.|
| LISTA DE Restrições da Plataforma (com explicação) | - Dependência de conexão com a internet: Por ser uma interface web, é necessário estar conectado à internet para seu funcionamento, podendo ocorrer baixa performance em casos de instabilidade ou má qualidade da conexão. <br> - Ausência de operações financeiras reais: A plataforma apenas recomenda carteiras de investimento ao investidor, ela não executa compras, vendas ou movimentações financeiras. <br> - Disponibilidade restrita aos navegadores: O sistema é acessível apenas em navegadores web, não havendo um aplicativo próprio para seu uso. <br> - Capacidade de armazenamento de informações do banco de dados limitada: Depende do número de usuários que utilizarem o nosso sistema, sendo possível a aquisição de um plano para uma maior capacidade de armazenamento do CockroachDB no futuro.|

   

2. **Princípios Gerais do Projeto (INCREMENTAR TABELA)**  
   

| Nome | Descrição | Link |
| :---- | :---- | :---- |
| Descrição do Contexto | .  |  |
| Lei Geral de Proteção de Dados (LGPD) \- Lei n.º 13.709/2018 | A LGPD é a legislação brasileira que regulamenta o tratamento de dados pessoais no Brasil. É importante para o projeto porque estabelece regras sobre como os dados dos usuários devem ser coletados, armazenados, processados e protegidos, garantindo sua privacidade e segurança. | [https://www.planalto.gov.br/ccivil\_03/\_ato2015-2018/2018/lei/l13709.htm](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm) |
| ABNT NBR ISO 9241 Ergonomia da interação humano-sistema |  Esta série de normas brasileiras, baseadas nas normas ISO 9241, fornece diretrizes e orientações para o design centrado no usuário de sistemas interativos, incluindo a concepção de interfaces de usuário. A parte 210 aborda o processo de design centrado no humano, enquanto a parte 11 fornece orientações específicas sobre usabilidade. Essas normas são importantes para o projeto porque estabelecem princípios e métodos para garantir que a interface do usuário atenda às necessidades e expectativas dos usuários. | [https://www.inf.ufsc.br/\~edla.ramos/ine5624/\_Walter/Normas/Parte%2011/iso9241-11F2.pdf](https://www.inf.ufsc.br/~edla.ramos/ine5624/_Walter/Normas/Parte%2011/iso9241-11F2.pdf) |
| Diretriz ANBIMA de Suitability | A Diretriz ANBIMA de Suitability estabelece as regras e parâmetros que as Instituições Participantes (Associadas ou Aderentes ao Código ANBIMA) devem seguir para verificar a adequação dos Produtos de Investimento, serviços e operações ao perfil do investidor. <br> O principal alvo da diretriz é garantir que as recomendações de investimento sejam compatíveis com o cliente. Para isso, são exigidas duas classificações principais: <br> - Perfil Conservador: Investidor com baixa tolerância a risco, que prioriza produtos com liquidez. <br> - Perfil Moderado:  Investidor com média tolerância a risco, que busca a preservação de capital no longo prazo e pode destinar uma parte a investimentos de maior risco. <br> - Perfil Agressivo: Investidor com tolerância a risco, que aceita potenciais perdas em busca de maiores retornos. <br> As instituições deve considerar no mínimo os riscos de crédito, liquidez e mercado, para atribuir uma pontuação de risco única a cada Produto de Investimento.| [https://github.com/jvgoverna/Interface-Humano-Computador/blob/main/Links/Diretriz-de-Suitability-20180622.pdf](https://cdn.discordapp.com/attachments/1372327706980651028/1433274485754167347/Diretriz-de-Suitability-20180622.pdf?ex=69041862&is=6902c6e2&hm=de00fdd38e367ce5240e7f61641f5c94a35396609c5eecb3dff1cc6b2b4ead9d&) |
| BRA-POL-029 Política de Suitability | PDF referente às perguntas utilizadas na formulação do questionário de suitability, assim como os pontos considerados. | [https://github.com/jvgoverna/Interface-Humano-Computador/blob/main/Links/BRA-POL-029-Pol%C3%ADtica-de-Suitability.pdf](https://cdn.discordapp.com/attachments/1372327706980651028/1433275278141952041/BRA-POL-029-Politica-de-Suitability.pdf?ex=6904191f&is=6902c79f&hm=1f2384890f32604b37d68c235f071574139d5b94913a6aa01a2ad14e24f98ca0&)  |
<!--| Lei n.º 10.098/2000 \- Lei da Acessibilidade |  Esta lei brasileira estabelece normas gerais e critérios básicos para a promoção da acessibilidade das pessoas com deficiência ou com mobilidade reduzida. É importante para o projeto porque define diretrizes para tornar produtos e serviços, incluindo interfaces de usuário, acessíveis a todos os usuários, independentemente de suas habilidades físicas ou cognitivas. | [https://www.planalto.gov.br/ccivil\_03/leis/l10098.htm](https://www.planalto.gov.br/ccivil_03/leis/l10098.htm) | -->


   

3. **Metas de Usabilidade**

   1. **Qualitativo**

    | Meta | Justificativa |
	| ----- | :---- |
	| Garantir que elementos clicáveis tenham feedback visual imediato| O feedback visual imediato nos elementos clicáveis evita dúvidas sobre o reconhecimento da ação. Isso reduz erros e aumenta a sensação de controle durante o uso. |
	| Evitar o uso de linguagem técnica nas simulações e recomendações de investimento | Facilitar o entendimento para investidores com pouca experiência, sem deixar de atender quem já tem mais conhecimento, usando uma comunicação simples e clara para que todos saibam exatamente o que foi recomendado e o que fazer. |
	| Priorizar uma navegação simples e de fácil entendimento  | O usuário deve compreender claramente as ações necessárias no sistema, evitando interpretações equivocadas e tornando a experiência mais fluida. |
	| Durante a simulação, permitir que o usuário altere ou remova ações selecionadas | Durante a simulação, permitir que o usuário altere ou remova ações selecionadas e o orçamento disponível para o investimento. |
	| Permitir que o usuário refaça o questionário a qualquer momento | O usuário pode refazer o questionário de suitability sempre que desejar ajustar seu perfil de investimento. |
	| Assegurar que os dados do usuário e o site estejam sempre disponíveis.  | Garante que o usuário possa acessar a plataforma a qualquer momento, com segurança de que suas informações e dados estão protegidos.  |


   2. **Quantitativo**

	| Metas | Porcentagem | Justificativa |
	| ----- | :---- | :---- |
	| Facilidade de aprendizado (Learnability) | 20% | Tempo médio necessário para realizar o cadastro e responder as perguntas para compreender o seu perfil de investimento.|
	| Eficiência no uso (Efficiency) | 20% | Tempo médio para completar tarefas após entender o funcionamento da plataforma (número de cliques ou passos necessários). |
	| Facilidade de retomar o uso (Memorability)  | 20% | Taxa de sucesso em realizar simulações de investimento após determinado intervalo de tempo (ex.: 1 semana sem uso). |
	| Baixa taxa de erros (Errors) | 15% | Número de erros críticos cometidos por usuário; frequência de erros recuperáveis vs irreversíveis. |
	| Satisfação do usuário (Satisfaction) | 25% | Avaliação média de satisfação em escala (ex.: 1 a 5); número de feedbacks positivos vs negativos. |
	| **Total** | **100%** |  |
      
      
<!--
| Metas | Porcentagem | Justificativa |
| ----- | :---- | :---- |
| Facilidade de … |  |  |
|  |  |  |
|  |  |  |
|  | 1% |  |
|  | 20% |  |
| **Total** | **100%** |  |
-->



# **Entrega 9 (data) \[em andamento/concluído\]**

**\[1 solução completa por pessoa da equipe\]**

# ---- João ----

1) **Cenários de Interação (destacar em cor diferente o texto alterado entre Cenário Problema e Cenário de Interação)**

## Cenário de Análise/Problema - João Vitor
**Clareza e Simplicidade: A Necessidade de Usabilidade para Investidores Iniciantes**
Atores: João Vitor (investidor iniciante)

João Vitor, é um senhor de 65 anos de idade professor da rede pública do estado de São Paulo, ele passou muitos anos guardando dinheiro em sua poupança, após ouvir rumores a respeito do mercado de investimento sobre maior rentabilidade de seu patrimônio em comparação com a poupança. Então decide retirar seu investimento aplicado e comprar ações.

Após um longo dia de trabalho, João está em sua casa à frente de seu computador pessoal com o objetivo de explorar, entender e encontrar investimentos além da poupança. Seu plano mental é que ao navegar pelas ações recomendadas para seu perfil a plataforma apresente informações claras e com uma linguagem condizente ao seu perfil. Então João cria uma conta em uma plataforma de recomendação de ações e preenche o questionário de suitability, onde o classifica como perfil conservador.

Após a classificação é recomendado diversas ações para investir, porém essas recomendações apresentam uma linguagem de difícil entendimento, com gráficos e dashboards com letras pequenas, linguagem técnica e cores de fácil confusão, não entendendo o significado de termos como volatilidade e não encontrando explicação simples no site.

João avalia a plataforma de forma negativa, concluindo que o site é útil para pessoas que apresentam um conhecimento prévio sobre investimento financeiro, não sendo o caso dele e se sentindo frustado e inseguro se realmente vale a pena retirar seu investimento na poupança, por sua incapacidade de interpretar as informações e gráficos oferecidos a ele. Sua ação final foi de fechar a plataforma, abandonar o uso e continuar pesquisando sobre esse universo com amigos.


## Questões de refinamento (João Vitor):

| Indice | Elemento |Pergunta | Resposta |
| -- | -- | -- | -- |
| 	[1]   |   objetivo       | De que informações ou conhecimento João precisa para explorar, entender e encontrar investimentos além da poupança?  |  |
| 	[2]   |   ambiente       | Em que situação João decide decide aplicar seu investimento em ações (quando, onde e por quê)?                       |  |
| 	[3]   |   ator(es)		 | Quais características de João auxiliou a atrapalhar o alcance do objetivo?                                           |  |
| 	[4]   |   planejamento	 | Em que ordem João precisam realizar as ações? Poderia realizá-la de outra maneira?                            	    |  |
| 	[5]   |   ação       	 | Quais erros podem ser cometidos ao utilizar a plataforma? Como podem ser desfeitos? Quais são suas consequências?    |  |
| 	[6]   |   evento		 | Quais eventos disparam a necessidade de João alcançar o objetivo?    											    |  |
| 	[7]   |   avaliação		 | Qual é o resultado do alcance do objetivo?     																	    |  |

---
 
## Cenário de Interação – João Vitor
**Clareza e Simplicidade: A Necessidade de Usabilidade para Investidores Iniciantes** <br>
Atores: João Vitor (investidor iniciante)

João Vitor, é um senhor de 65 anos de idade professor da rede pública do estado de São Paulo, ele passou muitos anos guardando dinheiro em sua poupança, após ouvir rumores a respeito do mercado de investimento sobre maior rentabilidade de seu patrimônio em comparação com a poupança [6]. Então decide retirar seu investimento aplicado e comprar ações. [2]

Após um longo dia de trabalho, João está em sua casa à frente de seu computador pessoal [2] com o objetivo de explorar, entender e encontrar investimentos além da poupança [1]. Seu plano mental é que ao navegar pelas ações recomendadas para seu perfil a plataforma apresente informações claras e com uma linguagem condizente ao seu perfil [3]. **Então João acessa a plataforma de recomendação de ações Invest Mind** e preenche o questionário de suitability, onde o classifica como perfil conservador. **O sistema exibe um alerta informando que seu perfil de investidor foi classificado como conservador, valorizando a segurança e estabilidade em seus investimentos. Significando que o usuário prioriza retornos previsíveis e menor exposição a riscos [6].**

Após a classificação **do perfil, o sistema apresenta uma nova tela ao usuário [4]. Onde, é possível simular um investimento sem receber recomendações sobre quais ações investir [5]. Na parte superior direita da tela, há três botões que permitem ao usuário escolher o período de simulação: 6 meses, 1 ano ou 2 anos [5]. No meio da tela há um campo de input onde o usuário informa o orçamento disponível e, logo depois, ele pode distribuir esse valor entre diferentes ações, especificando o nome da ação e o valor a ser investido em cada uma, até que todo o orçamento seja alocado [5]. Após alocar todo o orçamento, o usuário pode clicar no botão 'Simular Portfólio'. Em seguida, o sistema exibirá, ao lado, o resultado da simulação, indicando quanto o usuário teria ganhado ou perdido no período selecionado previamente [6].** 

**Logo abaixo dos resultados da simulação personalizada, o sistema apresenta uma comparação com os ganhos que o usuário teria obtido caso seguisse as recomendações baseadas em seu perfil de investidor. Nessa seção, são exibidas as ações recomendadas, o valor sugerido para investir em cada uma e o lucro estimado permitindo ao usuário comparar diretamente com o resultado da simulação que ele mesmo criou [6][7].**

**Na mesma tela de simulação há um botão chamado “Menu” que, ao ser clicado, exibe uma janela deslizante com quatro opções clicáveis, cada uma direcionando para uma tela específica [4][5]. A primeira opção redireciona o usuário para o questionário de suitability, onde ele deverá refazer o questionário [5]. A segunda opção exibe os gráficos de previsão de fechamento de cada ação comparados aos valores reais, permitindo selecionar os gráficos de cada ação no período de 2023 a 2025 [6]. A terceira opção apresenta os gráficos históricos de cada ação referentes ao período de 2016 a 2023. Por fim, a quarta opção é um botão de sair, que realiza o logout do usuário e o redireciona para a página de login do sistema [7].**

**Seu objetivo de explorar e entender alternativas à poupança foi alcançado. Ele conseguiu identificar suas necessidades, limites de compreensão e a importância de informações claras, refletindo sobre como tomar decisões financeiras mais seguras e adequadas ao seu perfil [7].**

2) **Design Centrado na Comunicação**

**Nome do Cenário: Clareza e Simplicidade: A Necessidade de Usabilidade para Investidores Iniciantes**

| tópico \> subtópico (diálogo) | falas e signos |
|                         :---- |          :---- |
|   Cadastrar usuário na plataforma                            | U: Preciso me cadastrar na plataforma para poder acessar recomendação de carteiras de investimento de acordo com o meu perfil de investidor|
| \> informar dados do usuário                                 | D: Qual é o seu **nome**, **CPF**, **data de nascimento**, **telefone celular e residencial**, seu **e-mail**, **senha de acesso a plataforma** e você aceita a **política de privacidade** e **termos de uso da plataforma**?. <br> U: Certo, vou preencher meus dados e depois clicar no **botão de me cadastrar**. <br> D: Verificando informações...  cadastro realizado com sucesso. Redirecionando para a tela de **login na plataforma**.|
|   Login do usuário na plataforma                             | U: Preciso realizar o login na plataforma para poder simular investimentos de acordo com meu pefil de investimento identificado no questionário
| \> informar dados cadastrados do usuário                     | D: Qual é o seu **e-mail** e **senha** cadastrados anteriormente? <br> U: Vou preencher meus dados cadastrados e clicar no **botão de login**. <br> D: Verificando informações preenchidas... Cadastro encontrado no banco de dados. Redirecionando para a tela do **questionário**|
|   Responder questionário de suitability                      | U: Preciso responder o questionário de suitability para posteriormente simular investimento|
| \> responder perguntas com base no seu perfil                | D: Aqui estão **10 perguntas (questões do questionário)** que devem ser respondidas de acordo com seu conhecimento e familiaridade com investimentos. Cada resposta e **campo de resposta** atribui pontos que serão somados para a identificação do seu **perfil de investimento**. As questões 7, 8 e 9 permitem múltiplas respostas. No final clique no **botão de enviar seu questionário** <br> U: Vou preencher essas questões de acordo com meu conhecimento. <br> D: Ok, respostas recebidas, salvando pontuação no banco de dados, e redirecionando para a tela de simular investimento|


| tópico > subtópico (diálogo) | falas e signos |
| :---- | :---- |
| Simular Investimento | U: Quero **simular um investimento** com base no meu **orçamento disponível**, olhando o meu **perfil de investidor identificado** e o **card "Perfil Agressivo"** na tela. |
| > verificar movimentação histórica das ações | D: Ao clicar no campo **Menu** no canto superior direito, selecione **Histórico de cotações** para visualizar como foi o comportamento da ação em um período de 7 anos. |
| > informar o orçamento disponível | D: Informe o **valor total disponível para investir** no campo **"Seu Orçamento (R$)"**. <br> U: Digito **R$ 10.000,00**, e o sistema atualiza o texto **"Total Investido"**. |
| > distribuir orçamento | D: A partir desse **orçamento**, como você deseja distribuir esse valor para a compra de no mínimo **3 ações**? <br> U: Quero aplicar **R$ 2.000,00 em SBSP3**, **R$ 3.000,00 em ITUB4** e **R$ 5.000,00 em ELET3**, usando os campos de **"Ações para simular"**. <br> D: Após preencher, distribua o orçamento para cada ação e escolha o período de tempo nas abas de **horizonte (6 Meses / 1 Ano / 2 Anos)** e clique no botão **"Simular Portfólio"**. <br> U: Quero **simular investimento em um período de 12 meses**. |
| > resultado | D: **Simulação concluída.** Você teve prejuízo na ação da **ITUB4** de **R$ 20,00** e na **SBSP3** de **R$ 14,00**, mas teve um **lucro total de R$ 200,00** nesse investimento, conforme o bloco **"Resultado Histórico"**. A **Recomendação da IA** foi de investir **R$ 3.000,00 em SBSP3**, **R$ 5.000,00 em BBDC4** e **R$ 2.000,00 em BBAS3**, com um **lucro total de R$ 1.500,00**, exibidos nas **linhas de recomendação por ação**. |


| tópico \> subtópico (diálogo) | falas e signos |
|                         :---- |          :---- |
|  Refazer teste                |U: Coloquei respostas erradas no meu **questionário** e gostaria de refazê-lo.|
|  \> redirecionamento tela do questionário | D: Certo! Clique no **menu** e selecione a opção **refazer teste**. Você será redirecionado para a tela do **questionário** de suitability para refazê-lo.|


| tópico \> subtópico (diálogo) | falas e signos |
|                         :---- |          :---- |
|  Deslogar conta da plataforma                |U: Quero **encerrar minha sessão** na plataforma.|
|  \> Sair da plataforma | D: Certo! Clique no **menu** e selecione a opção **sair**. <br> U: OK! <br> D: Deslogando da plataforma e redirecionando para a tela de **login**.|

3) **Mapa de Objetivos (cada um coloca seu mapa de objetivos e deverá ter um diagrama de consolidação)**

![Mapa de Objetivos João](https://github.com/user-attachments/assets/b7b8e964-babc-4fe3-9769-dc3f212d136a)


4) **Esquema Conceitual Geral de Signos**

| | | | | | | | |
| :----     | :----      | :----           | :----                | :----                           | :----              | :----        | :----           |
| **signo**  | **origem** | **observações** | **tipo de conteúdo** | **restrições sobre o conteúdo** | **valor default** | **prevenção** | **recuperação** |
| Cadastrar na Plataforma | Sistema  | Tela de cadastro das informações do usuário na plataforma | interação de usuário (formulário) | Disponível apenas para usuários não autenticados. E-mail e CPF devem ser válidos, únicos e o aceite dos termos é obrigatório. | Campos vazios e campos obrigatórios marcados com *.| PP: Campos obrigatórios com expressão explícita (*), verificação em tempo real de CPF e e-mail previamente cadastrados| RA: mensagem de erro e possibilidade de editar campos incorretos |
| Recomendação de carteiras de investimento | sistema | Após a autenticação do usuário, o mapeamento do perfil e a realização da simulação manual, o sistema apresenta as três ações mais compatíveis com o perfil do investidor | Comportamento do sistema | Para que a recomendação seja gerada, o usuário deve simular no mínimo três ações. | Nenhuma recomendação disponível | PP: O sistema permite simular menos de três ações, porém exibe uma mensagem em vermelho informando que são necessárias pelo menos três para gerar recomendações.  | RA: Mensagem de erro em vermelho indicando o que o usuário deve editar  |
| Perfil de Investidor/Questionário | sistema/usuário | Tela de disponibilização do questionário de suitability para preenchimento do usuário | interação de usuário (questionário) | Para o envio do questionário é necessário que o usuário preencha ele por completo | Campos para resposta vazios | PA: O sistema bloqueia o envio do questionário de suitability enquanto não estiver totalmente preenchido, garantindo que todos os dados sejam fornecidos| - |
| Login na Plataforma | Sistema | Para realizar o login na plataforma é necessário ter uma conta cadastrada anteriormente | interação de usuário (formulário) | Cadastro efetuado anteriormente no sistema |campos vazios | PP: O sistema permite que o usuário tente efetuar o login com dados incorretos e exibe uma mensagem de erro, informando erro ao efetuar login, permitindo que ele corrija e tente novamente. | RA: O usuário corrige o login ou senha conforme a mensagem de erro e tenta novamente, permitindo que o acesso seja realizado com sucesso. |
| Política de privacidade e termos de uso | sistema | Na tela de cadastro, o usuário deve marcar uma caixa de seleção para aceitar os Termos de Uso e a Política de Privacidade da plataforma. É possível clicar nos links do texto para acessar as telas completas dos termos ou da política, e ambas as telas possuem um botão “Voltar” que retorna o usuário para a tela de cadastro| interação de usuário (caixa de seleção) | Para realizar o cadastro é necessário que essa caixa seja preenchida | Caixa de seleção desativada | PA: O botão de cadastro só é habilitado quando o usuário marca a caixa de seleção aceitando os Termos de Uso e a Política de Privacidade, impedindo que o cadastro seja concluído sem o aceite obrigatório. | - |
| Simular Investimento | Sistema | Na tela de simulação de investimento, o usuário deve informar seu orçamento disponível e selecionar as ações e respectivos valores que deseja simular | interação de usuário  | O usuário deve selecionar pelo menos uma ação cujo valor para compra seja menor ou igual ao orçamento disponível. | Campos vazios | PA: O sistema impede que o usuário simule valores acima do orçamento disponível, exibindo uma mensagem de erro em vermelho e desabilitando o botão de simulação até que os valores sejam corrigidos. | RA: O usuário corrige os valores das ações para que fiquem menores ou iguais ao orçamento disponível, permitindo que o botão de simulação seja habilitado e a simulação seja realizada. |
| Histórico | Sistema | O usuário pode acessar o histórico de todas as 8 ações a qualquer momento clicando no botão de menu disponível na tela de simulação | interação de usuário |- | - | -| - |
| Refazer Teste | Sistema | Na tela de simulação de investimento, o usuário pode refazer o questionário a qualquer momento: basta abrir o menu no canto superior direito, selecionar “Refazer teste” e será redirecionado para a tela do questionário. | Comportamento do sistema | - | Barra lateral do menu fechada | - | - |
| Encerrar minha sessão | Sistema | Na tela de simulação de investimento, o usuário pode encerrar sua sessão a qualquer momento: basta abrir o menu no canto superior direito, selecionar "sair" e será redirecionado para a tela de login da plataforma | Comportamento sistema | - |  Barra lateral do menu fechada  | - | - |

# ---- Felipe ----

1) **Cenários de Interação (destacar em cor diferente o texto alterado entre Cenário Problema e Cenário de Interação)**

## Cenário de Interação – Felipe Orlando

Felipe Orlando, engenheiro civil de 42 anos, possui mais de 10 anos de experiência no mercado de ações. Ao longo da trajetória, desenvolveu domínio de conceitos técnicos como volatilidade, dividend yield e valuation. Seu objetivo prático é converter previsões em decisões rápidas; por isso, considera essenciais os gráficos de previsão com horizonte de 24 meses e um caminho de recomendação coerente ao seu perfil agressivo [1].

O cenário ocorre em seu cotidiano de investidor ativo, que dedica tempo diário à análise de relatórios e ao acompanhamento do mercado [2]. Nesse ambiente, a plataforma surge como complemento às ferramentas que já utiliza, mas precisa responder à expectativa de um usuário com alto nível de conhecimento; limitações de clareza metodológica ou de flexibilidade são percebidas rapidamente [3].

Ao utilizar a plataforma, Felipe segue a sequência já mapeada no refinamento: cria sua conta, responde ao questionário de suitability e é classificado como investidor agressivo. **Imediatamente após a classificação, o sistema o direciona para a aba Simulação de Ações**, onde ele executa a simulação para o seu perfil [4]. **Nessa etapa não há gráficos: a tela exibe somente as ações recomendadas para Felipe** com base no modelo e **mostra, para cada papel, a estimativa de crescimento projetada para 6, 12 ou 24 meses (conforme a opção escolhida), além do resultado estimado do portfólio para o horizonte selecionado.O objetivo aqui é dar uma resposta direta sobre “o que comprar” e “quanto tende a subir” segundo a predição, sem exigir ajustes avançados** [4][5].

Depois de verificar a lista recomendada e o ganho estimado, **Felipe clica no botão Menu e acessa Gráficos de Previsões. Nessa área, ele analisa, gráfico a gráfico, as previsões de 24 meses das ações sugeridas, para entender melhor os motivos da escolha da IA e visualizar o andamento projetado de cada papel segundo o modelo. Essa navegação complementa a etapa de simulação: primeiro ele vê as recomendações e os percentuais de alta; na sequência, aprofunda-se nos gráficos para validar a coerência das projeções com sua leitura de mercado e decidir com mais segurança** [6].

**Ao final, Felipe avalia que o fluxo está coerente com seu perfil: simulação objetiva → lista de ações recomendadas com estimativa de crescimento (6/12/24m) → análise visual nos gráficos de previsão, mantendo a simplicidade operacional e a clareza de resultados que espera do sistema. Ainda reconhece espaço para evoluir em clareza metodológica e opções de personalização, conforme apontado no refinamento, mas considera que as previsões no horizonte selecionado e a recomendação alinhada ao perfil agressivo já permitem transformar as projeções em um plano de execução prático** [7].

2) **Design Centrado na Comunicação**

**Nome do Cenário: Felipe Orlando**

| tópico > subtópico (diálogo) | falas e signos |
|---|---|
| **Cadastrar usuário na plataforma** | **U:** Quero me cadastrar para receber recomendações alinhadas ao meu **perfil agressivo** e já simular posições. |
| > **informar dados do usuário** | **D:** Informe **nome, CPF, data de nascimento, telefone (celular e residencial), e-mail, senha**, aceite a **política de privacidade** e **termos de uso** e clique no **botão de cadastrar**. <br> **U:** Preencho meus dados. <br> **D:** *Verificando informações…* Cadastro concluído. Redirecionando para **login**. |
| **Login do usuário na plataforma** | **U:** Vou fazer **login** para seguir com a simulação conforme meu perfil de investimento. |
| > **informar dados cadastrados do usuário** | **D:** Qual é o **e-mail** e a **senha** cadastrados? <br> **U:** Informo minhas credenciais e clico no **botão de login**. <br> **D:** *Validando…* Login realizado. Redirecionando para o **questionário de suitability**. |
| **Responder questionário de suitability** | **U:** Quero responder o **questionário** para configurar as recomendações ao meu perfil agressivo. |
| > **responder perguntas com base no seu perfil** | **D:** São **10 perguntas**; algumas aceitam múltiplas respostas. No final, clique em **Enviar**. <br> **U:** Respondo de acordo com minha experiência, aceitando alta volatilidade, maior risco visando ganho mais rápido e mostrando meu conhecimento com investimentos. <br> **D:** *Processando…* **Perfil identificado: Agressivo.** Redirecionando para **Simulação de Ações**. |

| tópico > subtópico (diálogo) | falas e signos |
|---|---|
| **Simular Investimento** | **U:** Quero **simular um investimento** com base no meu **orçamento disponível**, escolhendo **6 meses** porque busco **ganhos mais rápidos** (na tela **Simular Investimento**). |
| > **informar o orçamento disponível** | **D:** Informe o **valor total** disponível para investir no campo **"Seu Orçamento (R$)"**; o **"Total Investido"** será atualizado automaticamente. <br> **U:** **R$ 10.000,00**. |
| > **selecionar ações e distribuir orçamento** | **D:** Selecione **ao menos 3 ações** nos cartões **"Ações para simular"** e **distribua o orçamento**; em seguida, escolha o horizonte nas abas **6 Meses / 1 Ano / 2 Anos** e clique em **"Simular Portfólio"**. <br> **U:** **ABEV3 R$ 3.000,00**, **ITUB4 R$ 3.000,00**, **ELET3 R$ 4.000,00**. <br> **U:** Defino o período de **6 meses** para a simulação. |
| > **resultado** | **D:** *Simulação concluída (6 meses).* <br> **Resultado Histórico (6m):** **R$ 1.637,89** — **ABEV3** **R$ -159,55**, **ITUB4** **R$ +869,50**, **ELET3** **R$ +927,95** (lista de **resultados por ação**). <br> **Recomendação da IA (6m):** **Lucro total estimado: R$ 3.109,70** — **SBSP3 (R$ 5.000,00)** **R$ +1.776,23**; **ITUB4 (R$ 3.000,00)** **R$ +869,50**; **ELET3 (R$ 2.000,00)** **R$ +463,97** (lista de **recomendações por ação**). |

| tópico > subtópico (diálogo) | falas e signos |
|---|---|
| **Acessar Previsões** | **U:** Quero ver os **gráficos de previsão** para entender o porquê das recomendações. |
| > **abrir menu** | **D:** Toque em **Menu** para acessar as seções da plataforma. <br> **U:** Abro o **Menu**. |
| > **ir para “Previsões”** | **D:** Selecione **Previsões** para visualizar os **gráficos dos próximos 24 meses**. <br> **U:** Clico em **Previsões**. |
| > **escolher ação para visualizar** | **D:** **Selecione a ação para comparar o modelo** e ver seu respectivo **gráfico de acurácia** de previsão (24m) e leia a **legenda do gráfico** para compreender melhor. <br> **U:** Examino as ações indicadas pela IA para validar as recomendações. |

3) **Mapa de Objetivos (cada um coloca seu mapa de objetivos e deverá ter um diagrama de consolidação)**

![Mapa de Objetivos Felipe](https://github.com/user-attachments/assets/f378bca9-ab33-456a-b98a-635682e6fa4b)


4) **Esquema Conceitual Geral de Signos**

| signo | origem | observações | tipo de conteúdo | restrições sobre o conteúdo | valor default | prevenção |
|---|---|---|---|---|---|---|
| Cadastrar na Plataforma | sistema | Tela de cadastro das informações do usuário. | interação de usuário (formulário) | Disponível só para não autenticados. **E-mail** e **CPF** devem ser válidos/únicos; aceite dos **Termos** e **Política** é obrigatório. | Campos vazios; obrigatórios marcados com * | **PP:** Máscara e validação de CPF/e-mail; **PA:** Botão “Cadastrar” desabilitado até todos obrigatórios + aceite. |
| Login na Plataforma | sistema | Acesso com e-mail e senha cadastrados. | interação de usuário (formulário) | Requer conta criada; | Campos vazios | **PP:** Mensagem de erro clara em caso de credencial inválida; manter campos preenchidos para correção. |
| Política de Privacidade e Termos de Uso | sistema | Caixa de seleção para aceite; links abrem os textos completos e retornam ao cadastro. | interação de usuário (caixa de seleção) | Aceite obrigatório para concluir cadastro. | Caixa desmarcada | **PA:** Botão “Cadastrar” só habilita após marcar a caixa. |
| Perfil de Investidor / Questionário (Suitability) | sistema/usuário | 10 perguntas (algumas múltipla escolha) para classificar o perfil. | interação de usuário (questionário) | Envio apenas com todas as questões respondidas. | Campos de resposta vazios | **PA:** Botão “Enviar” desabilitado até 100% de progresso; **PP:** instruções curtas por questão. |
| Simular Investimento | sistema | Na tela de simulação, o usuário informa **orçamento** e seleciona **≥ 3 ações**, distribuindo os valores; escolhe **6/12/24 meses**. | interação de usuário (formulário de seleção) | Somatório por ação **= orçamento**; mínimo **3 ações**; valores numéricos válidos; horizonte selecionado (6/12/24m). | Orçamento vazio; sem ações; horizonte não selecionado | **PA:** Botão “Simular Portfólio” desabilitado até cumprir regras. **PP:** Máscara de moeda; mensagem em vermelho se < 3 ações ou soma ≠ orçamento. |
| Recomendação de Carteiras de Investimento (IA) | sistema | Após simulação válida, o sistema mostra **somente as ações recomendadas** para o **horizonte escolhido (6/12/24m)** com a **estimativa de crescimento** por ação e o **lucro total estimado** do portfólio. | comportamento do sistema (resumo) | Exibida somente se a simulação tiver ≥ 3 ações válidas no horizonte selecionado. | Nenhuma recomendação disponível | **PA:** Não gera recomendação sem cumprir regras da simulação; **PP:** textos objetivos (+/− em verde/vermelho). |
| Previsões (Gráficos 24 meses) | sistema | Acesso via **Menu → Previsões**. Exibe **gráfico a gráfico (24m)** das **ações recomendadas** para entender o racional da IA. | visualização de dados (gráfico) | - | Lista vazia de gráficos | - |

# ----- Pedro -----

1) **Cenários de Interação (destacar em cor diferente o texto alterado entre Cenário Problema e Cenário de Interação)**

## Cenário de Interação – Pedro

Pedro começou a investir no ano passado utilizando o software InvestMind, buscando organizar suas aplicações e receber recomendações de carteiras alinhadas ao seu estilo de investimento [1]. Ao descobrir a plataforma, em um contexto de interesse crescente por investimentos em ações e influência de amigos que já utilizavam ferramentas digitais para investir, ele decidiu criar uma conta e experimentar o sistema [2]. Assim como no cenário problema, ele criou sua conta, fez login, respondeu ao questionário de Suitability e foi classificado como investidor agressivo, o que naquele momento fazia sentido para seu comportamento. A partir desse cadastro inicial, o sistema passou a exibir, no topo da tela de simulação, o texto “Perfil de Investidor Identificado: Agressivo” e o card explicativo do perfil, deixando claro o tipo de recomendação que seria gerada para ele [3].

Antes de investir novamente, já após um ano de uso, Pedro agora tem metas diferentes: ele deseja reduzir a exposição à volatilidade, priorizar ações mais estáveis e preservar o capital, ainda que com retornos potencialmente menores [4]. **Ao acessar novamente a InvestMind, Pedro identifica que já se passaram mais de seis meses desde a última avaliação de perfil e decide refazer o questionário de Suitability. Dessa forma, antes mesmo de seguir para novas recomendações, Pedro percebe que o perfil utilizado até então pode não refletir mais sua realidade atual [6].**

**Ao clicar em “Refazer Teste”, Pedro realiza uma sequência de ações na interface: é direcionado para a tela do questionário de Suitability, responde novamente às 10 perguntas sobre seu conhecimento, objetivos e tolerância a risco e, por fim, clica em “Enviar questionário” [5]. O sistema processa as respostas e exibe a mensagem: “Novo perfil identificado: Conservador”, seguida de uma breve descrição do que isso significa em termos de risco e volatilidade. Em seguida, a plataforma o redireciona automaticamente para a tela de simulação de investimentos, agora com o cabeçalho atualizado para “Perfil de Investidor Identificado: Conservador” e com o card de perfil conservador em destaque, reforçando visualmente a mudança [3][6].**

**Na área de simulação, Pedro informa seu orçamento, escolhe o horizonte de tempo de 2 anos e seleciona as ações para testar. A partir da nova configuração, o sistema passa a apresentar nas Recomendações da IA, apenas ativos compatíveis com o perfil conservador, priorizando ações menos voláteis e mais estáveis, permitindo que ele ajuste a carteira de acordo com o seu novo perfil de investidor antes de tomar a decisão final [4][5].**

**Ao final do fluxo, Pedro consegue montar uma carteira alinhada ao seu novo perfil, com recomendações coerentes com sua postura mais cautelosa. O sistema, ao tornar o perfil sempre visível na tela principal evita que Pedro continue investindo como se ainda fosse agressivo. Em sua avaliação, a InvestMind passa a ser vista como uma ferramenta mais segura e confiável, pois demonstra preocupação em se adaptar às mudanças de comportamento do investidor e em prevenir recomendações inadequadas [7]. Dessa forma, a interação corrige diretamente as falhas levantadas no cenário problema, relacionadas à falta de feedback e de mecanismos de prevenção de erro entre humano e sistema.**

2) **Design Centrado na Comunicação**
 
**Nome do Cenário: Pedro**

| tópico > subtópico (diálogo) | falas e signos |
| :---- | :---- |
| Login do usuário na plataforma | U: Quero realizar o login na plataforma InvestMind para revisar meus investimentos. <br> D: Exibe a tela de login com campos para **e-mail** e **senha**, **botão Entrar** |
| > informar dados cadastrados do usuário | D: Qual é o **e-mail** e a **senha** cadastrados anteriormente? <br> U: Informo minhas credenciais e clico no **botão de login**. <br> D: Validando... Login realizado com sucesso. Redirecionando para a tela de **simulação de investimentos**. |
| Acesso ao **menu** | U: Quero verificar se o meu **perfil de investidor** ainda faz sentido para mim. <br> D: Exibe, no canto superior direito, o **ícone/botão Menu**. |
| > abrir **menu** | U: Clico no botão **Menu**. <br> D: Abre um painel lateral com as opções **Refazer Teste**, **Previsões**, **Histórico** e **Sair**. |
| > selecionar **Refazer Teste** | U: Clico na opção **Refazer Teste** para atualizar meu **perfil de investidor**. <br> D: Fecha o **menu** e redireciona para a tela do **Questionário de Suitability**. |
| Responder **questionário de suitability** | U: Quero responder novamente ao **questionário** para que as recomendações acompanhem meu comportamento atual, mais conservador. <br> D: Exibe o título **Questionário de Suitability** e as **questões do questionário**. |
| > responder perguntas com base no novo perfil | D: São **10 perguntas**; algumas aceitam múltiplas respostas. No final, clique em **Enviar questionário**. <br> U: Respondo às **perguntas** de acordo com meu novo objetivo de reduzir riscos, escolhendo alternativas mais conservadoras. <br> D: Verificando respostas... |
| > envio e confirmação do novo perfil | U: Clico no botão **Enviar questionário**. <br> D: Processando... Novo perfil identificado: Conservador. |
| Retornar à simulação com perfil atualizado | D: Redireciona para a tela de simulação, atualiza o cabeçalho para **Perfil de Investidor Identificado: Conservador** e passa a gerar recomendações compatíveis com esse perfil. |

| tópico > subtópico (diálogo) | falas e signos |
| :---- | :---- |
| **Simular Investimento** | **U:** Quero montar uma simulação na tela de **Simular Investimento** usando meu **orçamento total**, escolhendo o horizonte de **2 anos** para avaliar o retorno no médio prazo. |
| > **informar o orçamento disponível** | **D:** Digite o **valor total** que você pretende investir nesta simulação no campo **"Seu Orçamento (R$)"**; o texto **"Total Investido"** será atualizado conforme a distribuição entre as ações. <br> **U:** Preencho com **R$ 10.000,00**. |
| > **selecionar ações e distribuir orçamento** | **D:** Selecione **pelo menos 3 ações** nos cartões de **"Ações para simular"** e divida o orçamento entre elas. Em seguida, escolha o horizonte nas abas **6 Meses / 1 Ano / 2 Anos** e clique em **"Simular Portfólio"**. <br> **U:** Escolho **ELET3 R$ 3.000,00**, **BBAS3 R$ 5.000,00** e **ITUB4 R$ 2.000,00**. <br> **D:** Após o preenchimento, o sistema confirma a soma de **R$ 10.000,00** como **"Total Investido"**. <br> **U:** Mantenho o período configurado em **2 anos** na aba correspondente para a simulação. |
| > **resultado** | **D:** *Simulação concluída (2 anos).* <br> **Resultado Histórico (2 anos):** **R$ 2.963,37** — **ELET3**: **+ R$ 1.204,49**, **BBAS3**: **+ R$ 166,36**, **ITUB4**: **+ R$ 1.592,53**, exibidos no bloco de **Resultado Histórico** e nas **linhas de resultado por ação**. <br> **Recomendação da IA (2 anos):** **Lucro total estimado R$ 9.163,11** — **SBSP3 (R$ 5.000,00)** **+ R$ 5.971,33**; **ITUB4 (R$ 3.000,00)** **+ R$ 2.388,79**; **ELET3 (R$ 2.000,00)** **+ R$ 803,00**, apresentados no bloco de **Recomendação da IA (2 Anos)** e nas **recomendações por ação**. |

3) **Mapa de Objetivos (cada um coloca seu mapa de objetivos e deverá ter um diagrama de consolidação)**

![Mapa de Objetivos Pedro](https://github.com/user-attachments/assets/626d7c85-ffdc-4dd5-8b8f-c679281652a0)


4) **Esquema Conceitual Geral de Signos**

| signo | origem | observações | tipo de conteúdo | restrições sobre o conteúdo | valor default | prevenção |
|---|---|---|---|---|---|---|
| Login na Plataforma | sistema | Tela com campos de e-mail e senha para que Pedro acesse sua conta já existente. | interação de usuário (formulário) | Requer conta previamente cadastrada e credenciais corretas. | Campos vazios | **PP:** mensagem clara em caso de credencial inválida; manter campos preenchidos para correção. |
| Menu / Acesso ao “Refazer Teste” | sistema | Ícone de **Menu** no canto superior direito que abre a lista de opções, incluindo **Refazer Teste**. | navegação | Disponível apenas para usuário autenticado. | Menu fechado | **PP:** rótulo “Refazer Teste” deixa explícito que o perfil pode ser recalibrado; evita que o usuário ignore essa possibilidade. |
| Questionário de Suitability (refazer teste) | sistema/usuário | Conjunto de 10 perguntas que Pedro responde novamente para atualizar o perfil de investidor. | interação de usuário (questionário) | Envio permitido apenas quando todas as perguntas forem respondidas. | Campos de resposta vazios | **PA:** botão “Enviar questionário” desabilitado até 100% de preenchimento; **PP:** instruções curtas em cada pergunta. |
| Confirmação de novo perfil | sistema | Após o envio, o sistema exibe “Novo perfil identificado: Conservador”, com um resumo do perfil e botão “Ir para Simulação de Ações”. | feedback do sistema | Exibido somente após processamento válido do questionário. | Não exibido antes do envio | **PP:** reforça visualmente a mudança de perfil, evitando que Pedro continue achando que ainda é agressivo. |
| Simular Investimento | sistema | Na tela de simulação, Pedro informa o orçamento, escolhe pelo menos 3 ações e define o horizonte (6 meses, 1 ano ou 2 anos) antes de clicar em “Simular Portfólio”. | interação de usuário (formulário de seleção) | Somatório dos valores por ação = orçamento; mínimo 3 ações; valores numéricos válidos; horizonte selecionado. | Orçamento vazio; sem ações; horizonte não selecionado | **PA:** botão “Simular Portfólio” desabilitado até cumprir as regras; **PP:** máscara de moeda e avisos em vermelho se < 3 ações ou soma ≠ orçamento. |
| Recomendação de Carteiras de Investimento (IA) | sistema | Após simulação válida, o sistema mostra apenas as ações sugeridas pela IA para o horizonte escolhido, com lucro total estimado e ganho por papel, ajustados ao novo perfil de Pedro. | comportamento do sistema (resumo) | Exibida somente se houver simulação válida com perfil identificado. | Nenhuma recomendação disponível | **PA:** não gera recomendação sem simulação consistente; **PP:** ganhos e riscos apresentados de forma objetiva, com uso de cores para destacar lucros/perdas. |


# Esquema Conceitual de Signos

4a) **Esquema conceitual de signos: Cadastrar usuário na plataforma**

| Credenciais (C) \- credenciais para Cadastrar usuário na plataforma  | | | | | | | |
| :----     | :----      | :----           | :----                | :----                           | :----              | :----        | :----           |
| **signo**  | **origem** | **observações** | **tipo de conteúdo** | **restrições sobre o conteúdo** | **valor default** | **prevenção** | **recuperação** |
| nome  | usuário  | campo obrigatório | interação de usuário (formulário) | - |  campo vazio | PP: Campo obrigatório com expressão explícita (*) | RA: Destaque nos campos incorretos e mensagem de erro|
| CPF  | usuário | Campo obrigatório e único | interação de usuário (formulário) | O CPF informado deve ser único e válido | campo vazio | PP: Campo do CPF obrigatório, único e válido | RA: Destaque no campo incorreto e mensagem de erro  |
| data de nascimento  | usuário  | Campo obrigatório  | interação de usuário | Não permitir datas futuras (posteriores ao dia atual) e uma idade mínima de 18 anos  | campo vazio | PP: Campo de data de nascimento obrigatória e válido | RA: Destaque no campo incorreto e mensagem de erro |
| telefone celular  | usuário | Campo Obrigatório | interação de usuário | - | campo vazio | PP: Campo de telefone celular obrigatório | RA: Destaque no campo incorreto e mensagem de erro |
| telefone residencial  | usuário | campo opcional | interação de usuário | - | campo vazio | - | - |
| e-mail  | usuário | Campo obrigatório e único | interação de usuário | O e-mail de ser único e validado | campo vazio | PP: Campo do e-mail obrigatório, único e válido  | RA: Destaque no campo incorreto e mensagem de erro |
| senha  | usuário | Campo obrigatório | interação de usuário | - | campo vazio | PP: Campo de senha obrigatório | RA: Destaque no campo incorreto e mensagem de erro |
| política de privacidade  | usuário | Campo obrigatório | interação de usuário | - | Caixa de escolha desmarcada | PP: Obrigatório marcar com um check o botão das políticas | RA: Destaque no campo incorreto e mensagem de erro |
| termos de uso da plataforma  | usuário | campo obrigatório  | interação de usuário | -  | Caixa de escolha desmarcada | PP: Obrigatório marcar com um check o botão dos termos | RA: Destaque no campo incorreto e mensagem de erro |
| botão Cadastrar | sistema | Envia o formulário quando todos os requisitos forem atendidos; evita duplo clique com estado de carregamento. | controle de ação | Só habilita com formulário válido e aceite marcado | desabilitado | PA: desabilitado até cumprir regras; loading e bloqueio de reenvio; | RA: se e-mail/CPF já existentes, exibe aviso; mantém dados para corrigir e reenviar. |
| login na plataforma  | sistema | Após o cadastro do usuário o sistema redireciona para a tela de login do sistema  | sistema | Cadastro efetuado com sucesso  | - | PP: O sistema válida todos os campos preenchidos e redireciona para a tela de login | RA: Caso ocorra alguma informação incorreta o sistema retorna mensagens de erro e deixa o usuário realizar a mudança |

4b) **Esquema conceitual de signos: Login do usuário na plataforma**

| Credenciais (C) \- credenciais para realizar Login do usuário na plataforma  | | | | | | | |
| :----     | :----      | :----           | :----                | :----                           | :----              | :----        | :----           |
| **signo**  | **origem** | **observações** | **tipo de conteúdo** | **restrições sobre o conteúdo** | **valor default** | **prevenção** | **recuperação** |
| e-mail | usuário | Campo obrigatório e único, deve ser cadastrado anteriomente | interação de usuário | o e-mail deve ser único e cadastrado anteriormente | campo vazio  | PP: Campo do e=mail obrigatório, único e válido  | RA: Destaque no campo incorreto e mensagem de erro|
| senha | usuário | Campo obrigatório e único, deve ser cadastrado anteriomente | interação de usuário | a senha deve ter sido cadastrada anteriormente | campo vazio | PP: Campo de senha obrigatório, cadastrado anteriormente e com nmáscara de caracteres  | RA: Destaque no campo incorreto e mensagem de erro  |
| botão Entrar | sistema | Realiza a autenticação quando os campos estão válidos. | controle de ação | Só habilita com e-mail válido e senha preenchida. | desabilitado | PA: desabilitado até cumprir requisitos; feedback do que falta. | RA: em falha do backend, mostrar aviso e permitir tentar novamente. |
| questionário | usuário | Após a efetuação do login no sistema, ele verifica se o questionário já foi preenchido anteriormente se sim redireciona para a tela de simulação de investimento, caso ao contrário para a tela de questionário de suitabilty | interação de usuário | Ter realizado o login no sistema  | respostas vazias | PA: Bloqueio do botão de enviar questionário até o preenchimento de todas as questões | - |

4c) **Esquema conceitual de signos: Responder questionário de suitability**

| signo | origem | observações | tipo de conteúdo | restrições sobre o conteúdo | valor default | prevenção | recuperação |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| questões do questionário | sistema | Conjunto de 10 perguntas sobre conhecimento, objetivo e tolerância a risco | interação do usuário (questionário) | Todas as perguntas devem ser respondidas; algumas permitem múltipla escolha | campos vazios | PP: indicar obrigatoriedade com * e/ou barra de progresso de respostas | RA: ao voltar ou em erro, manter as respostas já preenchidas, evitando recomeçar do zero |
| campos de resposta | usuário | Seleção das alternativas de acordo com o perfil do usuário (experiência, aceitação de risco) | interação do usuário (formulário) | Nenhuma questão pode ficar em branco; respostas devem ser válidas para a pergunta | não preenchidos | PP: ao tentar enviar com itens em branco, destacar visualmente as questões faltantes | RA: manter todas as respostas que já foram marcadas e focar diretamente na questão que falta |
| botão Enviar questionário | sistema | Envia o questionário para cálculo do perfil de investidor | controle de ação | Só habilita quando **todas** as perguntas forem respondidas. | desabilitado | PA: permanece desabilitado enquanto houver questão sem resposta. | RA: em falha de envio, exibir mensagem de erro e permitir reenviar com as mesmas respostas salvas. |

4d) **Esquema conceitual de signos: Simular Investimento**

| signo | origem | observações | tipo de conteúdo | restrições sobre o conteúdo | valor default | prevenção | recuperação |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| perfil de investidor identificado | sistema | Texto no topo da tela: “Perfil de Investidor Identificado: Agressivo”, indicando o perfil atual usado na simulação | comportamento do sistema (feedback) | Exibido somente para usuário autenticado e com questionário de suitability concluído | não exibido antes do login/suitability | PP: evita que o usuário esqueça qual perfil está sendo usado na recomendação | RA: caso o usuário discorde do perfil, pode acessar “Refazer teste” pelo menu para recalibrar |
| card “Perfil Agressivo” | sistema | Card lateral com descrição do perfil agressivo (“Foca na alta rentabilidade…”), reforçando o contexto de risco | texto explicativo / apoio | Deve corresponder exatamente ao perfil identificado; texto estático por perfil | card correspondente ao perfil do usuário | PP: ajuda a alinhar expectativa de risco/retorno com o tipo de recomendação exibida | RA: ao refazer o suitability, o card é atualizado automaticamente para o novo perfil |
| orçamento (campo “Seu Orçamento (R$)”) | sistema | Campo para informar o valor total disponível para investir na simulação | interação de usuário (formulário) | Valor deve ser numérico e maior que zero | vazio | PP: máscara de moeda; validação imediata; não aceitar letras ou valores negativos | RA: mensagem de erro mantendo o valor digitado para correção |
| total investido | sistema | Texto “Total Investido: R$ …” que mostra a soma dos valores digitados em cada ação | feedback do sistema | Deve sempre refletir a soma dos campos “Seu Valor a investir (R$)” e nunca ultrapassar o orçamento | R$ 0,00 | PP: atualização automática a cada edição; alerta visual se soma for maior que o orçamento | RA: ao ajustar os valores por ação, o total é recalculado e o alerta some |
| ações para simular (seleção + valor) | sistema | Conjunto de cartões “Ações para simular”, cada um com um seletor de ação (ticker) e o campo “Seu Valor a investir (R$)” | interação de usuário (formulário) | Mínimo de 3 ações; cada valor ≥ 0; soma dos valores deve ser igual ao orçamento | lista vazia; campos em branco | PP: aviso em vermelho se houver menos de 3 ações ou se a soma ≠ orçamento; impedir entrada de valores negativos | RA: destacar apenas os campos com problema e manter os demais; permitir ajuste sem perder o preenchimento correto |
| botão “+ Adicionar Ação” | sistema | Permite incluir novos cartões de ação para diversificar a simulação | controle de ação | Não deve ultrapassar o limite máximo de ações definido pelo sistema (se houver) | botão habilitado | PP: desabilitar o botão ao atingir o limite; instrução visual caso o limite seja alcançado | RA: permitir excluir ações desnecessárias para liberar espaço para novas |
| horizonte (abas 6 Meses / 1 Ano / 2 Anos) | sistema | Abas que definem o período da simulação; no exemplo, Felipe escolhe 6 meses buscando ganhos mais rápidos | interação de usuário (controle de opção) | Deve existir exatamente uma aba selecionada: 6 meses, 1 ano ou 2 anos | nenhuma aba selecionada inicialmente (ou 6 meses como padrão, conforme regra do sistema) | PA: botão “Simular Portfólio” desabilitado enquanto não houver horizonte definido (se não houver padrão) | RA: ao voltar de outra tela, manter a aba selecionada anteriormente |
| botão “Simular Portfólio” | sistema | Dispara o cálculo da simulação com base no orçamento, ações e horizonte escolhidos | controle de ação | Só habilita com orçamento válido, pelo menos 3 ações preenchidas e horizonte selecionado | desabilitado | PA: permanece desabilitado até cumprir todas as regras; tooltip pode indicar o que falta | RA: em caso de erro no backend, exibir mensagem de falha e permitir tentar novamente sem perder o preenchimento |
| bloco “Resultado Histórico (horizonte)” | sistema | Card que apresenta o resultado histórico total do portfólio para o horizonte escolhido (ex.: “Resultado Histórico (6 Meses)” e “R$ -41,94”) | comportamento do sistema (resumo) | Exibido somente após uma simulação bem-sucedida | não exibido | PP: uso de cores para indicar ganho (verde) ou perda (vermelho), ajudando a leitura rápida | RA: caso os dados não possam ser carregados, exibir mensagem de erro e opção de recalcular |
| linhas de resultado por ação (histórico) | sistema | Lista das ações simuladas pelo usuário com o resultado individual (ex.: ABEV3, B3SA3, BBDC4 com valores negativos) | visualização de dados (lista) | Deve listar exatamente as ações escolhidas na simulação; valores podem ser positivos ou negativos | lista vazia | PP: sinalização clara de lucro/prejuízo por cor e sinal (+ / −) | RA: após nova simulação, a lista é atualizada com os novos resultados |
| bloco “Recomendação da IA (horizonte)” | sistema | Card que apresenta o lucro total estimado pela IA para o horizonte selecionado (ex.: “Recomendação da IA (6 Meses)” com R$ 310,97) | comportamento do sistema (resumo) | Depende de simulação válida; a recomendação é calculada com base no perfil agressivo do usuário | não exibido | PP: deixar claro no título que se trata de uma recomendação baseada em IA e no perfil do usuário | RA: se a recomendação falhar, exibir mensagem e instruir o usuário a simular novamente |
| linhas de recomendação por ação (IA) | sistema | Lista das ações sugeridas pela IA (ex.: SBSP3, ITUB4, ELET3), com o valor recomendado e o lucro estimado por papel | visualização de dados (lista) | Deve ser coerente com o perfil do investidor e com o horizonte selecionado; valores somados não podem ultrapassar o orçamento | lista vazia | PP: manter formatação consistente (valor investido + valor estimado em verde); ordenar por maior potencial de retorno | RA: ao refazer a simulação com novos parâmetros, recalcular e atualizar a lista inteira |

4e) **Esquema conceitual de signos: Menu lateral**

| signo | origem | observações | tipo de conteúdo | restrições sobre o conteúdo | valor default | prevenção | recuperação |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| botão "Menu" (ícone de usuário) | sistema | Ícone no canto superior direito que abre o painel lateral de opções | navegação | Disponível apenas para usuário autenticado | botão visível, painel fechado | PP: manter o ícone sempre no mesmo lugar para facilitar o reconhecimento | RA: ao reabrir, o menu volta a exibir as mesmas opções, sem alterar o estado das telas principais |
| opção "Refazer Teste" | sistema | Leva o usuário de volta ao questionário de suitability para recalibrar o perfil de investidor | navegação | Disponível apenas para usuários autenticados que já realizaram pelo menos um questionário | opção ativa | PP: texto claro indicando que o teste será refeito; pode exibir uma confirmação antes de redirecionar | RA: se o usuário desistir no meio do questionário, o perfil atual continua valendo e ele pode voltar à simulação |
| opção "Previsões" | sistema | Redireciona para a tela de gráficos de previsão das ações recomendadas (24 meses) | navegação | Só faz sentido após existir ao menos uma simulação com recomendação da IA | opção ativa | PP: caso não exista simulação válida, exibir mensagem orientando a simular antes de acessar as previsões | RA: após realizar uma simulação, o acesso passa a mostrar normalmente os gráficos das ações recomendadas |
| opção "Histórico" | sistema | Abre a tela com o histórico das simulações ou resultados já realizados na plataforma (quando implementado) | navegação | Exibe apenas dados do próprio usuário autenticado | opção ativa (ou desabilitada, se ainda não implementado) | PP: indicar claramente se o recurso está disponível ou em desenvolvimento, para não gerar confusão | RA: em caso de erro ao carregar o histórico, exibir mensagem e oferecer opção de tentar novamente |
| opção "Sair" | sistema | Encerra a sessão do usuário e retorna para a tela de login da plataforma | controle de ação | Disponível apenas para usuário autenticado | opção ativa | PP: pode exibir confirmação rápida ("Deseja realmente sair?") para evitar clique acidental | RA: após sair, permitir novo login normalmente; caso seja clicado por engano, o usuário pode entrar novamente com suas credenciais |

4f) **Esquema conceitual de signos: Histórico de cotações**

| signo | origem | observações | tipo de conteúdo | restrições sobre o conteúdo | valor default | prevenção | recuperação |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| título "Histórico de Cotações" | sistema | Cabeçalho da página que indica que o usuário está na área de histórico de preços das ações | texto informativo | Exibido apenas para usuários autenticados que acessaram a opção Histórico pelo menu | título visível | PP: ajuda o usuário a entender rapidamente o contexto da tela | RA: ao voltar de outra página, o título reforça que ele retornou ao histórico |
| seletor "Selecione a ação para ver o histórico" | sistema | Campo de seleção com a lista de todas as ações disponíveis (ABEV3, B3SA3, BBAS3, BBDC4, ELET3, ITUB4, SBSP3, VALE3) | interação de usuário (lista suspensa) | Apenas ações cadastradas podem aparecer na lista; uma ação deve estar selecionada para exibir o gráfico | primeira ação da lista selecionada ou placeholder | PP: placeholder ou texto explicativo deixando claro que é necessário escolher uma ação | RA: se o usuário trocar de ação, o sistema atualiza o gráfico sem perder o contexto da página |
| gráfico de histórico de cotações | sistema | Exibe o comportamento da ação selecionada ao longo do tempo, com as curvas traçadas em função de Data x Valor | visualização de dados (gráfico) | Depende de uma ação válida selecionada; só exibe dados para papéis suportados | não exibido antes da seleção | PP: eixos bem identificados (Data e Valor) e atualização automática ao mudar a ação | RA: em caso de falha no carregamento dos dados, exibir mensagem de erro e permitir tentar novamente ou escolher outra ação |
| legenda do gráfico (Abertura / Fechamento) | sistema | Indica quais cores/linhas representam os valores de Abertura e de Fechamento da ação | texto/ícone de apoio visual | Deve estar sempre visível quando o gráfico estiver sendo exibido | legenda visível | PP: uso de cores e rótulos claros para diferenciar Abertura e Fechamento e evitar interpretações erradas | RA: se a legenda falhar, manter a distinção por rótulos próximos às linhas ou reapresentar o gráfico com a legenda corrigida |


4g) **Esquema conceitual de signos: Gráficos de acurácia das previsões**

| signo | origem | observações | tipo de conteúdo | restrições sobre o conteúdo | valor default | prevenção | recuperação |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| título "Gráficos de Acurácia das Previsões" | sistema | Cabeçalho da página que indica que o usuário está comparando o modelo de previsão com os valores reais | texto informativo | Exibido apenas para usuários autenticados que acessaram a opção de previsões pelo menu | título visível | PP: ajuda o usuário a entender que o foco é avaliar a acurácia do modelo, não simular investimentos | RA: ao voltar de outra página, o título reforça que ele retornou à tela de previsões |
| seletor "Selecione a ação para comparar o modelo" | sistema | Campo de seleção com a lista de ações disponíveis para análise da acurácia (ex.: ABEV3, B3SA3, BBAS3 etc.) | interação de usuário (lista suspensa) | Apenas ações suportadas pelo modelo podem aparecer na lista; uma ação deve estar selecionada para exibir o gráfico | primeira ação da lista selecionada ou placeholder | PP: texto explicando que é necessário escolher uma ação para ver o gráfico | RA: ao trocar de ação, o gráfico é atualizado mantendo o contexto da página |
| gráfico de acurácia (Valor Predito x Valor Real) | sistema | Exibe duas curvas ao longo do tempo, comparando o valor predito pelo modelo e o valor real da ação | visualização de dados (gráfico) | Depende de uma ação válida selecionada; só exibe dados para papéis suportados | não exibido antes da seleção | PP: eixos e legenda claramente identificados (“Valor Predito”, “Valor Real”) e atualização automática ao mudar a ação | RA: em caso de falha no carregamento dos dados, exibir mensagem de erro e permitir tentar novamente ou escolher outra ação |
| legenda do gráfico | sistema | Indica quais cores/linhas representam o Valor Predito e o Valor Real | texto/ícone de apoio visual | Deve estar sempre presente quando o gráfico for exibido | legenda visível | PP: uso de cores bem contrastantes para facilitar a distinção entre predito e real | RA: se a legenda falhar ou não puder ser carregada, manter a distinção por rótulos diretos nas linhas do gráfico |



<!--
Exemplo: (fazer a junção das 3 tabelas abaixo em uma única)

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |
| :---- | :---- | :---- |
| **signo** | **origem** | **observações** |
| usuário | domínio |  |
| senha | domínio |  |

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |  |
| :---- | :---- | :---- | :---- |
| **signo** | **Tipo de conteúdo** | **restrição sobre conteúdo** | **valor default** |
| usuário | texto | não pode ser nulo | — |
| senha | texto | não pode ser nulo | — |

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |
| :---- | :---- | :---- |
| **signo** | **prevenção** | **recuperação** |
| usuário | PP: campo obrigatório | RA |
| senha | PP campo obrigatório  | RA |
-->
# **Entrega 10 (data) \[em andamento/concluído\]**

**\[1 solução completa por pessoa da equipe\]**

**MOLIC**

**Nome do Cenário:**  
**Diagrama: Cadastrar na Plataforma**
![MOLIC Cadastrar](https://github.com/user-attachments/assets/11a8caae-2717-4d03-998d-ec81fc6256fe)

**Diagrama: Logar na Plataforma**

![MOLIC Logar](https://github.com/user-attachments/assets/b611f194-c612-49a0-8932-e1cf873b4d36)

**Diagrama: Questionário**

![MOLIC Questionário](https://github.com/user-attachments/assets/84da4efd-55f9-462a-ab63-a5ef633e0595)

**Diagrama: Simular Investimento**

![MOLIC Simular](https://github.com/user-attachments/assets/b256cf25-6d48-4657-a7a2-20682aa93405)

**Diagrama: Menu Refazer Teste**

![MOLIC Refazer](https://github.com/user-attachments/assets/5c2a9a63-e878-40da-a975-eb64a4b678bf)

**Diagrama: Menu Histórico**

![MOLIC Historico](https://github.com/user-attachments/assets/e369b4d1-231c-4baa-bdf7-6017a886c9fd)

**Diagrama: Menu Previsão**

![MOLIC Previsao](https://github.com/user-attachments/assets/0ea2d18c-bfd6-4e98-8237-bf95fcb41d36)

# **Entrega 11 (data) \[em andamento/concluído\]**

**\[1 solução completa por pessoa da equipe\]**

# 

**Protótipo Correspondente ao MOLIC**  
**Link para o FIGMA:**

## Página de Cadastro
![Página de Cadastro](https://github.com/user-attachments/assets/ae798937-e948-45a1-a3c3-bed8bfb8616a)


## Página de Login
![Página de Login](https://github.com/user-attachments/assets/16ebb668-5335-4668-bc1e-6cb65408b017)

## Políticas
![Políticas da Empresa](https://github.com/user-attachments/assets/bd06ae5e-29ba-4a0e-ba09-226f17c54fa3)
![Políticas de Privacidade](https://github.com/user-attachments/assets/68c7d345-6b4f-4f02-9a80-9a586041f880)


## Questionário de Suitability
![Questionário de Suitability 01](https://github.com/user-attachments/assets/01e3cb8e-e582-485d-9f6e-15d0b52408fa)
![Questionário de Suitability 02](https://github.com/user-attachments/assets/12afc1ee-1f2b-4e27-9d27-340721e2f580)
![Questionário de Suitability 03](https://github.com/user-attachments/assets/b74a9651-aa7b-4a05-88b0-dae058ac6515)


## Simulação de Ações
![Simulação de Ações 01](https://github.com/user-attachments/assets/ea18e458-b394-4864-a650-171fc0412f83)
![Simulação de Ações 02](https://github.com/user-attachments/assets/bf653ce8-79f1-45ca-99ac-d16558c551c9)


## Gráfico de Previsões
![Gráfico de Previsões](https://github.com/user-attachments/assets/ee725d4d-8d5a-41c1-92c6-65edb37d7ff4)


## Gráfico do Histórico
![Gráfico do Histórico](https://github.com/user-attachments/assets/9b1ca156-a56b-4507-b8bb-c49445389a76)



# **Entrega 12 (data) \[em andamento/concluído\]**

**\[1 solução por equipe\]**

# 

1) **Planejamento de Usabilidade (método DECIDE)**

| D | Avaliar se a plataforma InvestMind ofere uma experiência de uso clara, acessível e eficiente para os três perfis de investidores: investidor iniciante familiarizado com tecnologia, investidor iniciante conservador com dificuldades de acessibilidade e investidor experiente e agressivo|
| :---: | :---- |
| **E** | Na dimensão de **analisar a apropriação da tecnologia**, a avaliação buscará entender se, após usar o InvestMind, o investidor passa a confiar mais nas recomendações da IA do que nas próprias escolhas, se a plataforma realmente o ajuda a decidir onde aplicar o dinheiro com segurança e se o apoio computacional é adequado ao seu perfil (idade, experiência digital e conhecimento financeiro). Para usuários mais experientes, será verificado se a solução torna mais eficiente a identificação de oportunidades e a tomada de decisão.<br> Na dimensão de **identificar problemas na interação e na interface**, a avaliação investigará quais falhas de navegação e feedback (falta de mensagens claras, carregamentos confusos, ausência de confirmações) dificultam a conclusão das tarefas. Também será observado se o usuário entende o que fazer em cada etapa do fluxo e em quais pontos dos dashboards sente maior frustração, seja por falta de clareza, seja por excesso de informações redundantes.  |
| **C** | Na avaliação heurística, a equipe inspecionará as telas-chave do InvestMind (cadastro, questionário, simulação, dashboards) de acordo com as heurísticas de usabilidade e acessibilidade de Nielsen, identificando problemas de linguagem, navegação, feedback e clareza na apresentação de risco e retorno das ações. <br> Em seguida, serão realizados testes com usuários, com participantes que representem diferentes perfis de investidor. Eles executarão tarefas típicas na plataforma enquanto são observados e convidados a relatar suas percepções. Serão coletados dados de sucesso nas tarefas, tempo, dúvidas e grau de confiança nas recomendações, permitindo verificar, na prática, como os investidores se apropriam da tecnologia e quais problemas de interação e interface mais impactam a experiência.|
| **I** | A avaliação de usabilidade do InvestMind será organizada da seguinte forma: primeiro, definem-se as telas e fluxos a serem analisados (cadastro/login, questionário, simulação/recomendação). Em seguida, a equipe realiza uma avaliação heurística nessas telas, registrando problemas de usabilidade e acessibilidade. Paralelamente, são preparados o roteiro e os materiais dos testes com usuários e recrutados até 10 participantes com perfis de investidor distintos. Por fim, os testes são aplicados individualmente, observando a execução das tarefas e registrando dificuldades, erros, tempos e percepções, para que todos os dados sejam posteriormente consolidados e analisados. |
| **D** | A avaliação de usabilidade do InvestMind respeita a privacidade e a integridade dos participantes. Como a plataforma envolve respostas de questionários de perfil comportamental e dados pessoais (como nome, idade e CPF), deve-se deixar claro, antes do teste, que a participação é voluntária, que o usuário pode desistir a qualquer momento e que as informações serão usadas apenas para fins acadêmicos. Também é importante esclarecer que o foco do estudo é avaliar a usabilidade do sistema, e não julgar o conhecimento financeiro ou a capacidade dos participantes, evitando qualquer situação de constrangimento. |
| **E** | Os dados da avaliação heurística e dos testes com usuários serão organizados e analisados em conjunto. Serão identificados os principais problemas de usabilidade e acessibilidade, bem como evidências de apropriação (ou não) da tecnologia pelos investidores. |

2) Lista de Instrumentos (exemplos \- dica… tudo pronto por atividades anteriores ou compartilhado pelo professor)  
   1) Termo de consentimento  

	**TÍTULO DO ESTUDO:** Avaliação de Usabilidade da Plataforma InvestMind  
	**INSTITUIÇÃO:** ____________________________________________  
	**PESQUISADOR(A) RESPONSÁVEL:** __________________  **CONTATO:** _____________________  
	**PARTICIPANTE:** __________________________________  **Data:** ____ / ____ / ______ **ID:** _______
	
	---
	
	## 1. Objetivo do estudo
	Você está sendo convidado(a) a participar de um estudo de **avaliação de usabilidade** da plataforma InvestMind. O objetivo é compreender a **clareza, facilidade de uso e acessibilidade** das telas (cadastro/login, questionário de perfil, simulação de investimentos e dashboards preditivos) para orientar melhorias no sistema.
	
	## 2. Procedimentos
	A sessão durará aproximadamente ____ minutos. Você realizará tarefas típicas (ex.: criar conta, responder questionário de perfil, montar uma simulação e interpretar resultados) e poderá ser convidado(a) a **pensar em voz alta** enquanto usa a plataforma. Com sua permissão, poderemos **gravar a tela/áudio/vídeo** para fins de análise posterior.
	
	## 3. Riscos e desconfortos
	Os riscos são mínimos, relacionados a possível cansaço ou desconforto ao usar computador/celular. Você pode **interromper** a participação a qualquer momento, sem qualquer penalidade.
	
	## 4. Benefícios esperados
	Embora não haja benefício financeiro direto, sua participação contribuirá para **melhorias de usabilidade e acessibilidade** do InvestMind e para fins **acadêmicos**.
	
	## 5. Privacidade, confidencialidade e LGPD
	- Suas informações serão tratadas conforme a **Lei Geral de Proteção de Dados (LGPD)**.  
	- Os registros serão **anonimizados** (identificação por código) e utilizados **apenas para fins acadêmicos**.  
	- Sempre que possível, serão utilizados **dados fictícios** (ex.: CPF simulado). **Não forneça senhas nem informações bancárias reais.**  
	- Os dados ficarão armazenados com **acesso restrito** à equipe por até ____ meses e, após esse período, serão **descartados** de maneira segura.
	
	## 6. Voluntariedade e desistência
	Sua participação é **voluntária**. Você pode recusar-se a participar ou sair a qualquer momento, sem justificativa e sem qualquer prejuízo.
	
	## 7. Consentimentos
	**Autoriza a gravação de tela/áudio/vídeo para fins acadêmicos deste estudo?**  
	- [ ] SIM  
	- [ ] NÃO
	
	**Caso SIM, autoriza o uso de trechos anonimizados (sem identificação pessoal) em relatórios acadêmicos e apresentações de sala?**  
	- [ ] SIM  
	- [ ] NÃO
	
	## 8. Esclarecimentos e dúvidas
	Você poderá solicitar esclarecimentos antes, durante ou após a sessão pelos contatos acima.
	
	---
	
	### Declarações e assinaturas
	
	**Participante**  
	**Nome completo:** __________________________________________  
	**Documento (RG/CPF)\***: ____________________________________  
	\*Preferencialmente, utilizar **CPF simulado** fornecido pela equipe.  
	**Assinatura:** ______________________________________________  
	**Data:** ____ / ____ / ______
	
	**Responsável pela coleta**  
	**Nome:** ___________________________________________________  
	**Assinatura:** ______________________________________________  
	**Data:** ____ / ____ / ______





   2) Questionários  

	## 1) Qual é a sua faixa etária?
	- [ ] Menos que 18
	- [ ] Entre 18 e 30
	- [ ] Entre 31 e 45
	- [ ] Entre 46 e 60
	- [ ] Mais que 60

	## 2) Qual é o seu nível de escolaridade?
	- [ ] Ensino Fundamental
	- [ ] Ensino Médio
	- [ ] Superior em andamento
	- [ ] Superior completo
	- [ ] Pós-graduação
	
	## 3) Qual é a sua ocupação?
	- [ ] Estudante
	- [ ] CLT
	- [ ] Autônomo/MEI
	- [ ] Empresário(a)
	- [ ] Desempregado(a)
	- [ ] Aposentado(a)
	- [ ] Prefiro não informar
	
	## 4) Qual dispositivo você mais usa para acessar suas finanças?
	- [ ] Celular
	- [ ] Computador
	- [ ] Tablet
	- [ ] Outro
	
	## 5) Em uma escala de 1 a 5, como você avalia seu nível de habilidade em aplicativos de investimento?
	- [ ] 1 (Iniciante)
	- [ ] 2
	- [ ] 3
	- [ ] 4
	- [ ] 5 (Avançado)
	
	## 6) Com que frequência você usa apps de investimento?
	- [ ] Várias vezes ao dia
	- [ ] Diariamente
	- [ ] Semanalmente
	- [ ] Mensalmente
	- [ ] Quase nunca
	- [ ] Nunca usei
	
	## 7) Qual é o seu nível de conhecimento em investimentos?
	- [ ] Nenhum
	- [ ] Básico
	- [ ] Intermediário
	- [ ] Avançado
	
	## 8) Há quanto tempo você investe?
	- [ ] Nunca investi
	- [ ] Menos de 6 meses
	- [ ] Entre 6 e 24 meses
	- [ ] Entre 2 e 5 anos
	- [ ] Mais de 5 anos
	
	## 9) Qual é o seu objetivo principal ao investir?
	- [ ] Reserva de emergência
	- [ ] Renda extra
	- [ ] Aposentadoria
	- [ ] Grande compra
	- [ ] Aprendizado
	- [ ] Outro: __________________________
	
	## 10) Qual é o seu horizonte de investimento?
	- [ ] Curto (até 1 ano)
	- [ ] Médio (1–5 anos)
	- [ ] Longo (> 5 anos)
	- [ ] Não sei
  
   3) Tabela de Observação:

	  Escopo das tarefas e gatilhos temporais (Start/Stop)
      | Tarefa | Módulo | Objetivo | Start (início) | Stop (fim) |
      | ----- | ----- | ----- | ----- | ----- |
      | T1 | Cadastro | Criar uma conta para acessar a plataforma | Abrir a plataforma e clicar em "Cadastrar" | Conta criada e dados salvos no sistema |
      | T2 | Login | Poder acessar a plataforma | Abrir a plataforma | Acesso a plataforma |
      | T3 | Questionário | Ter seu perfil de investidor identificado | Ter realizado o login | Perfil identificado de acordo com sua pontuação |
      | T4 | Gráfico dos Históricos das Ações | Visualizar as cotações antigas de cada ativo | Abrir a opção de "Menu", clicar em "Histórico" e selecionar a ação que deseja visualizar | Cotações antigas da ação selecionada |
	  | T5 | Simulação / Recomendação de Ações | Receber recomendações de ações de acordo com o seu perfil de investidor identificado | Abrir a opção de "Menu", clicar em "Voltar à Home" e fazer uma simulação de investimentos | Recomendação de 3 ações de acordo com o seu perfil de investidor |
      | T6 | Gráfico das Previsões das Ações | Visualizar as previsões de cada ativo para o intervalo de 2 anos | Abrir a opção de "Menu", clicar em "Previsões" e selecionar a ação que deseja visualizar | Previsão da ação selecionada |

   4) Formulário de avaliação Heuristica.

	## Cadastro/Login
	| Heurística | Check (o que validar) | Evidência (print/passos) | Sev. | Recomendação |
	| ----- | ----- | ----- | ----- | ----- |
	| H1 Visibilidade | Feedback claro ao criar conta/login (loading, erros, sucesso) |  |  | Exibir alerta de “Conta criada/Erro” |
	| H2 Compatibilidade | Linguagem simples em campos/erros (sem jargão técnico) |  |  | Padronizar microcópias (“Senha muito curta. Use 8+ caracteres”) |
	| H3 Controle/Liberdade | Usuário pode refazer o seu questionário quando quiser |  |  | Disponibilizar opção para refazer questionário |
	| H5 Prevenção de erros | Regras de senha, confirmação e-mail, mensagens preventivas |  |  | Erro inline no campo + dica de correção |
	| H8 Minimalista | Formulário com apenas campos essenciais |  |  | Remover campos não obrigatórios |
	    
		
	## Questionário de Perfil (Suitability)
	| Heurística | Check | Evidência | Sev. | Recomendação |
	| ----- | ----- | ----- | ----- | ----- |
    | H1 | Visibilidade |  |  | Exibir alerta de questionário criado junto a pontuação e perfil de investidor |
	| H2 Compatibilidade | Perguntas claras, simples e objetivas |  |  | Exibir perguntas do dia a dia com linguagem simples |
	| H7 Eficiência | Progresso visível e salvar rascunho |  |  | Barra de progresso + “Continuar depois”. |
	| H8 Minimalista | Sem excesso de texto; layout limpo |  |  | Perguntas com textos curtos sem enrolação |
	| H9 Auxiliar | Deixar claro caso o usuário não tenha respondido todas as questões |  |  | Alerta de erro para a pergunta que ainda não foi respondida em caso de tentativa de envio do questionário |
		
	## Simulação de Investimento
	| Heurística | Check | Evidência | Sev. | Recomendação |
	| ----- | ----- | ----- | ----- | ----- |
	| H1 Visibilidade | Estado claro ao simular (processando/sucesso/erro) |  |  | Mensagens de erro em caso de problemas |
	| H4 Consistência | Padrões de botões/inputs iguais às outras telas |  |  | Usar um mesmo padrão de letrar, botões e cores |
	| H5 Prevenção de erros | Validar orçamento, percentuais, limites |  |  | Colocar mensagens preventivas para evitar erros |
	| H8 Minimalista | Sem excesso de opções e textos |  |  | Colocar apenas o essencial para que o usuário faça sua simulação e receba sua recomendação |
	| H9 Auxiliar | Deixar claro possíveis erros que possam acontecer com a simulação |  |  | Detalhar bem os erros que o usuário teve para simular seu investimento |
		
	## Gráficos de Históricos e Previsões
	| Heurística | Check | Evidência | Sev. | Recomendação |
	| ----- | ----- | ----- | ----- | ----- |
    | H1 Visibilidade | Ao selecionar uma ação para ver o gráfico, o sistema dá feedback imediato |  |  | Ter um tempo de resposta < 0.1 seg após o usuário selecionar a ação que deseja visualizar o gráfico |
	| H2 Compatibilidade | uso de termos compreensíveis |  |  | Deixar explicações claras e objetivas em caso de uso de termos financeiros |
	| H3 Controle/Liberdade | Usuários podem visualizar a hora que quiserem os gráficos |  |  | Deixar a opção de visualização dos gráficos sempre ativa no Menu de opções |
	| H4 Consistência | Utilizar o mesmo padrão para todos os gráficos |  |  | Escolher as mesmas fontes, cores e tamanhos |
	| H8 Minimalista | Evitar redundância com foco no essencial |  |  | Mostrar apenas as informações essenciais nos gráficos |


# **Entrega 13 (data) \[em andamento/concluído\]**

DICA: MATERIAL ABAIXO DISPONÍVEL EM ARQUIVO NO MOODLE.

1) **Avaliação de IHC através de inspeção HEURÍSTICA \[1 solução completa por pessoa da equipe \- todas as telas do projeto\]**

**DICA: SOMENTE VIOLAÇÕES**

Dez Heurísticas de Nielsen

**Descrição da avaliação**

Avaliação heurística, definida por Nielsen e Molich (1994), é um método de avaliação de usabilidade onde um avaliador procura problemas de usabilidade numa interface com o usuário através da análise e interpretação de um conjunto de princípios ou heurísticas. Este método de avaliação é baseado no julgamento do avaliador.

1\. Primeiramente, leia e analise as dez heurísticas (ver Tabela 1).

**Tabela 1 \- Conjunto de heurísticas de Nielsen (1994)**

| 1\. | Visibilidade do status do sistema: |
| :---- | :---- |
| O sistema deve sempre manter os usuários informados sobre o que está acontecendo através de feedback apropriado, em um tempo razoável. |  |
| **2\.** | **Compatibilidade entre sistema e mundo real:** |
| O sistema deve utilizar a linguagem do usuário, com palavras, frases e conceitos familiares para ele, ao invés de termos específicos de sistemas. Seguir convenções do mundo real, fazendo com que a informação apareça em uma ordem lógica e natural. |  |
| **3\.** | **Controle e liberdade para o usuário:** |
| Estão relacionados à situação em que os usuários frequentemente escolhem as funções do sistema por engano e então necessitam de "uma saída de emergência” claramente definida para sair do estado não desejado sem ter que percorrer um longo diálogo, ou seja, é necessário suporte a *undo* e *redo*. |  |
| **4\.** | **Consistência e padrões:** |
| Referem-se ao fato de que os usuários não deveriam ter acesso a diferentes situações, palavras ou ações representando a mesma coisa. A interface deve ter convenções não-ambíguas. |  |
| **5\.** | **Prevenção de erros:** |
| Os erros são as principais fontes de frustração, ineficiência e ineficácia durante a utilização do sistema. |  |
| **6\.** |  **Reconhecimento em lugar de lembrança:** |
| Tornar objetos, ações, opções visíveis e coerentes. O usuário não deve ter que lembrar informações de uma parte do diálogo para outra. Instruções para o uso do sistema devem estar visíveis ou facilmente acessíveis. |  |
| **7\.** | **Flexibilidade e eficiência de uso:** |
| A ineficiência nas tarefas pode reduzir a eficácia do usuário e causar-lhes frustração. O sistema deve ser adequado tanto para usuários inexperientes quanto para usuários experientes. |  |
| **8\.** | **Projeto minimalista e estético:** |
| Os diálogos não devem conter informações irrelevantes ou raramente necessárias. Cada unidade extra de informação em um diálogo compete com unidades relevantes e diminui sua visibilidade relativa. |  |
| **9\.** | **Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros:** |
| Mensagens de erro devem ser expressas em linguagem natural (sem códigos), indicando precisamente o erro e sugerindo uma solução. |  |
| **10\.** | **Ajuda e documentação:** |
| Mesmo que seja melhor que o sistema possa ser usado sem documentação, pode ser necessário fornecer ajuda e documentação. Tais informações devem ser fáceis de encontrar, ser centradas na tarefa do usuário, listar passos concretos a serem seguidos e não ser muito grandes. A ajuda deve estar facilmente acessível e on-line. |  |

	2\. A seguir, avalie o sistema procurando possíveis problemas de usabilidade.   
3\. Quando um problema qualquer for detectado, classifique-o em uma das dez heurísticas de Nielsen, anotando o problema na tabela correspondente e atribuindo o **grau de severidade** (0 até 4\) para este problema (dado pela tabela 2\) e recomece novamente até não encontrar mais problemas de usabilidade.

**Tabela 2 \- Grau de severidade dos problemas de usabilidade**

| Grau de severidade | Tipo | Descrição |
| ----- | :---- | :---- |
| 0 | Sem importância | Não afeta a operação da interface |
| 1 | Cosmético | Não há necessidade imediata de solução |
| 2 | Simples | Problema de baixa prioridade (pode ser reparado) |
| 3 | Grave | Problema de alta prioridade (deve ser reparado) |
| 4 | Catastrófico | Muito grave, deve ser reparado de qualquer forma. |

## Avaliação Heurística - **Felipe**

### 1. Visibilidade do status do sistema
**Verificação:** Os usuários são mantidos informados sobre o progresso do sistema com apropriado feedback em um tempo razoável?

**Problema:** Após concluir o questionário de perfil de investidor, o sistema muda de tela diretamente para a página de simulação sem mostrar uma mensagem de confirmação, podendo gerar dúvidas ao usuário se suas respostas foram realmente salvas.

**Grau de Severidade:** Simples - 2

**Print da tela:** Não há print de tela específico

### 2. Compatibilidade entre o sistema e o mundo real
**Verificação:** O sistema utiliza conceitos e linguagem familiar com o usuário em vez de termos orientados ao sistema? <br>
O sistema utiliza convenções do mundo real, exibindo informações com uma ordem lógica e natural?

**Problema:** Na lista de ações recomendadas, os ativos são exibidos apenas pelo ticker (ex: SBSP3), sem o nome da empresa por extenso junto à ação, causando dificuldades para usuários com pouca familiaridade com o mercado acionário.

**Grau de severidade:** Simples - 2

**Print da tela:** <br>![](https://github.com/user-attachments/assets/5617e7f8-3274-4884-ab74-6ec5c82e29db)

### 3. Liberdade e controle do usuário
**Verificação:** Os usuários podem fazer o que querem quando querem?

**Problema:** Na tela de ‘Refazer Questionário de Suitability’, não é existem botões de ‘Voltar’ a tela inicial, obrigando o usuário a responder o questionário novamente.

**Grau de Severidade:** Grave - 3

**Print da tela:** <br>![](https://github.com/user-attachments/assets/114dbd33-de03-4dfe-96df-366d98b98db6)

### 4. Consistência e padrões
**Verificação:** O projeto de elementos como objetos e ações tem o mesmo significado ou efeito em diferentes situações?

**Problema:** Na tela de resultados da simulação, os símbolos de ganho e perda não seguem um padrão. Valores positivos usam + R$ 100,00, enquanto negativos usam R$ -100,00, com o sinal em posições diferentes, o que prejudica a leitura rápida dos resultados.

**Grau de Severidade:** Sem importância - 0

**Print da tela:** <br>![](https://github.com/user-attachments/assets/1ef598bd-bc29-4b89-b82a-2f4b6b5bf138)

### 5. Prevenção contra erros
**Verificação:** Os usuários podem cometer erros dos quais bons projetos poderiam prevenir?

**Problema:** Os campos de valor a investir aceitam números incoerentes (como zero ou negativos) sem validação clara, o que poderia ser prevenido com restrição de entrada e mensagens de orientação.

**Grau de Severidade:** Simples - 2

**Print da tela:** <br>![](https://github.com/user-attachments/assets/078509f7-62c5-4536-9fa2-9971cc82deff)

### 6. Reconhecimento em lugar de lembrança
**Verificação:** Os elementos de projeto como objetos, ações e opções são possíveis? <br>
O usuário é forçado a relembrar informações de uma parte do sistema para outra?

**Problema:** Ao selecionar ações e valores para simular e navegar para Histórico de Cotações ou Acurácia das Previsões, as escolhas são apagadas ao voltar. O usuário precisa lembrar tudo e reconfigurar o portfólio do zero, aumentando a carga de memória.

**Grau de Severidade:** Grave - 3

**Print da tela:** Não há print de tela específico

### 7. Flexibilidade e eficiência de uso
**Verificação:** As tarefas de usuário são eficientes e podem se adaptar ao gosto do usuário em suas ações mais freqüentes ou ele utiliza atalhos?

**Problema:** Para comparar diferentes cenários de investimento, o usuário precisa recriar todo o portfólio do zero (ações e valores) a cada nova simulação, sem opção de reaproveitar ou duplicar uma configuração anterior, o que reduz a eficiência de uso.

**Grau de Severidade:** Sem importância - 0

**Print da tela:** Não há print de tela específico

### 8. Projeto minimalista e estético
**Verificação:** Os diálogos contém informações irrelevantes ou raramente necessárias?

**Problema:** Não foi encontrado nenhum diálogo com informações irrelevantes ou raramente necessárias.

**Grau de Severidade:** - ![]()

**Print da tela:** Não há print de tela específico

### 9. Auxiliar os usuários a reconhecer, diagnosticar e recuperar-se de erros
**Verificação:** As mensagens de erro são expressas em linguagem simples (sem códigos) descrevendo exatamente o problema e sugerindo uma solução?

**Problema:** Na página de cadastro, quando a senha e a confirmação de senha não coincidem, o botão “Cadastrar” fica desabilitado, mas nenhuma mensagem de erro é exibida. O usuário não sabe qual é o problema nem o que precisa ajustar para prosseguir.

**Grau de Severidade:** Simples - 2

**Print da tela:** <br>![](https://github.com/user-attachments/assets/1ce3fed2-e417-4c00-b394-6a40b88b0bdf)

### 10. Ajuda e documentação
**Verificação:** São fornecidas apropriadas informações de ajuda, e estas informações são fáceis de procurar e de focalizar nas tarefas do usuário?

**Problema:** A aplicação não possui uma seção de ajuda ou FAQ acessível a partir das telas principais. Quando o usuário tem dúvidas sobre como usar a simulação ou interpretar os resultados, precisa descobrir sozinho, sem apoio direto do sistema.

**Grau de Severidade:** Grave - 3

**Print da tela:** Não há print de tela específico


## Avaliação Heurística - **João**

### 1. Visibilidade do status do sistema
**Verificação:** Os usuários são mantidos informados sobre o progresso do sistema com apropriado feedback em um tempo razoável?

**Problema:** Ao realizar o questionário não aparece nenhuma informação logo de cara alertando o usuário sua pontuação e perfil de investidor.

**Grau de Severidade:** Simples - 2

**Print da tela:** Não há print de tela específico

### 2. Compatibilidade entre o sistema e o mundo real
**Verificação:** O sistema utiliza conceitos e linguagem familiar com o usuário em vez de termos orientados ao sistema? <br>
O sistema utiliza convenções do mundo real, exibindo informações com uma ordem lógica e natural?

**Problema:** Nos menus de Histórico das ações e de Previsão das ações, o nome das ações não fica com o nome completo da empresa por completo, apenas com o ticker.

**Grau de severidade:** Simples - 2

**Print da tela:** <br>![](https://github.com/user-attachments/assets/459fe130-7992-4035-a06e-93365eabca09)<br>![](https://github.com/user-attachments/assets/cb7fbfb3-7bd5-413c-a3ea-bdc1c6dfe4e5)

### 3. Liberdade e controle do usuário
**Verificação:** Os usuários podem fazer o que querem quando querem?

**Problema:** Na aba de simulações não existe um botão para limpar todas as ações escolhidas e fazer uma nova simulação, sendo necessário remover uma a uma.

**Grau de Severidade:** Sem importância - 0

**Print da tela:** <br>![](https://github.com/user-attachments/assets/f7ae9c86-0cc7-4d51-befa-283272c04f75)

### 4. Consistência e padrões
**Verificação:** O projeto de elementos como objetos e ações tem o mesmo significado ou efeito em diferentes situações?

**Problema:** Nos resultados por ação, ganhos e perdas são exibidos com sinal (+/-) e cor, mas nos totais o valor aparece apenas em verde, sem o sinal de ganho, quebrando o padrão de representação dos resultados.

**Grau de Severidade:** Sem importância - 0

**Print da tela:** <br>![](https://github.com/user-attachments/assets/7b5a7a35-4eec-4fd8-929b-a659b3315f8a)

### 5. Prevenção contra erros
**Verificação:** Os usuários podem cometer erros dos quais bons projetos poderiam prevenir?

**Problema:** Na parte de simulações não existe um aviso que informe o usuário de que as recomendações só são feitas depois do usuário escolher no mínimo 3 ações para simular portfólio.

**Grau de Severidade:** Cosmético - 1

**Print da tela:** <br>![](https://github.com/user-attachments/assets/45fd68fb-9258-4535-9be3-82d643f93aca)

### 6. Reconhecimento em lugar de lembrança
**Verificação:** Os elementos de projeto como objetos, ações e opções são possíveis? <br>
O usuário é forçado a relembrar informações de uma parte do sistema para outra?

**Problema:** Ao clicar em “Refazer questionário”, todas as respostas anteriores são apagadas e o formulário é exibido em branco. O usuário não consegue ver o que havia escolhido antes e precisa lembrar e refazer todas as respostas do zero.

**Grau de Severidade:** Grave - 3

**Print da tela:** Não há print de tela específico

### 7. Flexibilidade e eficiência de uso
**Verificação:** As tarefas de usuário são eficientes e podem se adaptar ao gosto do usuário em suas ações mais freqüentes ou ele utiliza atalhos?

**Problema:** Nas telas de Histórico de Cotações e Acurácia das Previsões, o usuário precisa selecionar cada ação no filtro, mesmo quando ela já foi usada na simulação anterior, pois não existe atalho para carregar automaticamente os tickers já utilizados.

**Grau de Severidade:** Sem importância - 0

**Print da tela:** Não há print de tela específico

### 8. Projeto minimalista e estético
**Verificação:** Os diálogos contém informações irrelevantes ou raramente necessárias?

**Problema:** Nada foi encontrado.

**Grau de Severidade:** -

**Print da tela:** Não há print de tela específico

### 9. Auxiliar os usuários a reconhecer, diagnosticar e recuperar-se de erros
**Verificação:** As mensagens de erro são expressas em linguagem simples (sem códigos) descrevendo exatamente o problema e sugerindo uma solução?

**Problema:** Na tela de login, quando o usuário digita e-mail ou senha incorretos, o sistema mostra apenas a mensagem genérica “e-mail ou senha inválidos”. Isso não deixa claro se o problema está no e-mail, na senha ou em ambos, dificultando a correção do erro.

**Grau de Severidade:** Sem importância - 0

**Print da tela:** <br>![](https://github.com/user-attachments/assets/9b3734fc-af53-4675-805d-63b25760a8f4)

### 10. Ajuda e documentação
**Verificação:** São fornecidas apropriadas informações de ajuda, e estas informações são fáceis de procurar e de focalizar nas tarefas do usuário?

**Problema:** Não há documentação integrada explicando conceitos importantes, como perfil de investidor, risco, retorno estimado ou funcionamento da recomendação da IA. Isso dificulta o entendimento das funcionalidades por usuários com pouca experiência em investimentos.

**Grau de Severidade:** Grave - 3

**Print da tela:** Não há print de tela específico


## Avaliação Heurística - **Pedro**

### 1. Visibilidade do status do sistema
**Verificação:** Os usuários são mantidos informados sobre o progresso do sistema com apropriado feedback em um tempo razoável?

**Problema:** Ao criar uma conta o pop-up de ‘cadastro realizado’ aparece na tela por pouquíssimo tempo, podendo não dar tempo do usuário identificar se o cadastro foi realizado com sucesso.

**Grau de Severidade:** Simples - 2

**Print da tela:** Não há print de tela específico

### 2. Compatibilidade entre o sistema e o mundo real
**Verificação:** O sistema utiliza conceitos e linguagem familiar com o usuário em vez de termos orientados ao sistema? <br>
O sistema utiliza convenções do mundo real, exibindo informações com uma ordem lógica e natural?

**Problema:** Tanto nas telas de simulação de ações, quanto nas de previsão e histórico, as ações são identificadas pelos seus respectivos tickers e não pelo nome da empresa.

**Grau de severidade:** Simples - 2

**Print da tela:** <br>![](https://github.com/user-attachments/assets/e5184f9d-be08-4401-9111-3263391b7524)<br>![](https://github.com/user-attachments/assets/5f98f86c-50c6-4508-aa71-c225fc6c5969)

### 3. Liberdade e controle do usuário
**Verificação:** Os usuários podem fazer o que querem quando querem?

**Problema:** Não existe um botão de ‘Voltar’ quando o usuário clica em ‘Refazer Questionário de Suitability’, fazendo com que ele tenha que refazer todo o questionário novamente.

**Grau de Severidade:** Grave - 3

**Print da tela:** <br>![](https://github.com/user-attachments/assets/4fc10dd0-7b48-4688-8d99-46d7edaf2427)

### 4. Consistência e padrões
**Verificação:** O projeto de elementos como objetos e ações tem o mesmo significado ou efeito em diferentes situações?

**Problema:** As telas “Histórico de Cotações” e “Gráficos de Acurácia das Previsões” são muito semelhantes visualmente, mudando quase só o título e a legenda, o que pode gerar dúvida se o usuário está vendo apenas o histórico ou a comparação real × predito.

**Grau de Severidade:** Cosmético

**Print da tela:** <br>![](https://github.com/user-attachments/assets/f529b9c6-4adf-4736-895c-758de17ce01b)<br>![](https://github.com/user-attachments/assets/b7ff71f9-50e4-47e3-a193-c3493ff32316)

### 5. Prevenção contra erros
**Verificação:** Os usuários podem cometer erros dos quais bons projetos poderiam prevenir?

**Problema:** Na área de simulação, o sistema exige que o usuário selecione pelo menos três ações para gerar a recomendação de portfólio, mas não informa esse requisito de forma clara.

**Grau de Severidade:** Simples - 2

**Print da tela:** <br>![](https://github.com/user-attachments/assets/67d09762-6d53-40ff-841e-5cc64879ba08)

### 6. Reconhecimento em lugar de lembrança
**Verificação:** Os elementos de projeto como objetos, ações e opções são possíveis? <br>
O usuário é forçado a relembrar informações de uma parte do sistema para outra?

**Problema:** Ao optar por refazer o questionário, o sistema zera todas as respostas já registradas e apresenta apenas as perguntas em branco. Dessa forma, o usuário perde qualquer referência às escolhas anteriores e precisa recordar e selecionar novamente todas as opções.

**Grau de Severidade:** Grave - 3

**Print da tela:** Não há print de tela específico

### 7. Flexibilidade e eficiência de uso
**Verificação:** As tarefas de usuário são eficientes e podem se adaptar ao gosto do usuário em suas ações mais freqüentes ou ele utiliza atalhos?

**Problema:** Sempre que deseja testar um novo cenário de investimento, o usuário é obrigado a montar novamente o portfólio (escolher ações e preencher valores), pois não existe recurso para copiar ou reutilizar uma simulação anterior, tornando o processo mais demorado e pouco eficiente.

**Grau de Severidade:** Cosmético - 1

**Print da tela:** Não há print de tela específico

### 8. Projeto minimalista e estético
**Verificação:** Os diálogos contém informações irrelevantes ou raramente necessárias?

**Problema:** Não foi encontrado um problema.

**Grau de Severidade:** -

**Print da tela:** Não há print de tela específico

### 9. Auxiliar os usuários a reconhecer, diagnosticar e recuperar-se de erros
**Verificação:** As mensagens de erro são expressas em linguagem simples (sem códigos) descrevendo exatamente o problema e sugerindo uma solução?

**Problema:** Ao errar as credenciais de acesso, a página de login exibe uma única mensagem informando que “o e-mail ou a senha estão incorretos”, sem indicar qual campo está errado. Essa falta de precisão faz o usuário tentar adivinhar o que ajustar, tornando a recuperação do erro menos eficiente.

**Grau de Severidade:** Cosmético - 1

**Print da tela:** <br>![](https://github.com/user-attachments/assets/13cb4224-750a-47b0-8e66-f9fe08ac1197)

### 10. Ajuda e documentação
**Verificação:** São fornecidas apropriadas informações de ajuda, e estas informações são fáceis de procurar e de focalizar nas tarefas do usuário?

**Problema:** A interface não oferece dicas contextuais (como ícones de ajuda ou tooltips) próximas aos campos e gráficos. Em tarefas mais complexas, o usuário não encontra orientações rápidas sobre o que cada elemento significa ou como deve ser preenchido.

**Grau de Severidade:** Simples - 2

**Print da tela:** Não há print de tela específico


2) **INDICAÇÃO DE BOAS PRÁTICAS DE HEURÍSTICA \- HEURÍSTICAS NÃO VIOLADAS \[1 solução completa por pessoa da equipe\]**

Heurísticas não violadas (Pedro):

1) Visibilidade do status do sistema: Ao realizar um novo cadastro na página de cadastro, após a conclusão, há um popup no canto superior da tela, em verde, escrito "cadastro realizado com sucesso".

2) Compatibilidade entre sistema e mundo real: O sistema utiliza convenções utilizadas no mercado para a classificação do perfil de investidor: "Conservador, Moderado ou Agressivo".

3) Controle e liberdade para o usuário: Ao selecionar o menu, o usuário consegue abrir e fechar livremente clicando em qualquer lugar da tela overlay (fundo esmaecido), não restringindo o usuário a necessariamente precisar mudar de fluxo.

4) Consistência e padrões: O cabeçalho (Header) e o menu lateral (Sidebar) são idênticos em design em todas as telas onde estão presentes.

5) Prevenção de erros: Na tela de cadastro, o botão "Cadastrar" só se torna clicável quando o usuário preenche todos os campos obrigatórios, confirma a senha, aceita os termos e é maior de 18 anos.

6) Reconhecimento em lugar de lembrança: O período de simulação selecionado ("6 Meses", "1 Ano", "2 Anos") é mantido visualmente ativo (com fundo azul), para que o usuário saiba qual período está sendo analisado sem ter que se lembrar de sua última seleção.

7) Flexibilidade e eficiência de uso: O menu lateral funciona como um acelerador, permitindo que o usuário "pule" diretamente entre as seções principais (Home, Previsões, Histórico, Sair) sem precisar navegar de forma linear.

8) Projeto minimalista e estético: As páginas de gráficos são extremamente minimalistas, contêm apenas o gráfico plotado e uma box para a escolha da ação para visualização do gráfico, que atualiza assim que clicada.

9) Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros: Quando o usuário excede o orçamento na simulação, a mensagem não é "Erro 502: Limite Excedido". A mensagem é "Atenção: O total excede seu orçamento!". A caixa fica vermelha e o botão é desabilitado, indicando que o usuário deve ajustar seu orçamento ou o valor destinado às ações.

10) Ajuda e documentação: Os campos de entrada de valores (como "Seu Orçamento") usam placeholder (ex: "Ex: 10000") que funciona como uma mini-documentação, guiando o usuário sobre o formato de entrada esperado.

Heurísticas não violadas (João):
1) Visibilidade do status do sistema: Ao realizar uma simulação de investimento, quando é escolhida apenas uma ação, a IA mostra quanto a pessoa teria de lucro/prejuízo e informa que só realiza recomendação se a pessoa selecionar pelo menos 3 ações.

2) Compatibilidade entre sistema e mundo real: O fluxo da realização da simulação segue uma ordem natural: o usuário primeiro define suas entradas (Orçamento e Ações) na coluna da esquerda e depois vê os resultados (Simulações) na coluna da direita.

3) Controle e liberdade para o usuário: O usuário consegue facilmente escolher as ações na ordem que quiser, bem como seu valor de investimento, além de poder excluir ou adicionar uma nova ação para simulação.

4) Consistência e padrões: O design de ambas as interfaces de gráficos, tanto para a previsão da IA quanto para o valor real, são idênticos, assim como a ordem das ações presentes no menu suspenso (dropdown). Ao clicar em alguma, o gráfico já é plotado para a respectiva ação e já é atualizada no menu suspenso a ação selecionada.

5) Prevenção de erros: O sistema impede que o usuário adicione mais de 8 ações, só é possível adicionar uma entrada para cada ação e o sistema não deixa adicionar duplicatas.

6) Reconhecimento em lugar de lembrança: O usuário não precisa lembrar qual é o seu perfil de investidor: na página inicial, é exibido o perfil (ex: "Moderado") e sua descrição completa.

7) Flexibilidade e eficiência de uso: Um usuário experiente pode usar a ferramenta de forma avançada, montando seu próprio portfólio de até 8 ações para testar suas teses de investimento e comparar seu desempenho diretamente contra o modelo da IA.

8) Projeto minimalista e estético: As caixas de resultado (Histórico e IA) e as mensagens de erro (como "Excede seu orçamento") só aparecem após a interação do usuário. A tela inicial é limpa e focada na entrada de dados.

9) Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros: Se a simulação falha (ex: API offline), a caixa de resultado exibe uma mensagem de erro (ex: "Erro na Simulação"), em vez de simplesmente travar a aplicação, permitindo que o usuário tente novamente.

10) Ajuda e documentação: A tela de cadastro (RegisterForm) possui links diretos para as "políticas da empresa" e "políticas de privacidade", fornecendo a documentação completa antes que o usuário aceite os termos.

Heurísticas não violadas (Felipe):
1) Visibilidade do status do sistema: Ao realizar um cadastro e é informado um CPF inexistente, a interface informa em vermelho no canto superior à direita: "CPF inválido".

2) Compatibilidade entre sistema e mundo real: O sistema usa cores de forma intuitiva e padronizada no mundo real: verde para lucros (prefixados com "+") e vermelho para prejuízos (prefixados com "-").

3) Controle e liberdade para o usuário: O usuário não fica apenas restrito a simular uma ação para consultar os gráficos posteriormente, ele pode executar qualquer uma dessas ações na ordem que ele quiser através da interface de menu presente nas páginas, além de poder optar por deslogar da sua conta caso não queira deixar as credenciais salvas na máquina.

4) Consistência e padrões: Enquanto os campos obrigatórios nos formulários (teste de perfil de investidor e cadastro) não são preenchidos, o botão de submissão sempre ficará com a cor cinza, porém, ao preencher todos os campos obrigatórios, ele fica azul.

5) Prevenção de erros: No questionário de suitability, a opção "Nunca investi" é mutuamente exclusiva, impedindo o usuário de selecionar outro tipo de opção de investimento. Caso ele selecione outra opção, a "Nunca investi" é desmarcada e é marcada a última opção que o usuário selecionou, assim como funciona vice-versa.

6) Reconhecimento em lugar de lembrança: Na caixa de "Resultados", o sistema exibe as ações onde o usuário decidiu investir a partir da última simulação realizada, sem que ele tenha que se lembrar de sua última seleção.

7) Flexibilidade e eficiência de uso: Um usuário inexperiente não precisa montar um portfólio complexo. Ele pode simplesmente definir seu orçamento (ex: R$ 1000) e clicar em "Simular Portfólio" com 3 ações quaisquer. A "Recomendação da IA" funcionará como um atalho, fornecendo uma carteira otimizada para ele.

8) Projeto minimalista e estético: A página inicial é dividida em duas colunas com propósitos claros: Ações do Usuário (esquerda) e Resultados do Sistema (direita), e não há informações irrelevantes poluindo a tela.

9) Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros: Se o usuário não seleciona 3 ações, a IA não falha silenciosamente. Ela exibe uma mensagem clara: "É necessário selecionar pelo menos 3 ações distintas para a recomendação da IA."

10) Ajuda e documentação: Na página de cadastro, nos campos de entrada de valores, há placeholders (ex: "Ex: 10000") que funcionam como um mini-guia para o usuário.

**DICA: 1 EXEMPLO DO SEU SISTEMA ONDE A HEURÍSTICA FOI ATENDIDA (ISSO NÃO É USADO NO MERCADO, SERVE APENAS PARA APRENDIZADO)**

# **Entrega 14 [concluído]** - Avaliação de Usabilidade por Observação do Usuário

**\[1 solução completa por pessoa da equipe\]**

**Método de Avaliação de Usabilidade por Observação do Usuário**   
**(o número de usuários observados é igual o número de membros da equipe)**

1) **Fluxograma de Avaliação de Usabilidade por Observação do Usuário \[1 solução por equipe\]**

![fluxograma-avaliacao-usabilidade](https://github.com/user-attachments/assets/24ad2864-b54f-4d90-b7af-296d6e31fda4)

2) **DESCRIÇÃO DO PROCEDIMENTO DE PREPARAÇÃO DO TESTE \[1 solução por equipe\]**

**Passo1:** Definir objetivos, escopo e participantes 
  - Objetivos principais da avaliação:

    - O1. Usuário conseguir acessar o site

    - O2. Usuário realizar uma simulação de investimento com êxito
      
   
  - Escopo da avaliação:

    - Investmind: Cadastro → Login → Simulação

    - Pensamentos e questionamentos do uso de cada interface

    - Métricas coletadas para realização de cada objetivo

  - Participantes (3 usuários observados, 1 por membro da equipe):

    - Usuário 1 (U1) – Estudante Autista 21 anos, e estudante de Ciência da Computação (conforme a persona do Pedro)

    - Usuário 2 (U2) – Aposentado 65 anos

    - Usuário 3 (U3) – Profissional da área da computação, estudante de Análise de Sistemas e 22 anos


**Passo 2: Lista de tarefas que o usuário deve cumprir.**  

  A tarefa é apresentada em linguagem natural, sem mostrar o “caminho de cliques”, para observar o comportamento espontâneo.

  - Tarefa 1 – Acesso a plataforma (T1):
      "Acessar a plataforma Investmind descrevendo todos os pensamentos e dificuldades encontradas "

  - Tarefa 2 – Realização de investimento (T1):
      "Realizar uma simulação de investimendo, descrevendo todos os pensamentos e dificuldades encontradas "

**Passo 3: Formulário de perfil do usuário**  

  ## Formulário de Perfil de perfil do usuário

---


**1.1. Qual o seu nível de experiência com investimentos em ações?**
* Iniciante/Nenhuma
* Básico (Começando agora/Poucas operações)
* Intermediário (Invisto há mais de 1 ano, entendo termos básicos)
* Avançado (Invisto há mais de 5 anos, acompanho o mercado ativamente)

---

**1.2. Qual a sua tolerância a risco?**
* Conservador (Busco máxima segurança, aceito retornos menores)
* Moderado (Busco equilíbrio entre segurança e rentabilidade)
* Agressivo (Aceito grandes riscos por chance de alto retorno)

---

**1.3. Você entende os seguintes conceitos: *Volatilidade*, *Dividend Yield*, *Valuation*?**
* Sim, todos
* Entendo a maioria
* Entendo apenas alguns/Nenhum

---

### 2. Rotina e Ambiente de Uso

**2.1. Quanto tempo, em média, você dedica por semana para estudar o mercado financeiro?**
* Menos de 1h
* 1h - 3h
* Mais de 3h

---

**2.2. Qual dispositivo você mais utiliza para realizar operações e consultas rápidas?**
* Celular/Tablet
* Notebook/Computador de mesa

---

### 3. Usabilidade e Apresentação de Dados

**3.1. Qual fator é mais importante para você na visualização das informações?**
* Clareza/Linguagem Simples, sem termos técnicos (Ex: "Risco: Baixo")
* Detalhamento/Termos técnicos claros e gráficos preditivos avançados

---

**3.2. Qual o tamanho ideal para você da fonte e dos elementos gráficos em um dashboard?**
* Não tenho preferência, o padrão está bom
* Maior/Legível, evitando confusão
* Preciso de recursos de ajuste de tamanho (zoom, redimensionamento)

---

**3.3. Em uma recomendação de compra e venda, o que você mais valoriza?**
* Uma indicação clara de Ponto de Entrada, *Stop* e *Alvo*
* A indicação do potencial de crescimento projetado e a faixa de confiança
* Apenas o nível de risco e o potencial de retorno

---

### 4. Necessidades Específicas e Funcionalidades

**4.1. Qual o seu principal objetivo ao usar uma plataforma de análise?**
* Ganhar dinheiro rápido (Capturar movimentos de mercado)
* Construir uma reserva para o futuro financeiro
* Ter uma fonte de renda passiva e segura para a aposentadoria

---

**4.2. Você precisa integrar dados da plataforma com ferramentas externas (Excel, Google Sheets, API, Home Broker)?**
* Sim, é fundamental para minhas análises
* Talvez, se a plataforma for muito boa
* Não, prefiro fazer tudo na plataforma

---

**4.3. O que você acha mais importante em gráficos preditivos/modelos de IA?**
* A transparência sobre os fatores externos (dólar, commodities, política monetária) que influenciam a previsão
* A precisão da análise temporal e a confiança na indicação do modelo

**Passo 4: Instrumentos de apoio e configuração do ambiente**

  - Instrumentos:

      - Termo de consentimento (versão curta, com objetivo, duração, voluntariedade e uso dos dados).
      
      - Questionário para identificação de perfil (pré-teste).
      
      - Lista de tarefas impressa apenas para o avaliador.
      
      - Planilha de observação (tempo, erros, tipo de erro, ajudas, comentários).
      
      - Questionário pós-teste com:
      
          - SEQ (“Quão fácil foi completar esta tarefa?” – escala 1 a 7) por tarefa.
          
          - SUS simplificado (itens principais de facilidade, complexidade e confiança – escala 1 a 5).
          
          - Perguntas abertas finais (“Onde travou?”, “O que mudaria?”, etc.).

  - Ambientes de teste (cenários simulados):

      - U1 – Ambiente profissional simulado oline (**Pedro**):
      
          - Local: Local residencial e livre de ruídos
          
          - Dispositivo: notebook com interação do designer com base nas decisões escolhidas do usuário
          
          - Foco: tarefa detalhada de cada etapa, cada comportamento observado e cada passo pensado com calma e reflexão do usuário
      
      - U2 – Ambiente profissional simulado (**João**):
      
          - Local: sala tranquila e livre de ruídos
          
          - Dispositivo: computador de trabalho
          
          - Foco: todas as etapas da aplicação
      
      - U3 – Ambiente acadêmico simulado (**Felipe**):
      
          - Local: quarto de casa e livre de ruídos
          
          - Dispositivo: notebook de estudo
    
          - Foco: desde realizar um cadastro até receber uma recomendação de ações com base no perfil de investidor
       
  
**Passo 5: Execução do teste (roteiro operacional)**

  1. Recepção e explicação inicial
  
      - Cumprimentar o participante, explicar que é a interface que está sendo avaliada, não a pessoa.
      
      - Deixar claro que ele(a) pode interromper o teste a qualquer momento, sem prejuízo.
  
  2. Termo de consentimento
  
      - Apresentar o termo de consentimento.
      
      - Tirar dúvidas e registrar seu aceite.
  
  3. Aplicação do formulário de perfil (pré-teste)
  
      - Aplicar um questionário para mapeamento do perfil da pessoa.
  
  4. Explicação das tarefas
  
      - Explicar, em voz alta, apenas o objetivo de cada tarefa, sem demonstrar os passos.
      
      - Solicitar que o participante pense em voz alta durante toda a interação.
  
  5. Execução das tarefas com observação
  
      - Iniciar o cronômetro ao sinal de início da tarefa.
      
      - Registrar:
  
          - Grau de sucesso (Total / Parcial / Falha),
          
          - Tempo para conclusão,
          
          - Erros (tipo: compreensão, navegação, filtro, etc.),
          
          - Necessidade de ajudas (H0 = nenhuma, H1 = dica leve, H2 = intervenção mais forte),
          
          - Comentários relevantes (“insights” espontâneos do participante).
  
      - Não interferir, exceto quando o participante travar por muito tempo.
  
  6. Questionário pós-teste
      
      - Para cada tarefa: registrar a nota SEQ (1–7).
      
      - Aplicar SUS simplificado (escala 1–5 em afirmações do tipo: “Foi fácil usar o sistema”, “Eu me senti confiante usando o sistema”, etc.).
      
      - Fazer 2–4 perguntas abertas sobre dificuldades, pontos positivos e sugestões.
  
  7. Encerramento
  
      - Agradecer a participação.
      
      - Explicar rapidamente como os resultados serão utilizados para melhoria do aplicativo e sobre a matéria de IHC.

3) **RESULTADOS DO TESTE \[1 solução por equipe\]**

**Avaliação de cada Tarefa (para cada usuário)**

#### Usuário 1 – Estudante (U1)

| Tarefa | Grau de Sucesso  | Total de Erros cometidos | Tipos de Erros                                                                 | Tempo Necessário | Grau de Satisfação      |
| ------ | ---------------- | ------------------------ | ------------------------------------------------------------------------------ | ---------------- | ----------------------- |
| **1 – Acesso a plataforma** | **Sucesso Parcial**   | **2**                    | **(1)Inserção de senha incorreta; (1)Inserção de CPF inexistente;**                                                                           | **16 min 43 s** | **Baixa satisfação (3/7)** |
| **2 – Realização de investimento** | **Sucesso Parcial** | **2**                    | **(1) Não entendeu o motivo do questionário; (1) dúvida sobre termos do questionário; (1) Não selecionou ação para simular**              | **18 min 21 s**   | **Baixa satisfação (2/7)** |



**Links dos vídeos: (descrições simuladas)**

  - Vídeo 1 – <url>https://youtu.be/XDlEIVOTheg</url>
    


**Respostas do Formulário do Usuário (Vitor):**

### 1. Perfil e Conhecimento

**1.1. Qual o seu nível de experiência com investimentos em ações?**
* Iniciante/Nenhuma

**1.2. Qual a sua tolerância a risco?**
* Conservador (Busco máxima segurança, aceito retornos menores)

**1.3. Você entende os seguintes conceitos: *Volatilidade*, *Dividend Yield*, *Valuation*?**
* Entendo apenas alguns/Nenhum

---

### 2. Rotina e Ambiente de Uso

**2.1. Quanto tempo, em média, você dedica por semana para estudar o mercado financeiro?**
* Menos de 1h

**2.2. Qual dispositivo você mais utiliza para realizar operações e consultas rápidas?**
* Celular/Tablet

---

### 3. Usabilidade e Apresentação de Dados

**3.1. Qual fator é mais importante para você na visualização das informações?**
* Clareza/Linguagem Simples, sem termos técnicos (Ex: "Risco: Baixo")

**3.2. Qual o tamanho ideal para você da fonte e dos elementos gráficos em um dashboard?**
* Não tenho preferência, o padrão está bom

**3.3. Em uma recomendação de compra e venda, o que você mais valoriza?**
* A indicação do potencial de crescimento projetado e a faixa de confiança

---

### 4. Necessidades Específicas e Funcionalidades

**4.1. Qual o seu principal objetivo ao usar uma plataforma de análise?**
* Construir uma reserva para o futuro financeiro

**4.2. Você precisa integrar dados da plataforma com ferramentas externas (Excel, Google Sheets, API, Home Broker)?**
* Não, prefiro fazer tudo na plataforma

**4.3. O que você acha mais importante em gráficos preditivos/modelos de IA?**
* A precisão da análise temporal e a confiança na indicação do modelo
  

**SEQ por tarefa:**
  
  - T1 Acessar a página: 2/7
    
  - T2 Realizar simulação: 3/7

**SUS por tarefa:**

**Escala de Resposta:**

| Nível | Significado |
| :--- | :--- |
| **1** | Discordo Fortemente |
| **2** | Discordo |
| **3** | Neutro |
| **4** | Concordo |
| **5** | Concordo Fortemente |

| # | Afirmação | 1 | 2 | 3 | 4 | 5 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **1.** | Eu acho que usaria este sistema com frequência. | $\square$ | $\square$ | [x] | $\square$ | $\square$ |
| **2.** | Eu achei o sistema desnecessariamente complexo. | $\square$ | [x]| $\square$ | $\square$ | $\square$ |
| **3.** | Eu achei o sistema fácil de usar. | $\square$ | $\square$ | $\square$ | [x] | $\square$ |
| **4.** | Eu acho que precisaria de suporte técnico para usar este sistema. | [x] | $\square$ | $\square$ | $\square$ | $\square$ |
| **5.** | Eu achei as várias funções neste sistema bem integradas. | $\square$ | $\square$ | $\square$ | [x] | $\square$ |
| **6.** | Eu achei que havia muita inconsistência neste sistema. | [x] | $\square$ | $\square$ | $\square$ | $\square$ |
| **7.** | Eu imagino que a maioria das pessoas aprenderia a usar este sistema rapidamente. | $\square$ | $\square$ | $\square$ | $\square$ | [x] |
| **8.** | Eu achei o sistema muito complicado de usar. | [x] | $\square$ | $\square$ | $\square$ | $\square$ |
| **9.** | Eu me senti muito confiante ao usar o sistema. | $\square$ | $\square$ | [x] | $\square$ | $\square$ |
| **10.** | Eu precisei aprender muitas coisas antes de começar a usar este sistema. | $\square$ | [x] | $\square$ | $\square$ | $\square$ |

---
  
  **Comentário final:**
  
    "Sistema bem feito, intuitivo, facil de ultilizar e ideia de aplicativo interessante"
	
--- 
#### Usuário 2 – Aposentado

| Tarefa | Grau de Sucesso  | Total de Erros cometidos | Tipos de Erros  | Tempo Necessário | Grau de Satisfação |
| ------ | ---------------- | ------------------------ | ------------------------------------------------------------------------------ | ---------------- | ----------------------- |
| **1 – Identificação do perfil de investimento** | **Sucesso** | **0** | - | **4 min 25 s** | **Média satisfação (4/7)** |
| **2 – Realização de investimento** | **Sucesso Parcial** | **1** | Selecionou apenas 1 ação para receber as recomendações ao invés de 3 | **7 min*   | **Alta satisfação (7/7)** |



**Links dos vídeos: (descrições simuladas)**
  - Vídeo 2 - <url>https://www.youtube.com/watch?v=A2ij7HW_Nus</url>

  **Respostas do Formulário do Usuário (João):**

### 1. Perfil e Conhecimento

**1.1. Qual o seu nível de experiência com investimentos em ações?**
* Intermediário

**1.2. Qual a sua tolerância a risco?**
* Conservador (Busco máxima segurança, aceito retornos menores)

**1.3. Você entende os seguintes conceitos: *Volatilidade*, *Dividend Yield*, *Valuation*?**
* Entendo apenas alguns
---

### 2. Rotina e Ambiente de Uso

**2.1. Quanto tempo, em média, você dedica por semana para estudar o mercado financeiro?**
* 2h

**2.2. Qual dispositivo você mais utiliza para realizar operações e consultas rápidas?**
* Computador
  
---
### 3. Usabilidade e Apresentação de Dados

**3.1. Qual fator é mais importante para você na visualização das informações?**
* Clareza/Linguagem Simples na explicação das recomendações

**3.2. Qual o tamanho ideal para você da fonte e dos elementos gráficos em um dashboard?**
* O padrão que está no site é o suficiente

**3.3. Em uma recomendação de compra e venda, o que você mais valoriza?**
* Qual o orçamento necessário para realizar o investimento, qual será o lucro estimado com a venda do ativo e em quanto tempo após a compra será recomendável realizar essa venda?

---

### 4. Necessidades Específicas e Funcionalidades

**4.1. Qual o seu principal objetivo ao usar uma plataforma de análise?**
* Entender, de forma simples e objetiva, quais investimentos são mais seguros, com menor risco e mais adequados ao meu perfil, além de receber orientações claras sobre quando comprar ou vender um ativo sem precisar analisar dados complexos.

**4.2. Você precisa integrar dados da plataforma com ferramentas externas (Excel, Google Sheets, API, Home Broker)?**
* Prefiro realizar tudo isso na plataforma

**4.3. O que você acha mais importante em gráficos preditivos/modelos de IA?**
* Que as informações sejam apresentadas de forma clara, simples e diretamente compreensível, permitindo entender facilmente o que a IA está recomendando fazer.

**SEQ por tarefa:**
  
  - T1 Identificação do perfil de investimento: 7/7
    
  - T2 Realização de investimento: 7/7

**SUS por tarefa:**

**Escala de Resposta:**

| Nível | Significado |
| :--- | :--- |
| **1** | Discordo Fortemente |
| **2** | Discordo |
| **3** | Neutro |
| **4** | Concordo |
| **5** | Concordo Fortemente |

| # | Afirmação | 1 | 2 | 3 | 4 | 5 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **1.** | Eu acho que usaria este sistema com frequência. | $\square$ | $\square$ | [x] | $\square$ | $\square$ |
| **2.** | Eu achei o sistema desnecessariamente complexo. | [x] | $\square$| $\square$ | $\square$ | $\square$ |
| **3.** | Eu achei o sistema fácil de usar. | $\square$ | $\square$ | [x] | $\square$ | $\square$ |
| **4.** | Eu acho que precisaria de suporte técnico para usar este sistema. | $\square$ | $\square$ | [x] | $\square$ | $\square$ |
| **5.** | Eu achei as várias funções neste sistema bem integradas. | $\square$ | $\square$ | $\square$ | [x] | $\square$ |
| **6.** | Eu achei que havia muita inconsistência neste sistema. | [x] | $\square$ | $\square$ | $\square$ | $\square$ |
| **7.** | Eu imagino que a maioria das pessoas aprenderia a usar este sistema rapidamente. | $\square$ | $\square$ | [x] | $\square$ | $\square$ |
| **8.** | Eu achei o sistema muito complicado de usar. | [x] | $\square$ | $\square$ | $\square$ | $\square$ |
| **9.** | Eu me senti muito confiante ao usar o sistema. | $\square$ | $\square$ | [x] | $\square$ | $\square$ |
| **10.** | Eu precisei aprender muitas coisas antes de começar a usar este sistema. | $\square$ | [x] | $\square$ | $\square$ | $\square$ |

---
  
  **Comentário final:**
  
    "Aplicação muito bem desenvolvida. Gostei da ideia de poder simular as ações nas quais tenho interesse e comparar com a recomendação da IA para verificar se teria lucro ou não."

--- 
#### Usuário 3 – Profissional na área da computação

| Tarefa | Grau de Sucesso  | Total de Erros cometidos | Tipos de Erros  | Tempo Necessário | Grau de Satisfação |
| ------ | ---------------- | ------------------------ | ------------------------------------------------------------------------------ | ---------------- | ----------------------- |
| **1 – Identificação do perfil de investimento** | **Sucesso** | **0** | - | **3 min 24 s** | **Média satisfação (7/7)** |
| **2 – Realização de investimento** | **Sucesso Parcial** | **2** | **(1) Tentou simular um investimento sem colocar orçamento; (2) Tentou receber a recomendação de ações fazendo a simulação com apenas 1 ação ao invés de 3** | **7 min 14s** | **Alta satisfação (3/7)** |

**Links dos vídeos: (descrições simuladas)**
  - Vídeo 2 - <url>https://www.youtube.com/watch?v=tm3_jO07X3g

  **Respostas do Formulário do Usuário (Felipe):**

### 1. Perfil e Conhecimento

**1.1. Qual o seu nível de experiência com investimentos em ações?**
* Intermediário

**1.2. Qual a sua tolerância a risco?**
* Conservador (Buscando segurança acima de retorno)

**1.3. Você entende os seguintes conceitos: *Volatilidade*, *Dividend Yield*, *Valuation*?**
* Entende Volatilidade e Dividend Yield
---

### 2. Rotina e Ambiente de Uso

**2.1. Quanto tempo, em média, você dedica por semana para estudar o mercado financeiro?**
* 1h

**2.2. Qual dispositivo você mais utiliza para realizar operações e consultas rápidas?**
* Computador
  
---
### 3. Usabilidade e Apresentação de Dados

**3.1. Qual fator é mais importante para você na visualização das informações?**
* Explicações objetivas e da fácil entendimento

**3.2. Qual o tamanho ideal para você da fonte e dos elementos gráficos em um dashboard?**
* Tamanho padrão

**3.3. Em uma recomendação de compra e venda, o que você mais valoriza?**
* Para compra seria informações mais precisas sobre a empresa pela qual a ação pertence, além de possíveis projeções de crescimento. Para venda seria a porcentagem de crescimento que aquela ação teve desde sua compra e se ainda há margem para mais crescimento.

---

### 4. Necessidades Específicas e Funcionalidades

**4.1. Qual o seu principal objetivo ao usar uma plataforma de análise?**
* Compreender melhor sobre o mercado de ações

**4.2. Você precisa integrar dados da plataforma com ferramentas externas (Excel, Google Sheets, API, Home Broker)?**
* Não e nem gostaria

**4.3. O que você acha mais importante em gráficos preditivos/modelos de IA?**
* Explicações claras do porquê aquela ação possui previsões de quedas/subidas, dando mais clareza e confiança na hora de investir

**SEQ por tarefa:**
  
  - T1 Identificação do perfil de investimento: 7/7
    
  - T2 Realização de investimento: 3/7

**SUS por tarefa:**

**Escala de Resposta:**

| Nível | Significado |
| :--- | :--- |
| **1** | Discordo Fortemente |
| **2** | Discordo |
| **3** | Neutro |
| **4** | Concordo |
| **5** | Concordo Fortemente |

| # | Afirmação | 1 | 2 | 3 | 4 | 5 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **1.** | Eu acho que usaria este sistema com frequência. | $\square$ | [x] | $\square$ | $\square$ | $\square$ |
| **2.** | Eu achei o sistema desnecessariamente complexo. | $\square$ | $\square$| [x] | $\square$ | $\square$ |
| **3.** | Eu achei o sistema fácil de usar. | $\square$ | $\square$ | [x] | $\square$ | $\square$ |
| **4.** | Eu acho que precisaria de suporte técnico para usar este sistema. | $\square$ | $\square$ | $\square$ | [x] | $\square$ |
| **5.** | Eu achei as várias funções neste sistema bem integradas. | $\square$ | $\square$ | $\square$ | [x] | $\square$ |
| **6.** | Eu achei que havia muita inconsistência neste sistema. | $\square$ | [x] | $\square$ | $\square$ | $\square$ |
| **7.** | Eu imagino que a maioria das pessoas aprenderia a usar este sistema rapidamente. | $\square$ | $\square$ | [x] | $\square$ | $\square$ |
| **8.** | Eu achei o sistema muito complicado de usar. | $\square$ | [x] | $\square$ | $\square$ | $\square$ |
| **9.** | Eu me senti muito confiante ao usar o sistema. | $\square$ | $\square$ | [x] | $\square$ | $\square$ |
| **10.** | Eu precisei aprender muitas coisas antes de começar a usar este sistema. | $\square$ | [x] | $\square$ | $\square$ | $\square$ |

---
  
  **Comentário final:**
  
    "A ideia é muito interessante, porém muito confuso de modo geral, principalmente a página de recomendação/simulação de ações. Falta um pouco mais de clareza e de explicações."
	
---

### 5. Conclusão Final
  
  A avaliação por observação com 3 usuários (estudante, aposentado e profissional) mostrou que: <br>
  	- Houve uma boa aceitação por parte das pessoas que testaram, porém tiveram certa dificuldade para entender o que deveria ser preenchido em determinados campos da aplicação. <br>
	- Algumas pessoas não concordaram com o perfil de investimento que foi identificado. <br>
	- Os usuários se sentiram um pouco confusos na aba de simulação/previsão de ações.
  
