Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.network "private_network", ip: "192.168.50.10"
  # Gitlab CI Runner configuration
  config.vm.provision :shell, path: "provision.sh"
end
