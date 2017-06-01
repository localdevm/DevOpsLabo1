
Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/precise64"
  config.vm.hostname="maarten.be"
  config.vm.provision "shell", path: "web.sh"
  config.ssh.insert_key = false
end
