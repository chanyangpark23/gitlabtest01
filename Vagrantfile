Vagrant.configure("2") do |config|

  config.vm.define "frontend" do |frontend|
    frontend.vm.box = "centos/7"
    frontend.vm.host_name = "front"
    frontend.vm.network "private_network", ip: "192.168.33.10"
    frontend.vm.provider :virtualbox do |spec|
      spec.cpus = 4
      spec.memory = 2048
  end
end

end
