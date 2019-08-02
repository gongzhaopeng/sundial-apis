# sundial-apis
Sundial Swagger APIs.

# Swagger-UI Command(MUST COPY FROM RAW, ELSE \" WILL BE REPLACED BY "):
docker run -p 80:8080 -e URLS="[{name:\"QUESTION-SERVICE\", url:\"https://raw.githubusercontent.com/gongzhaopeng/sundial-apis/master/benbenedu-alpha-question-service-genesis-swagger.yaml\"}, {name:\"EXAMPAPER-SERVICE\", url:\"https://raw.githubusercontent.com/gongzhaopeng/sundial-apis/master/benbenedu-alpha-exampaper-service-genesis-swagger.yaml\"}, {name:\"EXAM-SERVICE\", url:\"https://raw.githubusercontent.com/gongzhaopeng/sundial-apis/master/benbenedu-beta-exam-service-genesis-swagger.yaml\"}, {name:\"ANSWERSHEET-SERVICE\", url:\"https://raw.githubusercontent.com/gongzhaopeng/sundial-apis/master/benbenedu-alpha-answersheet-service-genesis-swagger.yaml\"}, {name:\"RESOURCE-SERVICE\", url:\"https://raw.githubusercontent.com/gongzhaopeng/sundial-apis/master/benbenedu-beta-resource-service-genesis-swagger.yaml\"}, {name:\"ACCOUNT-SERVICE\", url:\"https://raw.githubusercontent.com/gongzhaopeng/sundial-apis/master/benbenedu-beta-account-service-genesis-swagger.yaml\"}, {name:\"MOUSE\", url:\"https://raw.githubusercontent.com/gongzhaopeng/sundial-apis/master/mouse.yaml\"}]" swaggerapi/swagger-ui

# Swagger-Editor Command:
docker run -d -p 81:8080 swaggerapi/swagger-editor
