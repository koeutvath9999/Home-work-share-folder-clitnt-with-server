
Vagrant.configure("2") do |config|

  # First machine
  config.vm.define "node1" do |node1|
    node1.vm.box = "bento/ubuntu-24.04"
    node1.vm.hostname = "node1"
    node1.vm.network "private_network", ip: "192.168.33.10"
  end

  # Second machine
  config.vm.define "node2" do |node2|
    node2.vm.box = "bento/ubuntu-24.04"
    node2.vm.hostname = "node2"
    node2.vm.network "private_network", ip: "192.168.33.11"
  end

  # Third machine
  config.vm.define "node3" do |node3|
    node3.vm.box = "bento/ubuntu-24.04"
    node3.vm.hostname = "node3"
    node3.vm.network "private_network", ip: "192.168.33.12"
  end

end