# try-prometheus

## インストール

```shell
$ git clone https://github.com/macaron/try-prometheus
# 3行目はSlack Webhook URLを指定
$ vi alertmanager/alertmanager.yml
# 26行目はRaspberryPiのIPアドレスを指定
$ vi prometheus/prometheus.yml
$ docker-compose up -d
```
