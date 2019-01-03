# machineLearning 

I am in a group with Weihao Zeng, Yue Cheng, Xin Su. We took the Avito Demand Prediction Challenge. You can find more about the challenge at (https://www.kaggle.com/c/avito-demand-prediction/submissions?sortBy=date&group=all&page=1)
Because of the humongous data size, we had to run our model on AWS EC2 instance. Setting up the instance was quite a journey, so to those who may use AWS EC2 with python and H2O, I am going to attach my setups for my instance. 


1. you need to get your annaconda installed. You can find the detailed steps at (https://medium.com/@alexjsanchez/python-3-notebooks-on-aws-ec2-in-15-mostly-easy-steps-2ec5e662c6c6)
2. you need to install java. You can find detailed steps at (https://blog.knoldus.com/2017/02/08/installing-latest-oracle-jdk-on-linux-ec2-instance-centos/)
3. you need to install h2o. you can find detailed steps at (http://h2o-release.s3.amazonaws.com/h2o/master/3888/docs-website/h2o-docs/downloading.html#install-in-python)
4. to prevent jupyter notebook from shutting down automatically: 
https://medium.com/@jim901127/running-jupyter-notebook-in-the-background-b6e950c4b7ee
