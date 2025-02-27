# OSProject Running Containers for Application Development

Group Name: lilnas. 

Section: 7. 

Team Mates:
1. Noor Sheereen Iman binti Zainal Abidin and 2315342
2. Nur Afifah Amni binti Ariffin and 2318824
3. Nadia Erdeena and 2319226

## Rules
1. You are allowed to have **3 group** members. *Exception* is allowed **IFF (if and only if)** you are allowed to have 4 group members if you are a **multinational** or a **multigender** group. 
2. When you complete the project, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this OS project repository
1. First thing you need in doing this project is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the OS project repository in your own github account. 

    1. Go to https://github.com/joeynor/OSProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork OSProject in your repository.
```bash
https://github.com/gumdumballs/OSProject/tree/main
```
2. How many files and folders are in this repository.
```bash
1 folder with 6 pictures and 1 file.
```

## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own OSProject repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name, section and team members along with their matric IDs. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces.
```bash
Ubuntu Linux.
```
2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces.
```bash
2-core, 8GB RAM, 32GB and 4-core, 16GB RAM, 32GB.
```
3. Why must we commit and sync our current work on source control?
```bash
This is to avoid work loss since it is not saved into our main repository.
```

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
```bash
@sheereeniman ➜ /workspaces/OSProject (main) $ pwd
/workspaces/OSProject
```
2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
```bash
@sheereeniman ➜ /workspaces/OSProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
```
3. Run the command **df** . ***(1 mark)*** 
```bash
@sheereeniman ➜ /workspaces/OSProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10706188  20447392  35% /
tmpfs              65536        0     65536   0% /dev
shm                65536        0     65536   0% /dev/shm
/dev/root       30298176 25232908   5048884  84% /vscode
/dev/loop4      32847680 10706188  20447392  35% /workspaces
/dev/sdb1       46127956 18750736  25001644  43% /tmp
```
4. Run the command **du** . ***(1 mark)*** 
```bash
@sheereeniman ➜ /workspaces/OSProject (main) $ du
8       ./.git/refs/heads
4       ./.git/refs/tags
16      ./.git/refs/remotes/origin
20      ./.git/refs/remotes
36      ./.git/refs
68      ./.git/hooks
8       ./.git/info
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/branches
8       ./.git/objects/b7
8       ./.git/objects/5a
8       ./.git/objects/8f
4       ./.git/objects/info
8       ./.git/objects/eb
12      ./.git/objects/19
12      ./.git/objects/db
1872    ./.git/objects/pack
8       ./.git/objects/42
1944    ./.git/objects
8       ./.git/logs/refs/heads
16      ./.git/logs/refs/remotes/origin
20      ./.git/logs/refs/remotes
32      ./.git/logs/refs
40      ./.git/logs
2144    ./.git
1972    ./images
4140    .
```
5. Run the command **ls** . ***(1 mark)*** 
```bash
@sheereeniman ➜ /workspaces/OSProject (main) $ ls
README.md  images
```
6. Run the command **ls -asl** . ***(1 mark)***
```bash 
@sheereeniman ➜ /workspaces/OSProject (main) $ ls -asl
total 36
 4 drwxrwxrwx+ 4 codespace root  4096 Jan 26 13:18 .
 4 drwxr-xrwx+ 5 codespace root  4096 Jan 26 13:18 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jan 27 11:19 .git
20 -rw-rw-rw-  1 codespace root 19865 Jan 27 12:03 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 Jan 26 13:18 images
 ```
