# stock-service
Service that searches the text for the names of publicly traded companies and then annotates the text with current stock price quotes for those companies

## Setup

- Install Java 8
- Install jruby-9.1.7.0
- Install curl

## Commands

1. `$ bundle install`
2. `$ java -jar stock-service.war`
3. `$ curl -d "Hello Apple, a computer company" http://localhost:8080/stockify`

## THIRD PARTY DEPRECATION WARNING

- Since the `finance.yahoo.com` is no longer available the project will not work as expected.
- This will be the output: `<h1>Internal Server Error</h1>%`
