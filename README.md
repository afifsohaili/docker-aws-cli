# Dockerized aws-cli
Docker image for aws-cli

### Current version: 1.15.26

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
