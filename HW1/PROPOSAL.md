## DATA620 Spring 2023  

### Team Members  

Josh Iden  
Wilson Ng  

![](https://github.com/josh1den/DATA620-GROUP/blob/main/HW1/IMG/ASSIGNMENT.png)

### Idea 1: Social Network: MOOC User Action Dataset

Source: [https://snap.stanford.edu/data/act-mooc.html](https://snap.stanford.edu/data/act-mooc.html)

From dataset documentation:

The MOOC user action dataset represents the actions taken by users on a popular MOOC platform. The actions are represented as a directed, temporal network. The nodes represent users and course activities (targets), and edges represent the actions by users on the targets. The actions have attributes and timestamps. To protect user privacy, we anonimize the users and timestamps are standardized to start from timestamp 0. The dataset is directed, temporal, and attributed.

Additionally, each action has a binary label, representing whether the user dropped-out of the course after this action, i.e., whether this is last action of the user.

Could centrality measures be used to predict the number of actions students perform before dropping out? 
