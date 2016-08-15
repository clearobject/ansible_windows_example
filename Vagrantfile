# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.define "windows2k12r2" do |windows2k12r2|
      windows2k12r2.vm.box = "opentable/win-2012r2-standard-amd64-nocm"
      windows2k12r2.vm.hostname = "windows2k12r2"
      # You can change this value you anything you'd like
      windows2k12r2.vm.network "private_network", ip: "192.168.10.80"
  end

end
