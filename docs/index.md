# **AI Software Template GitOps**

This repository contains the necessary content required for managing GitOps. It was created as part of an AI Software Template execution. The associated source component is available for reference in the **Overview** tab as described in the following image.

![Overview Tab](./images/overview-dependency.png)

# **Deployed Resources**

A deployment with the following characteristics was made based on input from the AI Software Template.

## **Model & Model Server**

A [whisper.cpp]( https://github.com/containers/ai-lab-recipes/tree/main/model_servers/whispercpp) model server was deployed to serve the []() model.

!!! info

    This model server is available on port 8001!

# **Application**

The AI Software Template that was executed comes with a sample application. This application will be built from https://github.com/rhdh-JslYoon-org/rhdhpai-581-sep09-3, stored in [quay.io/rh-ee-lyoon/rhdhpai-581-sep09-3](https://quay.io/rh-ee-lyoon/rhdhpai-581-sep09-3) and deployed through ArgoCD. 

This sample application is accessible through port 8501.