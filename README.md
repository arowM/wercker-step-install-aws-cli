install-aws-cli
===========================

Install AWS Command Line Tools


Example
--------

Installs the latest version of AWS CLI when no version is specified, or else it will install the specified version.
`version` is optional.

Add AWS_KEY and AWS_SECRET as deploy target or application environment variables.
`region` is optional.

```
    - joepjoosten/install-aws-cli:
        key: $AWS_KEY
        secret: $AWS_SECRET
        region: $AWS_REGION
        version: 1.7.15
```
