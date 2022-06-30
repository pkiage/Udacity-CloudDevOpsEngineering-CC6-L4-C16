# Shell Commands

## AWS

### Configure

```shell
aws configure
```

### List

#### Key Pairs

```shell
aws ec2 describe-key-pairs
```

#### Stacks

CREATE_COMPLETE:

```shell
aws cloudformation list-stacks --stack-status-filter CREATE_COMPLETE
```

### Delete Stack

```shell
aws cloudformation delete-stack --stack-name my-stack
```
