# ucore-os-2020
* Tsinghua University Operating System (Fall 2020)
* Timeline: 2020-10-01 -> 2020-12-31
* class page: https://github.com/chyyuu/os_kernel_lab/tree/master
* lab instruction gitbook: https://learningos.github.io/ucore_os_webdocs/ ~~https://chyyuu.gitbooks.io/ucore_os_docs/content/~~
* My Notes in Notion.so: https://www.notion.so/hzhang413/2020-ca36632638cc4577a3a01a79d0ec7d08
* 2020 RISC-V lecture notes: https://github.com/dramforever/os-lectures-build/releases

# Classes
* ucore: https://next.xuetangx.com/learn/THU08091000267/THU08091000267/4231154/video/6287033
* rcore: https://next.xuetangx.com/learn/thu08091002729/thu08091002729/4231868/video/6354337

# Labs
## lab0: preparing
## lab1: boot/protect mode/stack/interrupt
## lab2: physical memory management
## lab3: virtual memory management
## lab4: kernel thread management
## lab5: user process management
## lab6: scheduling
## lab7: mutex/sync
## lab8: filesystem

# Quiz

# Exercise Steps
```
0 Get the newest os lab src code/docs.(Insure you can connect to github in ubuntu running on VrtualBox)
0.1 If you try to get all code
  $rm -rf ucore_lab
  $git clone git://github.com/chyyuu/ucore_os_lab.git
  $cd ucore_lab
0.2 If you cloned ucore_lab and only try to get the updated code
  $cd ucore_os_lab
  $git pull
1 $cd labX  
2 read code (specially the modified or added files)
3 add your code
4 compile your code
  $make
5 check your code
  $make qemu
OR
  $make grade

6 debug your code
  $make debug

7 handin your code
  $make handin
```