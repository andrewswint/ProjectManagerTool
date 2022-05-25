# ProjectManagerTool

Postman calls:
Create Project:
  curl --location --request POST 'http://localhost:8080/api/project' \
  --header 'Content-Type: application/json' \
  --data-raw '{
    "projectName": "{{projectName}}",
    "projectIdentifier": "{{projectIdentifier}}",
      "description": "{{description}}"
  }'
