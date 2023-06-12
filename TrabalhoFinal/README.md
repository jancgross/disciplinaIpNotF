# Introdução à Programação (IP) - Trabalho Final

Prazo máximo para definir as equipes: 14/06/2023.  
Prazo máximo para apresentação do trabalho (para o professor): 28/07/2023 (quarta).  
Equipes: mínimo de dois, e máximo com três alunos.  

## Definições

- Só é permitido o uso de comandos estudados em sala de aula até o momento.  
- O conteúdo necessário para desenvolver este trabalho em sua grande maioria são conteúdos já abordados nas aulas, mas algumas partes serão explicadas durante as aulas destinadas ao desenvolvimento do trabalho.  
- As dúvidas referente a este trabalho serão respondidas SOMENTE durante os dias/horários das nossas aulas.  
- Lembre de consultar o repositório desta disciplina para ajudar no desenvolvimento deste trabalho.  
- Os trabalhos podem ser desenvolvidos em equipe, mas as avaliações serão individuais, podendo gerar notas diferentes para cada integrante da equipe.  
- Uma vez apresentado o trabalho para avaliação, este não poderá ser reapresentado.  
- A ordem de apresentação dos trabalhos serão definidos pelo professor, e poderão ser somente apresentados durante os dias/horários de aula definidos no cronograma.  
<!-- - O professor criar uma chamada com TODOS os integrantes da equipe, e num primeiro momento vai conversar individualmente com cada integrante da equipe, e no final com todos integrantes juntos.   -->
<!-- - O professor vai conversar individualmente com cada integrante da equipe, e no final com todos integrantes juntos.  
<!-- - Durante a chamada o aluno precisará compartilhar sua tela e, eventualmente, abrir sua câmera para conversar com o professor. No caso do compartilhamento de tela, o aluno deverá mostrar o código desenvolvido na IDE VSCode (ou outra da sua escolha) para permitir editar e executar o referido código se for preciso.   --> 
- Durante a apresentação do trabalho o aluno deverá mostrar o código desenvolvido na IDE VSCode (ou outra da sua escolha) para permitir editar e executar o referido código se for preciso.  
<!-- - Assim que quiserem fazer a apresentação do trabalho final avisem para o professor usando o seu canal individual no MS-Teams.   -->
- Assim que a equipe quiser fazer a apresentação do trabalho final deve avisar para o professor.  
- A apresentação só poderá ser feita após a equipe postar os fontes (.java) do trabalho no AVA3.  
- O código postado/apresentado não pode ter erros de execução (use comentários para tirar possíveis erros).  

Com base nas seguintes descrições, implemente o problema do jogo **Liga-4**.  

**ATENÇÃO**: deve seguir fielmente a descrição seguinte. 

## Liga-4

![image](https://github.com/dalton-reis/disciplinaIpPrivado/assets/22553125/c7e93d1d-a3ec-4517-9a88-4211bfcfcd0b)

- o único import que deve ser usado é *java.util.Scanner*;  
- o construtor declara a única ocorrência do objeto *teclado* da classe *Scanner* para permitir ler dados do console usando o teclado;
- o método main só instância o construtor desta classe;  
- o construtor declara a matriz do tipo char que representa o *tabuleiro  
- a matriz *tabuleiro* tem o tamanho 6 por 7;
- o jogo será implementado para ser jogado entre um jogador e o computador;
- devem ser implementados métodos que por sua vez serão chamados no construtor. Esses métodos serão a sua escolha, bem como os tipos de retorno ou parâmetros;
- não poderá ser declarados atributos de classe.

**OBS:** caso um dos itens acima não seja atendido, será descontado 0,5 pontos por item não atendido. <br />

## Regras do Jogo Liga-4
O Liga-4 é um jogo de estratégia em que dois jogadores alternam em colocar discos em uma grade vertical de 6 linhas por 7 colunas. <br />
O objetivo do jogo é ser o primeiro a formar uma linha contínua de quatro discos da mesma cor, seja horizontal, vertical ou diagonalmente.  <br />
O jogo é bastante simples, mas requer planejamento e antecipação para bloquear os movimentos do oponente enquanto tenta formar sua própria linha de quatro discos.  <br />
O jogador precisa estar atento às possibilidades de seu oponente e tomar decisões estratégicas para garantir a vitória.  <br />

Implemente o jogo, seguindo os seguintes Requisitos Funcionais (RF):  
RF01 - o tabuleiro deve começar com todas as casas em branco representando pelo valor "B" **(0,5)** <br />
RF02 - o jogador deve escolher a sua cor entre V (vermelho) ou A (azul)  **(0,5)** <br />
RF03 - na sua vez, o jogador deve informar uma posição de coluna para jogar. A peça ficará posicionada na primeira linha disponível daquela coluna (considerar a linha mais abaixo possível) **(1,0)** <br />
RF04 - após o jogador executar sua jogada, o computador deve executar sua jogada de forma aleatória (utilizar o método Math.random para sortear a coluna) **(1,0)** <br />
RF05 - deve ser possível imprimir o tabuleiro a qualquer momento **(1,0)** <br />
RF06 - quando o jogador ou o computador ganhar, deve-se imprimir quem foi o vencedor (considerar vitória para 4 cores posicionadas linearmente na horizontal, vertical ou diagonal). **(4,0 -- 1,0 para cada posição - horizontal, vertical, diagonal para direita, diagonal para esquerda)** -  <br /> 
RF07 - se o jogador ou o computador informar uma coluna que está com todas as linhas preenchidas, deve-se solicitar novamente que faça sua jogada. **(0,5)** <br />
RF08 - se o tabuleiro estiver completo e não houver vitória deve-se imprimir EMPATE **(0,5)** <br />
RF09 - quando um jogador vence ou há empate, deve-se perguntar se deseja jogar novamente e, caso afirmativo, deve-se reiniciar a partida. **(1,0)** <br />




