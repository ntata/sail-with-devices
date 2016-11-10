#Swift setup-scripts

A set of bash scripts with comments inline to install Swift All in One.
This setup mimics the layout of [SAIO - Swift All In One](http://docs.openstack.org/developer/swift/development_saio.html)

It uses 4 physical devices instead of loopback devices for swift

These scripts as targeted and tested for Ubuntu 14.04

##One-step setup:

```bash
sudo ./one_step_setup.sh
```

At this point, Swift is installed and is running; source openrc and start using Swift

##Remove Swift:

```bash
sudo ./stop_swift.sh 
sudo ./sys_swift_remove.sh
```
