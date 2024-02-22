step1:构建nginx镜像
  ```
  docker build -t nginx:1.12.0 .
  ```
step2:使用docker-compose 运行所有容器（kibana,logstash,elasticsearch,nginx）
  ```
  docker-compose up -d
  ```
step3:
  ```
  创建地理位置索引，已兼容地理坐标
  详见 kibana.txt
  ```
step4:
  ```
  kibana 索引模式创建索引值为nginx*的索引
  ```
step5:
  ```
  创建map，添加图层，选择文档
  ```
  
