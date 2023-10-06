# Тестовое задание от 29 сентября 2023

## Описание
Развертывание виртуальной машины с Ubuntu 20.04 LTS с установленным node_exporter и контейнерами Prometheus и Grafana.

## Зависимости
Работоспособность была проверена на машине с: 
+ Vagrant 2.3.7
+ Ansible 2.15.4
+ VirtualBox 7.0

Тестирование проводилось на машине с ОС openSUSE Tumbleweed (20231003))

## Использование

```
git clone https://github.com/herzeleid02/task_29092023_public
cd ./task29092023_public/vagrant/
vagrant up
```

## TODO
+ сборка .deb-пакета node_exporter (как пример -- [openSUSE](https://software.opensuse.org/package/golang-github-prometheus-node_exporter), [Fedora](https://packages.fedoraproject.org/pkgs/golang-github-prometheus-node-exporter/golang-github-prometheus-node-exporter/)))
