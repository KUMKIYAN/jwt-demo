# jwt-demo

  curl --location --request POST 'http://localhost:8081/authenticate' \
--header 'Content-Type: application/json' \
--data-raw '{
    "username" : "admin",
    "password" : "password"
}'


curl --location --request GET 'http://localhost:8081/' \
> --header 'Authorization: Bearer eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJhZG1pbiIsImV4cCI6MTY3MzM1ODgxMiwiaWF0IjoxNjczMzU4NTEyfQ.0Jg4_-we5yrbLAbE7p7wHVAHZu6sQPKOXxPHtVAoOJ2oTfZj6I0jXIk_1A2zUrgitXAszCk3mEvnUrv2XbZLfg'
