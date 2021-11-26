# Jarkom-Modul-4-IUP1-2021


| Subnet  | Alias | Jumlah IP | Netmask |
| ------------- | ------------- | ------------- | ------------- |
| A1  | jipangu - pucci  | 101 | /25 |
| A2  | courtyard - calmbelt - pucci  | 2021 | /21 |
| A3  | pucci - water7 | 2 | /30 |
| A4  | cipher - water7  | 701 | /22 |
| A5  | blueno - foosha  | 1001 | /22 |
| A6  | water7 - foosha | 2 | /30 |
| A7  | foosha - guanhao  | 2 | /30 |
| A8  | jabra - guanhao  | 521 | /22 |
| A9  | guanhao - alabasta - maingate  | 502 | /23 |
| A10  | alabasta - jorge  | 13 | /28 |
| A11  | guanhao - oimo  | 2 | /30 |
| A12  | enieslobby - seastone - oimo  | 252 | /24 |
| A13  | seastone - elena  | 721 | /22 |
| A14  | foosha -doriki  | 2 | /30 |
| A15  | oimo - fukurou | 2 | /30 |
| Total  | -  | 5845 | /19 |

![Pohon IP Modul 4 (1)](https://user-images.githubusercontent.com/61174498/143044829-9ad476ae-82f5-4138-8bfa-3df2cad446ef.png)

![Untitled (2)](https://user-images.githubusercontent.com/61174498/142999208-15716177-3ac1-4f7d-b9b9-2caec471dc9b.png)

| Subnet | Node | IP | Subnet Mask | Length |
| --- | --- | --- | --- | --- |
| A1 | Pucci | 10.38.27.1 | 255.255.255.128 | /25 |
| A1 | Jipangu | 10.38.27.2 | 255.255.255.128 |  |
| A2 | Pucci | 10.38.0.1 | 255.255.248.0 | /21 |
| A2 | Courtyard | 10.38.0.2 | 255.255.248.0 |  |
| A2 | Calmbelt | 10.38.0.3 | 255.255.248.0 |  |
| A3 | Pucci | 10.38.27.145 | 255.255.255.252 | /30 |
| A3 | Water7 | 10.38.27.146 | 255.255.255.252 |  |
| A4 | Water7 | 10.38.8.1 | 255.255.252.0 | /22 |
| A4 | Cipher | 10.38.8.2 | 255.255.252.0 |  |
| A5 | Foosha | 10.38.12.1 | 255.255.252.0 | /22 |
| A5 | Blueno | 10.38.12.2 | 255.255.252.0 |  |
| A6 | Water7 | 10.38.27.149 | 255.255.255.252 | /30 |
| A6 | Foosha | 10.38.27.150 | 255.255.255.252 |  |
| A7 | Foosha | 10.38.27.153 | 255.255.255.252 | /30 |
| A7 | Guanhao | 10.38.27.154 | 255.255.255.252 |  |
| A8 | Guanhao | 10.38.16.1 | 255.255.252.0 | /22 |
| A8 | Jabra | 10.38.16.2 | 255.255.252.0 |  |
| A9 | Guanhao | 10.38.24.1 | 255.255.254.0 | /23 |
| A9 | Alabasta | 10.38.24.2 | 255.255.254.0 |  |
| A9 | Maingate | 10.38.24.3 | 255.255.254.0 |  |
| A10 | Alabasta | 10.38.27.129 | 255.255.255.240 | /28 |
| A10 | Jorge | 10.38.27.130 | 255.255.255.240 |  |
| A11 | Guanhao | 10.38.27.157 | 255.255.255.252 | /30 |
| A11 | Oimo | 10.38.27.158 | 255.255.255.252 |  |
| A12 | Oimo | 10.38.26.1 | 255.255.255.0 | /24 |
| A12 | Seastone | 10.38.26.2 | 255.255.255.0 |  |
| A12 | Enieslobby | 10.38.26.3 | 255.255.255.0 |  |
| A13 | Seastone | 10.38.20.1 | 255.255.252.0 | /22 |
| A13 | Elena | 10.38.20.2 | 255.255.252.0 |  |
| A14 | Foosha | 10.38.27.161 | 255.255.255.252 | /30 |
| A14 | Doriki | 10.38.27.162 | 255.255.255.252 |  |
| A15 | Oimo | 10.38.27.165 | 255.255.255.252 | /30 |
| A15 | Fukurou | 10.38.27.166 | 255.255.255.252 |  |


# A.) VLSM (Variable Length Subnet Masking)

## a.) Subnetting

### a1.) Config Router


#### 1. FOOSHA

##### FA 0/0
```

```

##### FA 0/1
```

```

##### FA 1/1
```

```

##### FA 0/3/0
```

```

##### FA 1/0
```

```


#### 2. WATER7

##### FA 0/0
```

```

##### FA 0/1
```

```

##### FA 1/0
```

```


#### 3. PUCCI

##### FA 0/0
```

```

##### FA 0/1
```

```

##### FA 1/0
```

```


#### 4. GUANHAO

##### FA 0/0
```

```

##### FA 0/1
```

```

##### FA 1/0
```

```

##### FA 1/1
```

```


#### 5. ALABASTA

##### FA 0/0
```

```

##### FA 0/1
```

```


#### 6. OIMO

##### FA 0/0
```

```

##### FA 0/1
```

```

##### FA 1/0
```

```


#### 7. SEASTONE

##### FA 0/0
```

```

##### FA 0/1
```

```


### a2.) Config PC & Server

#### 1. BLUENO
```

```

#### 2. CIPHER
```

```


#### 3. JIPANGU
```

```


#### 4. COURTYARD
```

```


#### 5. CALMBELT
```

```

#### 6. JABRA
```

```

#### 7. MAINGATE
```

```

#### 8. JORGE
```

```

#### 9. FUKUROU
```

```

#### 10. ENIESLOBBY
```

```

#### 11. ELENA
```

```

#### 12. DORIKI
```

```


## Static Routing

### 1. FOOSHA
```
BLUENO
10.38.12.0 
255.255.252.0
10.38.12.2

Cipher
10.38.8.0
255.255.252.0
10.38.27.150


JIPANGU
10.38.27.0
255.255.255.128
10.38.27.150


COURTYARD & CALMBELT
10.38.0.0
255.255.248.0
10.38.27.150

Doriki
10.38.27.160
255.255.255.252
10.38.27.162

Jabra
10.38.16.0
255.255.252.0
10.38.27.154

Maingate
10.38.24.0
255.255.254.0
10.38.27.154

Jorge
10.38.27.128
255.255.255.240
10.38.27.154

EniesLobby
10.38.26.0
255.255.255.0
10.38.27.154

Elena
10.38.20.0
255.255.252.0
10.38.27.154

Fukurou
10.38.27.164
255.255.255.252
10.38.27.154

```

Ruter terakhir 0.0.0.0 via sebelum menuju ruter
0.0.0.0/0 via 10.38.1.1

Ruter sebelum IP A yang belum via ip dari sebelum ke ruter
0.0.0.0/0 via 10.38.1.5
10.38.1.128/25 via 10.38.1.2



### 2. WATER7
```
JIPANGU
10.38.27.0
255.255.255.128
10.38.27.146

COURTYARD
10.38.0.0
255.255.248.0
10.38.27.146

0.0.0.0
0.0.0.0
10.38.27.149

```

### 3. PUCCI
```
0.0.0.0
0.0.0.0
10.38.27.145

```

### 4. GUANHAO
```
JORGE
10.38.27.128
255.255.255.240
10.38.24.2

FUKUROU
10.38.27.164
255.255.255.252
10.38.27.158

ENIESLOBBY
10.38.26.0
255.255.255.0
10.38.27.158

ELENA
10.38.20.0
255.255.252.0
10.38.27.158


0.0.0.0
0.0.0.0
10.38.27.153


```

### 5. ALABASTA
```
0.0.0.0
0.0.0.0
10.38.24.1
```

### 6. OIMO
```
ELENA
10.38.20.0
255.255.252.0
10.38.26.2

0.0.0.0
0.0.0.0
10.38.27.157
```

### 7. SEASTONE
```
0.0.0.0
0.0.0.0
10.38.26.1
```



# B.) CIDR (Classless Inter Domain Routing)

## Config ETH

| Subnet | Node | IP | Subnet Mask | Length |
| --- | --- | --- | --- | --- |
| A1 | jipangu pucci | 10.38.8.0 | 255.255.255.128 | 25 |
| A2 | court, calm, puc | 10.38.0.0 | 255.255.248.0 | 21 |
| A3 | pucci water | 10.38.16.0 | 255.255.255.252 | 30 |
| A4 | cipher water | 10.38.32.0 | 255.255.252.0 | 22 |
| A5 | blueno foosh | 10.38.128.0 | 255.255.252.0 | 22 |
| A6 | foosh wat | 10.38.64.0 | 255.255.255.252 | 30 |
| A7 | foosh guan | 10.38.64.0 | 255.255.255.252 | 30 |
| A8 | guan jabra | 10.38.36.0 | 255.255.252.0 | 22 |
| A9 | guanhao maingate alabas | 10.38.0.0 | 255.255.254.0 | 23 |
| A10 | alabas jorge | 10.38.34.0 | 255.255.255.240 | 28 |
| A11 | guan oimo | 10.38.16.0 | 255.255.255.252 | 30 |
| A12 | oimo enies seastone | 10.38.4.0 | 255.255.255.0 | 24 |
| A13 | seas elena | 10.38.0.0 | 255.255.252.0 | 22 |
| A14 | foosha doriki | 10.38.128.0 | 255.255.255.252 | 30 |
| A15 | fukurou oimo | 10.38.8.0 | 255.255.255.252 | 30 |

## Config GNS

### PUCCI
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.38.16.2
```

### PUCCI
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.38.64.2
route add -net 10.38.8.0 netmask 255.255.255.128 gw 10.38.16.1
route add -net 10.38.0.0 netmask 255.255.248.0 gw 10.38.16.1
```

### PUCCI
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.38.4.1
```

### PUCCI
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.38.16.1
route add -net 10.38.0.0 netmask 255.255.252.0 gw 10.38.4.2
```

### PUCCI
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.38.0.1
```

### PUCCI
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.200.64.1
route add -net 10.38.4.0 netmask 255.255.255.0 gw 10.38.16.2
route add -net 10.38.0.0 netmask 255.255.252.0 gw 10.38.16.2
route add -net 10.38.8.0 netmask 255.255.255.252 gw 10.38.16.2
```

### PUCCI
```
# bawah
route add -net 10.38.4.0 netmask 255.255.255.0 gw 10.38.64.2
route add -net 10.38.0.0 netmask 255.255.252.0 gw 10.38.64.2
route add -net 10.38.8.0 netmask 255.255.255.252 gw 10.38.64.2
route add -net 10.38.36.0 netmask 255.255.252.0 gw 10.38.64.2
route add -net 10.38.0.0 netmask 255.255.254.0 gw 10.38.64.2
route add -net 10.38.34.0 netmask 255.255.255.240 gw 10.38.64.2

# kiri
route add -net 10.38.8.0 netmask 255.255.255.128 gw 10.38.64.1
route add -net 10.38.0.0 netmask 255.255.248.0 gw 10.38.64.1
route add -net 10.38.32.0 netmask 255.255.252.0 gw 10.38.64.1
```

```
iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 10.38.0.0/15
```

```
echo "nameserver 10.38.122.1" > /etc/resolv.conf
```

## Config ETH

### Jipangu
```
auto eth0
iface eth0 inet static
address 10.38.8.2
netmask 255.255.255.128
gateway 10.38.8.1
```

### Pucci
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.38.16.1
netmask 255.255.255.252
gateway 10.38.16.2

auto eth1
iface eth1 inet static
address 10.38.8.1
netmask 255.255.255.128

auto eth2
iface eth2 inet static
address 10.38.0.1
netmask 255.255.248.0
```


### Courtyard
```
auto eth0
iface eth0 inet static
address 10.38.0.2
netmask 255.255.248.0
gateway 10.38.0.1
```


### Calmbelt
```
auto eth0
iface eth0 inet static
address 10.38.0.3
netmask 255.255.248.0
gateway 10.38.0.1
```


### Water7
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.38.64.1
netmask 255.255.255.252
gateway 10.38.64.2

auto eth1
iface eth1 inet static
address 10.38.32.1
netmask 255.255.252.0

auto eth2
iface eth2 inet static
address 10.38.16.2
netmask 255.255.255.252
```


### Cipher
```
auto eth0
iface eth0 inet static
address 10.38.32.2
netmask 255.255.252.0
gateway 10.38.32.1
```

### Foosha
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
address 10.38.128.1
netmask 255.255.252.0

auto eth2
iface eth2 inet static
address 10.38.64.2
netmask 255.255.255.252

auto eth3
iface eth3 inet static
address 10.38.128.1
netmask 255.255.255.252

auto eth4
iface eth4 inet static
address 10.38.64.1
netmask 255.255.255.252
```

### Blueno
```
auto eth0
iface eth0 inet static
address 10.38.128.2
netmask 255.255.252.0
gateway 10.38.128.1
```

### Doriki
```
auto eth0
iface eth0 inet static
address 10.38.128.2
netmask 255.255.255.252
gateway 10.38.128.1
```

### Guanhao
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.38.64.2
netmask 255.255.255.252
gateway 10.38.64.1

auto eth1
iface eth1 inet static
address 10.38.36.1
netmask 255.255.252.0

auto eth2
iface eth2 inet static
address 10.38.0.1
netmask 255.255.254.0


auto eth3
iface eth3 inet static
address 10.38.16.1
netmask 255.255.255.252
```

### Jabra
```
auto eth0
iface eth0 inet static
address 10.38.36.2
netmask 255.255.252.0
gateway 10.38.36.1
```

### Maingate
```
auto eth0
iface eth0 inet static
address 10.38.0.3
netmask 255.255.254.0
gateway 10.38.0.1
```

### Alabasta
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.38.0.2
netmask 255.255.254.0
gateway 10.38.0.1

auto eth1
iface eth1 inet static
address 10.38.34.1
netmask 255.255.255.240
```


### Jorge
```
auto eth0
iface eth0 inet static
address 10.38.34.2
netmask 255.255.255.240
gateway 10.38.34.1
```


### Oimo
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.38.16.2
netmask 255.255.255.252
gateway 10.38.16.1

auto eth1
iface eth1 inet static
address 10.38.8.1
netmask 255.255.255.252

auto eth2
iface eth2 inet static
address 10.38.4.1
netmask 255.255.255.0
```


### EniesLobby
```
auto eth0
iface eth0 inet static
address 10.38.4.3
netmask 255.255.255.0
gateway 10.38.4.1
```


### Seastone
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.38.4.2
netmask 255.255.255.0
gateway 10.38.4.1

auto eth1
iface eth1 inet static
address 255.255.252.1
netmask 10.38.0.0
```


### Elena
```
auto eth0
iface eth0 inet static
address 10.38.0.2
netmask 255.255.252.0
gateway 10.38.0.1
```
