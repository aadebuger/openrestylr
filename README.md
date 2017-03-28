# openrestylr


# run openresty 
docker run --rm -p 9091:80 -v $PWD/work:/code  aadebuger/openresty
docker exec -it   dockname /bin/bash

测试命令
/usr/local/openresty/bin/resty  /code/testjson.lua