# Chat app | django-channels2

* development requirements

```bash
$ sudo apt install python3
$ sudo apt install python3-dev
$ sudo apt install rabbitmq-server
```

* configure rabbitmq

```bash
$ sudo apt install rabbitmq-server
$ sudo rabbitmqctl add_user {my_user} {my__password}
$ sudo rabbitmqctl add_vhost {virtual_host}
$ sudo rabbitmqctl set_user_tags {user} {tag}
$ sudo rabbitmqctl set_permissions -p {vhost} {user} ".*" ".*" ".*"
```
