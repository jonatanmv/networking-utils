# networking-utils
Notes about networking tools

# tcpdump
sudo tcpdump 'tcp[tcpflags] & (tcp-syn|tcp-fin) != 0 and src and dst 192.168.1.142'
