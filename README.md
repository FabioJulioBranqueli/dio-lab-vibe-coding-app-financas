# 💸 App de Finanças Pessoais do Fábio JB com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

 PRD Refinado no Copilot eb.
``` Markdon
PRD – Aplicativo de Organização de Finanças Pessoais

1. Contexto
O aplicativo tem como objetivo simplificar o controle financeiro pessoal por meio de conversas em linguagem natural.
Em vez de formulários ou planilhas complexas, o usuário interage com um “Agente Financeiro” que entende suas mensagens e transforma em registros, metas e recomendações.
Diretriz de design: a interface seguirá os princípios do Material Design do Google, garantindo consistência visual, usabilidade e familiaridade, sem abrir mão dos pilares de simplicidade e Design Universal.

2. Problema
- Os apps atuais exigem muita entrada manual e pouca personalização.
- Isso gera frustração e abandono do hábito de controlar gastos.
- A solução proposta é oferecer uma experiência conversacional, intuitiva e personalizada, com recomendações automáticas de economia.
- O design será universal e acessível, permitindo que o maior número possível de pessoas tenha boa experiência, e ao mesmo tempo consistente com o Material Design.

3. Público-Alvo
- Pessoas que desejam iniciar o controle financeiro de forma prática e sem complicação.
- Principalmente iniciantes que não têm familiaridade com planilhas ou aplicativos tradicionais.
- Usuários que valorizam simplicidade, acessibilidade e linguagem clara.
- Pessoas que se beneficiam de interfaces consistentes e familiares, como as baseadas em Material Design.

4. Funcionalidades-Chave
1. Registro de gastos via chat: o usuário descreve em linguagem natural (“gastei 50 reais no mercado”) e o app registra.
2. Classificação automática: o sistema identifica categorias (alimentação, transporte, lazer).
3. Metas financeiras: o usuário define objetivos (ex.: economizar R$ 200/mês) e acompanha o progresso.
4. Agente Financeiro: fornece dicas de economia personalizadas com base nos hábitos do usuário.
5. Relatórios simples e personalizados: visão clara de gastos, metas e recomendações.
6. Design Universal + Material Design: interface acessível, responsiva e consistente, com uso de cores, tipografia e componentes que seguem os padrões do Google.

5. Entregável da IA (MVP)
- Principais telas:
  - Tela de chat (interação com o Agente Financeiro).
  - Tela de metas (definição e acompanhamento).
  - Tela de relatórios (gráficos simples e insights).

- Recursos necessários:
  - Processamento de linguagem natural (NLP).
  - Banco de dados para transações e categorias.
  - Motor de recomendações para dicas de economia.
  - Interface amigável, responsiva e inclusiva (Design Universal + Material Design).

- Validação inicial:
  - Testar com grupo diverso de usuários (diferentes idades, níveis de experiência digital).
  - Medir engajamento (quantidade de interações no chat).
  - Avaliar clareza das recomendações e relatórios.
  - Coletar feedback sobre simplicidade, acessibilidade e consistência visual.
````

 Interações com o Lovable 
> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document):
> Está dando erro na tela de login e registro.
> Tem erro para reconhecer os valores que eu digito na moeda real brasileiro.
> O agente financeiro não cria metas quando eu mando o texto com as informações.
> Pedi pra ele zerar os valores das minhas receitas e despesas só que não aconteceu.
> Obs: os erros que eu apontei o Lovable corrigiu.

Resultado final no Lovable: https://talk-to-money.lovable.app/
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/cf633883-8d22-4bc6-a963-499cf880ac84" />


- Um resumo do que o seu **App de Finanças Pessoais** faz;
  # Funcionalidades do Aplicativo de Organização de Finanças Pessoais

## Registro e Organização
- Registro de receitas e despesas em linguagem natural via chat.  
- Classificação automática das transações por categoria (alimentação, transporte, lazer etc.).

## Relatórios Financeiros
- Resumo mensal com:
  - Total de receitas.  
  - Total de despesas.  
  - Saldo do mês.  
- Feedback motivacional (mensagens de incentivo quando o usuário economiza parte da renda).  
- Relatórios visuais simples, como gráficos de gastos por categoria.

## Metas e Recomendações
- Definição e acompanhamento de metas financeiras (ex.: economizar R$ 200/mês).  
- Dicas de economia personalizadas fornecidas pelo “Agente Financeiro”.

## Navegação e Experiência
- Seções principais:  
  - **Chat** (interação com o Agente Financeiro).  
  - **Metas** (definição e acompanhamento).  
  - **Relatórios** (visualização de desempenho e insights).  
- Interface baseada em **Material Design do Google**, garantindo consistência visual e usabilidade.  
- Aplicação dos princípios de **Design Universal**, para que o app seja acessível e inclusivo para o maior número possível de usuários.

  ## Refleção:
  ### O que funcionou bem?
  O refinamento do PRD no Copilot ajudou bastante, pois os créditos do Lovable acabaram em poucas interações.
  ### O que não funcionou como o esperado?
  Esperava interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Coding.
  ### O que aprendeu sobre conversar com IAs?
  Aprendi que é basicamente a mesma coisa que conversar com uma pessoa, quanto mais detalhes e clareza você dá, melhor é interação.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
