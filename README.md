# SIG-BPS

## Configuraciones de ELK Stack del Proyecto SIG-BPS  

Elasticsearch: eslasticsearch.yml  
Logstash: logstash.conf  
Kibana: kibana.yml  

## Comando para iniciar Logstash  
```bash
logstash -f "Ubicacion del archivo de configuracion de logstash" --config.reload.automatic
```  

## Url embed de Kibana para los graficos  
```html
http://localhost:5601/app/dashboards#/view/020c4c67-574f-4d89-88d3-28f943bad2f3?_g=()&embed=true
```  
