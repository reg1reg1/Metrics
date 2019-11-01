# Cyber Metrics: Abstract
Quantifying cyber risk is one of the biggest challenges in info sec today. Since the advent of the Orange book, people have been trying to quantify security or measure it in some form. Does the phrase "less" or "more secure" have any inference ? Though security may never be directly measured, can there be some metrics for it. There are various frameworks, and organizations such as PCI-DSS, NIST standards, BSIMM which focuses on software security. 

This endeavour of cyber metrics done by the research team at NYU asks the question whether a reliable metrics of cyber metrics can be formed by asking the gut feeling of cybersecurity experts.

NYU's cyber metrics index of expert opinion or "gut feeling" on status of cyber security has been collecting opinion data over the last 8 years. This is an attempt to parse through and analyze the data with the ELK stack and conclude whether any corelations can be drawn between "gut feeling of experts" and "the actual state of cyber security". 


## Overview
A part of a team of 6 students in the Fall semester, working to find relation between various aspects of the data collected by survey started 8 years back by Dan Geer and Mukul Pareek. This repository stores the work done by me as part of contributing to the index and improving the data collection process and co-relation 

## Collection

The collection of the data has been done over the past few years by sending out survey questions to handpicked cyber security veterans and experts in fields on a monthly basis, and storing the data in a csv format. Over-time this posed challenges, as the insights that can be drawn from flat files is limited, as well as the searchability of data is also restricted. It was then collectively decided to move to better way of collecting, aggregating and visualizing this data. The collective plan is to now ship the data in a streamlined basis into a manageable format. This repository documents work done in this area using the ELK stack (Elasticsearch, Logstash , Kibana) and also outlines the plan for the future setup of the data pipeline.

<h3> Collection infrastructure </h3> (planned) for the cyber metrics index is shown below. 
![alt test](./arch.png)



## Corelation of different aspects of data


