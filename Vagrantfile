# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

     config.vm.define "acs" do |acs|
          acs.vm.box = "ubuntu/trusty64"
          acs.vm.hostname = "acs"
          acs.vm.network "private_network", ip: "192.168.43.10"
     end

     config.vm.define "web" do |web|
          web.vm.box = "ubuntu/trusty64"
          web.vm.hostname = "acs"
          web.vm.network "private_network", ip: "192.168.43.20"
     end

     config.vm.define "db" do |db|
          db.vm.box = "ubuntu/trusty64"
          db.vm.hostname = "acs"
          db.vm.network "private_network", ip: "192.168.43.30"
     end
     
end
