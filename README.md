# Dockerized aws-cli

Docker image for aws-cli

### Current version:
```
aws-cli/1.16.202 Python/3.7.4 Linux/4.9.125-linuxkit botocore/1.12.192
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
