Vagrant.configure(2) do |config|
  config.vm.define "ansible" do |m|
    m.vm.box = "bento/centos-7.4"
    m.vm.network "private_network", ip: "192.168.33.10"
    m.vm.hostname = "ansible"
  end
  config.vm.define "nodejs" do |m|
    m.vm.box = "bento/centos-7.4"
    m.vm.network "private_network", ip: "192.168.33.20"
    m.vm.hostname = "nodejs"
  end
  config.vm.define "mongodb" do |m|
    m.vm.box = "bento/centos-7.4"
    m.vm.network "private_network", ip: "192.168.33.30"
    m.vm.hostname = "mongodb"
  end
  config.vm.define "nginx" do |m|
    m.vm.box = "bento/centos-7.4"
    m.vm.network "private_network", ip: "192.168.33.100"
    m.vm.hostname = "nginx"
  end
end
