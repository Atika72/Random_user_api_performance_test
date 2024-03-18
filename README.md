### Random User API Performance Testing

## Introduction
In this project, we'll be rigorously testing the performance of the Random User Generator API (https://randomuser.me/) through load testing. We'll simulate a scenario where a massive wave of 120,000 users access the API over a 12-hour period. This will help us achieve two key goals:

1. Measure True Capacity: We'll determine the API's actual Transactions per Second (TPS), revealing its maximum processing power under high user load.

2. Identify Bottlenecks: By analyzing the system's behavior under stress, we'll pinpoint any weaknesses that cause errors. Our target is to maintain an error rate below 1% even under heavy use.


## Tool used
 -Apache JMeter
 

## Steps for setup JMeter
-   Download and open [JMeter](https://jmeter.apache.org/download_jmeter.cgi)
-   Add thread group with users and time
-   Add sampler http request
-   Add listeners
-   Run thread group
-   

### Expected TPS(Transaction Per Second) & Bottleneck  or Stress test point: 
  Google Sheet: https://docs.google.com/spreadsheets/d/1Lm_hyyY3A40I-zrvegVnxs8IUQXzz1_QEvPtt6819mg/edit?usp=sharing

## Screenshot of expected TPS:
<img width="613" alt="Screenshot 2024-03-19 012507" src="https://github.com/Atika72/Random_user_api_performance_test/assets/67384608/184de9e8-9c64-4b9c-bf84-376bcf0d063b">

## Screenshot of Bottleneck  or Stress test point:

<img width="623" alt="Screenshot 2024-03-18 220444" src="https://github.com/Atika72/Random_user_api_performance_test/assets/67384608/e15ce1b2-1da8-4e32-b6d3-de85d0737ab0">

