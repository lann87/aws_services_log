# Documentation
> Created ec2 to ec2 connection limited/no resources, using amazon's linux & linux2


# CLI logs

```sh
alann@AP-Workstation-ThinkPad-P53:~$ ssh -i /home/alann/Downloads/alan_ce_useast1.pem ec2-user@44.211.54.66
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
Last login: Wed Jul 17 09:47:23 2024 from 119.56.109.172
[ec2-user@ip-10-0-1-211 ~]$ ssh -i ~/.ssh/id_rsa 3.83.161.151
The authenticity of host '3.83.161.151 (3.83.161.151)' can't be established.
ED25519 key fingerprint is SHA256:DND0hsmnD/4iosCpIVD9mRWS/6h1J8a9tVFvHGRM5bQ.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added '3.83.161.151' (ED25519) to the list of known hosts.
Last login: Wed Jul 17 09:51:57 2024 from 119.56.109.172
   ,     #_
   ~\_  ####_        Amazon Linux 2
  ~~  \_#####\
  ~~     \###|       AL2 End of Life is 2025-06-30.
  ~~       \#/ ___
   ~~       V~' '->
    ~~~         /    A newer version of Amazon Linux is available!
      ~~._.   _/
         _/ _/       Amazon Linux 2023, GA and supported until 2028-03-15.
       _/m/'           https://aws.amazon.com/linux/amazon-linux-2023/

[ec2-user@ip-10-0-2-82 ~]$ ping 44.211.54.66
PING 44.211.54.66 (44.211.54.66) 56(84) bytes of data.
64 bytes from 44.211.54.66: icmp_seq=1 ttl=126 time=0.704 ms
64 bytes from 44.211.54.66: icmp_seq=2 ttl=126 time=0.795 ms
64 bytes from 44.211.54.66: icmp_seq=3 ttl=126 time=0.784 ms
64 bytes from 44.211.54.66: icmp_seq=4 ttl=126 time=0.833 ms
64 bytes from 44.211.54.66: icmp_seq=5 ttl=126 time=0.821 ms
64 bytes from 44.211.54.66: icmp_seq=6 ttl=126 time=0.877 ms
^C
--- 44.211.54.66 ping statistics ---
6 packets transmitted, 6 received, 0% packet loss, time 5107ms
rtt min/avg/max/mdev = 0.704/0.802/0.877/0.057 ms
```
