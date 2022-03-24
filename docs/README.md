```shell
sudo yum install git-lfs

wget -c https://s3-us-west-1.amazonaws.com/roofsolar/inception_classification.tar.gz

wget -c https://s3-us-west-1.amazonaws.com/roofsolar/inception_segmentation.tar.gz

pip install -r requirements.txt -i https://pypi.douban.com/simple

pip install --upgrade pip

docker run -ti --volume="$(pwd)":/DeepSolarV1 --rm python:2.7 bash
# docker run -ti --volume="$(pwd)":/DeepSolarV1 --rm python:3.7 bash

pip install inception -i https://pypi.douban.com/simple
pip install pandas -i https://pypi.douban.com/simple

https://github.com/wangzhecheng/DeepSolar/issues/8
wget https://s3-us-west-1.amazonaws.com/roofsolar/SPI_train.tar.gz
wget https://s3-us-west-1.amazonaws.com/roofsolar/SPI_eval.tar.gz
wget https://s3-us-west-1.amazonaws.com/roofsolar/SPI_val.tar.gz

SPI_train.tar.gz
https://academictorrents.com/details/8649f33cf8d661cbf3290bd4216c6ac637b777e0
SPI_eval.tar.gz
https://academictorrents.com/details/0a3344160f3bb1b6a82f2552cf8503d25e1b6b48
SPI_val.tar.gz
https://academictorrents.com/details/f0977a00ca9d61eefdfa232515ac6690d3b56fc5

http://academictorrents.com/browse.php?search=SPI_train
http://academictorrents.com/browse.php?search=SPI_eval

python train_classification.py --fine_tune=True
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
