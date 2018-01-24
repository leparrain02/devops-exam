Vagrant.configure("2") do |config|
  config.vm.box = "bento/centos-7.3"
  config.vm.network "private_network", ip: "192.168.50.4"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "devops.yml"
  end
end
