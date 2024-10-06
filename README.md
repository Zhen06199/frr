# Simple OSPF lab using FRR

This lab example consists of three FRR routers connected in a ring topology. Each router has one PC connected to it.

This is also an example of how to pre-configure lab nodes on "linux" node types in Containerlab.

To start this lab, run the *run.sh* script, which will run the containerlab deploy commands, and then configure the PC interfaces.

The lab configuration is documented in detail at: https://www.brianlinkletter.com/2021/05/use-containerlab-to-emulate-open-source-routers/

# Add images
run *topo.sh*

前提环境 docker,clab,brctl(建立网桥) 

1.在宿主机上建立网桥br0，并连接以太网接口enp025
2.br0与containerlab相连,br0的类型是bridge
3.在ternimal里输入br0的ip和路由信息
