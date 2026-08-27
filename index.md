---
layout: default
subnav: workshops
---


# The 9th International Workshop on Symbolic and Numerical Reasoning about games (SNR)

Games are a fundamental framework for modelling interaction and strategic behaviour in verification, synthesis and logic. Reasoning about games often requires a combination of symbolic methods, such as strategy improvement, fixpoint computation, automata-theoretic techniques, and logical encodings, with numerical methods, such as value iteration, policy iteration, approximation, and quantitative optimisation.

The goal of the **SNR (Symbolic and Numerical Reasoning about games)** workshop is to provide a platform for exploring symbolic and numerical techniques for reasoning about games, with applications in verification, synthesis, reactive systems, probabilistic models, and related areas.

SNR will be held on Saturday **5 September 2026**. 


###  Call for submissions
SNR solicits submissions for contributed talks in the form of extended abstracts (LIPIcs style, upto 2 pages without reference). We encourage submissions of ongoing works and new results as well as works published elsewhere. All submissions will undergo a lightweight peer-reviewing process. Authors of selected submissions presenting original unpublished work will subsequently be invited to submit a full version of their work for publication in formal proceedings, to be published by [EPTCS](https://about.eptcs.org/).
          

Submissions are judged on the expected interest and relevance to the theme of the workshop. The topics include (but are not limited to) :
- Numerical and symbolic methods in games 
- Automata theory for strategy synthesis 
- Verification using games  
- Logical method for games 
- Quantitative aspects of games 
- Strategy synthesis in probabilistic models 
- Heuristics for solving games

Submissions should be made via EasyChair [https://easychair.org/conferences/?conf=snr26](https://easychair.org/conferences/?conf=snr26). 



### Program Committee
[K. S. Thejaswini](https://thejaswiniraghavan.github.io/) (Université Libre de Bruxelles)             
[Mickael Randour](https://www.randour.com/) (FRS - FNRS and UMONS - Université de Mons)           
[Suman Sadhukhan](https://sites.google.com/view/suman-sadhukhan/home) (TU Clausthal)          
[Aline Goeminne](https://alinegoeminne.github.io/) (ENS Rennes, IRISA)        
[Sven Schewe](https://www.csc.liv.ac.uk/~sven/) (University of Liverpool)           
[Ashutosh Trivedi](https://ashutoshtrivedi.com/)  (University of Colorado, Boulder) (PC Chair)             
[Dominik Wojtczak](https://intranet.csc.liv.ac.uk/~dominik/)  (University of Liverpool)             
[Anirban Majumdar](https://anirban11.github.io/) (TIFR, Mumbai)           


### Invited Talks
[Munyque Mittelmann](https://sites.google.com/view/mittelmann), CNRS,  LIPN, Université Sorbonne-Paris-Nord   

<b>Can We Change the Game? Reasoning about Dynamic Multi-Agent Systems</b>       
<details>
          <summary>Abstract</summary>
Most research on logics for strategic reasoning in Multi-Agent Systems (MAS) has traditionally focused on static models, such as concurrent game structures, which represent a fixed set of system configurations and the transitions between them. Such models are unable to capture scenarios where the system’s structure undergoes dynamic changes, whether triggered by agent actions or caused by an external factor.  As MAS increasingly operate in dynamic and unpredictable settings, their design and maintenance require reasoning about how structural changes affect system behavior. When existing models fail to produce desirable outcomes or are incorrect, computing repairs offers an alternative to complete redesigns. This talk explores recent advances in logic-based methods for dynamic MAS, including reasoning about model modifications and repairing flawed games.
</details>   

[Prince Mathew](https://princemathew07.github.io/), Université Libre de Bruxelles (ULB)       

<b>Active Learning for the Synthesis of POMDP Policies</b>
<details>
          <summary>Abstract</summary>
Partially Observable Markov Decision Processes (POMDPs) are a fundamental model for decision-making under uncertainty, with applications ranging from robotics and autonomous systems to planning and verification. However, synthesising correct policies for POMDPs is, in general, undecidable. Existing approaches face a fundamental trade-off. Sampling-based techniques, such as reinforcement learning and Monte Carlo methods, scale well to large problems but provide no formal correctness guarantees, making them unsuitable for safety-critical applications. In contrast, formal synthesis techniques offer correctness-by-construction but often struggle to scale.       
          
          

In this talk, I will present a synthesis framework that combines automata learning, model checking, and policy-generation techniques to bridge this gap. Inspired by Angluin's L* algorithm, the framework views policy generation as a membership oracle and model checking as an equivalence oracle to actively learn finite-state controllers. The membership oracle can be instantiated by any algorithm capable of suggesting a suitable action for a given action-observation history. I will present the theoretical foundations of the framework and show that it is relatively complete: whenever the policy induced by the membership oracle is regular, the algorithm is guaranteed to synthesise a correct finite-state controller. Finally, I will present experimental results demonstrating that the proposed method successfully solves threshold-safety problems that remain challenging for existing formal synthesis tools. This work illustrates how active learning provides a principled bridge between scalable policy-generation techniques and formal methods, opening a promising new direction for POMDP policy synthesis.
</details>      

[James Main](https://alexandermain.github.io/), University of Oxford      

<b> Randomised Decision Making: Expressiveness and Complexity </b>
<details>
          <summary>Abstract</summary>
Games on graphs are a prevalent framework for automated controller synthesis for reactive systems. Given a game modelling the interaction of a reactive system and its environment, we can construct a controller (enforcing some formal specification) from a good strategy in the game, where a strategy describes the decisions to be made based on the past history of the ongoing play. In many settings, e.g., concurrent, imperfect information or multi-objective settings, pure (i.e., deterministic) strategies do not suffice to play optimally. In the first two cases, randomised decision making can be used to be unpredictable against an adversary, and in the latter case, randomness is useful to balance multiple objectives.      
          


This talk will focus on the power and expressiveness of randomised strategies. First, we will survey different definitions of randomised strategies. In particular, we will consider finite-memory strategies, i.e., strategies that can be encoded as finite automata with outputs. Finite-memory strategies are of particular interest for synthesis, as these represent strategies that can be implemented in practice. We will present a complete taxonomy of finite-memory randomised strategies in terms of expressive power. In the second part of the talk, we will focus on multi-objective Markov decision processes (i.e., one-player stochastic games), and provide a complete description of randomisation requirements for this setting. In particular, we show that limited randomisation often suffices for these multi-objective specifications.          


This talk is based on joint works with Mickael Randour (Université de Mons, Belgium).      

</details>     


#### Program 

The full program can be found [here](https://confest-2026.github.io/program/snr/).       

The program includes an open problem session which will feature very short individual presentations of open problems withing the scope of the workshop topics.  Anyone is welcome to present problems. Please contact the organisers if you intend to present an open problem.        

      

#### Organisers
[Sougata Bose](https://sites.google.com/view/sougatabose) (UMONS - Université de Mons)            
[Soumyajit Paul](https://soumyajit-paul.github.io/) (University of Liverpool)                
[Ashutosh Trivedi](https://ashutoshtrivedi.com/) (University of Colorado, Boulder)                    
[Dominik Wojtczak](https://intranet.csc.liv.ac.uk/~dominik/) (University of Liverpool)            

#### Previous Editions
- [8th International Workshop on Symbolic-Numeric Methods for Reachability Analysis (SNR'22)](https://plv.colorado.edu/snr22/), affiliated with CONFEST'22
- [7th Int. Workshop on Symbolic-Numeric Methods for Reasoning about CPS and IoT (SNR’21)](https://sites.google.com/view/snr21/), affiliated with QONFEST'21.
- [6th Int. Workshop on Symbolic-Numeric Methods for Reasoning about CPS and IoT (SNR’20)](https://www.cs.cas.cz/snr2020/), affiliated with QONFEST'20.
- [5th Int. Workshop on Symbolic-Numeric Methods for Reasoning about CPS and IoT (SNR’19)](https://snr19.ncl.ac.uk/index.html), affiliated with CPS-IoT Week 2019.
- [4rd Int. Workshop on Symbolic and Numerical Methods for Reachability Analysis (SNR’18)](https://snr2018.verivital.com/), affiliated with ETAPS'18.
- [3rd Int. Workshop on Symbolic and Numerical Methods for Reachability Analysis (SNR’17)](https://snr2017.pages.ist.ac.at/), affiliated with ETAPS'17.
- [2nd Int. Workshop on Symbolic and Numerical Methods for Reachability Analysis (SNR’16)](https://snr2016.pages.ist.ac.at/), affiliated with CPSWeek’16.
- [1st Int. Workshop on Symbolic and Numerical Methods for Reachability Analysis (SNR’15)](https://snrworkshop.github.io/), affiliated with CAV’15.