7. Run the command **free -h** . ***(1 mark)***
```bash
@sheereeniman ➜ /workspaces/OSProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.5Gi       358Mi        62Mi       5.9Gi       5.9Gi
Swap:            0B          0B          0B
```
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
```bash
@sheereeniman ➜ /workspaces/OSProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3196.532
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.87
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3242.416
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.87
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
```
9. Run the command **top** and type **q** to quit. ***(1 mark)*** 
```bash
processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3242.416
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
top - 12:13:40 up 21 min,  0 users,  load average: 0.13, 0.28, 0.56
Tasks:  23 total,   1 running,  21 sleeping,   1 stopped,   0 zombie
top - 12:14:10 up 22 min,  0 users,  load average: 0.08, 0.25, 0.54
Tasks:  23 total,   1 running,  21 sleeping,   1 stopped,   0 zombie
%Cpu(s):  2.8 us,  3.7 sy,  0.0 ni, 93.5 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    423.1 free,   1443.6 used,   6062.8 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6108.8 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                                                                    
   4537 codespa+  20   0   41.5g 332412  50944 S   0.7   4.1   0:23.90 node                                                                                                       
    586 codespa+  20   0   11.3g 114640  47488 S   0.3   1.4   0:05.66 node                                                                                                       
   1066 codespa+  20   0   11.2g  68448  44672 S   0.3   0.8   0:01.50 node                                                                                                       
      1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.05 docker-init                                                                                                
      8 codespa+  20   0    7236   1664   1664 S   0.0   0.0   0:00.02 sleep                                                                                                      
     35 root      20   0   12196   3480   2560 S   0.0   0.0   0:00.00 sshd                                                                                                       
    388 codespa+  20   0    2616   1408   1408 S   0.0   0.0   0:00.01 sh                                                                                                         
    414 root      20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh    
```
10. Run the command **uname -a**. ***(1 mark)*** 
```bash
@sheereeniman ➜ /workspaces/OSProject (main) $ uname -a
Linux codespaces-5e8389 6.5.0-1025-azure #26~22.04.1-Ubuntu SMP Thu Jul 11 22:33:04 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```
11. What is the available free memory in the system. ***(1 mark)*** 
```bash
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.5Gi       358Mi        62Mi       5.9Gi       5.9Gi

available free memory in the system is 5.9Gi
```
12. What is the available disk space mounted on /workspace. ***(1 mark)*** 
```bash
Filesystem     1K-blocks     Used Available Use% Mounted on
/dev/loop4      32847680 10706188  20447392  35% /workspaces

available disk space mounted on /workspace is 20,447,392 KB or 20.4 GB
```
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** 
```bash
Linux codespaces-5e8389 6.5.0-1025-azure #26~22.04.1-Ubuntu SMP Thu Jul 11 22:33:04 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux

the version is Ubuntu 22.04.1 
the hardware architecture is x86_64 
```
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** 
```bash
ls is used for a quick look at the directory contents.
ls -asl is used for a detailed overview, including file sizes, permissions, and hidden files.
```
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** 
```bash
TLB size        : 2560 4K pages
```
16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** 
```bash
processor       : 0
cpu MHz         : 3196.532

processor       : 1
cpu MHz         : 3242.416
```
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** 
```bash
PID  USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME COMMAND                                                                                                      
4537 codespa+  20   0   41.5g 332412  50944 S   0.7   4.1   0:23.90 node

top running process consuming the most CPU cycles is the process with PID 4537, which is running the node command. It is using 0.7% of the CPU and 4.1% of the memory. The process has a virtual memory size of 41.5 GB and a resident memory size of 332,412 KB.
```

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)***
```
No, it's not persistent. When a container is deleted, Docker destroys the container’s filesystem and creates a new clean instance if you restart it.
```
2. Can we run two, or three instances of debian linux? . ***(1 mark)***
```
Yes, we can run multiple instances because each container runs independently with its own isolated filesystem, processes, and network stack
```

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)***
```
@nffhmn ➜ /workspaces/OSProject/myroot (main) $ ls -l /workspaces/OSProject/myroot
total 4
-rw-rw-rw- 1 root      root      33 Jan 31 03:52 byeeworld.txt

permissions : -rw-rw-rw-
user : root
group : root

```   
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
```
Yes, you can.

@nffhmn ➜ /workspaces/OSProject/myroot (main) $ sudo chown -R codespace:codespace /workspaces/OSProject/myroot
@nffhmn ➜ /workspaces/OSProject/myroot (main) $ ls -l /workspaces/OSProject/myroot
total 4
-rw-rw-rw- 1 codespace codespace 33 Jan 31 04:37 byeeworld.txt
```

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)***
```bash
@gumdumballs ➜ /workspaces/OSProject (main) $ docker exec -it $(docker ps -q) ls -ld /usr/local/apache2/htdocs/
drwxrwxrwx+ 6 1000 root 4096 Jan 29 19:21 /usr/local/apache2/htdocs/

Permission: drwxrwxrwx+
User & Group: 1000 root
```
2. What port is the apache web server running. ***(1 mark)***
```bash
Port 80
```
3. What port is open for http protocol on the host machine? ***(1 mark)***
```bash
8080
```

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)***
```bash
BusyBox is an open-source software package that merges numerous Unix tools into one executable file. It's tailored for embedded operating systems with constrained resources, such as IoT devices and cloud computing environments.

--name: is to custom the name of the container instead of using the one that is randomly generated.
```

