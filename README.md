# overthewire-wargames-bandit

```6$``` ```find -size 1033c ! -executable```

```7$``` ```find / -size 33c -user bandit7 -group bandit6```

```8$``` ```grep millionth data.txt```

```9$``` ```sort data.txt | uniq -u```

```10$``` ```strings data.txt | grep "=="```

```11$``` ```base64 data.txt -d```

```12$``` ```cat data.txt | tr a-zA-Z n-za-mN-ZA-M```

```13$``` ```xxd -r data.txt data.gz``` ```gzip -d data.gz``` ```bzip2 -d data``` ```...``` ```tar -xf data``` ```...```

```14$``` ```ssh -i sshkey.private bandit14@localhost```

```15$``` ```telnet localhost 30000``` or ```nc localhost 30000```

```16$``` ```openssl s_client -connect localhost:30001```

```17$``` ```nmap localhost -p 31000-32000 -sV```

```18$``` ```diff passwords.old passwords.new```

```19$``` ```ssh bandit18@bandit.labs.overthewire.org -p 2220 "cat readme"```

```20$``` ```./bandit20-do cat /etc/bandit_pass/bandit20```

https://overthewire.org/wargames/bandit/
