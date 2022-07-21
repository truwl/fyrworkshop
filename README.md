# fyrworkshop
```
bash resize.sh 100
```

- Create policy
- Create role
- Create batch compute environment

#disable temp credentials
https://catalog.us-east-1.prod.workshops.aws/workshops/8213ad51-878f-493b-8e5a-fbea22c4360c/en-US/setup/cloud9/disable-cred
```
npm install -g c9
c9 open nextflow.config
wget -qO- https://get.nextflow.io | bash
NXF_VER=22.04.0 ./nextflow run hello -bucket-dir s3://truwl-fyr/jul19
```

Create docker container
```
docker build -t truwl/fyr:latest .
docker push truwl/fyr:latest
```

