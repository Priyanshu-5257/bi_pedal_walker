# Bipedal_walker_v3 Using Deep Q Network Learning 
### Library used - Tensorflow, Numpy , Gym


We have to find approximate q_value function of the bellman eqution.


![image](https://user-images.githubusercontent.com/94728532/219999223-e22a8688-dc59-4de8-a184-f92ea8da1af9.png)

So we create two identical neural netwrok, q_network and target_q_network.

And update the q_network according the following loss -
![image](https://user-images.githubusercontent.com/94728532/219998982-5d056e80-ca2a-454a-a48d-68cfeacaf174.png)

and then update  the q_network to target_q_network.
