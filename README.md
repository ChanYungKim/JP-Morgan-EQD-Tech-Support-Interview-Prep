# JP-Morgan-EQD-Tech-Support-Interview-Prep

## Introduction
- 
- during my time at SocGen ...
  - provided morning support and developed server connection testing tool for automation 
  - setting up ELK stack, grafana and telegraf on the application servers
- developed adapter that collects Update Order and Update Execution data from Elastic Search through Elastic Search Query and API to populate date to SocGen's internal web dashboard and provided support on capacity monitoring

## Technical

### Monitoring Tools 

#### **ELK (Elastic Search, Logstash, Kibana)**

- Elastic Search

  - document based db (데이터 적재)

- Logstash

  -

- Kibana

  - 단점
    - only uses Elastic Search as datasource
    - does not support free alerting service (paid plan)

#### **Grafana**

- interactive web monitoring dashboard tool to visualize data of connected data sources (not limited to Elastic Search)
- support 다양한 DBs (data sources) --> 선택폭 넓음 
- 슬랙 / 텔레그램 / etc .. 통해 알람을 받는 기능 제공

#### **Prometheus**

#### **Telegraf**

- system metric data (RAM, CPU, etc ... ) 수집 server agent
- 데이터 수집후 특정 destination 에 적재하는 역할

### FIX


#### **References**
[DVWY DevOps](https://youtube.com/playlist?list=PL3Re5Ri5rZmkDCTd8X8qRQtmRES1SVyNf&si=nRtZwEJOeI9GLR2O)
