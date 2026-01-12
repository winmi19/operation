docker exec -it [容器名（dinov2)]  /bin/bash进入容器

docker save

docker load 

docker run -d --name dinov3 （容器名字）--gpus all 
-v /data/linmiaoju/miniconda3:/data/miniconda3 
-v /data/linmiaoju/dinov2:/workspace/dinov2 
dinov2-test（镜像）
tail -f /dev/null (运行容器永久）
/bin/bash

docker run -d --name vjepac --gpus all -v $(pwd)/jepa:/workspace/jepa -v /data/xuwenmin/imagenet:/dataset vjepai tail -f /dev/null

docker exec -it dinov2（容器名字） /bin/bash

docker build -t vjepai .
docker build -t dinoi .
docker build -t maei2 .

docker stop dinov2c
docker rm dinov2c

docker cp /home/xuwenmin/dinov2_deploy/wheels/pip/antlr4-python3-runtime-4.9.3.tar.gz dinov2c2:/workspace/wheels/pip/
Successfully copied 119kB to dinov2c2:/workspace/wheels/pip/


free -h 看共享内存

ndivia-smi 看显卡情况

