# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config| # указываем брать конфигурацию только для Vagrant версии 2 и работаем с обьектом config
  config.vm.box = "ubuntu/focal64" # указываем имя виртуальной машины, которое можно взять из репозитория виртуальных машин Vagrant
  config.vm.network "forwarded_port", guest: 80, host 8080
end