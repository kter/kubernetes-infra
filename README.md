# creating stack

```
aws cloudformation create-stack --stack-name kubernetes-infra --template-body file://main.yml
```

# creating stack

```
aws cloudformation create-change-set --change-set-name update  --stack-name kubernetes-infra --template-body file://main.yml
```
