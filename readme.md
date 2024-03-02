clone git@github.com:wongsyrone/qca-nss-sfe.git

lede build faild

1. lede 编译的时候碰到priv_flags_ext,IFF_EXT_MAPT,priv_flags_ext,netif_is_gretap,netif_is_ip6gretap的问题

implicit declaration of function 和 error: 'struct net_device' has no member named

不清楚是编译环境哪里问题

2. 12.2 以上编译的时候碰到<linux/if_trustsec.h>找不到头文件问题，不清楚是ubuntu内核不存在还是lede的kernel里不存在。也没找到哪里解决

