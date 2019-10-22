# tennis-agent

in the 3nd project of the **DRLND** from udacity we will try to train two agent to play tennis

<p align="center">
  <img src="https://video.udacity-data.com/topher/2018/May/5af7955a_tennis/tennis.png"/>
</p>

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping. 

---
so how to run this project ?

the depepandencies that you need to install inorder to run this project are:

  - numpy
  - matplotlib
  - pytorch
  - pandas
  - jupyter
  - and the Unity ML-Agents (you find below the link to how install it page ) 

or you can install them in defrent ways, by derectly run the folowing scripit in the terminal ` pip install -r requirements.txt `

or you have to create a vertual python env and  install the dependencies . or you can simply follow the instractions below
 - 1 - clone this project 
 - 2 - move to it's folder and open the terminal there 
 - 3 - run `  conda env create -f tennis-agent.yml ` this will create an envirenment and install the needed depandecies automaticly <br/


 and finaly now you will have to install the Unity ML-Agent, inorder to do that just [follow this link](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) <br/>

now if u did all this correctly you are able to run the code. in the same folder run this ` source activate tennis-agent ` than `jupyter notebook`. and yfrom the notebook home page you can open `tennis-agent.jpynb`.

