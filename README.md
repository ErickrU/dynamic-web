# dynamic-web

docker build -t dynamicweb:0.1 .

docker run -it -v /workspace/dynamic-web/code/:/home/ --net=host --name dynamicweb -h psypc dynamicweb:0.1