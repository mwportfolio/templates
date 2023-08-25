```bash
nmap --top-ports=1000 -sC -sV -Pn --open $IP | tee ./enum/nmap/nmap_top1000ports.txt
```

