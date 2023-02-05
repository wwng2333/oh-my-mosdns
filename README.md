# oh-my-mosdns
My mosdns configure file and Grafana dashboard .
```bash
[root@nas ~]# git clone https://github.com/wwng2333/oh-my-mosdns.git
Cloning into 'oh-my-mosdns'...
remote: Enumerating objects: 176, done.
remote: Counting objects: 100% (40/40), done.
remote: Compressing objects: 100% (31/31), done.
remote: Total 176 (delta 21), reused 11 (delta 8), pack-reused 136
Receiving objects: 100% (176/176), 49.00 KiB | 88.00 KiB/s, done.
Resolving deltas: 100% (85/85), done.
[root@nas ~]# tree oh-my-mosdns/
oh-my-mosdns/
├── dashboard.json        # (v4.x)Grafana dashboard
├── dmm.yaml              # (v4.x)The configure for DNS unlock multimedia.
├── ecs_cn_domain.txt     # The configure using at China.
├── ecs.yaml              # The configure using at VPS, add ECS for DNS query.
├── full.yaml             # Main configure, backend of adguardhome.
├── leagcy                # Leagcy version of configures used at Mosdns v4.x
│   ├── full_v4.yaml
│   └── router_v4.yaml
├── LICENSE
├── README.md             # This file.
└── router.yaml           # Using at Router, forward DoH to UDP DNS, no cache. 
```
