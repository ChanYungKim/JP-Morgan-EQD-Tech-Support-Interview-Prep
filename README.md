# JP-Morgan-EQD-Tech-Support-Interview-Prep

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
    - does not support alerting (paid plan)

#### **Grafana**

- interactive web monitoring dashboard tool to visualize data of connected data sources (not limited to Elastic Search)
- support 다양한 DBs (data sources) --> 선택폭 넓음 
- 슬랙 / 텔레그램 / etc .. 통해 알람을 받는 기능 제공

#### **Prometheus**

#### **Telegraf**

- system metric data (RAM, CPU, etc ... ) 수집 server agent
- 데이터 수집후 특정 destination 에 적재하는 역할

#### **References**

