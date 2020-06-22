# Testando Lambda AWS

Função para fazer uma cópia de uma imagem, porém com qualidade e tamanho menor, a partir do momento em que é feito um upload no S3.

```sh
## Para criar:
serverless create --template aws-nodejs --path nodeless

cd nodeless

## Config credentials
serverless config credentials -o --provider aws --key=<chave_de_acesso> --secret <senha>

## Deploy
serverless deploy -v

## Run function
nodeless serverless invoke -f hello -l

## Remove function
serverless remove
```

