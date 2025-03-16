# Student Grade Pretictor
An INF2008 Machine Learning Project by Group 1.

## Table of Contents
- [Background](#background)
- [Motivation](#motivation)
- [Objectives](#objectives)
- [Guide](#guide)
- [Contributors](#contributors)

## Background
There is increasing emphasis on proactive student support for educators, which indicates a growing trend in education where institutions prioritise providing early intervention and preventative measures to address potential student challenges rather than reacting to these issues when they arise.

## Motivation
Early prediction of Failure can help institutions intervene before the academic challenges escalate. This project aims to build a predictive model that forecasts students’ failing early in the school term to allow early intervention and support for students who are at risk.

## Objectives
The team has declared these objectives for our project:
- Implement and compare multiple machine learning models to predict a student passing or failing.
- Evaluate models using appropriate performance metrics
- Compare the team's implemented models with another [Scientific Paper](https://www.scitepress.org/Papers/2019/77679/77679.pdf).

## Dataset Used
The team utilized the [Open University Learning Analytics Dataset (OULAD)](https://www.kaggle.com/datasets/anlgrbz/student-demographics-online-education-dataoulad/data) due to its comprehensive and diverse data. It is a reliably sourced dataset derived from real student interactions rather than synthetically generated data, ensuring authenticity and applicability to real-world scenarios.

## Guide 

- For **Data Preprocessing, Analysis & Feature Extraction**, please refer to  
    - [1)DataProcessing_Analysis_FeatureExtraction/EDA.ipynb](1%29DataProcessing_Analysis_FeatureExtraction/EDA.ipynb)
- For **Training Data Results**, refer to the following files:
    - [2)ML_Algo/Training_LogisticRegression_ALL.ipynb](2%29ML_Algo/Training_LogisticRegression_ALL.ipynb)
    - [2)ML_Algo/Training_DT_RF_AB_FFF.ipynb](2%29ML_Algo/Training_DT_RF_AB_FFF.ipynb)
- For **Fine-Tuning Data Results**, refer to the following files:
    - [2)ML_Algo/Finetuning_Training_DT_RF_AB_Base_ALL.ipynb](2%29ML_Algo/Finetuning_Training_DT_RF_AB_Base_ALL.ipynb)
    - [2)ML_Algo/Finetuning_DT_RF_AB_CostSensitive_ALL.ipynb](2%29ML_Algo/Finetuning_DT_RF_AB_CostSensitive_ALL.ipynb)
    - [2)ML_Algo/Finetuning_DT_RF_AB_DomainAdaptation_ALL.ipynb](2%29ML_Algo/Finetuning_DT_RF_AB_DomainAdaptation_ALL.ipynb)

- For **Final Results**, refer to the following files:
    - [2)ML_Algo/FinalResults_KMeans.ipynb](2%29ML_Algo/FinalResults_KMeans.ipynb)
    - [2)ML_Algo/FinalResults_Testing+DBScan.ipynb](2%29ML_Algo/FinalResults_Testing+DBScan.ipynb)

- For Comparisons to the [Scientific Paper](https://www.scitepress.org/Papers/2019/77679/77679.pdf), refer to the following files:
    - [2)ML_Algo/PaperComparison_Dropout.ipynb](2%29ML_Algo/PaperComparison_Dropout.ipynb)
    - [2)ML_Algo/PaperComparison_Pass_Fail.ipynb](2%29ML_Algo/PaperComparison_Pass_Fail.ipynb)


## Contributors
This Project is created with love from these wonderful developers :stars:

<table>
    <tbody>
        <tr>
            <td align="center" valign="top"><a href="https://www.linkedin.com/in/travis-teo-hao-han/" target="_blank"><img src="https://drive.google.com/uc?export=view&id=1CgG7OaGfiK1osTXme4zgO_8LubSCbaEy" width="100px;" alt="Travis"/><br /><sub><b>Travis Teo</b></a><br><b>CEO</b></td>
            <td align="center" valign="top"><a href="https://www.linkedin.com/in/junjie2912/" target="_blank"><img src="https://drive.google.com/uc?export=view&id=1rQyIwC1G0pmxkV-3Uhnjbd6SjDt_WSJa" width="100px;" alt="Jun Jie"/><br /><sub><b>Jun Jie</b></a><br><b>CTO</b></td>
        </tr>
        <tr>
            <td align="center" valign="top"><a href="https://www.linkedin.com/in/yu-rui-pang/" target="_blank"><img src="https://drive.google.com/uc?export=view&id=1IasDBL-8X23HNfz7TXKsdOU-qS35HBge" width="100px;" alt="Yu Rui"/><br /><sub><b>Yu Rui</b></a><br>Senior SWE<br>Developer</b></td>
            <td align="center" valign="top"><a href="https://www.linkedin.com/in/tanhengjoo/" target="_blank"><img src="https://drive.google.com/uc?export=view&id=1uO0sSMxC-YM35bz-y9WSWaHLKrRrmm8V" width="100px;" alt="Joo"/><br /><sub><b>Joo</b></a><br>Scrum Master</b></td>
        </tr>
        <tr>
            <td align="center" valign="top"><a href="https://www.linkedin.com/in/alanwongml/" target="_blank"><img src="https://drive.google.com/uc?export=view&id=13Gu6DrQa-FtFr0IVwpb3aiWX42jqIXmV" width="100px;" alt="Alan"/><br /><sub><b>Alan</b></a><br>Janitor</b></td>
        </tr>
    </tbody>
</table>
