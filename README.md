# linux-0.01-compilable at centos8
linux kernel 0.01 ?


# Reference from 
https://github.com/mariuz/linux-0.01  
https://github.com/mariuz/linux-0.01/pull/2  


# Essential Package
yum groupinstall "Development Tools"  
yum install glibc-devel.i686   
yum install libgcc.i686  

# make linux-0.01 image
./make  

