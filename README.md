# gcr.io
[![Build Status](https://www.travis-ci.org/latelee/gcrsync.svg?branch=master)](https://www.travis-ci.org/latelee/gcrsync)

all of the gcr.io docker image mirror

# gcr.io  

### �ֿ�˵��
gcr(Google Container Registry)ͬ���ֿ��б�  

ͬ����ľ����ļ�λ��dockerhub��[gcrcontainer](https://hub.docker.com/r/gcrcontainer/)�˺��С�  

���ֿ���[travis-ci](https://www.travis-ci.org/latelee/gcrsync)ÿ���Զ���ʱ�������Ա�֤������gcrͬ������  

ͬ������Դ��λ��[latelee/gcrsync](https://github.com/latelee/gcrsync)����лԭ����[mritd](https://github.com/mritd)�ṩԴ�롣  

### ����ռ�
gcr.io����಻ͬ�������ռ䣬��Ӧ���ֿ���ӦĿ¼����`gcr.io/google-containers`��Ӧ`google-containers`Ŀ¼������`README.md`��`ImageList`�鿴���徵�����ơ�  

gcr.io�ľ�����[https://hub.docker.com/r/gcrcontainer/](https://hub.docker.com/r/gcrcontainer/)һһ��Ӧ���羵��`gcr.io/google-containers/pause-amd64:3.0`��Ӧ`gcrcontainer/pause-amd64:3.0`��(ע�⣬Ŀǰδ���ǵ���ͬ�����ռ侵���������)    


ʵ������ȡ���¾���  
```
docker pull gcr.io/google-containers/pause-amd64:3.0
```
��Ч�ڣ�  
```
docker pull gcrcontainer/pause-amd64:3.0
```
��ӦĳЩ���ϱ���ʹ��gcr.ioǰ׺�ģ�����`docker tag`����ﵽĿ�ģ�ʾ�����£�  
```
docker tag gcrcontainer/pause-amd64:3.0 gcr.io/google-containers/pause-amd64:3.0
```
