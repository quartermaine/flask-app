# flask-app

This is a repo for a flask app with continuous delivery with AWS Elastic Beanstalk


### Deploy via AWs Cloud9 + AWS Code Build

A. create cloud9 environment

B. manually install [EB CLI](https://github.com/aws/aws-elastic-beanstalk-cli-setup)

C. follow the [Flask EB tutorial](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create-deploy-python-flask.html) to create venv, built the flask app and deploy your site with the EB CLI

D. if you want to use the Makefile don't forget to add **pytest** and **pylint** in the requirements file to be installed inside the environment and update **eb deploy** in the Makefile with the environment you created in the previous step with **eb create**

E. create your buildspec.yml file







