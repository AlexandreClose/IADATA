docker-compose -f create-certs.yml run --rm create_certs

Creating network "es_elk" with the default driver
Creating volume "es_certs" with default driver
WARNING: An illegal reflective access operation has occurred
WARNING: Illegal reflective access by org.bouncycastle.jcajce.provider.drbg.DRBG (file:/usr/share/elasticsearch/lib/tools/security-cli/bcprov-jdk15on-1.61.jar) to constructor sun.security.provider.Sun()
WARNING: Please consider reporting this to the maintainers of org.bouncycastle.jcajce.provider.drbg.DRBG
WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
WARNING: All illegal access operations will be denied in a future release
Archive:  /certs/bundle.zip
   creating: /certs/ca/
  inflating: /certs/ca/ca.crt
   creating: /certs/elasticsearch/
  inflating: /certs/elasticsearch/elasticsearch.crt
  inflating: /certs/elasticsearch/elasticsearch.key
   creating: /certs/elasticsearch1/
  inflating: /certs/elasticsearch1/elasticsearch1.crt
  inflating: /certs/elasticsearch1/elasticsearch1.key
   creating: /certs/elasticsearch2/
  inflating: /certs/elasticsearch2/elasticsearch2.crt
  inflating: /certs/elasticsearch2/elasticsearch2.key
   creating: /certs/logstash/
  inflating: /certs/logstash/logstash.crt
  inflating: /certs/logstash/logstash.key
   creating: /certs/kibana/
  inflating: /certs/kibana/kibana.crt
  inflating: /certs/kibana/kibana.key
