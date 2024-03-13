# CML MLOps Workshop - PRD Project

This is the PRD git repository for the [CML MLOps Workshop](https://github.com/pdefusco/CML_MLOps_ACE_Workshop). For a more detailed expalantion of the use case and artifacts, please visit the [step by step guide](https://github.com/pdefusco/CML_MLOps_ACE_Workshop).

### Project Deployment

If you are following the MLOps Workshop guide, this project will be automatically deployed for you when you run notebook [3_register_model.ipynb](https://github.com/pdefusco/MLOps_CML_DEV_Proj/blob/main/code/3_register_model.ipynb). You cannot deploy this project as a standalone. Please complete the labs in the DEV project before coming to this repository.

### High Level Workflow

In this part of the workshop you will monitor and redeploy a Classifier to predict credit card fraud. This project will effectively work as your production environment. All scripts are located in the "code" folder.

1. With a CML Session with Workbench Editor run "04_mlops_simulation.py" to create synthetic credit card prediction requests to the API endpoint hosted in this project.
2. Using the same CML Session, run through the "05_mlops_visual.py" script to monitor model quality in production.
3. Using the same CML Session, run through the "06_redeployment.py" script to deploy a new model build in production.
