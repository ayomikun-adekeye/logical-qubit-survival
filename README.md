# logical-qubit-survival

In this repo, I did another quantum memory experiment. Unlike the last one where I was estimating QEC code thresholds, in this one I saw how an increased number of error detection rounds affect the experiment. More measurement rounds gives us more data for the decoding step which should be good, but here's the tradeoff. More measurements equals more noise introduced into the system, because measurement is an external interaction. Eventually, this noise destroys the quantum memory, so the expected advantage is lost.  

I did this with Riverlane's Deltakit, an SDK dedicated to quantum error correction.

**The Workflow**

Define the circuit for the code you want to study

Inject some noise via noise models

Simulate & Decode 

Visualize results by plotting the logical error rate against the number of rounds.




