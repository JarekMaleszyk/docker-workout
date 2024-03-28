1. docker build -t node-js-test-image .
2. docker run -d -p 8081:8080 --name node-js-test-container node-js-test-image