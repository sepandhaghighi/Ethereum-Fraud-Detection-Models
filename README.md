# Ethereum Fraud Detection Models

--------------

### [Sepand Haghighi](https://github.com/sepandhaghighi) - [Farzad Ramezani](https://github.com/Farziiii)

### September 2022

--------------

## Overview

The goal of data analytics is to detect potential fraud by spotting anomalies or deviations from “normal” behavior or patterns. To do that, an expert establishes a baseline of non-fraudulent activity to compare to the suspicious dataset. Understanding the concept of fraud detection analytics requires knowledge of the definition of the terms fraud and fraud detection. Fraud is a crime or deceptive action done by a criminal to get unlawful gain or unlawful access to information and assets. 

Fraud detection is the process of identifying this form of deceptive action. It can be done before fraud occurs, during the process of fraud, or after the fraud has taken place. Fraud detection analytics refers to a combination of techniques of fraud detection and data analytics that are employed to detect and prevent the occurrence of fraud. Some of the data analytics techniques that are used in fraud detection include data mining, clustering analysis, data pre-processing, and data matching.

It may also be possible to identify data known to be associated with fraud. Perhaps fraudulent activity is more likely to occur at certain times of the day, in certain geographic locations, in certain types of accounts or in certain amounts.

The following are the reasons why fraud detection analytics is important in organizations:

1. Reduced fraud exposure: With fraud detection analytics, the system seals any loopholes for conducting fraudulent activities. Fraudsters have limited opportunities for conducting fraud, which reduces fraud exposure.

2. Reliable fraud detection: Fraud detection analytics offers a reliable way of detecting fraudulent activity even before damage has been caused. This is in the case of early-detection systems. These systems can identify any attempt to undertake a fraudulent activity. This enhances control and security in the organization.

3. Increased customer trust: Fraud detection analytics ensures that the system of the organization is safe. When customers experience little or no security issues, they develop trust. Increased customer trust contributes towards customer loyalty, which is important for an organization’s growth.

4. Makes use of unstructured data: Many fraudsters conduct fraudulent actions when the data is unstructured. Fraud detection analytics is capable of reviewing unstructured data to identify and prevent fraudulent activities.

5. Supports data integration: This system collects data from diverse sources and combines it, which enhances the integration of data in the organization.

6. Detects hidden patterns: Some of the traditional techniques of identifying fraud may fail to detect hidden patterns. Fraud detection analytics is superior to these techniques because it can identify hidden trends, scenarios, and patterns.

7. Improved organizational performance: Fraud detection analytics minimizes fraudulent activities, which significantly reduces the loss of revenue as a result of fraud. Organizations achieve huge financial gains as a result of fraud analytics. These systems enhance efficiency and improve processes in financial transactions in organizations.

How can data analytics help detect and prevent fraud? Here are three real-world examples:

1. An insurance company used data analytics to uncover a fraudulent claim for flood damage to a car. By including social media data, its system was able to show that the car was out of town on the day the flood occurred.

2. PayPal uses data analytics to protect its customers against fraud. The company analyzes historical payment data to identify factors that are closely associated with potential fraud, such as the type of device used, country of origin and certain details from user profiles. The company uses this information to create machine-learning algorithms that evaluate each transaction for signs of fraud.

3. The SEC used data analytics to catch an investment advisor guilty of “cherry picking.” The data revealed that, rather than follow his firm’s pro rata allocation guidelines, the advisor allocated a disproportionate number of profitable trades to his account or those belonging to someone else with the same last name.

Old data analysis techniques were oriented toward extracting quantitative and statistical data characteristics. These techniques facilitate useful data interpretations and may help to urge better insights into the processes behind the info.

Although the normal data analysis techniques can indirectly lead us to knowledge, it’s still created by human analysts.

To go beyond, a knowledge analysis system has got to be equipped with a considerable amount of background, and be ready to perform reasoning tasks involving that knowledge and therefore the data provided. In effort to satisfy this goal, researchers have turned to ideas from the machine learning field.

This is a natural source of ideas, since the machine learning task are often described as turning background and examples (input) into knowledge (output).

If data processing leads to discovering meaningful patterns, data turns into information. Information or patterns that are novel, valid and potentially useful aren’t merely information, but knowledge.

One speaks of discovering knowledge, before hidden within the huge amount of knowledge, but now revealed.

The machine learning and AI solutions could also be classified into two categories: ‘supervised’ and ‘unsupervised’ learning.

These methods seek for accounts, customers, suppliers, etc. that behave ‘unusually’ so as to output suspicion scores, rules or visual anomalies, counting on the tactic .

Whether supervised or unsupervised methods are used, note that the output gives us only a sign of fraud likelihood. No stand-alone statistical analysis can assure that a specific object may be a fraudulent one, but they will identify them with very high degrees of accuracy.

Here we have compared various classification models to check which model gives the best result and also an attempt has been made to interpret them.

**Classification models:**

1. KNN
2. Random Forest
3. Neural Network (MLP)


## Datasets

We will use two data set in this report.

