## how to upload data to s3 buket

###### get dataset from url

```
!wget http://aws-tc-largeobjects.s3-us-west-2.amazonaws.com/DIG-TF-200-MLBEES-10-EN/dataset.zip 
!unzip -qo dataset.zip

```

## to upload data to s3 buket

```
BUCKET = 'ahmed-ai' // buket name 
PREFIX = 'input' # name folder which contain img inside BUCKET name   /ahmed-ai/input
```