2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)*** 
```bash
@gumdumballs ➜ /workspaces/OSProject (main) $ docker network ls
NETWORK ID     NAME                                                                     DRIVER    SCOPE
c8abdf8dac05   bluenet                                                                  bridge    local
62b4df09c174   bridge                                                                   bridge    local
63b393f3e289   host                                                                     host      local
b4fb20a18646   none                                                                     null      local
964f1b0b66b2   rednet                                                                   bridge    local
fd426b26cf4c   rednet964f1b0b66b2e7f1274368ad88de8fe13da5bd43fd3cfc8f190a0a6b8c1d910e   bridge    local
```
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
```bash
Gateway of Bluenet [docker inspect c1]: 172.18.0.1
Gateway of Rednet [docker inspect c2]: 172.19.0.1
```
4. What is the network address for the running container c1 and c2? ***(1 mark)***
```bash
IP Address of Bluenet: 172.18.0.2
IP Address of Rednet: 172.19.0.2
```
5. Using the command ```docker exec c1 ping c2```, which basically tries to do a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** 
```bash
@gumdumballs ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
ping: bad address 'c2'

Since c1 and c2 are not on the same network, the ping will fail.
```

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
***Questions:***

1. Are you able to ping? Show your output . ***(1 mark)*** 
```bash
yes, the ping was successfull

@sheereeniman ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=0.148 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.061 ms
64 bytes from 172.20.0.3: seq=3 ttl=64 time=0.072 ms
64 bytes from 172.20.0.3: seq=4 ttl=64 time=0.067 ms
64 bytes from 172.20.0.3: seq=5 ttl=64 time=0.067 ms
64 bytes from 172.20.0.3: seq=6 ttl=64 time=0.082 ms
64 bytes from 172.20.0.3: seq=7 ttl=64 time=0.061 ms
64 bytes from 172.20.0.3: seq=8 ttl=64 time=0.081 ms
64 bytes from 172.20.0.3: seq=9 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=10 ttl=64 time=0.066 ms
64 bytes from 172.20.0.3: seq=11 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=12 ttl=64 time=0.062 ms
64 bytes from 172.20.0.3: seq=13 ttl=64 time=0.237 ms
64 bytes from 172.20.0.3: seq=14 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=15 ttl=64 time=0.061 ms
64 bytes from 172.20.0.3: seq=16 ttl=64 time=0.064 ms
64 bytes from 172.20.0.3: seq=17 ttl=64 time=0.079 ms
64 bytes from 172.20.0.3: seq=18 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=19 ttl=64 time=0.068 ms
64 bytes from 172.20.0.3: seq=20 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=21 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=22 ttl=64 time=0.089 ms
64 bytes from 172.20.0.3: seq=23 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=24 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=25 ttl=64 time=0.066 ms
64 bytes from 172.20.0.3: seq=26 ttl=64 time=0.062 ms
64 bytes from 172.20.0.3: seq=27 ttl=64 time=0.072 ms
64 bytes from 172.20.0.3: seq=28 ttl=64 time=0.096 ms
64 bytes from 172.20.0.3: seq=29 ttl=64 time=0.065 ms
64 bytes from 172.20.0.3: seq=30 ttl=64 time=0.086 ms
64 bytes from 172.20.0.3: seq=31 ttl=64 time=0.075 ms
64 bytes from 172.20.0.3: seq=32 ttl=64 time=0.069 ms
64 bytes from 172.20.0.3: seq=33 ttl=64 time=0.064 ms
64 bytes from 172.20.0.3: seq=34 ttl=64 time=0.060 ms
64 bytes from 172.20.0.3: seq=35 ttl=64 time=0.075 ms
64 bytes from 172.20.0.3: seq=36 ttl=64 time=0.105 ms
64 bytes from 172.20.0.3: seq=37 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=38 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=39 ttl=64 time=0.075 ms
64 bytes from 172.20.0.3: seq=40 ttl=64 time=0.113 ms
64 bytes from 172.20.0.3: seq=41 ttl=64 time=0.083 ms
64 bytes from 172.20.0.3: seq=42 ttl=64 time=0.087 ms
64 bytes from 172.20.0.3: seq=43 ttl=64 time=0.082 ms
64 bytes from 172.20.0.3: seq=44 ttl=64 time=0.088 ms
64 bytes from 172.20.0.3: seq=45 ttl=64 time=0.075 ms
64 bytes from 172.20.0.3: seq=46 ttl=64 time=0.083 ms
64 bytes from 172.20.0.3: seq=47 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=48 ttl=64 time=0.080 ms
64 bytes from 172.20.0.3: seq=49 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=50 ttl=64 time=0.103 ms
64 bytes from 172.20.0.3: seq=51 ttl=64 time=0.084 ms
64 bytes from 172.20.0.3: seq=52 ttl=64 time=0.118 ms
64 bytes from 172.20.0.3: seq=53 ttl=64 time=0.083 ms
64 bytes from 172.20.0.3: seq=54 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=55 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=56 ttl=64 time=0.083 ms
64 bytes from 172.20.0.3: seq=57 ttl=64 time=0.088 ms
64 bytes from 172.20.0.3: seq=58 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=59 ttl=64 time=0.071 ms
64 bytes from 172.20.0.3: seq=60 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=61 ttl=64 time=0.079 ms
64 bytes from 172.20.0.3: seq=62 ttl=64 time=0.073 ms
64 bytes from 172.20.0.3: seq=63 ttl=64 time=0.072 ms
64 bytes from 172.20.0.3: seq=64 ttl=64 time=0.085 ms
64 bytes from 172.20.0.3: seq=65 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=66 ttl=64 time=0.074 ms
64 bytes from 172.20.0.3: seq=67 ttl=64 time=0.080 ms
64 bytes from 172.20.0.3: seq=68 ttl=64 time=0.088 ms
64 bytes from 172.20.0.3: seq=69 ttl=64 time=0.084 ms
64 bytes from 172.20.0.3: seq=70 ttl=64 time=0.100 ms
```
2. What is different from the previous ping in the section above? ***(1 mark)*** 
```bash
previous :
@sheereeniman ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
ping: bad address 'c2'

in the previous ping, it failed because the container c1 couldn't find container c2 to send a message. This occurred because the containers were placed on different networks and there was no network bridging, which isolated them from each other.

in this new ping, the ping was successful. both containers were on the same network because of the network bridging. container c1 was able to send a message to container c2, and c2 replied back.
```

