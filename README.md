# AWS-AIML-ondemand-trainings
Unofficial repository of training resources for the AWS Artificial Intelligennce &amp; Machine Learning (AIML) services




## Deep Dive video series
This includes 2 sets of 5 one-hour videos, diving deeper on the basic functionality and the MLOps feautes of Amazon SageMaker. You will need an AWS account to access the videos, under Skills Builder. 

### Amazon SageMaker basic functionality
Amazon SageMaker is a fully managed service to build, train, and deploy machine learning (ML) models for any use case with fully managed infrastructure, tools, and workflows. In this series, learn how to use Amazon SageMaker to support your end-to-end ML lifecycle, from data labeling to model deployment. Understand the core functionality of the service, how Amazon SageMaker works under the hood, and how to develop your ML models in a cost-effective manner. This series is designed for data engineers, data scientists, and developers with prior experience in machine learning and basic knowledge of AWS services. 

1. [**Data labelling and quick starts**](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/11791/aws-partnercast-amazon-sagemaker-deep-dive-series-data-labeling-and-quick-starts-technical) (i.e. Ground Truth, Canvas, Autopilot, JumpStart). Supervised machine learning algorithms rely on high-quality labelled training data. Learn how to take advantage of Amazon SageMaker Ground Truth, which offers pre-built and custom labelling workflows for any use case, various workforce options, automated labelling, and more. Once a labelled dataset is available, learn how to use Amazon SageMaker Canvas, Autopilot, and JumpStart, built to help data analysts and data scientists quickly train high-quality machine learning models using auto ML and open-source models.

2. [**Experimentation and development with notebooks**](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/11794/aws-partnercast-amazon-sagemaker-deep-dive-series-experimentation-and-development-with-notebooks-technical) Amazon SageMaker enables data scientists to develop algorithms in familiar development environments, using powerful frameworks. In this video, learn how to choose between classic Jupyter notebooks, Amazon SageMaker Studio, and RStudio to set up your preferred workspace. For every environment, Amazon SageMaker provides built-in algorithms, managed environments with popular frameworks and libraries, and the option to bring your own environment and algorithm. Understanding each mechanism and how to use it helps data scientists increase their productivity.

3. [**Data preprocessing and feature engineering**](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/11798/aws-partnercast-amazon-sagemaker-deep-dive-series-data-preprocessing-and-feature-engineering-technical) Data scientists and data engineers spend a significant amount of time aggregating, analysing, and cleaning data before performing feature engineering. In this session, learn how to use Amazon SageMaker Data Wrangler to build a visual data processing workflow. Alternatively, learn about Amazon SageMaker Processing Jobs to perform data manipulation through code, or learn how Amazon SageMaker integrates with Amazon EMR for processing data on large clusters using Hadoop or Spark. Finally, understand how Amazon SageMaker Clarify can be used to identify bias in datasets as part of your responsible AI workflow.

4. [**Model training and tuning**](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/11790/aws-partnercast-amazon-sagemaker-deep-dive-series-model-training-and-tuning-technical) It can be challenging to arrange the infrastructure needed for large-scale model training and hyperparameter tuning. Amazon SageMaker provides scalable, easy-to-use training jobs and hyperparameter tuning jobs to run workloads for large datasets and models. Learn how to use these core Amazon SageMaker components, and understand the additional features available for reducing cost and improving productivity, including Debugger, distributed training, and managed spot training.

5. [**Model deployment**](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/11792/aws-partnercast-amazon-sagemaker-deep-dive-series-model-deployment-technical) Determining the best deployment methods for your model requires balancing requirements for cost, availability, latency, reliability, and more. In this session, learn about the various deployment methods provided by Amazon SageMaker, the benefits of each method, and how to make the right choice using Inference Recommender.


### MLOps with Amazon SageMaker
Amazon SageMaker is a managed ML platform that aims to streamline the whole, end-to-end Machine Learning (ML) lifecycle. In this series, we will dive deeper on the value proposition of Amazon SageMaker for Machine Learning Operations (MLOps). We start from the basics: what is MLOps, how it relates to DevOps and why we need it. We then gradually, dive deeper on different tools that Amazon SageMaker offers for MLOps, covering task orchestration, feature store, inference options, and MLOps architectural patterns. This series is designed for data engineers, data scientists, and developers with prior experience in Amazon SageMaker and basic knowledge of AWS services. 

1. [**Introduction to MLOps**](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12800/aws-partnercast-mlops-on-amazon-sagemaker-series-introduction-to-mlops-technical) This is an introductory session to MLOps, with zero assumptions about the viewers’ knowledge. In this session, you will learn about the concept of MLOps, how it relates to DevOps, as well as, the business benefits of adopting it. You will see MLOps from 3 different dimensions: people, processes and technology. Finally, you will learn about the MLOps Amazon SageMaker value proposition, and the tools that AWS offers in this domain. 

2. [**Orchestration tools**](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12797/aws-partnercast-mlops-on-amazon-sagemaker-series-orchestration-tools-for-mlops-technical) The ML lifecycle is an experimental, iterative process, with many different branches and workflows. In this session you will learn about the native AWS task orchestration tools. First, we will start with an overview of the most known MLOps orchestration tools (3rd party and AWS native). Then, we will dive deeper on AWS Step Functions and SageMaker Pipelines. You will learn how to create, manage and orchestrate ML workflows, in order to operationalize your ML projects. 

3. [**Feature Store**](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12801/aws-partnercast-mlops-on-amazon-sagemaker-series-feature-store-technical) During the model development phase, long time is usually spent in feature engineering. In many cases, ML teams tend to re-compute features across different projects, leading to duplicated effort, reproducibility issues and slower time to market. In this session you will learn how Amazon SageMaker Feature Store can provide a solution to this, by offering a central repository of feature values. You will learn how to ingest data to online/offline stores, as well as, different architectural patterns for incorporating Feature Store to your ML projects. 

4. [**MLOps architectures**](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12901/aws-partnercast-mlops-on-amazon-sagemaker-series-mlops-architectures-technical) When it comes MLOps, there is no one universal implementation approach. In this session you will learn about different architectural patterns for MLOps, including single and multi-account approaches. You will also learn about SageMaker Feature Store, SageMaker Project and SageMaker Lineage Tracking, and how you can incorporate them into your MLOps architectures. 

5. [**Inference**](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12900/aws-partnercast-mlops-on-amazon-sagemaker-series-inference-technical) Deploying a model to production, is not the end of the ML lifecycle. Specific actions have to take place in order to ensure that the model stays relevant, and avoid different types of drift. In this session, you will learn how to use SageMaker Model Monitor, in order to ensure that your models will remain free of data/model/bias/explainability drift. You will also learn how to conduct A/B testing on different model versions, using Amazon SageMaker’s managed endpoints.


## Full pre-recorded immersion days
This is a series of full training events (~4h), focusing on specific topics, including presentations and hands-on labs. The PDF slide deck is also included. Each event has its own series of training notebooks (links included in the slide deck) which you can try at your own time.

- **Amazon SageMaker basics**. [[recording](https://d2upiv8700olhh.cloudfront.net/Meeting-Recording-SageMaker-DataWrangler-Training-Basics(6-1-2023).mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-SageMaker-basics(2023-01).pdf)]
    - Introduction to Amazon SageMaker
    - Amazon SageMaker Data Wrangler
    - Training with Built-in algorithms (XGBoost)
    - Inference options (real-time endpoints, batch transform)
