# Case Study: ALphaZero

## Concepts
1. [AlphaZero Preview](https://www.youtube.com/watch?v=Zzc1XJ1aJ-4&feature=emb_logo)
	> In 2016, researchers at DeepMind announced a new breakthrough -- the development of a new AI engine, alphago for the game of go.The AI was able to beat a professional player LeeSedol. The breakthrough was significant, because go was far more complex than chess: the number of possible games is so high, that a professional go engine was believed to be way out of reach at that point, and human intuition was believed to be a key component in professional play. Still, performance in alphago depends on expert input during the training step, and so the algorithm cannot be easily be transferred to other domains
	> This changed in 2017, when the team at DeepMind updated their algorithm, and developed a new engine called alphago zero. This time, instead of depending on expert gameplay for the training, alphago zero learned from playing against itself, only knowing the rules of the game. More impressively, the algorithm was generic enough to be adapted to chess and shogi (also known as japanese chess). This leads to an entirely new framework for developing AI engine, and the researchers called their algorithm, simply as the alphazero.
	> The best part of the alphazero algorithm is simplicity: it consists of a Monte Carlo tree search, guided by a deep neural network. This is analogous to the way humans think about board games -- where professional players employ hard calculations guides with intuitions.
	> In the following lesson, we will cover how the alphazero algorithm works, and implement it to play an advanced version of tic-tac-toe. So let’s get started!
	> (Much of the lesson material is derived from the original paper, for [alphago zero](https://deepmind.com/documents/119/agz_unformatted_nature.pdf), and [alphazero](https://arxiv.org/abs/1712.01815) by the researchers at DeepMind. I encourage you to visit links -- click on the words-- to check out those papers)
1. [Zero-Sum Game](https://www.youtube.com/watch?v=uPw1dHVqdXQ&feature=emb_logo)
1. [Monte Carlo Tree Search 1 - Random Sampling](https://www.youtube.com/watch?v=wn2B3j_Qz6E&feature=emb_logo)
1. [Monte Carlo Tree Search 2 - Expansion and Back-propagation](https://www.youtube.com/watch?v=H34Wtk1iNDY&feature=emb_logo)
1. [AlphaZero 1: Guided Tree Search](https://www.youtube.com/watch?v=LinuRy47xbw&feature=emb_logo)
1. [AlphaZero 2: Self-Play Training](https://www.youtube.com/watch?v=wl1qfPXqRuQ&feature=emb_logo)
1.[TicTacToe using AlphaZero - walkthrough-part1](https://www.youtube.com/watch?v=uUFuBscf98I&feature=emb_logo) [TicTacToe using AlphaZero - walkthrough-Part2](https://www.youtube.com/watch?v=hKnBQvtJ_zQ&feature=emb_logo)
1. [TicTacToe using AlphaZero - Workspace](workspace-1539639357.tar.gz)
1. [Advanced TicTacToe with AlphaZero - Walkthrough](https://www.youtube.com/watch?v=MOIk_BbCjRw&feature=emb_logo) [workspace](workspace-1539639357.tar.gz)