1. [Ethereum Fraud Detection Dataset](https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset)
2. [Ethereum Fraud Dataset](https://www.kaggle.com/datasets/gescobero/ethereum-fraud-dataset)

We will analyze these two datasets both individually and in combination.

<div style="text-align:center;" align="center">
	<table style="text-align:center;border-collapse:collapse;">
		<th>
			<td>Number of Features</td>
			<td>Total Cases</td>
			<td>Fraud Cases</td>
			<td>Non-Fraud Cases</td>
		</th>
		<tr>
			<td style="text-align:left;">Ethereum Fraud Detection Dataset</td>
			<td>37</td>
			<td>9816</td>
			<td>2179</td>
			<td>7637</td>
		</tr>
		<tr>
			<td style="text-align:left;">Ethereum Fraud Dataset</td>
			<td>31</td>
			<td>12146</td>
			<td>5150</td>
			<td>6996</td>
		</tr>
		<tr>
			<td style="text-align:left;">Merged Dataset</td>
			<td>17</td>
			<td>20302</td>
			<td>5675</td>
			<td>14627</td>
		</tr>
	</table>
	<p>Table1. Datasets Overview</p>
</div>


## Requirements

1. Python >= 3.5
2. pandas >= 0.24.2
3. matplotlib >= 3.0.3
4. seaborn >= 0.9.1
5. numpy >= 1.18.5
6. scikit-learn >= 0.22.2
7. pycm >= 2.2
8. notebook >= 5.7.4

- Run `pip install -r requirements.txt` or `pip3 install -r requirements.txt`

## Notebooks

<div style="text-align:center;" align="center">
	<table style="text-align:center;border-collapse:collapse;">
		<th>
			<td>GitHub Viewer</td>
			<td>NB Viewer</td>
			<td>Google Colab</td>
		</th>
		<tr>
			<td style="text-align:left;">Ethereum Fraud Detection Dataset</td>
			<td><a href="https://github.com/sepandhaghighi/Ethereum-Fraud-Detection-Models/blob/master/1.ipynb">Link</a></td>
			<td><a href="https://nbviewer.org/github/sepandhaghighi/Ethereum-Fraud-Detection-Models/blob/master/1.ipynb">Link</a></td>
			<td><a href="https://colab.research.google.com/github/sepandhaghighi/Ethereum-Fraud-Detection-Models/blob/master">Link</a></td>
		</tr>
		<tr>
			<td style="text-align:left;">Ethereum Fraud Dataset</td>
			<td><a href="https://github.com/sepandhaghighi/Ethereum-Fraud-Detection-Models/blob/master/2.ipynb">Link</a></td>
			<td><a href="https://nbviewer.org/github/sepandhaghighi/Ethereum-Fraud-Detection-Models/blob/master/2.ipynb">Link</a></td>
			<td><a href="https://colab.research.google.com/github/sepandhaghighi/Ethereum-Fraud-Detection-Models/blob/master">Link</a></td>
		</tr>
		<tr>
			<td style="text-align:left;">Merged Dataset</td>
			<td><a href="https://github.com/sepandhaghighi/Ethereum-Fraud-Detection-Models/blob/master/3.ipynb">Link</a></td>
			<td><a href="https://nbviewer.org/github/sepandhaghighi/Ethereum-Fraud-Detection-Models/blob/master/3.ipynb">Link</a></td>
			<td><a href="https://colab.research.google.com/github/sepandhaghighi/Ethereum-Fraud-Detection-Models/blob/master">Link</a></td>
		</tr>
	</table>
	<p>Table2. Notebooks</p>
</div>

## Analytics Example

Here you can see a limited number of examples. The full version of this analytics and all codes can be seen in the notebooks!

<div style="text-align:center;" align="center">
<pre>
ERC20_min_val_rec                                      0.154421
Total_ERC20_tnxs                                       0.114916
ERC20_uniq_rec_addr                                    0.085711
Time_Diff_between_first_and_last_Mins                  0.080427
ERC20_uniq_rec_contract_addr                           0.069955
Avg_min_between_received_tnx                           0.058168
Average_of_Unique_Received_From_Addresses              0.046456
total_ether_received                                   0.037595
total_transactions_including_tnx_to_create_contract    0.036712
ERC20_avg_val_rec                                      0.030953
avg_val_received                                       0.030111
Sent_tnx                                               0.022398
Received_Tnx                                           0.021866
min_val_sent                                           0.021263
ERC20_total_ether_sent                                 0.020375
ERC20_total_Ether_received                             0.018861
ERC20_uniq_sent_addr_1                                 0.018135
max_value_received                                     0.017657
ERC20_total_Ether_sent_contract                        0.016291
total_ether_balance                                    0.016271
min_value_received                                     0.014136
ERC20_uniq_sent_addr                                   0.013666
total_Ether_sent                                       0.011947
Avg_min_between_sent_tnx                               0.010480
avg_val_sent                                           0.010065
max_val_sent                                           0.008923
Average_of_Unique_Sent_To_Addresses                    0.008289
Number_of_Created_Contracts                            0.003955
</pre>
<p>Fig1. Features Importance</p>
<hr/>

<pre>
Best : Random Forest

Rank   Name              Class-Score       Overall-Score
1      Random Forest     0.76667           0.87778
2      KNN               0.725             0.78056
3      Neural Network    0.65              0.74722
</pre>
<p>Fig2. Confusion Matrices Compare</p>
<hr/>

<img src="images/cm.png">
<p>Fig3. Confusion Matrix</p>
<hr/>

<img src="images/rf.png">
<p>Fig4. Decision Tree Classifier Diagram</p>
</div>

## Cite

If you use this repo in your work, please cite it using the following metadata:

<pre>
Haghighi, S., & Ramezani, F. (2022). Ethereum Fraud Detection Models (Version 1.0) [Computer software]. https://github.com/sepandhaghighi/Ethereum-Fraud-Detection-Models
</pre>
<pre>

@software{Haghighi_Ethereum_Fraud_Detection_2022,
author = {Haghighi, Sepand and Ramezani, Farzad},
license = {MIT},
month = {10},
title = {{Ethereum Fraud Detection Models}},
url = {https://github.com/sepandhaghighi/Ethereum-Fraud-Detection-Models},
version = {1.0},
year = {2022}
}

</pre>
