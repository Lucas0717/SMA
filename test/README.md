## test data (3k repos with dependency files)

3k_valid_repos



## test file

1. Get dependency:         
(1).py files:      
    - extractor_depend_1repo.py: Extract the 1-hop in the dependencies of the repository
    - extractor_depend.py: Extract the multi-hop in the dependencies of the repository
(2).ipynb files:
    - test_extractor_depend_1repo_1hop.ipynb: test and extract 1-hop dependencies in 1 repository
    - test_extractor_depend_1repo_2hop.ipynb: test and extract 2-hop dependencies in 1 repository
    - test_extractor_depend_3k_1hop.ipynb: test and extract 1-hop dependencies in 3k repository
2. cluter:      
(1).py file:
    - cluster.py: load data and use kmeans,gmm, LDA methods to analysis these repositories similarity
(2).ipynb file:           
    - test_cluster.ipynb: Given data repository name and get analysis result
      
## Output result

Extract dependency result:
- 1_repodata_1hop: Get extract  1-hop dependency result from 1 repository
- 1_repodata_2hop: Get extract  2-hop dependency result from 1 repository
- 3k_repodata_1hop: Get extract  1-hop dependency result from 3k repository

  
