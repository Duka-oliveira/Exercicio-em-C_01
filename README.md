Construa o seguinte jogo usuário x computador: o objetivo de cada rodada é obter mais pontos que o computador. 
Inicialmente o programa deve perguntar a quantidade de rodadas.
Em cada rodada:
I.	Um valor entre 1 e 50 é sorteado para o computador e exibido ao usuário (pontos do computador)
II.	jogador recebe inicialmente a mesma quantidade de números (cujos valores variam entre 1 e 5) que a rodada, isto é, na 1ª rodada, recebe um número, na 2ª rodada, recebe dois números, na 3ª rodada recebe 3 números e assim sucessivamente. 
III.	O programa deve exibir os números iniciais gerados e a soma destes números, que representa o total de pontos do jogador. 
IV.	A seguir, o jogador pode fazer solicitações de n números (término das solicitações:  n==0 ou ter feito o dobro da rodada de solicitações). A cada solicitação, o programa mostra os n valores gerados nesta solicitação e a soma destes novos valores é somada ao total de pontos. No entanto, se um dos valores gerados for igual a 1/8 do total de pontos, o jogador “perde” 20 pontos do seu total de pontos  
V.	O jogador perde a rodada caso seu total de pontos “estourar” 50 pontos ou for inferior à pontuação do computador