## Intermediate Level (10 marks bonus)

### Node.js and MySQL in Docker Containers

This guide will help you set up a simple Node.js website that retrieves a random row from a MySQL database. Both the MySQL server and the Node.js server will run in separate Docker containers on two separate networks. Your job is to make it work by making the two containers in two separate network bridged together.

#### Step 1: Set Up the Docker Network

Create a Docker network to for the two containers.
For mysql, call it **mysqlnet** for nodejs call it **nodejsnet** .

#### Step 2: Set Up the MySQL Container

Run a MySQL container on the created network.

```sh
docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
```

#### Step 3: Set Up the Node.js Container

1. **Create a directory for your Node.js application and initialize it.**

    ```sh
    mkdir nodejs-app
    cd nodejs-app
    npm init -y
    npm install express mysql
    ```

2. **Create a file named `index.js` with the following content:**

    ```js
    const express = require('express');
    const mysql = require('mysql');

    const app = express();
    const port = 3000;

    // Create a MySQL connection
    const connection = mysql.createConnection({
      host: 'mysql-container',
      user: 'myuser',
      password: 'mypassword',
      database: 'mydatabase'
    });

    // Connect to MySQL
    connection.connect((err) => {
      if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
      }
      console.log('Connected to MySQL');
    });

    // Define a route to get a random row
    app.get('/random', (req, res) => {
      const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
      connection.query(query, (err, results) => {
        if (err) {
          console.error('Error executing query:', err);
          res.status(500).send('Server Error');
          return;
        }
        res.json(results[0]);
      });
    });

    // Start the server
    app.listen(port, () => {
      console.log(`Server running at http://localhost:${port}`);
    });
    ```

3. **Create a Dockerfile for the Node.js application:**

    ```Dockerfile
    # Use the official Node.js image
    FROM node:14

    # Create and change to the app directory
    WORKDIR /usr/src/app

    # Copy application dependency manifests to the container image
    COPY package*.json ./

    # Install production dependencies
    RUN npm install

    # Copy local code to the container image
    COPY . .

    # Run the web service on container startup
    CMD [ "node", "index.js" ]
    ```

#### Step 4: Build and Run the Node.js Container

1. **Build the Docker image for the Node.js application.**

    ```sh
    docker build -t nodejs-app .
    ```

2. **Run the Node.js container on the same network as the MySQL container.**

    ```sh
    docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
    ```

#### Step 5: Test the Setup

You can now test the setup by accessing the Node.js application in your browser or using a tool like `curl`:

```sh
curl http://localhost:3000/random
```

#### Step 6: Ensure `mytable` is Populated

Make sure you have created the `mytable` table and populated it with some data in your MySQL database for the above steps to work correctly.

You can use the following SQL commands to create and populate the table (run these commands in the MySQL container):

```sql
CREATE TABLE mytable (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  value VARCHAR(255) NOT NULL
);

INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
```

### Summary

You have now set up a Node.js application in a Docker container on nodejsnet netowrk and a MySQL database in another Docker container on mysqlnet network. Now bridge the two network together.

***Questions:***

1. What is the output of step 5 above, explain the error? ***(1 mark)***
```
Output :
@nffhmn ➜ /workspaces/OSProject (main) $ curl http://localhost:3000/random
curl: (7) Failed to connect to localhost port 3000: Connection refused

The error occurs because Node.js and MySQL are running on separate networks (nodejsnet and mysqlnet).
The Node.js container cannot resolve the hostname mysql-container because it is in a different network.

```
2. Show the instruction needed to make this work. ***(1 mark)***
```
@nffhmn ➜ /workspaces/OSProject (main) $ docker start mysql-container nodejs-container
mysql-container
nodejs-container
@nffhmn ➜ /workspaces/OSProject (main) $ docker network create mybridge
b2e449103ba062783b20931ede1ffde2cf4c08b9081aea416f38cf43899aa395
@nffhmn ➜ /workspaces/OSProject (main) $ docker network ls 
NETWORK ID     NAME        DRIVER    SCOPE
557f798c4602   bridge      bridge    local
05f292d1745a   host        host      local
b2e449103ba0   mybridge    bridge    local
16363c015231   mysqlnet    bridge    local
13423b8cda27   nodejsnet   bridge    local
716313e8b00f   none        null      local

@nffhmn ➜ /workspaces/OSProject (main) $ docker network connect mybridge mysql-container
@nffhmn ➜ /workspaces/OSProject (main) $ docker network connect mybridge nodejs-container

@nffhmn ➜ /workspaces/OSProject (main) $ docker run --name mysql-container --network mybridge -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
f36c6e50ccaca7fa319da112d10efb8772bdbca54b40b7e25eacd731dfec87cc
@nffhmn ➜ /workspaces/OSProject (main) $ docker run --name nodejs-container --network mybridge -p 3000:3000 -d nodejs-app
35626def763127b3dc0476fdbad4f867791ad503b4b2e5cb1ed4b8d62d293f75
@nffhmn ➜ /workspaces/OSProject (main) $ docker exec -it mysql-container mysql -umyuser -pmypassword mydatabase
mysql: [Warning] Using a password on the command line interface can be insecure.
Welcome to the MySQL monitor.  Commands end with ; or \g.
Server version: 9.2.0 MySQL Community Server - GPL

Copyright (c) 2000, 2025, Oracle and/or its affiliates.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql> CREATE TABLE mytable (
    ->   id INT AUTO_INCREMENT PRIMARY KEY,
    ->   name VARCHAR(255) NOT NULL,
    ->   value VARCHAR(255) NOT NULL
    -> );
Query OK, 0 rows affected (0.01 sec)

mysql> INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
Query OK, 3 rows affected (0.00 sec)
Records: 3  Duplicates: 0  Warnings: 0

mysql> ^DBye


```



## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***AS STATED IN ITALEEM SYSTEM***
