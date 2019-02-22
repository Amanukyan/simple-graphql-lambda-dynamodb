# Simple API using: Graphql, Lambda, DynamoDB

Creating a simple serveless GraphQL API using Lambda and DynamoDB

https://serverless.com/blog/make-serverless-graphql-api-using-lambda-dynamodb/

## Deploy

```
serveless deploy
```

### Testing

Add a nickname to the user:
```
curl -G 'API URL HERE' --data-urlencode 'query=mutation {changeNickname(firstName:"Jeremy", nickname: "Jer")}'
```

Print message using nickname:
```
curl -G 'API URL HERE' --data-urlencode 'query={greeting(firstName: "Jeremy")}'
```

## License
