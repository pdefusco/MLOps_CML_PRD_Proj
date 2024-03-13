# CML MLOps Workshop - PRD Project

This is the PRD git repository for the [CML MLOps Workshop](https://github.com/pdefusco/CML_MLOps_ACE_Workshop). For a more detailed expalantion of the use case and artifacts, please visit the [step by step guide](https://github.com/pdefusco/CML_MLOps_ACE_Workshop).

### Project Deployment

If you are following the MLOps Workshop guide, this project will be automatically deployed for you when you run notebook [3_register_model.ipynb](https://github.com/pdefusco/MLOps_CML_DEV_Proj/blob/main/code/3_register_model.ipynb). You cannot deploy this project as a standalone. Please complete the labs in the DEV project before coming to this repository.

### High Level Workflow

In this part of the workshop you will develop a Classifier to predict credit card fraud. All scripts are located in the "code" folder.

1. With a CML Session with Workbench Editor run "0_data_gen.py" to create synthetic credit card data.
2. With a CML Session with JupyterLab Editor and Spark Add-On 3.2+ run through the "1_data_exploration.ipynb" notebook to familiarize yourself with the data. Run every cell without modification.
3. Using the same CML Session, run through the "2_model_building.ipynb" notebook to build a Spark Mllib classifier and manage data with Apache Iceberg. Run every cell without modification.
4. Using the same CML Session, run through the "3_register_model.ipynb" notebook to deploy the PRD project and then the classifier in it. Run every cell without modification.
5. Navigate back to the CML Home Page. You should now see a new CML Project denominated "PRD". Open it and continue from there with the instructions provided in the readme.  
