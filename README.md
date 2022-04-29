<img src="./serverless.png"/>

## aws credential setting

```
mkdir .aws
cd .aws
touch credentials
```

credentials

```
[default]
aws_access_key_id=<your access key>
aws_secret_access_key=<your secret key>
```

## install dependency

```
npm install -g serverless
npm install --save aws-serverless-express
npm install --save aws-lambda
npm install --save-dev serverless-plugin-typescript
npm install --save-dev serverless-plugin-optimize
npm install --save-dev serverless-offline plugin
```

## local test

```
sls offline start
```

## deploy

```
sls deploy -v
```

## remove

```
serverless remove
```
