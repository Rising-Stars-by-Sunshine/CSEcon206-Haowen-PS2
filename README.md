#  Problem Set 2: Decipher Game Theory
- **Author**: Haowen Ji, Data Science, Class 2023, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to Problem Set 2 for [CSEcon 206 Computational Microeconomics, 2023 Spring Term (Seven Week - Second)](https://ms.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgements**: I would like to thank Prof. Luyao Zhang for her instructions in CSEcon 206 and thank all my classmates for the inspiring discussions and feedback. Thank Yiwei, Yuchen, and Rong for precious advice.
- **Project Information**: 
  This project mainly has two parts:
  - Game theory reflection and exploration in Overleaf. This part goes through the milestones of game theory and explores Bayesian Nash Equilibrium and game theory glossary.
  - Normal and extensive form games in Colab. This part introduces, realizes and analyzes two forms of games with coding and stored in the .ipynb file.
 

## Table of Contents

- [Structure](#structure)
- [Spotlight](#spotlight)
- [More about the Author](#More-about-the-Author)
- [References](#references)

### Structure

- [Game theory reflection and exploration](https://github.com/Rising-Stars-by-Sunshine/CSEcon206-Haowen-PS2/blob/main/code/CSECON206_ProblemSet2_Spring2023-Haowen.zip)
  - The first part briefly outlines the milestones in the history of game theory. 
  - The second part focuses on Bayesian Nash equilibrium and provides definitions and explanations of the concept. Two textbooks are referenced in this section, namely, "Multiagent Systems: Algorithmic, Game-theoretic, and Logical Foundations" (Shoham and Leyton-Brown 2009), and "A Course in Game Theory" (Osborne and Rubinstein 1994), both of which define Bayesian Nash equilibrium and provide explanations. However, no theorem or proof related to Bayesian Nash equilibrium is provided in either textbook.
  - The third part reflects a game theory glossary, and is linked with original sources.
- [Normal and extensive form games](https://github.com/Rising-Stars-by-Sunshine/CSEcon206-Haowen-PS2/blob/main/code/Normal_Form_Game%26Extensive_Form_Game.ipynb)
  - This section discusses two different game theory problems: the Modified Prisoner's Dilemma and the Matching Pennies without Observation game, explaining their game descriptions, strategic form matrices, game trees, and solutions including Nash equilibrium and expected payoff.

### Spotlight
#### [Game theory reflection and exploration in Overleaf](https://github.com/Rising-Stars-by-Sunshine/CSEcon206-Haowen-PS2/blob/main/code/CSECON206_ProblemSet2_Spring2023-Haowen.zip)
- The main findings in this section consist of two parts. The first part provides an overview of the milestones in the history of game theory. The second part focuses on Bayesian Nash Equilibrium, which is a mixed-strategy equilibrium strategy profile. The section defines Bayesian Nash Equilibrium and provides an explanation of the concept. It also presents two definitions related to Bayesian Nash Equilibrium and discusses their similarities. However, no theorem or proof related to Bayesian Nash Equilibrium is presented. Besides, five new terminologies are introduced in this part. 
#### [Normal and extensive form games in Colab](https://github.com/Rising-Stars-by-Sunshine/CSEcon206-Haowen-PS2/blob/main/code/Normal_Form_Game%26Extensive_Form_Game.ipynb)
- In the Modified Prisoner's Dilemma, the Normal Form Game is represented by a 2x2 matrix where each player chooses between two actions: keep silent or betray, which is shown in Figure 1. The payoffs for each player are determined by both players' actions, and the Nash equilibrium is achieved when both players choose to betray each other. In this Nash equilibrium, neither player can unilaterally change their strategy to improve their own payoff, given the strategy of the other player.
<div align=center>
<img src="https://raw.githubusercontent.com/Rising-Stars-by-Sunshine/CSEcon206-Haowen-PS2/main/spotlight/normal.jpg" width="200" /><br/>
  Fig.1: Matrix for Modified Prisoner's Dilemma game
</div>

- In the Matching Pennies without Observation, the Extensive Form Game is represented by a game tree, shown in Figure 2, where each player selects either heads or tails for their coin without observing the outcome of the other player's move. The game has two symmetric payoff matrices, and the Nash equilibrium is achieved when both players play randomly, with each player choosing strategy 1 and strategy 2 with equal probability. The expected payoff for each player in this Nash equilibrium is 0, indicating that neither player has an advantage over the other.
<div align=center>
<img src="https://raw.githubusercontent.com/Rising-Stars-by-Sunshine/CSEcon206-Haowen-PS2/main/spotlight/Tree.jpg" width="200" /><br/>
  Fig.2: Game tree for Matching Pennies without Observation
</div>


### More about the Author
<div align=center>
<img src="https://raw.githubusercontent.com/Rising-Stars-by-Sunshine/CSEcon206-Haowen-PS2/main/spotlight/soccer.jpg" width="400" alt="Haowen" /><br/>
</div>

- Haowen Ji is a senior student at Duke Kunshan University, where he is currently pursuing a degree in data science. With a keen interest in interdisciplinary studies, he has dedicated his academic career to exploring the diverse applications of data science, including its integration with healthcare, computer vision, and economics. Apart from his academic pursuits, Haowen is an avid football enthusiast who loves to play and watch football games. His passion for football has taught him valuable lessons in teamwork, strategy, and perseverance, which he applies to both his personal and professional life.

### References

- Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.
- Osborne, Martin J, and Ariel Rubinstein. 1994. A Course in Game Theory. Cambridge, Mass.: Mit Press.
- Shoham, Yoav, and Kevin Leyton-Brown. 2009. “Multiagent Systems: Algorithmic, Game-Theoretic, and Logical Foundations.” Choice Reviews Online 46 (10): 46–566246–5662. https://doi.org/10.5860/choice.46-5662.
```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
@book{osborne_rubinstein_1994, 
   address={Cambridge, Mass.}, 
   title={A course in game theory}, 
   ISBN={9780262150415}, 
   publisher={Mit Press}, 
   author={Osborne, Martin J and Rubinstein, Ariel}, 
   year={1994} } 
@article{shoham_leyton-brown_2009, 
   title={Multiagent systems: algorithmic, game-theoretic, and logical foundations}, 
   volume={46}, 
   DOI={https://doi.org/10.5860/choice.46-5662}, 
   number={10}, 
   journal={Choice Reviews Online}, 
   author={Shoham, Yoav and Leyton-Brown, Kevin }, 
   year={2009}, 
   month={Jun}, 
   pages={46–566246–5662} }
```

