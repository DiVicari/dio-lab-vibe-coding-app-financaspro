# 💸 App Finanças Pro com Vibe Coding

- PRD trabalhado dentro do Copilot Web:
```markdown
# PRD Revisado - Aplicativo de Organização de Finanças Pessoais

## Contexto
O objetivo é criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas em linguagem natural.  
A solução deve ter **design universal**, garantindo acessibilidade e usabilidade para diferentes perfis de usuários, independentemente de idade, nível de instrução ou condição socioeconômica.  
A proposta é simplificar o controle financeiro, eliminando a necessidade de formulários manuais ou planilhas complexas.  
O aplicativo contará com personas e avatares que representam as classes econômicas brasileiras, de acordo com faixas de renda. Conforme o usuário interagir com o app, será incentivado pelo "Agente Financeiro" a melhorar suas finanças, revisando despesas e buscando novas fontes de renda. Tudo será baseado em análises automáticas das informações inseridas via chat.

## Problema
Muitos usuários desistem de controlar seus gastos porque os aplicativos atuais exigem entradas manuais extensas e oferecem pouca personalização.  
A proposta é criar uma experiência imersiva e motivadora, que inspire o usuário a alcançar metas financeiras e superar desafios.  
Para isso, são necessárias recomendações automáticas, fundamentadas em boas práticas de economia, apresentadas de forma clara e acessível.

## Público-Alvo
Brasileiros que desejam iniciar a organização de suas finanças de maneira prática e intuitiva.  
O foco inicial está em iniciantes, que aprenderão gradualmente com a ferramenta e aplicarão os insights e dicas em suas vidas cotidianas.

## Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras personalizadas.  
4. Receber desafios e dicas de economia do “Agente Financeiro”.  
5. Permitir que o "Agente Financeiro" crie metas definidas pelo usuário e sugira novas metas alinhadas ao perfil identificado.  
6. Abrir telas de visualização de extratos e gráficos mediante solicitação via chat.  
7. Exibir a classe econômica do usuário com avatar e nome da classe, além de uma estimativa do que falta para atingir a próxima classe, sem detalhar os dados que definiram a classificação.  
8. Garantir acessibilidade e design universal, incluindo suporte a diferentes dispositivos, tamanhos de tela e recursos de acessibilidade (ex.: leitura de tela, contraste adequado, navegação simplificada).

## Entregável da IA
Gerar um plano de MVP com:
- Principais telas:  
  - Tela de chat (interação com o Agente Financeiro)  
  - Tela de extratos e gráficos  
  - Tela de metas financeiras  
  - Tela de avatar e classe econômica  
- Recursos necessários:  
  - Processamento de linguagem natural  
  - Motor de classificação automática de transações  
  - Sistema de recomendação de metas e dicas  
  - Módulo de visualização de dados (gráficos e relatórios)  
- Esboço de validação inicial:  
  - Testes com grupo piloto de usuários iniciantes  
  - Avaliação da clareza das recomendações  
  - Medição da facilidade de uso e acessibilidade  
  - Coleta de feedback sobre motivação e engajamento  

## Roadmap Inicial
- **Discovery**: pesquisa com usuários e definição de personas.  
- **Design & Prototyping**: criação de wireframes e protótipos interativos com foco em design universal.  
- **MVP Development**: implementação das funcionalidades-chave.  
- **Beta Testing**: testes com grupo reduzido de usuários.  
- **Go-to-Market**: lançamento inicial com plano de comunicação e suporte.  
- **Post-Launch Monitoring**: acompanhamento de métricas de adoção, feedback contínuo e roadmap de melhorias.
```

- Interações realizadas com o Lovable após a aprovação do PRD:
> Boa noite! Preciso que crie um APP de controle de finanças pessoais à partir do Product Requirements Document que enviarei em seguida, com uma tela inicial de acesso com usuário e senha numérica simples, que dará acesso a uma tela de cadastro do usuário onde ele irá preencher somente o primeiro nome, a profissão e a faixa de renda mensal que ele se insere. Para que o usuário preencha a faixa de renda mensal, preciso que o app apresente ao menos 9 faixas de renda mensal, limitadas até R$ 1.000.000,00. Em seguida siga a PRD

> Preciso que realize alterações na aplicação. Na tela do chat onde as interações ocorrem, preciso que tudo o que o usuario solicitar de inclusão de receitas, despesas e demais informações relativas a movimentação financeira também seja migrado para a tela Extrato, e quando o extrato é solicitado ao "Agente Financeiro" no chat o usuário seja direcionado para a tela Extrato para então filtrar o período que deseja analisar. Além disso, quando o "Agente Financeiro" retorna as repostas no chat, preciso que as respostas sejam um pouco mais curtas e objetivas. Ainda na tela do Chat, preciso que o layout de tela seja alterado contendo a informação do saldo atual do usuário na parte superior da página e que a caixa do chat não ocupe toda a tela. Além disso, o histórico do chat pode ser separado por dias de interação do usuário, sem perder as informações inclusas, fincando listado ao lado direito do quadro do chat as datas anteriores de interações, caso o usuário queira consultar. Na tela Extrato, como informei anteriormente, preciso que as interações do usuário com o "Agente Financeiro" de inclusão de receitas e despesas também fiquem registradas para posterior geração do Extrato. Quero que também seja categorizado o tipo de despesa e receita conforme o usuário registra no chat. Adicione também na tela Extrato um gráfico em pizza que mostre as categorias dos gastos do usuário e seus respectivos percentuais sobre o total gasto. Na tela Metas, preciso que o "Agente Financeiro" tenha conhecimento da meta criada pelo usuário e que interaja também sobre os lançamentos que o usuário solicite pelo chat para incremento ou redução da meta criada. Também preciso que o "Agente Financeiro" calcule o prazo que o usuário deve demorar para alcançar a meta e motive o a alcançar a meta. Agora quanto a informações da aplicação, não sei se já está disponível com as verificações de segurança que solicitei, porém preciso que o usuário tenha a possibilidade de excluir seu perfil caso queira. Pode concluir todas estas alterações para mim, por favor?

