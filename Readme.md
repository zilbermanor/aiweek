# Data Science from Research to Production with Jupyter, Kubeflow & Nuclio
## Ai-Week (17.11.2019)

3 hour workshop, showing how to use [**Nuclio**](http://nuclio.io) & [**MLRun**](http://www.github.com/mlrun/mlrun) with [*Kubeflow*](https://www.kubeflow.org/) to deploy jupyter notebooks as serverless functions or pipelines without leaving the jupyter environment.

## Preperations
### Install Nuclio [[website](http://nuclio.io)|[github](http://www.github.com/nuclio/nuclio)]
 - Locally on docker: ```docker run -p 8070:8070 -v /var/run/docker.sock:/var/run/docker.sock -v /tmp:/tmp nuclio/dashboard:stable-amd64```
 - On Kubernetes (Or local minikube) / AKS / GCP: [Nuclio installation notes](https://nuclio.io/docs/latest/setup/)

### Jupyter integration
- ```pip install nuclio-jupyter```
 
### Install MLRun [[github](https://github.com/mlrun/mlrun)]
- ```pip install mlrun```