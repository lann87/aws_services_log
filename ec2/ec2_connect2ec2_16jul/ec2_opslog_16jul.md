# CLI Documentation - EC2 to EC2 connection.

  
```sh
alann@AP-Workstation-ThinkPad-P53:~$ ssh -i /home/alann/Downloads/alan_ce_useast1.pem ec2-user@18.215.63.212
   ,     #_
   ~\_  ####_        Amazon Linux 2023
  ~~  \_#####\
  ~~     \###|
  ~~       \#/ ___   https://aws.amazon.com/linux/amazon-linux-2023
   ~~       V~' '->
    ~~~         /
      ~~._.   _/
         _/ _/
       _/m/'
Last login: Tue Jul 16 10:24:36 2024 from 119.56.111.136
[ec2-user@ip-10-0-1-34 ~]$ ssh -i ~/.ssh/id_rsa 52.87.243.116
   ,     #_
   ~\_  ####_        Amazon Linux 2023
  ~~  \_#####\
  ~~     \###|
  ~~       \#/ ___   https://aws.amazon.com/linux/amazon-linux-2023
   ~~       V~' '->
    ~~~         /
      ~~._.   _/
         _/ _/
       _/m/'
Last login: Tue Jul 16 10:23:48 2024 from 119.56.111.136
[ec2-user@ip-10-0-2-208 ~]$ ping 18.215.63.212
PING 18.215.63.212 (18.215.63.212) 56(84) bytes of data.
64 bytes from 18.215.63.212: icmp_seq=1 ttl=126 time=0.702 ms
64 bytes from 18.215.63.212: icmp_seq=2 ttl=126 time=0.827 ms
64 bytes from 18.215.63.212: icmp_seq=3 ttl=126 time=0.855 ms
64 bytes from 18.215.63.212: icmp_seq=4 ttl=126 time=0.868 ms
64 bytes from 18.215.63.212: icmp_seq=5 ttl=126 time=0.766 ms
^C
--- 18.215.63.212 ping statistics ---
5 packets transmitted, 5 received, 0% packet loss, time 4090ms
rtt min/avg/max/mdev = 0.702/0.803/0.868/0.061 ms
[ec2-user@ip-10-0-2-208 ~]$
```
