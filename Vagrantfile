Vagrant.configure("2") do |config|
  config.vm.define "dev" do |dev|
    dev.vm.box = "ubuntu/trusty64"
    dev.vm.network "forwarded_port", guest: 8000, host: 8000
    dev.vm.provision "puppet" do |puppet|
    end
  end
end
