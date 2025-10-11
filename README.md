# MEU6505
Variable Compliance from Demonstrations for Contact-rich tasks with Offline RL


# Offline RL papers
CQL, IQL, TD3+BC, COMBO, RAMBO, MOBILE, CBOP, FQL

# Offline-to-Online(020) papers
RLPD, CAL-QL, FQL


## Meeting 1(9/28)
- task: wiping
  
- detail: Change the stiffness for wiping
- Why do we use Offline RL?
- By using offline RL with data of A-B and B-C, we can make A-C.
<img width="1098" height="419" alt="Image" src="https://github.com/user-attachments/assets/59a7710a-4428-4ab4-b3cb-87c2c69a9cbc" />

### 
Offline RL's output is stiffness `k`. 
But now, `k` is defined as `[-1,0,1]`. If we change `k` to contionous, we can stitching `k` over `t`. 
      
