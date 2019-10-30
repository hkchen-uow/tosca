# MiCADO: METADATA Ontology for TOSCA Repository & Use Cases

##This repository holds the TOSCA related material developed as a part of the [COLA Project](https://project-cola.eu/)
------------
### ADT/
###### Application Description Templates are kept here
These templates describe the application topology and policies for COLA use-cases. They are submitted to the toscasubmitter component in MiCADO to deploy applications to the cloud.

There are mainly two types of ADT:
* *prototypes/*

    Live application's ADTs are kept here.The ADT name standard format is constructed using the following Metadata:
    
    * *APP_ID*: Unique ID for the APP.
    * *APP_Name*: Application name.
    * *APP_Keywords*: List of application keywords.
    * *APP_Version*: Application version.
     
* *tests-demos/*

    Tests/Demos ADTs are kept here

### node_example/
###### node_example definitions are kept here
There are three types of node_example:
* *applications/*
    
   The *application* node example name standard format is constructed using the following Metadata:
   
    * *APP_ID*: Unique ID for the APP.
    * *APP_Name*: Application name.
    * *APP_Keywords*: List of application keywords
    * *APP_Version*: Application version.
    
* *Occopus/*

    The *Occopus* node example name standard format is constructed using the following Metadata:
    
    * *PROVIDER_NAME*: The name of the cloud provider.

* *policies/*
    
    The *policies* node example name standard format is constructed using the following Metadata:
    
    * *APP_ID*: Unique ID for the APP.
    * *APP_Name*: Application name.
    * *APP_Deployment*: The deployment type of the application, e.g. VM or container
    * *Policy_Type*: Type of the policy, e.g. Monitoring, Scaling, Network and Secret.
    * *Policy_Name*: The name of the policy.
    * *Policy_Keywords*: List of policy keywords, e.g. Basic, CPU, Memory, Deadline, Optimizer ……
    * *Policy_Version*: Policy version.
    
------------
#### Use Cases

