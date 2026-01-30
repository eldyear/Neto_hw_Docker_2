# Домашнее задание к занятию "`Docker. Часть 2`" - `Элдияр Акматов`


### Задание 1

`Docker Compose — это инструмент для оркестрации многоконтейнерных приложений, позволяющий описать всю инфраструктуру (сервисы, сети, тома) в одном файле docker-compose.yml и запускать её одной командой. Лично мою жизнь он упрощает тем, что избавляет от необходимости вручную вводить длинные команды docker run с десятками флагов для каждого компонента проекта. Вместо того чтобы по отдельности поднимать базу данных PostgreSQL, бэкенд на Django и веб-сервер Nginx, я могу развернуть готовую среду разработки за считанные секунды, гарантируя, что она будет идентична на любом компьютере.`

### Задание 2

`Приведите ответ в свободной форме........`

```bash
eldyear@fedora:~/netology/Контейнеризация/Docker-2/Neto_hw_Docker_2/Compose-1$ docker compose up -d
WARN[0000] /home/eldyear/netology/Контейнеризация/Docker-2/Neto_hw_Docker_2/Compose-1/compose.yml: the attribute `version` is obsolete, it will be ignored, please remove it to avoid potential confusion 
[+] up 5/5
 ✔ Image alpine                          Pulled                                                                                                       4.4s
 ✔ Network Akmatov E.M.                  Created                                                                                                      0.1s
 ✔ Container compose-1-placeholder-app-1 Created                                                                                                      0.2s
eldyear@fedora:~/netology/Контейнеризация/Docker-2/Neto_hw_Docker_2/Compose-1$ docker network inspect Akmatov\ E.M.
[
    {
        "Name": "Akmatov E.M.",
        "Id": "428f673f8ace75f4c8a95d4ffe3a465488b0c8259f5fc3f04ed6c0108a62070a",
        "Created": "2026-01-30T21:05:06.719575768+06:00",
        "Scope": "local",
        "Driver": "bridge",
        "EnableIPv4": true,
        "EnableIPv6": false,
        "IPAM": {
            "Driver": "default",
            "Options": null,
            "Config": [
                {
                    "Subnet": "10.5.0.0/16",
                    "Gateway": "10.5.0.1"
                }
            ]
        },
        "Internal": false,
        "Attachable": false,
        "Ingress": false,
        "ConfigFrom": {
            "Network": ""
        },
        "ConfigOnly": false,
        "Options": {},
        "Labels": {
            "com.docker.compose.config-hash": "058a28b95b58802f8b6e86b92ef04248231e3278868d31c105e5164a2d7a22d6",
            "com.docker.compose.network": "my_network",
            "com.docker.compose.project": "compose-1",
            "com.docker.compose.version": "5.0.2"
        },
        "Containers": {
            "5498110c20e5af5cf9d31f397b3fe57b5a3929b7c8fc41d95a29334a7552f8fe": {
                "Name": "compose-1-placeholder-app-1",
                "EndpointID": "30239a7fe9393eed60290fca314116565b4c74963f3dc84fa0d993bae5987c56",
                "MacAddress": "96:70:06:1b:a4:50",
                "IPv4Address": "10.5.0.2/16",
                "IPv6Address": ""
            }
        },
        "Status": {
            "IPAM": {
                "Subnets": {
                    "10.5.0.0/16": {
                        "IPsInUse": 4,
                        "DynamicIPsAvailable": 65532
                    }
                }
            }
        }
    }
]
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота 2](ссылка на скриншот 2)`


---

### Задание 3

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

### Задание 4

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`
