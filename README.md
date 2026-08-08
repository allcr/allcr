# Craig Allen


## Toolbox

Daily: Python (Polars, statsmodels, scikit-learn), R, Stan/brms, SQL, git, Linux. 

Deep history: q/kdb+ from execution-desk years. 

Working: Docker, Kafka-style streaming, TimescaleDB, Grafana, GPU training (ROCm), QuestDB.

Interests that keep showing up in the work: stochastic processes, Bayesian data analysis and models


## Working on 


** Bayesian Workflow

I'm working my way through the text book [Bayesian Workflow](https://www.routledge.com/Bayesian-Workflow/Gelman-Vehtari-McElreath-Simpson-Margossian-Yao-Kennedy-Gabry-Burkner-Modrak-Barajas/p/book/9780367490140) and logging my code here.

** sta9794_redux

Refactoring the final project from my Experimental Design and Causal Inference course to include more robust methods. 

** 2025 F1 Analysis

Refactoring my F1 analysis into a presentable notebook/dashboard/Shiny application. 


** pmdgp  

I've decided against publishing this as the work to get the data generating process working was detracting from the main goal of reliably monitoring model drift via a dashboard. 

~~I'm teaching myself model drift monitoring by building a world that drifts on command (work in progress). I didn't feel comfortable trying to learn how to use these tools without good data; I couldn't find anything that had any prebuilt drifts that I was happy with.  So instead of pointing monitoring tools at data I didn't like, I'm building the data-generating process myself: a stochastic machine-degradation simulation with seven configurable drift regimes I can inject at will. 

The data generating process models the operation of a machine in a factory and the wear-and-tear of daily use. We also model the costs associated with repair, and multiple repairmen with different skill sets. 

Currently using four models to predict when the machine needs to be serviced:
- An Oracle model that sees the ground truth and knows exactly when and how the machine will break\which repairman to call, 
- A Vowpal Wabbit contextual bandit,
- a Bayesian Dynamic linear model, and 
- a fixed repair schuedule of thirty days. ~~


[LinkedIn](https://linkedin.com/in/craigjallen) 
