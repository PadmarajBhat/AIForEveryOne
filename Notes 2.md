##### Key Notes from week 2 training:
* Workflow of machine learning project  
    * collect data ==> train ==> deploy (and collect data)
    * though it sounds very silly for ml developer, it is indeed common mistake to take each step for granted.
        * collect data : data collection should happen from heterogenous system, so as to avail maximum various during training and very less surprises at prediction time. People often carried away with the size or number of samples but actually give no importance to quality
        * train data: it is not just model.fit. selection of metric to evaluate, experimentation with models, hyper parameter tuning, loss function and optimizer, thourough testing
        * deploy: take into consideration of size of model and its compatibility with host device (mobile cloud js). Thorough plan on data feedback to improve the model. CI/CD plan may be through tensorflow extended
        

* Workflow of datascience project
   * collect data ==> analyze data ==> hypothesis and actions
      * a datascientist would have various ideas to analyze the data from different angles and finally come up with hypothesis about the problem statement. He would also provide visualization on the insights.

* Datascience is about analytics and machine learning is about targetting a solution. Datascience is about exploring and ml is to exploit the one we have (data). Based on the data analytics business makes decision to go ahead with ml and its encompassing application.
