# RL_lspi_svd
RL SVD feature policy iteration

For 50 iterations or until A_next is identical to A

1)Sample according to policy

K=number of fetures

weights_list=np.zeros(n_actions,K)


For each action:
  2) Crate matrix A, A_next for each action
   
  4) Calculte low rank approximation

  6) Calculate by Woodbery Identity invers e for calculation of weights
  7) 
  weights_list[action,:]=weight

8) Update for agent our weight 
9) 
agent.set_weights(weights_list)

10) Sample according to agent policy

