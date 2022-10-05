### Setup local env & enable subs in local repo
```shell
git clone  https://github.com/sf-xuyan/EMP-Connector.git

cd EMP-Connector

mvn clean package

java -jar target/emp-connector-0.0.1-SNAPSHOT-phat.jar <username> <password> /data/Employee__ChangeEvent
```

### Test change event
1. Create Employee record in connected SF org
2. Monitor console to check Received json event message