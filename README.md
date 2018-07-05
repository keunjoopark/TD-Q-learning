# TD-Q-learning

## Temporal-Difference Learning = Dynamic Programming + MC method
* DP: When we know a given model, we ca update the value function every t+1 time.
* MC: It can be use even if there is no given model. However, we have to finish all episodes to update the value function. 
Thus, TD is find the value function at t+1 time under MC method by dynamic programming.

### Advantage of TD prediction
* It does not require the model about next state and reward of Dynamic Programming. We don't need to wait until finish episodes like MC method. So, Temporal-Difference Learning(non-episodic) is faster than MC method(episodic)

## Q Learning : off-policy TD control
* On-policy: use Q(St+1, a)
* Off-policy: use Q(S', a) -> optimal action-value function

## Difference between Sarsa (on-policy) and Q-Learning (off-policy)
* In reward, Sarsa looks have better results. However, Sarsa learned by safe path and Q-learning learned by optimal path.
