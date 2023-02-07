# testcat8kv

| 項目 | 値 |
|------|----|
| Hostname | sunbgp-test |

## ページ内リンク
 - [Interface](#インタフェース)
 - [Neighbors](#隣接関係)
 - [VLAN](#vlan)
 - [Device](#機器情報)
 - [Hardware](#ハードウェア情報)


<!--- インターフェイス情報 --->
## インタフェース
### GigabitEthernet1 
##### IPv4 
| address | subnet |
|------|----|
| 10.0.0.33 | 24 |

##### IPv6
準備中

##### その他
| macaddress | mtu  | bandwidth | mediatype |
|------------|------|-----------|-----------|
| 000c.29f4.808a | 1500 | 1000000 | Virtual |

| duplex | lineprotocol | operstatus | type |
|--------|--------------|------------|------|
| Full | up | up | vNIC |


[{'name': 'GigabitEthernet1', 'enabled': True}]  
[{'name': 'GigabitEthernet1'}]  
[{'name': 'GigabitEthernet1', 'ipv4': [{'address': '10.0.0.33/24'}]}]  

<!--- 隣接関係 --->
## 隣接関係
|装置名|ローカルインタフェース|隣接装置名|隣接インタフェース|
|------|--------------------|--------|-----------------|

## VLAN
| name | vlan id | state | shutdown | mtu |
|------|---------|-------|----------|-----|
| default | 1 | active | disabled | 1500 |   
| fddi-default | 1002 | active | enabled | 1500 |   
| token-ring-default | 1003 | active | enabled | 1500 |   
| fddinet-default | 1004 | active | enabled | 1500 |   
| trnet-default | 1005 | active | enabled | 1500 |   

## bgp  (準備中)

{}  
{}  

### AS Number : None

## ACL(準備中)

[{'afi': 'ipv4', 'acls': [{'name': 'meraki-fqdn-dns', 'acl_type': 'extended'}]}]  
[]  
## LACP(準備中)

{'system': {'priority': 32768}}  
[{'name': 'GigabitEthernet1'}]  
{}  
## LLDP(準備中)

None  
None  
## NTP (準備中)

{}  
## OSPF (準備中)

[{'name': 'GigabitEthernet1'}]  
None  
None  
## SNMP (準備中)

{}  

<!--- バージョン情報等 --->
## 機器情報
| 項目 | 値 |
|------|----|
| Serial Number | 95M0DF4TAXY |  
| OS Version | 17.07.01a |
| IOS Type | IOS-XE |  
| Model | C8000V |  
| Image | bootflash:packages.conf |  
| API | cliconf |    
| Python Version | 3.10.6 | 
<!--- ハードウェア情報 --->
## ハードウェア情報
### メモリ
| 項目 | 値 |
|------|----|
| memfree | 2049217.22265625 |  
| memtotal | 2228450.48046875 |  

### ファイルシステム
| name | spacetotal_kb | spacefree_kb |
|------|---------------|--------------|
  | filesystem | info.spacetotal_kb | info.spacefree_kb |
