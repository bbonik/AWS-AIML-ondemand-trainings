# AWS-AIML-ondemand-trainings
Unofficial repository of training resources for the AWS Artificial Intelligennce &amp; Machine Learning (AIML) services

## Table of Contents
1. [Generative AI](#generative-ai)
2. [Deep Dive series: Amazon SageMaker basic functionality](#amazon-sageMaker-basic-functionality)
2. [Deep Dive series: MLOps with Amazon SageMaker](#mlops-with-Amazon-SageMaker)
3. [Full pre-recorded immersion days](#full-pre-recorded-immersion-days)
4. [AIML Business Jumpstart series](#aiml-business-jumpstart-series)
5. [Service Updates sessions](#service-updates-sessions)
6. [Demos](#demos)

## Generative AI
- **GenAI L200**: 2h training on the latest AWS GenAI features (24 October 2024) [[recording](https://d2upiv8700olhh.cloudfront.net/GenAI/GenAI-L200-Oct2024.mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/GenAI/GenAI-L200-Oct2024.pdf)]
    - Business track (00:00:00)
    - Technical track (SageMaker, Bedrock, AmazonQ) (00:28:00)
    - Q&A (01:32:00)
- **GenAI PowerUp day 2**: 7h training on **MLOps and Security for GenAI** (3 September 2024) [[recording](https://d2upiv8700olhh.cloudfront.net/GenAI/GenAI-PowerUp-day2(MLOps-Security).mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/GenAI/GenAI-PowerUp-day2(MLOps-Security).pdf)]
    - A framework for Operationalizing GenAI applications (00:06:00)
    - MLOps for GenAI (01:25:00)
    - DEMO: Amazon Bedrock Prompt Management (02:23:15)
    - DEMO: Amazon Bedrock Prompt Flows (02:32:00)
    - Labs (03:41:40)
    - Security for GenAI (05:35:00)
- **GenAI PowerUp day 1**: 7h training on **Retrieval Augmented Generation** (19 June 2024) [[recording](https://d2upiv8700olhh.cloudfront.net/GenAI/GenAI-PowerUp-1-RAG-ASEAN.mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/GenAI/GenAI-PowerUp-1-RAG-ASEAN.pdf)]
    - Business training & AWS GenAI value proposition (00:04:24)
    - RAG basics (00:48:00)
    - RAG with Amazon Q Business (01:14:00)
    - RAG with Amazon Bedrock Knowledge Bases (01:31:00)
    - DIY RAG with Amazon SageMaker & Amazon Bedrock (02:03:00)
    - Comparison of RAG implementations (02:20:35)
    - Labs walkthrough (03:48:30)
    - Advanced RAG techniques (06:02:30)
    - RAG evaluation (06:32:30)
    - Security considerations (06:48:00)
- 3h training and demo sessions (19 October 2023) [[recording](https://d2upiv8700olhh.cloudfront.net/GenAI/GenAI-training(October2023).mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/GenAI/GenAI-training(October2023).pdf)]
    - Intro to GenAI: 00:02:00
    - Basics of Foundation Models: 00:14:00
    - Use-cases: 00:33:00
    - Prompt Engineering: 00:38:00
    - The AWS GenAI value proposition: 00:52:00
    - Amazon SageMaker Jumpstart: 00:59:00
    - Amazon Bedrock: 01:15:00
    - AWS custom silicon for GenAI: 01:54:00
    - Amazon CodeWhisperer: 01:55:00
    - Retrieval Augmented Generation (RAG): 01:58:00
    - Amazon SageMaker Studio Jumpstart walkthrough : 02:15:00
    - Deploying and using Flan T5 XL: 02:25:00
    - Deploying and using Stable Diffusion 2.1: 02:41:00
    - Example Finetunning Stable Diffusion: 02:47:00
    - Example Domain Adaptation Finetuning (GPT-J 6B): 02:49:00

## Deep Dive video series (Amazon SageMaker & MLOps)
This includes 2 sets of 5 one-hour videos, diving deeper on the basic functionality and the MLOps feautes of Amazon SageMaker. **You will need an AWS account in order to access this material in SkillsBuiler**. 

### Amazon SageMaker basic functionality
Amazon SageMaker is a fully managed service to build, train, and deploy machine learning (ML) models for any use case with fully managed infrastructure, tools, and workflows. In this series, learn how to use Amazon SageMaker to support your end-to-end ML lifecycle, from data labeling to model deployment. Understand the core functionality of the service, how Amazon SageMaker works under the hood, and how to develop your ML models in a cost-effective manner. This series is designed for data engineers, data scientists, and developers with prior experience in machine learning and basic knowledge of AWS services. 

1. **[Data labelling and quick starts](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/11791/aws-partnercast-amazon-sagemaker-deep-dive-series-data-labeling-and-quick-starts-technical)** (i.e. Ground Truth, Canvas, Autopilot, JumpStart). Supervised machine learning algorithms rely on high-quality labelled training data. Learn how to take advantage of Amazon SageMaker Ground Truth, which offers pre-built and custom labelling workflows for any use case, various workforce options, automated labelling, and more. Once a labelled dataset is available, learn how to use Amazon SageMaker Canvas, Autopilot, and JumpStart, built to help data analysts and data scientists quickly train high-quality machine learning models using auto ML and open-source models.

2. **[Experimentation and development with notebooks](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/11794/aws-partnercast-amazon-sagemaker-deep-dive-series-experimentation-and-development-with-notebooks-technical)** Amazon SageMaker enables data scientists to develop algorithms in familiar development environments, using powerful frameworks. In this video, learn how to choose between classic Jupyter notebooks, Amazon SageMaker Studio, and RStudio to set up your preferred workspace. For every environment, Amazon SageMaker provides built-in algorithms, managed environments with popular frameworks and libraries, and the option to bring your own environment and algorithm. Understanding each mechanism and how to use it helps data scientists increase their productivity.

3. **[Data preprocessing and feature engineering](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/11798/aws-partnercast-amazon-sagemaker-deep-dive-series-data-preprocessing-and-feature-engineering-technical)** Data scientists and data engineers spend a significant amount of time aggregating, analysing, and cleaning data before performing feature engineering. In this session, learn how to use Amazon SageMaker Data Wrangler to build a visual data processing workflow. Alternatively, learn about Amazon SageMaker Processing Jobs to perform data manipulation through code, or learn how Amazon SageMaker integrates with Amazon EMR for processing data on large clusters using Hadoop or Spark. Finally, understand how Amazon SageMaker Clarify can be used to identify bias in datasets as part of your responsible AI workflow.

4. **[Model training and tuning](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/11790/aws-partnercast-amazon-sagemaker-deep-dive-series-model-training-and-tuning-technical)** It can be challenging to arrange the infrastructure needed for large-scale model training and hyperparameter tuning. Amazon SageMaker provides scalable, easy-to-use training jobs and hyperparameter tuning jobs to run workloads for large datasets and models. Learn how to use these core Amazon SageMaker components, and understand the additional features available for reducing cost and improving productivity, including Debugger, distributed training, and managed spot training.

5. **[Model deployment](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/11792/aws-partnercast-amazon-sagemaker-deep-dive-series-model-deployment-technical)** Determining the best deployment methods for your model requires balancing requirements for cost, availability, latency, reliability, and more. In this session, learn about the various deployment methods provided by Amazon SageMaker, the benefits of each method, and how to make the right choice using Inference Recommender.


### MLOps with Amazon SageMaker
Amazon SageMaker is a managed ML platform that aims to streamline the whole, end-to-end Machine Learning (ML) lifecycle. In this series, we will dive deeper on the value proposition of Amazon SageMaker for Machine Learning Operations (MLOps). We start from the basics: what is MLOps, how it relates to DevOps and why we need it. We then gradually, dive deeper on different tools that Amazon SageMaker offers for MLOps, covering task orchestration, feature store, inference options, and MLOps architectural patterns. This series is designed for data engineers, data scientists, and developers with prior experience in Amazon SageMaker and basic knowledge of AWS services. You will need an AWS account in order to access this SkillsBuiler material.

1. **[Introduction to MLOps](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12800/aws-partnercast-mlops-on-amazon-sagemaker-series-introduction-to-mlops-technical)** This is an introductory session to MLOps, with zero assumptions about the viewers’ knowledge. In this session, you will learn about the concept of MLOps, how it relates to DevOps, as well as, the business benefits of adopting it. You will see MLOps from 3 different dimensions: people, processes and technology. Finally, you will learn about the MLOps Amazon SageMaker value proposition, and the tools that AWS offers in this domain. 

2. **[Orchestration tools](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12797/aws-partnercast-mlops-on-amazon-sagemaker-series-orchestration-tools-for-mlops-technical)** The ML lifecycle is an experimental, iterative process, with many different branches and workflows. In this session you will learn about the native AWS task orchestration tools. First, we will start with an overview of the most known MLOps orchestration tools (3rd party and AWS native). Then, we will dive deeper on AWS Step Functions and SageMaker Pipelines. You will learn how to create, manage and orchestrate ML workflows, in order to operationalize your ML projects. 

3. **[Feature Store](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12801/aws-partnercast-mlops-on-amazon-sagemaker-series-feature-store-technical)** During the model development phase, long time is usually spent in feature engineering. In many cases, ML teams tend to re-compute features across different projects, leading to duplicated effort, reproducibility issues and slower time to market. In this session you will learn how Amazon SageMaker Feature Store can provide a solution to this, by offering a central repository of feature values. You will learn how to ingest data to online/offline stores, as well as, different architectural patterns for incorporating Feature Store to your ML projects. 

4. **[MLOps architectures](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12901/aws-partnercast-mlops-on-amazon-sagemaker-series-mlops-architectures-technical)** When it comes MLOps, there is no one universal implementation approach. In this session you will learn about different architectural patterns for MLOps, including single and multi-account approaches. You will also learn about SageMaker Feature Store, SageMaker Project and SageMaker Lineage Tracking, and how you can incorporate them into your MLOps architectures. 

5. **[Inference](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12900/aws-partnercast-mlops-on-amazon-sagemaker-series-inference-technical)** Deploying a model to production, is not the end of the ML lifecycle. Specific actions have to take place in order to ensure that the model stays relevant, and avoid different types of drift. In this session, you will learn how to use SageMaker Model Monitor, in order to ensure that your models will remain free of data/model/bias/explainability drift. You will also learn how to conduct A/B testing on different model versions, using Amazon SageMaker’s managed endpoints.


## Full pre-recorded immersion days
This is a series of full training events, focusing on specific topics, including presentations and hands-on labs. The PDF slide deck is also included. Each event has its own series of training notebooks (links included in the slide deck) which you can try at your own time.

- **Amazon SageMaker overview (~1.5h)**. [[recording](https://d2upiv8700olhh.cloudfront.net/ODS-SageMaker-overview(2022-04).mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-SageMaker-overview(2022-04).pdf)]
    - Introduction to most of the features of Amazon SageMaker
    - End-to-end MLOps demo in SageMaker Studio using SageMaker Projects. 
- **Amazon SageMaker basics (~4h)**. [[recording](https://d2upiv8700olhh.cloudfront.net/ODS-SageMaker-basics(2023-01).mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-SageMaker-basics(2023-01).pdf)]
    - Introduction to Amazon SageMaker
    - Amazon SageMaker Data Wrangler
    - Training with Built-in algorithms (XGBoost)
    - Inference options (real-time endpoints, batch transform)
- **Amazon Forecast (~4.5h)**. [[recording](https://d2upiv8700olhh.cloudfront.net/ODS-Forecast-immersion-day(2023-01).mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-Forecast-immersion-day(2023-01)-v2.pdf)]
    - Guidance on forecasting projects
    - Introduction to Amazon Forecast
    - Deep dive on the features of Amazon Forecast
    - Tips & tricks
    - Customer case studies
    - Resources
- **Intelligent Document Processing: Amazon Textract (2h)**. [[recording](https://d2upiv8700olhh.cloudfront.net/ODS-IDP-Textract(2023-06-09).mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-Textract-Comprehend-IDP(2023-06).pdf)]
    - Introduction to IDP
    - Introduction to Amazon IDP services
    - Deep Dive on Amazon Textract
    - Demos and notebooks
- **Amazon Rekognition & Identity Verification (4h)**. [[recording](https://d2upiv8700olhh.cloudfront.net/immersion-days/ODS-Amazon-Rekognition-immersion-day(20-9-2023).mov)][[slides](https://d2upiv8700olhh.cloudfront.net/immersion-days/ODS-Amazon-Rekognition-immersion-day(20-9-2023).pdf)]
    - Introduction to Amazon Rekognition
    - Deep Dive on Amazon Rekognition APIs
    - Deep Dive on Amazon Rekognition Custom Labels
    - Identity Verification & Virtual Proctoring
    - Hands-on labs


## AIML Business Jumpstart series
AIML Business Jumpstart is a series of 1-hour trainings aiming at helping with structuring and managing AIML projects, through the lens of a **3D customer engagement model (Discover-Design-Deliver)**. This includes sharing field experience on how to qualify AIML opportunities, how to prioritize them, and how to educate/guide customers. The program starts with an overview of AIML and gradually focuses on specific use-cases, e.g. Personalization, MLOps etc. *You will need an AWS account to access the videos, under Skills Builder*. 

- **How to shape your AIML opportunities for success (May2022)**. [[recording](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/12749/aws-partnercast-the-consultative-approach-way-to-attract-cultivate-mature-your-aiml-opportunities-business)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-PartnerCast-AIML-May2022.pdf)]
- **Identifying and Shaping Successful Personalization Engagements (July2022)**. [[recording](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/13319/aws-partnercast-aiml-business-jumpstart-series-how-to-drive-a-successful-personalization-engagement-technical)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-PartnerCast-Personalization-July2022.pdf)]
- **How to Modernize & Automate Business Workflows With Intelligent Document Processing(Aug2022)**. [[recording](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/13810/aws-partnercast-how-to-modernize-automate-customers-business-workflows-with-intelligent-document-processing-business)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-PartnerCast-IDP-Aug2022.pdf)]
- **How to structure and scale Machine Learning Operations (MLOps) engagements (Nov2022)**. [[recording](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/14483/aws-partnercast-how-to-structure-and-scale-your-mlops-engagements-business)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-PartnerCast_MLOps_18Oct_2022.pdf)]
- **How to structure and scale Machine Learning Operations (MLOps) engagements (March2023)**. [[recording](https://d2upiv8700olhh.cloudfront.net/ODS-PartnerCast-MLOps(2023-03-24).mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-PartnerCast-MLOps(2023-03-24).pdf)]
- **Identifying and Shaping Successful Intelligent Search Engagements (February2023)**. [[recording](https://d2upiv8700olhh.cloudfront.net/ODS-PartnerCast-Knowledge-Portal-March2023.mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-PartnerCast-Knowledge-Portal-March2023.pdf)]
- **Maturing Engagement for Generative AI: Maximizing Benefits, Minimizing Risks (March2024)**. [[recording](https://amazon.webex.com/amazon/ldr.php?RCID=b767f1ae43bdfa8b31ab44517a775cba)][[slides](https://d2upiv8700olhh.cloudfront.net/GenAI/AIML-Business-Jumpstart-GenAI-success(2024-03-01).pdf)]



## Service updates sessions
AWS re:Invent is the largest AWS event where all the new advancements are announced. The following are recordings of the latest updates announced in AWS re:Invent, focusing in AI/ML, as well as quarterly updates on the AWS AIML stack. *You will need an AWS account to access some of the videos, under Skills Builder*. 

- **2025 Q1 AIML + GenAI service updates**. [[recording](https://amazon.webex.com/webappng/sites/amazon/recording/1d44f4f206d4103e9fdffad02c3d4d0f/playback)][[slides](https://d2upiv8700olhh.cloudfront.net/service-updates/2025Q1-AIML-service-updates.pdf)]
- **2024 Q4 AIML + GenAI service updates (re:Invent2024 recap)**. [[recording](https://amazon.webex.com/webappng/sites/amazon/recording/412e7b85c59b103dbf5faed4481fe1f9/playback)][[slides](https://d2upiv8700olhh.cloudfront.net/service-updates/Q42024(reInvent)-AIML-Service-Updates.pdf)]
- **2024 Q3 AIML + GenAI service updates**. [[recording](https://d2upiv8700olhh.cloudfront.net/whats-new-series/AWS_aiml_updates_Q3_2024.mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/whats-new-series/AWS_aiml_updates_Q3_2024.pdf)]
- **2024 H1 AIML + GenAI service updates**. [[recording](https://d2upiv8700olhh.cloudfront.net/whats-new-series/AWS_aiml_updates_H1_2024.mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/whats-new-series/AWS_aiml_updates_H1_2024.pdf)]
- **re:Invent2023 recap (GenAI & AIML)**. [[recording](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/18651/aws-partnercast-reinvent-recap-aws-aiml-services-technical)][[slides](https://explore.skillbuilder.aws/learn/course/18651/play/104781/reinvent-recap-aws-aiml-services)] (you need to be logged in SkillsBuilder)
- **2023 Q3 AIML service updates**. [[recording](https://amazon.webex.com/recordingservice/sites/amazon/recording/db50e5dd4aea103ca76d86c87d5b8840/playback)][[slides](https://d2upiv8700olhh.cloudfront.net/202310_Q3_AIML_updates.pdf)]
- **2023 Q2 AIML service updates**. [[recording](https://amazon.webex.com/webappng/sites/amazon/recording/7a92d23d0370103c926300505681f793/playback)]
- **2023 Q1 AIML service updates**. [[recording](https://amazon.webex.com/webappng/sites/amazon/recording/e6d76185bbeb103baafa00505681a350/playback)]
- **re:Invent2022 recap (AI services)**. [[recording](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/15270/aws-partnercast-reinvent-2022-announcements-ai-services-technical)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-reinvent2022-recap-AIServices-Feb9-2023.pdf)] (you need to be logged in SkillsBuilder)
- **re:Invent2022 recap (Amazon SageMaker)**. [[recording](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/15282/aws-partnercast-reinvent2022-aiml-recap-amazon-sagemaker-technical)][[slides](https://d2upiv8700olhh.cloudfront.net/ODS-reinvent-recap-SageMaker-Feb7-2023.pdf)] (you need to be logged in SkillsBuilder)

## Demos
Recordings and walkthroughs of AI/ML AWS services for particular use-cases.

- **Low-Code/No-Code ML for FSI**. [[recording](https://d2upiv8700olhh.cloudfront.net/DEMO-Canvas-QuickSight-FSI-walkthrough.mp4)][[slides](https://d2upiv8700olhh.cloudfront.net/DEMO-Canvas-QuickSight-FSI-slides.pdf)]
    - ML problem: predicting loan default.
    - Using Amazon SageMaker Canvas for data preparation, model training and predictions.
    - Using Amazon QuickSight for visualizing model predictions. 
    
- **Low-Code/No-Code ML for Retail**. [[recording](https://d2upiv8700olhh.cloudfront.net/DEMO-Canvas-Forecast-QuickSight-Retail-walkthrough.mp4)]
    - ML problem: timeseries forecasting.
    - Using Amazon SageMaker Canvas for data preparation, model training and predictions.
    - Using Amazon Forecast for timeseries forecasting. 
    - Using Amazon QuickSight for visualizing model predictions. 
    - Using AWS Step Functions for automation. 
