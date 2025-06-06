# etcd-docker-service


## related command lines to enable etcd docker as service ##
56350  2025-06-06 03:37:27 sudo netstat -tulnp | grep 2379
56351  2025-06-06 03:37:43 sudo kill -9 3144
56352  2025-06-06 03:37:48 docker compose up -d
56353  2025-06-06 03:38:00 sudo netstat -tulnp | grep 2379
56354  2025-06-06 03:38:15 sudo kill -9 893437
56355  2025-06-06 03:38:17 sudo netstat -tulnp | grep 2379
56356  2025-06-06 03:38:29 sudo kill -9 893647
56357  2025-06-06 03:38:31 sudo netstat -tulnp | grep 2379
56358  2025-06-06 03:38:54 sudo netstat -tulnp | grep 893666
56359  2025-06-06 03:39:09 sudo kill -9 893666
56360  2025-06-06 03:39:15 sudo netstat -tulnp | grep 2379
56361  2025-06-06 03:39:46 sudo systemctl status etcd
56362  2025-06-06 03:39:57 sudo systemctl stop etcd
56363  2025-06-06 03:39:57 sudo systemctl disable etcd
56364  2025-06-06 03:40:09 sudo netstat -tulnp | grep 2379
56365  2025-06-06 03:40:17 sudo lsof -i :2379
56366  2025-06-06 03:40:25 docker compose down
56367  2025-06-06 03:40:40 docker compse up -d
56368  2025-06-06 03:40:47 docker compose up -d
56369  2025-06-06 03:40:52 docker ps
56370  2025-06-06 03:41:04 docker exec -it ytang-mooncake
56371  2025-06-06 03:41:06 docker exec -it ytang-mooncake bash
56372  2025-06-06 03:46:22 ls
56373  2025-06-06 03:46:27 docker ps
56374  2025-06-06 03:46:37 docker log etcd
56375  2025-06-06 03:46:47 docker compose down -v
56376  2025-06-06 03:48:34 docker-compose down -v
56377  2025-06-06 03:48:35 sudo rm -rf ./etcd-data
56378  2025-06-06 03:48:58 docker compose up -d
56379  2025-06-06 03:49:06 docker exec -it etcd netstat -tuln | grep 2379
56380  2025-06-06 03:49:40 docker logs etcd
56381  2025-06-06 03:50:37 docker ps | grep etcd
56382  2025-06-06 03:50:48 export ETCDCTL_API=3
56383  2025-06-06 03:50:48 etcdctl --endpoints=http://localhost:2379 get foo
56384  2025-06-06 03:51:17 etcdctl --endpoints=http://localhost:2379 put foo bar
56385  2025-06-06 03:51:17 etcdctl --endpoints=http://localhost:2379 get foo
56386  2025-06-06 03:51:39 docker ps
56387  2025-06-06 03:51:50 docker exec -it ytang-mooncake bash
56388  2025-06-06 03:55:29 history
