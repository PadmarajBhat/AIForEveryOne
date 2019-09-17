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
   * ML projects can be in house or outsourced but Data Science related are closer to Industry and hence most of the in house.
   * ML projects also involves adapting latest industry standard rather to build in house. This not only helps to cut down the turn around time but also increases the possibilities of adopting later version/evolution of the industry standard project.


* Not all AI projects be important to business and not business relavant problem can be addressed by AI.
   * team composite of bothe domain and ai expert should finalize the scope of AI project
   * due deligence of cost and time has to be assessed by both AI and business team
   * Business team should make sure that adequate data and expected accuracy.
   * AI team might use terms like packages (TF, keras etc), CPU and GPU and also on prem/cloud/edge deployment
      * edge is deploying the model where data resides.
* AI does not replaces the jobs but replaces the repeated tasks in the job. And there by augmenting the professional.
   

* Data need not be big data to start AI Project
   * transfer learning
   * GAN
   * SMOT 
   * can help with smaller data set
   * at times even the business requirement is short term and need not want higher accuracy 

* Case study to identify the components of the complex AI:
   * Smart Speaker: 
      * Indentify the trigger word
      * speech recognition
      * intent detection
      * execution
   * Self driving car:
      Inut
      * Image/ radar
      * GPS /map
            * car detection
            * pedestrian detection
            * lane detection
            * obstacle detection
            * trajectory detection
               * motion planning
* AI Team usuallly (not mandatorily) has below teams:
   * software engineers - specialized task/actions on ml predictions
   * machine learning engineer - building model and meets the expected accuracy
   * machine learning research - extends the state of the art in ml
   * applied ml scientist -  ml engineer + researcher
   * Data scientist - insight driven presentation to teams/executives
   * Data Engineer - 
      - Organize data
      - accessible, secure and cost effective way
   * AI Product manager - makes decision of what is feasible and valueable

* AI Transformation Playbook
   * Execute pilot projects to gain momentum
      * experiment a little to gain traction which would kick start momentum of the AI project drive
   * Build in house AI Team
      * One team catering to multiple bu units. So that company can stratergise AI skillset development and thus other domains can leverage it.
   * AI training:
      * leads and executive : AI essentials and stratergy, resource allocation 
      * AI software engineering team :  hands on training for AI fundamentals 
   * AI Stratergy :
      * AI can be only specific to industry specific
      * keep cycling around collecting more data and improve product.
      * there may be an industry which might be doing similar work but your team need not compete with it. All we need to do is focus on applying latest industry standard available for our purpose.
