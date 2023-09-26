# ADS - 2023/02
## PROJETO 1 – 10 pontos
<img src="https://img.shields.io/badge/ADS-IFTM-green">  <img src="https://img.shields.io/badge/Projeto1-2023/02-blue">  

### 1.	DESCRIÇÃO
Os alunos devem se organizar em equipes de no mínimo 3 pessoas e no máximo 4 pessoas. Equipes com menos ou mais integrantes receberão nota zero na atividade. Cada equipe deverá escolher um nome de “time de desenvolvimento”. Essa equipe deverá ter um integrante líder, que fará a entrega do trabalho final.

Apresentado no dia 23 de novembro de 1996, o Tamagotchi era uma espécie de chaveiro que abrigava um bichinho virtual que pedia por doses regulares de alimento virtual, atenção virtual e carinho virtual. Agora, você! Isso mesmo, você, junto de seu time de desenvolvimento, terá a honra de implementar uma versão dessa febre dos anos 90.

O virtual pet terá as seguintes informações atreladas a ele:

 - **Tempo de vida:** inicia com 0 dias vivo, a cada 24 horas, envelhece um dia. O tempo máximo de vida é de 7 dias.
	
 - **Felicidade:** começa em 5. Comer ao estar com fome, brincar e dormir, aumentam esse atributo. Ser forçado a comer ou ficar muito tempo sujo e sem diversão (jogar), diminuem esse atributo. O valor máximo para esse atributo é 10. Caso o atributo felicidade chegue a zero, o virtual pet morre de tristeza 😕 .
	
 - **Limpeza:** Esse atributo inicia com 10 pontos. Ao passar o tempo sem tomar banho, esse atributo diminui. Um bichinho super sujo morre por sujeira. Tomar banho aumenta esse atributo. Tomar banho estando limpo diminui o atributo felicidade. 
	
 - **Fome:** Esse atributo inicia com 0. Ao passar o tempo, esse atributo aumenta. Um pet faminto morre de fome. Comer diminui esse atributo, até chegar ao máximo de zero. Tentar alimentar um pet contra sua vontade o deixará triste.
	
 - **Doente:** Esse atributo indicará se o pet está ou não doente. Ele poderá ficar doente ao acaso (de maneira aleatória). Caso ele esteja doente, a cada 8 horas ele deverá ter chance de se curar sozinho. Isso acontecerá com 33.3% de chance após 8 horas da doença iniciada. Após 16 horas ele terá 66.6% de chance de ser curado e após 24 horas ele estará curado.

O projeto deve conter todas as funcionalidades detalhadas na seção de menu a seguir. Além disso, ao iniciar o programa pela primeira vez, o usuário deverá escolher o nome para seu ‘virtual pet’. A partir daí, todas as frases deverão ser personalizadas para chamar o bichinho pelo nome escolhido.

O trabalho se consiste em desenvolver um projeto funcional de um bichinho virtual. O algoritmo deve ter um menu inicial, com as seguintes opções:

```
Projeto Virtual Pet 2023
<(^_^)>    (•_•)    _(x.x)_
Escolha uma opção a seguir: 
1.	Avançar o tempo
2.	Alimentar
3.	Jogar
4.	Dar banho
5.	Ver status
6.	Desligar

```

### 1.1 Detalhamento de funções

-	**Avançar o tempo:** Ao escolher essa função, o jogador faz o pet “avançar 8 horas de vida” em seu tempo. Isso impactará em diversas das funcionalidades do bichinho virtual. A cada 24horas passadas, o pet envelhece um dia. O tempo máximo de vida para o pet é de 7 dias, após isso, ele morre de velhice. Nesse caso, o jogador ‘ganha o jogo’, pois fez com que seu bichinho vivesse feliz até o fim.

-	**Alimentar:** Ao alimentar o pet, sua fome diminuirá em 4 pontos. Chegando ao máximo de fome 0. Tentar alimentar um pet que está com fome 0, fará com que sua felicidade diminua em 2 pontos.

-	**Jogar:** Ao escolher a função jogar, o pet e o usuário farão uma partida de pedra, papel e tesoura. Caso o pet vença, sua felicidade aumentará em 5 pontos. Caso ele perca, sua felicidade aumentará em 3 pontos.

-	**Dar banho:** A função de dar banho fará com que a limpeza de seu pet chegue a 10 pontos. A cada 8 horas, o pet perde 2 pontos em limpeza. Tentar dar banho em um pet com 10 pontos de limpeza, fará com que ele reduza a felicidade em 6 pontos.

-	**Ver status:** A função ver status deve mostrar ao usuário todas as informações pertinentes para que o usuário possa cuidar de seu pet da maneira adequada. Também deve mostrar a idade atual do pet. Extra: O programador pode disparar mensagens fora dessa função para alertar ao usuário quando seu pet estiver necessitando de cuidado urgente, para tentar evitar sua morte precoce.

> Caso o pet morra de fome, tristeza ou sujeira, o programa deverá encerrar, mostrando a mensagem para o usuário de tempo de vida do pet e informando a causa da sua morte precoce.

  ## 2. APRESENTAÇÃO

- 	O trabalho deverá ser entregue até o dia **16/10**. Apresentações acontecerão na próxima aula a partir desse dia.
- 	O trabalho deve estar no github. O LINK do repositório deve ser enviado via email pelo líder da equipe (Não deverá enviar o código pelo email.). O restante do grupo não deve enviar NADA.
-	Arquivos com problemas de compilação receberão nota zero. O professor não receberá outro arquivo no momento da entrevista, o arquivo que será compilado será o arquivo enviado ao professor.
-	Ao aluno que não enviar o código fonte, será atribuída nota zero.
-	Não serão recebidos trabalhos atrasados. Caso o aluno não submeta o trabalho até a data limite, a nota zero será atribuída aos alunos.
-	**FLAGRANTES DE CÓPIAS DE TRABALHOS OCASIONARÃO EM NOTA ZERO PARA TODOS OS TRABALHOS SEMELHANTES.**
-	O trabalho deverá ser apresentado ao professor em datas e horários definidos. O não comparecimento de um dos integrantes do grupo resultará em nota zero para o aluno que faltar. O questionamento será feito de forma direcionada aos alunos do grupo entrevistado. A nota de cada aluno é individual, sendo esta dada por:
  
_notafinal = notaProjeto * notaEntrevista_

-	Onde a notaEntrevista pode variar de 0 a 1.
-	A endentação de código, comentários e qualidade da solução farão parte da avaliação do projeto.
-	
### Observações ⚠️

     O professor em hipótese alguma ajudará na construção do código.
     O professor poderá tirar dúvidas sobre o enunciado do problema as funcionalidades pretendidas.




