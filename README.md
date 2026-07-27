# Craig Allen

Data scientist by way of ten years in financial services: trade-floor
systems, an algorithmic execution desk, and risk & regulatory
program work at a global bank. Currently finishing an M.S. in Statistics



## Toolbox

Daily: Python (Polars, NumPy, scikit-learn), R, Stan/brms, SQL, git, Linux. 

Deep history: q/kdb+ from execution-desk years. 

Working: Docker, Kafka-style streaming, TimescaleDB, Grafana, GPU training (ROCm).

Interests that keep showing up in the work: stochastic processes, Bayesian data anylsis and models


## Working on 

** pmdgp  
I'm teaching myself drift monitoring by building a world that drifts on command (work in progress). I didn't feel comfortable trying to learn how to use these tools without good data; I couldn't find anything that had any prebuild drifts that I was happy with.  So instead of pointing monitoring tools at data I didn't like, I'm building the data-generating process myself: a stochastic machine-degradation simulation with seven configurable drift regimes I can inject at will. 

The data generating process models the operation of a machine in a factory and the wear-and-tear of daily use. We also model the costs associated with repair, and multiple repairmen with different skill sets. 

Currently using four models to predict when the machine needs to be serviced:
- An Oracle model that sees the ground truth and knows exactly when and how the machine will break\which repairman to call, 
- A Vowpal Wabbit contextual bandit,
- a Bayesian Dynamic linear model, and 
- a fixed repair schuedule of thirty days. 


## Now 

Building out the pmdgp lab (fleet calibration, hierarchical hyperpriors in Stan) and looking for data science / quantitative roles

[LinkedIn](https://linkedin.com/in/craigjallen) 
