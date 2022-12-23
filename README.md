# june-commerce-fast-api
Fast API를 이용한 Commerce 연습


# install
```shell
pip install -r requireemtns.txt
```



# default ENV sample

```env
BOOTSTRAP_SERVERS="localhost:9092,localhost:9093,localhost:9094"
TOPIC_PEOPLE_BASIC_NAME="people.basic.python"
TOPIC_PEOPLE_BASIC_PARTITIONS=3
TOPIC_PEOPLE_BASIC_REPLICATION_FACTOR=3

```


# Run
```shell
uvicorn main::app --reload
```
