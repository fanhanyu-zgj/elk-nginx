step1:使用docker-compose 运行所有容器（kibana,logstash,elasticsearch,nginx）
  ```
  docker-compose up -d
  ```
step2:
  ```
  创建地理位置索引，已兼容地理坐标
  详见 kibana.txt
  ```
step3:
  ```
  kibana 索引模式创建索引值为nginx*的索引
  ```
step4:
  ```
  创建map，添加图层，选择文档
  ```