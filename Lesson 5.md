# Lesson 5
##CenturyLink Consumer Residential Bot Deep Dive

### Definitions:
*** 'Orchestrator'** 
Helps navigate the dialog by sending information either by input text or context to Watson Assistant
*** 'Router skill'**
Identifies the functional skill required and sends notice back to Orchestrator
*** 'masterAuthenticator'**
Authenication mapped to a context variable and routed to MASTER_ROUTER to begin authenticating the user. 
*** 'Router Classifier'**
Selects which workspace to direct users to based on intent triggered

![Test](Master_Router.png)


