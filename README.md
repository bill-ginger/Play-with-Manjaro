# Play-with-Manjaro

### Introduction
Manjaro was called the best distribution of linux. 

It is based on arch, and also known for its good support for hardwares(MHWD: Manjaro HardWare Detection).

You can see more about Manjaro at [wikipedia](https://en.wikipedia.org/wiki/Manjaro) and [official website](https://manjaro.org/)

The desktop environment I use is KDE, because I think it's beautiful and I want to learn about it. I have been quite familiar with gnome by using Ubuntu.

### The environment I use
I once installed Manjaro KDE on a physical machine, wanting to use it as a daily productive system, but I encountered problems concerning wine, so I dropped.

Now in this repo, I will play with Manjaro in a virtual machine.

With regard to virtual machine, I firstly installed it in VMware, as it's usually more convenient than VirtualBox.

But in VMware the auto-scaling of window is unusable, the system only supports resulotion of 800x600. It's horrible as I'm using an 4K monitor.

I figured out that it is because the open-vm-tool didn't work well. It can be solved by restarting open-vm-tool once you have entered the system by this command:
```bash
systemctl restart vmtoolsd.service
```
