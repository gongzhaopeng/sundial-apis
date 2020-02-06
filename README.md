# sundial-apis
Sundial Swagger APIs.

# Swagger-Editor Command:
docker run -d -p 81:8080 swaggerapi/swagger-editor

# Swagger-UI Command(MUST COPY FROM RAW, ELSE \\" WILL BE REPLACED BY "):
## DEV
docker run -p 82:8080 -e URLS="[{name:\"QUESTION-SERVICE\", url:\"http://192.168.0.158:8081/benbenedu-alpha-question-service-genesis-swagger.yaml\"}, {name:\"EXAMPAPER-SERVICE\", url:\"http://192.168.0.158:8081/benbenedu-alpha-exampaper-service-genesis-swagger.yaml\"}, {name:\"RESOURCE-SERVICE\", url:\"http://192.168.0.158:8081/benbenedu-beta-resource-service-genesis-swagger.yaml\"}, {name:\"DELIVERY-SERVICE\", url:\"http://192.168.0.158:8081/benbenedu-gamma-delivery-service-genesis-swagger.yaml\"}, {name:\"REPORT-SERVICE\", url:\"http://192.168.0.158:8081/sundial-report.yaml\"}, {name:\"MOUSE\", url:\"http://192.168.0.158:8081/mouse.yaml\"}]" swaggerapi/swagger-ui
## PROD
docker run -p 92:8080 -e URLS="[{name:\"QUESTION-SERVICE\", url:\"http://192.168.0.158:8091/benbenedu-alpha-question-service-genesis-swagger.yaml\"}, {name:\"EXAMPAPER-SERVICE\", url:\"http://192.168.0.158:8091/benbenedu-alpha-exampaper-service-genesis-swagger.yaml\"}, {name:\"RESOURCE-SERVICE\", url:\"http://192.168.0.158:8091/benbenedu-beta-resource-service-genesis-swagger.yaml\"}, {name:\"DELIVERY-SERVICE\", url:\"http://192.168.0.158:8091/benbenedu-gamma-delivery-service-genesis-swagger.yaml\"}, {name:\"REPORT-SERVICE\", url:\"http://192.168.0.158:8091/sundial-report.yaml\"}, {name:\"MOUSE\", url:\"http://192.168.0.158:8091/mouse.yaml\"}]" swaggerapi/swagger-ui
