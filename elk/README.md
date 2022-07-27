## 1. 실행 방법 
### 🧑🏻 docker-compose 실행
<pre>
sh docker-on.sh
</pre>

### 🧑🏻 docker-compose 종료
<pre>
sh docker-off.sh
</pre>

</br>

## 2. 설치 정보
### 🧑🏻‍💻 1.1 Elasticsearch
```
접속 - http://127.0.0.1:9200
포트 - 9200
```
</br>

### 🧑🏻‍💻 1.2. Kibana
```
접속 - http://127.0.0.1:5601
포트 - 5601
```
</br>


## 3. 특이사항
+ Elasticsearch 1대 당 1기가 메모리 필요 (3대 * 1기가), 메모리 부족시 도커 에러 발생
```
</br>