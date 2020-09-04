# ros_buildfarm

Installs and configures ROS build farm machines.

## Requirements

* Ubuntu 20.04.
* [Chef Infra](https://www.chef.io/products/chef-infra) or [Cinc client](https://cinc.sh/start/client/) 15
* [Jenkins cookbook](https://supermarket.chef.io/cookbooks/jenkins)


## Usage

This cookbook is primarily tested using chef-solo / cinc-solo for deployment onto fresh Ubuntu 20.04 virtual machines.
Use with chef server is not tested but should work.


## Recipes

This cookbook is currently organized with one recipe per machine role:
* jenkins
* repo
* agent

