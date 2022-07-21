# fyrworkshop
- Create policy
- Create role
- Create batch compute environment

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

