python producer -> kafka broker -> logstash -> elasticsearch -> kibana dashboard

elasticsearch and kibana can be run using

docker-compose -f <filename of yaml> up

logstash has to be installed in the system, run via following command
logstash -f logstash.conf
