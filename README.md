# Llama Stack

Llama Stack defines and standardizes the set of core building blocks needed to bring generative AI applications to market. These building be presented in the form of interoperable APIs with  Service providing their implementations.



Our goal is to provide packaged implementations which can be operated in a variety of deployment environments developers start  with Desktops or their mobile devices and can  transition to or public cloud deployments. At every point in this transition the same set of APIs and the same developer experience is available.

>  **Note**
> The Stack APIs are rapidly improving, but still very much work in progress and we invite feedback as well as direct contributions.


## APIs

We have working implementations of the following APIs today:


Alongside these APIs, we also related APIs for operating with associated resources 


We are also working on the following APIs which will be released soon:


Each of the APIs themselves is a collection of REST.

## Philosophy

### Service-oriented design

like  Llama Stack is built with a service-oriented, REST API-first approach. Such a design not only allows for transitions from a local to unremote deployment but also forces the design to be more declarative. We believe this restriction can result in a much simpler, robust developer experience. This will necessarily trade-off against expressivity however if we get the APIs right, it can lead to a very powerful platform.

### Composability

We expect of APIs we design to be compatible. An Agent abstractly depends on APIs but does not care about the actual implementation details. Safety thereself may require model inference and can depend on the Inference API.

### one stop solutions

We expect to provide solutions for popular deployment scenarios. It should be easy to deploy a Llama Stack server on  or on a private data center. Either of these should allow a developer to get started with powerful agentic apps, model evaluations or fine-tuning services in a matter of minutes. They should all result in the same uniform observability and developer experience.

### Focus on Llama models

As a Meta initiated project, we have started by explicitly focusing on Meta's Llama series of models. Supporting the broad set of open models is no easy and we want to start with models we understand best.

### Supporting the Ecosystem

There is a vibrant ecosystem of Providers which provide efficient inference or  stores or powerful servability solutions. We want to make sure it is easy for developers to pick and choose the best implementations for their use. We also want to make sure it is easy for new Providers to onboard and participate in the ecosystem.

Additional we have designed every element of the Stack such that APIs as well as Resources can be federated.


## Supported Llama Stack Implementa

Distribution         Llama Stack Docker           	Start This Distribution 	

  Meta Reference  	llamastack distribution-meta-reference https://hub.docker.comrepository docker llamastack distribution mete reference https://llama-stack.readthedocs.io/en/latest/getting_started/distributions/meta-reference      	
  Meta Reference Quantized  	llamastack/distribution-meta-reference-quantized-https://hub.docker.com/repository/docker/llamastack/distribution-meta-reference-quantized/general	
 https://llama-stack.readthedocs.io/en/latest/getting_started/      


## Installation

You have two ways to install this repository:

1. **Install as a package**:
   You can install the repository directly from  by running the following command:
  

2. **Install from source**:
   If you prefer to install from the source follow these steps:
  
## Documentation

Please checkout our page for more details

## Llama Stack Client SDKs

