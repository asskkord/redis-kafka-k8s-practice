Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/focal64"
    vm_memory = 2048
    vm_cpu = 2
  
    node00_ip = "192.168.100.100"
    config.vm.define "node00" do |node00|
      node00.vm.hostname = "node00"
      node00.vm.network "private_network", ip: node00_ip
      node00.vm.provider "virtualbox" do |vb|
        vb.name = "node00"
        vb.memory = vm_memory
        vb.cpus = vm_cpu
      end
    end
  
    node01_ip = "192.168.100.101"
    config.vm.define "node01" do |node01|
      node01.vm.hostname = "node01"
      node01.vm.network "private_network", ip: node01_ip
      node01.vm.provider "virtualbox" do |vb|
        vb.name = "node01"
        vb.memory = vm_memory
        vb.cpus = vm_cpu
      end
    end
  
    node02_ip = "192.168.100.102"
    config.vm.define "node02" do |node02|
      node02.vm.hostname = "node02"
      node02.vm.network "private_network", ip: node02_ip
      node02.vm.provider "virtualbox" do |vb|
        vb.name = "node02"
        vb.memory = vm_memory
        vb.cpus = vm_cpu
      end
    end

    node03_ip = "192.168.100.103"
    config.vm.define "node03" do |node03|
      node03.vm.hostname = "node03"
      node03.vm.network "private_network", ip: node03_ip
      node03.vm.provider "virtualbox" do |vb|
        vb.name = "node03"
        vb.memory = vm_memory
        vb.cpus = vm_cpu
      end
    end
  end