


## To make a bucket

```bash
$ s3cmd --no-ssl mb s3://mybucket
$ s3cmd --no-ssl put README.md s3://mybucket
$ s3cmd --no-ssl ls
$ s3cmd --no-ssl ls s3://mybucket
$ pushd . && cd /tmp/ && s3cmd --no-ssl get s3://mybucket/README.md >& /dev/null ; cat README.md && popd
```
