# DemoAPIPublisher
This is a script to import 51 demo APIs to a WSO2 API Manager setup

### Prerequisites

1. Download WSO2 API manager and start the server
2. Download and Initialize [API CTL tool](https://apim.docs.wso2.com/en/latest/learn/api-controller/getting-started-with-wso2-api-controller/#download-and-initialize-the-ctl-tool) 
3. Add an [environment](https://apim.docs.wso2.com/en/latest/learn/api-controller/getting-started-with-wso2-api-controller/#add-an-environment) as dev. 

### Import APIs to the API manager setup

1. apictl vcs deploy -e <environment>
