[![](https://images.microbadger.com/badges/image/rodrigozc/oracle11g.svg)](https://microbadger.com/images/rodrigozc/oracle11g "Get your own image badge on microbadger.com")

[![](https://images.microbadger.com/badges/version/rodrigozc/oracle11g.svg)](https://microbadger.com/images/rodrigozc/oracle11g "Get your own version badge on microbadger.com")

# Docker Oracle11g
Oracle11g XE with SSH Server

---------------------------------------
### Installation and Usage

    docker pull rodrigozc/oracle11g
---------------------------------------
Run with all ports opened:

    docker run -d -p 1521:1521 -p 8080:8080 -p 2222:22 rodrigozc/oracle11g
---------------------------------------
Root password for ssh access:

    oracle
---------------------------------------
Password for database users SYSTEM and SYS:

    oracle
