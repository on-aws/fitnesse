# Usage

1. Create AWS S3 Bucket
2. Upload to AWS S3 Bucket the following files:
  - [fitnesse-standalone.jar](http://fitnesse.org/FitNesseDownload)
  - [slim.ps1](https://raw.githubusercontent.com/konstantinvlasenko/PowerSlim/master/slim.ps1)
  - [client.ps1](https://raw.githubusercontent.com/konstantinvlasenko/PowerSlim/master/client.ps1)
  - [fitnesse.service](fitnesse.service)
  - [fitnesse.sh](fitnesse.sh)
3. Deploy CloudFormation Stack by using [state-manager.yaml](state-manager.yaml)
4. Deploy CloudFormation Stack by using [master.yaml](master.yaml)
