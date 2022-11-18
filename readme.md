도커로 실행

docker exec -it anaconda3 /bin/bash

jupyter notebook --ip='*' --port=8888 --allow-root