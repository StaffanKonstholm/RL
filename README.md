# Answers
## 1.1
### Define the following properties of the FishingDerbyRL MDP:
**State Space S** The total number of states of the enironment is subdivision * subdivision or 10x10

**Action Space A** All possible actions are {left, right, up, down, stay}

## 3.1
The learning rate alpha determines how fast we discard old ḱnowledge in favor of new knowledge. At 1, we do not care about
previous knowledge and therefore have a high variance.

The discount factor gamma determines the agents willingness to wait for reward. At a low gamma the agent prioritiezes immidiate
rewars. At a gamma of 1, the agent sees no difference between getting a reward now and getting a reward next year.