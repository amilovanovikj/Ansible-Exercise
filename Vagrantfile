Vagrant.configure("2") do |config|
  config.vm.box_check_update = false
  (31..33).each do |i|
    config.vm.define "centos#{i}" do | centos |
      centos.vm.box = "centos/7"
      centos.vm.network "private_network", ip: "192.168.50.#{i}"
    end
  end
  config.vm.provider "virtualbox" do |v|
      v.memory = 1024
      v.cpus = 1
  end
end