Vagrant.configure("2") do |config|
  config.vm.define "server1" do |server1|
    server1.vm.box = "centos/7"
    server1.vm.network "private_network" , ip: "10.5.25.10"
  end  
  config.vm.define "server2" do |server2|
    server2.vm.box = "ubuntu/bionic64"
    server2.vm.network "private_network" , ip: "10.5.25.20"
  end
end
