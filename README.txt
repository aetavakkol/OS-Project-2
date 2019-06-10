# 2019 Spring - Operating System Project 2 @ NTU

## Member

* 資工二 b06902093 王彥仁
* 資工二 b06902026 吳秉柔
* 資工二 b06902041 吳采耘
* 資工二 b06902054 蔡宥杏
* 醫學三 b05401009 謝德威
* 電機五 b03901056 孫凡耕

## Usage
./master_device : the device moudule for master server
./slave_device  : the device moudule for slave client
./ksocket: the device moudule including the funtions used for kernel socket
./data   : input/output data
./user_program : the user program "master" and "slave"


To use it, please:
1.change to super user
2.execute "./compile.sh" to compile codes and install modules(if you want to run the bonus, please execute ./compile_bonus.sh)
3.follow the input instrutions in the spec, 
i.e.
./master ../data/file1_in mmap
./slave ../data/file1_out fcntl 127.0.0.1

Make sure that you are under the path "./user_program" when you execute user programs.
Though the execution order of user program "master" and "slave" does not matter,
it is suggested to execute "master" first to get more precise transmission time.

## Report
[Report](https://github.com/wangyenjen/OS-Project-2/blob/master/report.pdf)