> A aplicação está ficando excelente, porém percebi que o usuário não como recuperar sua senha caso a esqueça. Poderia cuidar disso implementando uma opção de esqueci minha senha na tela de login onde há enviado um e-mail ao usuário com um link onde ele possa refazer sua senha de forma segura e sem riscos de vazamento de informações?

- Resultado final no Lovable: https://chat-financas-pro.lovable.app

<img width="1366" height="620" alt="image" src="https://github.com/user-attachments/assets/740c91d5-cdd5-4ae0-8334-c8293d1f8ce0" />

<img width="1366" height="617" alt="image" src="https://github.com/user-attachments/assets/995b8553-1b49-4064-85dd-af23ab98bb8f" />

<img width="1366" height="616" alt="image" src="https://github.com/user-attachments/assets/d8495630-03e7-4c20-aa00-e07af9ee97e5" />

<img width="1366" height="611" alt="image" src="https://github.com/user-attachments/assets/e81f793d-b9aa-4020-8459-5e0aab09dc89" />

<img width="1366" height="617" alt="image" src="https://github.com/user-attachments/assets/8d2d7468-e489-4f7e-9cd5-c4fe214a7cad" />

<img width="1366" height="616" alt="image" src="https://github.com/user-attachments/assets/ea1d80d3-9276-48ae-90a8-2e598cf6c9e2" />

<img width="1366" height="619" alt="image" src="https://github.com/user-attachments/assets/bae9b05a-6c8b-4d20-ab93-c60fefba4a6e" />

<img width="1366" height="615" alt="image" src="https://github.com/user-attachments/assets/89338387-97e3-4ff3-a1be-b8588f2be693" />

<img width="1366" height="620" alt="image" src="https://github.com/user-attachments/assets/296071aa-a1a3-405a-8a43-3aaaed77fb27" />


- # Resumo das Funcionalidades do Aplicativo de Organização de Finanças Pessoais

## 1. Interação via Chat
- Conversa com o **Agente Financeiro** em linguagem natural.  
- Exemplos de comandos: registrar despesas, consultar extratos, verificar metas.  
- Campo de entrada de mensagem sempre disponível para interação contínua.  

## 2. Registro de Gastos
- Botão dedicado para **Registrar gasto**.  
- Alternativa: inserir diretamente pelo chat (“Gastei R$ 50 no almoço”).  
- Transações são automaticamente classificadas.  

## 3. Visualização de Extratos
- Botão **Ver extrato** abre tela com histórico de receitas e despesas.  
- O Agente Financeiro também pode abrir gráficos e relatórios sob demanda.  

## 4. Metas Financeiras
- Botão **Minhas metas** permite acompanhar objetivos definidos.  
- O Agente Financeiro sugere metas personalizadas com base nos hábitos do usuário.  
- Feedback contínuo sobre progresso em direção às metas.  

## 5. Dicas de Economia
- Botão **Dica de economia** fornece recomendações práticas.  
- O Agente Financeiro motiva o usuário com desafios e insights para melhorar sua saúde financeira.  

## 6. Classes Econômicas e Avatares
- O app apresenta ao usuário sua **classe econômica atual** por meio de avatar e nome da classe.  
- Mostra estimativas do que falta para atingir a próxima classe, sem expor dados detalhados.  

## 7. Navegação Simples
- Menu lateral com seções: **Chat**, **Extratos**, **Metas**, **Perfil**, **Sair**.  
- Estrutura clara e acessível, alinhada ao princípio de **design universal**.  

---

## Em Resumo
O aplicativo combina **conversa natural** com funcionalidades práticas de controle financeiro, oferecendo:  
- Registro automático de gastos  
- Visualização de extratos  
- Definição de metas  
- Dicas de economia  
- Representação da classe econômica por avatares  

Tudo isso com foco em **acessibilidade, simplicidade e design universal**.
 
- # Pontos observados durante a criação do app e reflexões sobre o processo
  ## O que funcionou bem?
  A primeira interação com o Copilot ajudou muito a gerar a documentação inicial do app e refinar as informações para que pudesse partir para criação do mesmo no Lovable, uma vez que os créditos diários são baixos e acabam com poucas interações.  
  ## O que não funcionou como o esperado?
  Mesmo com o refinanmento da solução e do PRD no Copilot, ainda foram necessárias muitas interações com grandes correções de funcionalidades no Lovable, o que levou mais de um dia já que na versão free os créditos acabaram rapidamente, porém foi possível ir testando o app enquanto solicitava as devidas alterações e correções.
  ## O que aprendeu sobre conversar com IAs?
  O detalhamento do que é solicitado e a qualidade do prompt fazem muita diferença no que tange ao entendimento da tarefa pela IA. Mesmo assim, é necessário realizar algumnas interações com a mesma afim de deixar o resultado o mais próximo do desejado, não dando espaço para que a IA se abstraia do assunto para conseguir manter um raciocínio da máquina fluído e obter os resultados esperados.
