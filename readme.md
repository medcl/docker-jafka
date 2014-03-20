How to use?

#build
docker build -t jafka  .

#run
docker run -i -t -p 9092:9092  jafka /bin/bash

docker run -i -t  jafka /usr/local/jafka-1.4.0-SNAPSHOT/bin/run.sh console


