# Serverless Application with AWS Lambda

## Usage

### Deployment

In order to deploy the example, you need to run the following command:

```
serverless deploy
```

### Invocation

After successful deployment, you can call the created application via HTTP:

```
curl https://xxxxxxx.execute-api.us-east-1.amazonaws.com/hello
```

Which should result in response similar to:

```json
{ "message": "Hello! this is a simple example" }
```
