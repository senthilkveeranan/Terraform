Vagrant.configure("2") do |config|
 
     config.vm.define'ansible" do |ansible|
          ansible|.vm.hostname = "ansible"
          ansible.vm.box = "ubuntu/bionic64"
          ansible|.vm.network "private_network", ip: "192.168.137.10"
          vb.memory = "2048"
   end

     config.vm.define "web" do |web|
          ansible.vm.box = "ubuntu/bionic64"
          ansible|.vm.hostname = "web"
          ansible|.vm.network "private_network", ip: "192.168.137.20"
          ansible|.vm.provider "virtualbox" do |vb|
   end

     config.vm.define "db" do |db|
          db.vm.box = "ubuntu/bionic64"
          db.vm.hostname = "db"
          db.vm.network "private_network", ip: "192.168.137.30"
          db.vm.provider "virtualbox" do |vb|
   end

end
