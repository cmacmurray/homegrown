Vagrant.configure("2") do |config|

  config.vm.define "node1" do |node1|
    node1.vm.box = "centos/7"
    node1.vm.hostname = "node1"
    node1.vm.network "private_network", ip: "172.17.8.101"
    node1.vm.network "public_network", bridge: "en0: Wi-Fi (AirPort)", auto_config: true
    node1.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
      vb.cpus = 1
      vb.name = "node1"
    end
  end

  config.vm.define "node2" do |node2|
    node2.vm.box = "centos/7"
    node2.vm.hostname = "node2"
    node2.vm.network "private_network", ip: "172.17.8.103"
    node2.vm.network "public_network", bridge: "en0: Wi-Fi (AirPort)", auto_config: true
    node2.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
      vb.cpus = 1
      vb.name = "node2"
    end
  end

  config.vm.define "node3" do |node3|
    node3.vm.box = "centos/7"
    node3.vm.hostname = "node3"
    node3.vm.network "private_network", ip: "172.17.8.104"
    node3.vm.network "public_network", bridge: "en0: Wi-Fi (AirPort)", auto_config: true
    node3.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
      vb.cpus = 1
      vb.name = "node3"
    end
  end
end
