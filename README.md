# Dockerized aws-cli
Docker image for aws-cli

### Current version:
```
aws-cli/1.15.78 Python/2.7.14 Linux/4.9.93-linuxkit-aufs botocore/1.10.77
```

Pull:
```
docker pull afifsohaili/aws-cli
```

Usage:
```
docker run --rm \
  -e AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID \
  -e AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY \
  afifsohaili/aws-cli s3 sync to-upload s3://some-s3-bucket.yourcompany.com --acl=public-read
```
