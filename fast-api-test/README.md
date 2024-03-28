1. docker build -t fast-api-test-image .
2. docker run -d -p 8082:8000 --name fast-api-test-container fast-api-test-image