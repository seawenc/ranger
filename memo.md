参考： https://ranger.apache.org/quick_start_guide.html

```bash
#将jdk切换为1.8
export JAVA_HOME=%jdk 1.8 Home%
mvn -Pall clean 
mvn -Pall -DskipTests=true clean compile package install
```
