# 데이터 엔지니어링 튜토리얼 및 프로젝트

[1. ETL_Flight_Data.pdf](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/ETL_Flight_Data.pdf)  
 - 비행기 정보가 담긴 테이블에 대해서, 날씨에 따른 평균 비행 지연시간을 확인할 수 있는 예제입니다.
 - HiveQL을 통해 데이터를 다룬 후, Sqoop을 통해 Oracle DB로 Export 합니다.

[2. ElasticSearch_Tutorial.pdf](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/ElasticSearch_Tutorial.pdf) 
 - 엘라스틱 서치의 기본 사용방법을 정리한 튜토리얼 입니다.
 
[3. HDFS_Router_Multi_Namenode_Performence_Test.pdf](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/HDFS_Router_Multi_Namenode_Performance_Test.pdf) 
- HDFS Router 기반의 다중 네임노드 환경에서 클러스터의 성능과 안정성 개선에 대해 진행한 테스트 입니다.
- Observer Namenode는 Active Namenode에 몰리는 부하를 분산시켜주는 Load Balancer 역할을 합니다.
- Router 기반 Federation을 통한 확장에 따른 클러스터 성능 차이를 확인하고자 합니다.
- NC 소프트에서 진행한 프로젝트입니다.
![Cluster1](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/Pictures/Observer.png)
![Cluster2](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/Pictures/Federation.png)

[4. Movielens_Analysis.pdf](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/Movielens_Analysis.pdf) 
 - Hive QL을 사용해 영화 데이터를 분석하여 영화이름이나 영화장르를 중심으로 순위권에 드는 목록을 분석합니다.

[5. Movielens_Analysis_ver2.pdf](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/Movielens_Analysis_ver2.pdf) 
 - Movielens_Analysis와 비슷한 내용이나, HDFS에 저장된 내용을 Sqoop을 통해 Oracle로 Export 하는 내용입니다.

[6. Supersets_Tutorial.pdf](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/Supersets_Tutorial.pdf) 
- Twitter_Sentiment_Analysis의 내용을 Supersets을 통해 시각화 하는 내용입니다.
![Supersets](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/Pictures/Supersets.png)   

[7. Twitter_Sentiment_Analysis_PPT.pdf](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/Twitter_Sentiment_Analysis_PPT.pdf) 
- Streamsets으로 파이프라인을 만들어 Twitter 데이터를 수집,정제하고 해당 글의 긍정,중립,부정여부를 판단합니다.
- 시각화는 Kibana와 Excel 3D map을 이용하였습니다.
![Twitter](https://github.com/KimHyungkeun/Data_Engineer_Project/blob/main/Pictures/Twitter.png)   
