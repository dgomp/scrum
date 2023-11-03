# Scrum
Uma breve explicação sobre Scrum.

## O que é?

	O Scrum é um framework ágil e sua principal característica é trabalhar com time-boxes:
	caixas de tempo cujo tamanho, uma vez definido, não muda durante a Sprint atual.
 
### Sprint

	Sprint é a time-box básica do Scrum. Ela é o tempo que o time tem para agregar valor para o usuário do projeto.
	Pode durar, no máximo, 1 mês. O mais comum, no entanto, é durar 2 semanas.
	
 Sprints curtas (menos tempo para entrega) são boas pra quem se desconcentra rápido. Longas (menos feedback),
	para quem fica muito pressionado.

### Review Meeting

	Ocorre após a finalização de um Sprint, onde sentamos com o cliente para mostrar as funcionalidades,
	de modo que ele possa testar. Durante a mesma, podem vir sugestões, alertas de bugs etc, e o PO anota tudo.

### Retrospective

	Acontece após a Review Meeting. De modo a analisar como foi a Sprint, o que evoluiu e o que pode ser melhorado.

### Daily Scrum:
	São reuniões curtas e diárias, onde devemos responder: 
- O que eu fiz desde o último Daily Scrum?
- O que eu pretendo fazer até o próximo?
- Quais problemas me atrapalharam?

`Ocorrem:`
- Sempre no mesmo horário
- Sempre no mesmo lugar
- Durante 15 minutos
- Em pé, de preferência, para que seja rápido
	
`É importante:`
- Evitar reuniões no início e no final do dia (ideal ser um pouco antes do almoço ou após)
- Discussão rápida, só pra levantar os problemas. Se for pra resolver, deixa pra resolver após o daily.

### Planning Meeting (Reunião de Planejamento) / Sprint Planning
- Ocorre antes de começar o próximo Sprint, para definir o que e como vai desenvolver, além de definir o Product Owner;
- Tempo: Limitada a 5% do Sprint (ex: se são duas semanas, 4 horas);
- Todos participam (desenvolvedores, Scrum Master e Product Owner);
- PO vem com o Product Backlog, explicando o que deve ser feito. Ele faz esse arquivo baseado no Sprint anterior e nas conversas com o cliente;
- Objetivo de fazer o Sprint Backlog (Lista Priorizada) e meta;


`Mecânica da Reunião:`
- PO traz o topo do Backlog (já priorizado e refinado - Zooming) e o apresenta, sem dar sugestão na parte técnica;
- Desenvolvedores discutem o Backlog, subdividem a tarefa e estimam o tempo necessário para desenvolver;
- Há negociação do que realmente caberá nesse Sprint, de modo a saber o que será entregue ao fim desse Sprint, ou seja, o Sprint Backlog;
- Após a criação do Sprint Backlog, quanto valor de negócio essa Sprint agregará? Qual a meta? Qual a frase motivacional? Quanto de impacto esse Sprint gerará para o usuário?

#### Histórias (Story) e Tarefas - ambos ficam dentro do Product Backlog e do Sprint Backlog
	Exemplo de História (Story):
- (TÍTULO DA STORY)
- (Para) Motivar o time a bater a meta; 				(Por que é importante?)
- (Como) através de Fulano;					(Para quem é importante?)
- (Quero) que toque uma música quando uma meta for cumprida;	(O pedido em si)
- Isso é adicionado no planning.

Para desenvolver, é colocado em subitens, de modo a dividir, formando as Tasks (tarefas), para que a Story ocorra na prática.
Ex: seleção das músicas, javascript para rodar a música, notificação que a meta foi batida ...

#### Backlogs
##### Product Backlog:
- Gerenciado pelo Product Owner.
- Muito importante o refinamento (Zooming), de modo a deixar bem claro os itens mais importantes, prioritários e que caiba em Sprints.
- É para o projeto inteiro e seu desenvolvimento, além de ser uma junção do que ocorreu nos sprints anteriores, vem também das conversas com o cliente.
- Seria o "esqueleto" do projeto.
- Os menos importantes e/ou mais distantes, podem ficar mais "grosseiros", de modo que, conforme vai se aproximando (prioridade aumentando), vão sendo refinados.

##### Sprint Backlog:
- Lista priorizada. É gerenciado pelo time inteiro.
- É para aquele Sprint. Já fica dividido em Histórias e Tarefas.
- O cliente não pode dar palpite.
- É feito após apresentação e discussão acerca do Product Backlog, ou seja, é um segundo filtro, exclusivo para aquele Sprint.


#### O que é:
##### Scrum Master:
- Não é chefe, mas um líder, um coach.
- Gerencia o processo, controlando os horários, organização etc, de modo que todos respeitem os timeboxes.
- Educar a todos (desenvolvedores, PO e cliente) quanto ao processo.
- Caso o cliente "suma", deve conversar com o mesmo, mostrar a necessidade da presença dele em determinados momentos, para que o projeto continue a evoluir.
- Resolver IMPEDIMENTOS. Se tem um problema, cabe ao time resolver. Se tem um impedimento, cabe ao Scrum Master. Impedimento se dá quando o time tenta resolver e não consegue.

##### Product Owner:
- Faz parte do time. O único que é externo ao time, mas envolvido com o produto, é o cliente.
- É o representante do cliente dentro do time.
- Mantém o Backlog atualizado, ou seja, a prioridade das coisas.
- Conversa com o cliente.
- Desenvolvedor tem dúvida e o PO não sabe resolver? PO leva o desenvolvedor até o cliente, para desenvolvedor e cliente conversarem.
- Se o cliente tentar falar diretamente com o desenvolvedor para pedir algo, o desenvolvedor pede para o cliente falar com o PO.
		
##### Desenvolvedores:
- Analista, programador, arquiteto, DBA, front-end, tester.
- Ajudam o projeto a andar pra frente.
- Todos do time que não sejam Scrum Master ou Product Owner.
- Analisam o tempo necessário para o desenvolvimeto, junto ao PO.
- Negociam o que será realizado no Sprint, melhorando o ambiente. Isso é definido durante o Planning.
- O time decide quem fará o que, durante as daily.

		Pode ser Desenvolvedor e PO ou Desenvolvedor e Scrum Master, mas não pode ser Scrum Master e PO.

#### Time (fazer):
- Contratar pessoas;
- Resolver problemas;
- Apresentar pro cliente, participar de reuniões, fazer o processo andar;
- Fazer as ações das retrospectivas andarem;
- Definir duração da Sprint;
- Melhoria contínua;
