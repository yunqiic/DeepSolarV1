```shell
sudo yum install git-lfs

wget -c https://s3-us-west-1.amazonaws.com/roofsolar/inception_classification.tar.gz

wget -c https://s3-us-west-1.amazonaws.com/roofsolar/inception_segmentation.tar.gz

pip install -r requirements.txt -i https://pypi.douban.com/simple

pip install --upgrade pip
```

```
[core]
	repositoryformatversion = 0
	filemode = true
	bare = false
	logallrefupdates = true
	ignorecase = true
	precomposeunicode = true
[remote "origin"]
	url = git@github.com:yunqiic/DeepSolarV1.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "main"]
	remote = origin
	merge = refs/heads/main
```
