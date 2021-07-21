# OpenZappelin-Subgraph
This is an initial guide to get started with using openzeppelin/subgraphs library and deploy your subgraph to the hosted-servide / studio

## Steps to deploying a subgraph 
1. ``` graph init --from-example --product hosted-service ```
2. ``` npm i @openzeppelin/subgraphs ```
3. Replace the subgraph.yaml file in the folder with [this Yaml file](https://github.com/pranavdaa/OpenZappelin-Subgraph/blob/main/subgraph.yaml)
4. ``` graph codegen ```
5. ``` graph auth --product hosted-service <token> ```
6. ``` graph deploy --product hosted-service gituser/filename ```
7. Delete all the unnecessary files created due to using the Gravitar template 

## Subgraphs that can be deployed using the openzeppelin/subgraphs library 
[Refer openzeppelin docs ](https://docs.openzeppelin.com/subgraphs/0.1.x/#modules)

## For more info and detailed explanation
1. [openzeppelin docs](https://docs.openzeppelin.com/subgraphs/0.1.x/)
2. [EthCC Presentaiton](https://www.youtube.com/watch?v=BqNpvG3m164)
