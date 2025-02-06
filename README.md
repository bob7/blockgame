# blockgame
A 2-player board game related to compression of enumerations and Kolmgorov complexity. 

See the technical [article](https://arxiv.org/abs/2304.03030) (with X. Zhang and B. Zhan) in Arxiv. <br><br>

<p margin-top="400px" align="center"><img width="600"  src="https://github.com/bob7/blockgame/blob/main/img/evenImgd.png"></p>
<br><br>

Two players click the white and shaded boxes in alternate rounds (stages). At each stage:

- player 1 chooses any four boxes that he hasn’t chosen earlier (his picks are permanently marked with a gray half-fill)

- player 2 picks a shaded box in the range of boxed previously clicked by player 1 that he has not picked before (these are highlighted with light blue at his turn).

The player who first runs out of legitimate moves is the loser.

