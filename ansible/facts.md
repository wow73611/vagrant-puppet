puppet-master | SUCCESS => {
    "ansible_facts": {
        "ansible_all_ipv4_addresses": [
            "10.0.2.15", 
            "192.168.10.11"
        ], 
        "ansible_all_ipv6_addresses": [
            "fe80::6c:72ff:fe8e:2ff", 
            "fe80::a00:27ff:fe45:b874"
        ], 
        "ansible_architecture": "x86_64", 
        "ansible_bios_date": "12/01/2006", 
        "ansible_bios_version": "VirtualBox", 
        "ansible_cmdline": {
            "BOOT_IMAGE": "/boot/vmlinuz-4.4.0-141-generic", 
            "console": "ttyS0", 
            "ro": true, 
            "root": "LABEL=cloudimg-rootfs"
        }, 
        "ansible_date_time": {
            "date": "2019-01-07", 
            "day": "07", 
            "epoch": "1546832232", 
            "hour": "03", 
            "iso8601": "2019-01-07T03:37:12Z", 
            "iso8601_basic": "20190107T033712936609", 
            "iso8601_basic_short": "20190107T033712", 
            "iso8601_micro": "2019-01-07T03:37:12.936700Z", 
            "minute": "37", 
            "month": "01", 
            "second": "12", 
            "time": "03:37:12", 
            "tz": "UTC", 
            "tz_offset": "+0000", 
            "weekday": "Monday", 
            "weekday_number": "1", 
            "weeknumber": "01", 
            "year": "2019"
        }, 
        "ansible_default_ipv4": {
            "address": "10.0.2.15", 
            "alias": "enp0s3", 
            "broadcast": "10.0.2.255", 
            "gateway": "10.0.2.2", 
            "interface": "enp0s3", 
            "macaddress": "02:6c:72:8e:02:ff", 
            "mtu": 1500, 
            "netmask": "255.255.255.0", 
            "network": "10.0.2.0", 
            "type": "ether"
        }, 
        "ansible_default_ipv6": {}, 
        "ansible_devices": {
            "sda": {
                "holders": [], 
                "host": "SCSI storage controller: LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI", 
                "model": "HARDDISK", 
                "partitions": {
                    "sda1": {
                        "holders": [], 
                        "sectors": "20969439", 
                        "sectorsize": 512, 
                        "size": "10.00 GB", 
                        "start": "2048", 
                        "uuid": "92feb7e5-d622-440b-aa57-d61e8db0f495"
                    }
                }, 
                "removable": "0", 
                "rotational": "1", 
                "sas_address": null, 
                "sas_device_handle": null, 
                "scheduler_mode": "deadline", 
                "sectors": "20971520", 
                "sectorsize": "512", 
                "size": "10.00 GB", 
                "support_discard": "0", 
                "vendor": "VBOX"
            }, 
            "sdb": {
                "holders": [], 
                "host": "SCSI storage controller: LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI", 
                "model": "HARDDISK", 
                "partitions": {}, 
                "removable": "0", 
                "rotational": "1", 
                "sas_address": null, 
                "sas_device_handle": null, 
                "scheduler_mode": "deadline", 
                "sectors": "20480", 
                "sectorsize": "512", 
                "size": "10.00 MB", 
                "support_discard": "0", 
                "vendor": "VBOX"
            }
        }, 
        "ansible_distribution": "Ubuntu", 
        "ansible_distribution_major_version": "16", 
        "ansible_distribution_release": "xenial", 
        "ansible_distribution_version": "16.04", 
        "ansible_dns": {
            "nameservers": [
                "10.0.2.3"
            ]
        }, 
        "ansible_domain": "", 
        "ansible_enp0s3": {
            "active": true, 
            "device": "enp0s3", 
            "features": {
                "busy_poll": "on [fixed]", 
                "fcoe_mtu": "off [fixed]", 
                "generic_receive_offload": "on", 
                "generic_segmentation_offload": "on", 
                "highdma": "on [fixed]", 
                "hw_tc_offload": "off [fixed]", 
                "l2_fwd_offload": "off [fixed]", 
                "large_receive_offload": "off [fixed]", 
                "loopback": "off [fixed]", 
                "netns_local": "off [fixed]", 
                "ntuple_filters": "off [fixed]", 
                "receive_hashing": "off [fixed]", 
                "rx_all": "off [fixed]", 
                "rx_checksumming": "on [fixed]", 
                "rx_fcs": "off [fixed]", 
                "rx_vlan_filter": "on [fixed]", 
                "rx_vlan_offload": "off [fixed]", 
                "rx_vlan_stag_filter": "off [fixed]", 
                "rx_vlan_stag_hw_parse": "off [fixed]", 
                "scatter_gather": "on", 
                "tcp_segmentation_offload": "on", 
                "tx_checksum_fcoe_crc": "off [fixed]", 
                "tx_checksum_ip_generic": "on", 
                "tx_checksum_ipv4": "off [fixed]", 
                "tx_checksum_ipv6": "off [fixed]", 
                "tx_checksum_sctp": "off [fixed]", 
                "tx_checksumming": "on", 
                "tx_fcoe_segmentation": "off [fixed]", 
                "tx_gre_segmentation": "off [fixed]", 
                "tx_gso_robust": "on [fixed]", 
                "tx_ipip_segmentation": "off [fixed]", 
                "tx_lockless": "off [fixed]", 
                "tx_nocache_copy": "off", 
                "tx_scatter_gather": "on", 
                "tx_scatter_gather_fraglist": "off [fixed]", 
                "tx_sit_segmentation": "off [fixed]", 
                "tx_tcp6_segmentation": "on", 
                "tx_tcp_ecn_segmentation": "off [fixed]", 
                "tx_tcp_segmentation": "on", 
                "tx_udp_tnl_segmentation": "off [fixed]", 
                "tx_vlan_offload": "off [fixed]", 
                "tx_vlan_stag_hw_insert": "off [fixed]", 
                "udp_fragmentation_offload": "on", 
                "vlan_challenged": "off [fixed]"
            }, 
            "ipv4": {
                "address": "10.0.2.15", 
                "broadcast": "10.0.2.255", 
                "netmask": "255.255.255.0", 
                "network": "10.0.2.0"
            }, 
            "ipv6": [
                {
                    "address": "fe80::6c:72ff:fe8e:2ff", 
                    "prefix": "64", 
                    "scope": "link"
                }
            ], 
            "macaddress": "02:6c:72:8e:02:ff", 
            "mtu": 1500, 
            "pciid": "virtio0", 
            "promisc": false, 
            "speed": -1, 
            "type": "ether"
        }, 
        "ansible_enp0s8": {
            "active": true, 
            "device": "enp0s8", 
            "features": {
                "busy_poll": "on [fixed]", 
                "fcoe_mtu": "off [fixed]", 
                "generic_receive_offload": "on", 
                "generic_segmentation_offload": "on", 
                "highdma": "on [fixed]", 
                "hw_tc_offload": "off [fixed]", 
                "l2_fwd_offload": "off [fixed]", 
                "large_receive_offload": "off [fixed]", 
                "loopback": "off [fixed]", 
                "netns_local": "off [fixed]", 
                "ntuple_filters": "off [fixed]", 
                "receive_hashing": "off [fixed]", 
                "rx_all": "off [fixed]", 
                "rx_checksumming": "on [fixed]", 
                "rx_fcs": "off [fixed]", 
                "rx_vlan_filter": "on [fixed]", 
                "rx_vlan_offload": "off [fixed]", 
                "rx_vlan_stag_filter": "off [fixed]", 
                "rx_vlan_stag_hw_parse": "off [fixed]", 
                "scatter_gather": "on", 
                "tcp_segmentation_offload": "on", 
                "tx_checksum_fcoe_crc": "off [fixed]", 
                "tx_checksum_ip_generic": "on", 
                "tx_checksum_ipv4": "off [fixed]", 
                "tx_checksum_ipv6": "off [fixed]", 
                "tx_checksum_sctp": "off [fixed]", 
                "tx_checksumming": "on", 
                "tx_fcoe_segmentation": "off [fixed]", 
                "tx_gre_segmentation": "off [fixed]", 
                "tx_gso_robust": "on [fixed]", 
                "tx_ipip_segmentation": "off [fixed]", 
                "tx_lockless": "off [fixed]", 
                "tx_nocache_copy": "off", 
                "tx_scatter_gather": "on", 
                "tx_scatter_gather_fraglist": "off [fixed]", 
                "tx_sit_segmentation": "off [fixed]", 
                "tx_tcp6_segmentation": "on", 
                "tx_tcp_ecn_segmentation": "off [fixed]", 
                "tx_tcp_segmentation": "on", 
                "tx_udp_tnl_segmentation": "off [fixed]", 
                "tx_vlan_offload": "off [fixed]", 
                "tx_vlan_stag_hw_insert": "off [fixed]", 
                "udp_fragmentation_offload": "on", 
                "vlan_challenged": "off [fixed]"
            }, 
            "ipv4": {
                "address": "192.168.10.11", 
                "broadcast": "192.168.10.255", 
                "netmask": "255.255.255.0", 
                "network": "192.168.10.0"
            }, 
            "ipv6": [
                {
                    "address": "fe80::a00:27ff:fe45:b874", 
                    "prefix": "64", 
                    "scope": "link"
                }
            ], 
            "macaddress": "08:00:27:45:b8:74", 
            "mtu": 1500, 
            "pciid": "virtio1", 
            "promisc": false, 
            "speed": -1, 
            "type": "ether"
        }, 
        "ansible_env": {
            "HOME": "/home/vagrant", 
            "LANG": "en_US.UTF-8", 
            "LOGNAME": "vagrant", 
            "MAIL": "/var/mail/vagrant", 
            "PATH": "/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games", 
            "PWD": "/home/vagrant", 
            "SHELL": "/bin/bash", 
            "SHLVL": "1", 
            "SSH_CLIENT": "10.0.2.2 49759 22", 
            "SSH_CONNECTION": "10.0.2.2 49759 10.0.2.15 22", 
            "USER": "vagrant", 
            "XDG_RUNTIME_DIR": "/run/user/1000", 
            "XDG_SESSION_ID": "4", 
            "_": "/bin/sh"
        }, 
        "ansible_fips": false, 
        "ansible_form_factor": "Other", 
        "ansible_fqdn": "puppet-master", 
        "ansible_gather_subset": [
            "hardware", 
            "network", 
            "virtual"
        ], 
        "ansible_hostname": "puppet-master", 
        "ansible_interfaces": [
            "lo", 
            "enp0s3", 
            "enp0s8"
        ], 
        "ansible_kernel": "4.4.0-141-generic", 
        "ansible_lo": {
            "active": true, 
            "device": "lo", 
            "features": {
                "busy_poll": "off [fixed]", 
                "fcoe_mtu": "off [fixed]", 
                "generic_receive_offload": "on", 
                "generic_segmentation_offload": "on", 
                "highdma": "on [fixed]", 
                "hw_tc_offload": "off [fixed]", 
                "l2_fwd_offload": "off [fixed]", 
                "large_receive_offload": "off [fixed]", 
                "loopback": "on [fixed]", 
                "netns_local": "on [fixed]", 
                "ntuple_filters": "off [fixed]", 
                "receive_hashing": "off [fixed]", 
                "rx_all": "off [fixed]", 
                "rx_checksumming": "on [fixed]", 
                "rx_fcs": "off [fixed]", 
                "rx_vlan_filter": "off [fixed]", 
                "rx_vlan_offload": "off [fixed]", 
                "rx_vlan_stag_filter": "off [fixed]", 
                "rx_vlan_stag_hw_parse": "off [fixed]", 
                "scatter_gather": "on", 
                "tcp_segmentation_offload": "on", 
                "tx_checksum_fcoe_crc": "off [fixed]", 
                "tx_checksum_ip_generic": "on [fixed]", 
                "tx_checksum_ipv4": "off [fixed]", 
                "tx_checksum_ipv6": "off [fixed]", 
                "tx_checksum_sctp": "on [fixed]", 
                "tx_checksumming": "on", 
                "tx_fcoe_segmentation": "off [fixed]", 
                "tx_gre_segmentation": "off [fixed]", 
                "tx_gso_robust": "off [fixed]", 
                "tx_ipip_segmentation": "off [fixed]", 
                "tx_lockless": "on [fixed]", 
                "tx_nocache_copy": "off [fixed]", 
                "tx_scatter_gather": "on [fixed]", 
                "tx_scatter_gather_fraglist": "on [fixed]", 
                "tx_sit_segmentation": "off [fixed]", 
                "tx_tcp6_segmentation": "on", 
                "tx_tcp_ecn_segmentation": "on", 
                "tx_tcp_segmentation": "on", 
                "tx_udp_tnl_segmentation": "off [fixed]", 
                "tx_vlan_offload": "off [fixed]", 
                "tx_vlan_stag_hw_insert": "off [fixed]", 
                "udp_fragmentation_offload": "on", 
                "vlan_challenged": "on [fixed]"
            }, 
            "ipv4": {
                "address": "127.0.0.1", 
                "broadcast": "host", 
                "netmask": "255.0.0.0", 
                "network": "127.0.0.0"
            }, 
            "ipv6": [
                {
                    "address": "::1", 
                    "prefix": "128", 
                    "scope": "host"
                }
            ], 
            "mtu": 65536, 
            "promisc": false, 
            "type": "loopback"
        }, 
        "ansible_lsb": {
            "codename": "xenial", 
            "description": "Ubuntu 16.04.5 LTS", 
            "id": "Ubuntu", 
            "major_release": "16", 
            "release": "16.04"
        }, 
        "ansible_machine": "x86_64", 
        "ansible_machine_id": "e3019ead29e1458ea53affd2b2f3abbf", 
        "ansible_memfree_mb": 673, 
        "ansible_memory_mb": {
            "nocache": {
                "free": 905, 
                "used": 87
            }, 
            "real": {
                "free": 673, 
                "total": 992, 
                "used": 319
            }, 
            "swap": {
                "cached": 0, 
                "free": 0, 
                "total": 0, 
                "used": 0
            }
        }, 
        "ansible_memtotal_mb": 992, 
        "ansible_mounts": [
            {
                "device": "/dev/sda1", 
                "fstype": "ext4", 
                "mount": "/", 
                "options": "rw,relatime,data=ordered", 
                "size_available": 9370189824, 
                "size_total": 10340831232, 
                "uuid": "92feb7e5-d622-440b-aa57-d61e8db0f495"
            }
        ], 
        "ansible_nodename": "puppet-master", 
        "ansible_os_family": "Debian", 
        "ansible_pkg_mgr": "apt", 
        "ansible_processor": [
            "GenuineIntel", 
            "Intel(R) Core(TM) i7-7660U CPU @ 2.50GHz"
        ], 
        "ansible_processor_cores": 1, 
        "ansible_processor_count": 1, 
        "ansible_processor_threads_per_core": 1, 
        "ansible_processor_vcpus": 1, 
        "ansible_product_name": "VirtualBox", 
        "ansible_product_serial": "NA", 
        "ansible_product_uuid": "NA", 
        "ansible_product_version": "1.2", 
        "ansible_python": {
            "executable": "/usr/bin/python", 
            "has_sslcontext": true, 
            "type": "CPython", 
            "version": {
                "major": 2, 
                "micro": 12, 
                "minor": 7, 
                "releaselevel": "final", 
                "serial": 0
            }, 
            "version_info": [
                2, 
                7, 
                12, 
                "final", 
                0
            ]
        }, 
        "ansible_python_version": "2.7.12", 
        "ansible_selinux": false, 
        "ansible_service_mgr": "systemd", 
        "ansible_ssh_host_key_dsa_public": "AAAAB3NzaC1kc3MAAACBAPc9GikuBrvQJLn0mekRvKbM8Ow4MmwV5XjUYHlYLihhLbHyUTjGA2j0U6dKNVEdnx2F2jcxg/vjTgpiD+9ZUeLjR8dY/W2WKIXL8RX9O8YkRVPCWNujFt8xooXeFU+HTFsvnNmNbDP3vjE8IJv+jWrz/Xdhi0pNJJMpWY7kmQ5TAAAAFQD1yzXUal7AUnM/sIG71p58O8uRNQAAAIBcIB7v4BBM8mv0JZtTi4/mftyhjvaDX7izzDcbERTZANPfUudYDGSoC0pRBbtFuoACN0oo69gteIb/Ke5ZIHZ6iy21he93mB9Ahidw/QXy5nI1jn4POkx0wAPfkg3t/ffjBSADak/Lb03xik06vXUCllVMUd1oUNu7zqRdrksrEQAAAIA3Ge89KKQCm8oD9Dzjuan/bX7Y8iUUFyMP58iKQbOb9CxuC84tZOXkj+dFeeVHIwdXwKotmpzpS+KVairNnbA24xe9IDAKpG2vqc6pgJ34VoR6p5S7h6T/4jmdQdtq30fD0/FkxngdcJxqIo584QwuvZGgUYUX2zdvRB7/xbmzZw==", 
        "ansible_ssh_host_key_ecdsa_public": "AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBK3BJsV/GVTN7BCZhuDjb3Uj5qwh4ywTKKcwQbvRUUdTnD0uyLtaoJMqA2bnsH1dJYAWjxUJt+IskK/FAzQXn5w=", 
        "ansible_ssh_host_key_ed25519_public": "AAAAC3NzaC1lZDI1NTE5AAAAII76zdQ43W3jMaiEtdY80w2+0O58UvabXcZcazo6YePH", 
        "ansible_ssh_host_key_rsa_public": "AAAAB3NzaC1yc2EAAAADAQABAAABAQDI/IBJXBAPTvEjXStA4H64e/JwHIAde36dCHdwjgr/41/vRc9dIW2szvXO8j2gg3bhGdPeUqIDxTC/wimp8AdTHZTm+WVcuHVs6USfcjWa3P+SH2nEAUsHL4gMUDr2fbDdqAoAtdz2xXn23QOBJgTWZc08ZX7L5y9Zsg84rUQ85nIncB4FqTybkN25xsD5AOiFWqnncxHPn8Vrajz7o/VNuw7CZ0IiWJnmbXKlxjqUCoB8JNeVtWbJ0GiMqId+GPpUrnY9J3s5llcjEUh8GM/gnFYqY8rKkTUncQe95+6YzOc5oBruvXlvezYjdx5IdO91dkhFFFQJYs9Q+QedxKEp", 
        "ansible_swapfree_mb": 0, 
        "ansible_swaptotal_mb": 0, 
        "ansible_system": "Linux", 
        "ansible_system_capabilities": [
            ""
        ], 
        "ansible_system_capabilities_enforced": "True", 
        "ansible_system_vendor": "innotek GmbH", 
        "ansible_uptime_seconds": 2284, 
        "ansible_user_dir": "/home/vagrant", 
        "ansible_user_gecos": ",,,", 
        "ansible_user_gid": 1000, 
        "ansible_user_id": "vagrant", 
        "ansible_user_shell": "/bin/bash", 
        "ansible_user_uid": 1000, 
        "ansible_userspace_architecture": "x86_64", 
        "ansible_userspace_bits": "64", 
        "ansible_virtualization_role": "guest", 
        "ansible_virtualization_type": "virtualbox", 
        "module_setup": true
    }, 
    "changed": false
}
puppet-agent | SUCCESS => {
    "ansible_facts": {
        "ansible_all_ipv4_addresses": [
            "10.0.2.15", 
            "192.168.10.12"
        ], 
        "ansible_all_ipv6_addresses": [
            "fe80::6c:72ff:fe8e:2ff", 
            "fe80::a00:27ff:feae:7c3c"
        ], 
        "ansible_architecture": "x86_64", 
        "ansible_bios_date": "12/01/2006", 
        "ansible_bios_version": "VirtualBox", 
        "ansible_cmdline": {
            "BOOT_IMAGE": "/boot/vmlinuz-4.4.0-141-generic", 
            "console": "ttyS0", 
            "ro": true, 
            "root": "LABEL=cloudimg-rootfs"
        }, 
        "ansible_date_time": {
            "date": "2019-01-07", 
            "day": "07", 
            "epoch": "1546832232", 
            "hour": "03", 
            "iso8601": "2019-01-07T03:37:12Z", 
            "iso8601_basic": "20190107T033712365058", 
            "iso8601_basic_short": "20190107T033712", 
            "iso8601_micro": "2019-01-07T03:37:12.365150Z", 
            "minute": "37", 
            "month": "01", 
            "second": "12", 
            "time": "03:37:12", 
            "tz": "UTC", 
            "tz_offset": "+0000", 
            "weekday": "Monday", 
            "weekday_number": "1", 
            "weeknumber": "01", 
            "year": "2019"
        }, 
        "ansible_default_ipv4": {
            "address": "10.0.2.15", 
            "alias": "enp0s3", 
            "broadcast": "10.0.2.255", 
            "gateway": "10.0.2.2", 
            "interface": "enp0s3", 
            "macaddress": "02:6c:72:8e:02:ff", 
            "mtu": 1500, 
            "netmask": "255.255.255.0", 
            "network": "10.0.2.0", 
            "type": "ether"
        }, 
        "ansible_default_ipv6": {}, 
        "ansible_devices": {
            "sda": {
                "holders": [], 
                "host": "SCSI storage controller: LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI", 
                "model": "HARDDISK", 
                "partitions": {
                    "sda1": {
                        "holders": [], 
                        "sectors": "20969439", 
                        "sectorsize": 512, 
                        "size": "10.00 GB", 
                        "start": "2048", 
                        "uuid": "92feb7e5-d622-440b-aa57-d61e8db0f495"
                    }
                }, 
                "removable": "0", 
                "rotational": "1", 
                "sas_address": null, 
                "sas_device_handle": null, 
                "scheduler_mode": "deadline", 
                "sectors": "20971520", 
                "sectorsize": "512", 
                "size": "10.00 GB", 
                "support_discard": "0", 
                "vendor": "VBOX"
            }, 
            "sdb": {
                "holders": [], 
                "host": "SCSI storage controller: LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI", 
                "model": "HARDDISK", 
                "partitions": {}, 
                "removable": "0", 
                "rotational": "1", 
                "sas_address": null, 
                "sas_device_handle": null, 
                "scheduler_mode": "deadline", 
                "sectors": "20480", 
                "sectorsize": "512", 
                "size": "10.00 MB", 
                "support_discard": "0", 
                "vendor": "VBOX"
            }
        }, 
        "ansible_distribution": "Ubuntu", 
        "ansible_distribution_major_version": "16", 
        "ansible_distribution_release": "xenial", 
        "ansible_distribution_version": "16.04", 
        "ansible_dns": {
            "nameservers": [
                "10.0.2.3"
            ]
        }, 
        "ansible_domain": "", 
        "ansible_enp0s3": {
            "active": true, 
            "device": "enp0s3", 
            "features": {
                "busy_poll": "on [fixed]", 
                "fcoe_mtu": "off [fixed]", 
                "generic_receive_offload": "on", 
                "generic_segmentation_offload": "on", 
                "highdma": "on [fixed]", 
                "hw_tc_offload": "off [fixed]", 
                "l2_fwd_offload": "off [fixed]", 
                "large_receive_offload": "off [fixed]", 
                "loopback": "off [fixed]", 
                "netns_local": "off [fixed]", 
                "ntuple_filters": "off [fixed]", 
                "receive_hashing": "off [fixed]", 
                "rx_all": "off [fixed]", 
                "rx_checksumming": "on [fixed]", 
                "rx_fcs": "off [fixed]", 
                "rx_vlan_filter": "on [fixed]", 
                "rx_vlan_offload": "off [fixed]", 
                "rx_vlan_stag_filter": "off [fixed]", 
                "rx_vlan_stag_hw_parse": "off [fixed]", 
                "scatter_gather": "on", 
                "tcp_segmentation_offload": "on", 
                "tx_checksum_fcoe_crc": "off [fixed]", 
                "tx_checksum_ip_generic": "on", 
                "tx_checksum_ipv4": "off [fixed]", 
                "tx_checksum_ipv6": "off [fixed]", 
                "tx_checksum_sctp": "off [fixed]", 
                "tx_checksumming": "on", 
                "tx_fcoe_segmentation": "off [fixed]", 
                "tx_gre_segmentation": "off [fixed]", 
                "tx_gso_robust": "on [fixed]", 
                "tx_ipip_segmentation": "off [fixed]", 
                "tx_lockless": "off [fixed]", 
                "tx_nocache_copy": "off", 
                "tx_scatter_gather": "on", 
                "tx_scatter_gather_fraglist": "off [fixed]", 
                "tx_sit_segmentation": "off [fixed]", 
                "tx_tcp6_segmentation": "on", 
                "tx_tcp_ecn_segmentation": "off [fixed]", 
                "tx_tcp_segmentation": "on", 
                "tx_udp_tnl_segmentation": "off [fixed]", 
                "tx_vlan_offload": "off [fixed]", 
                "tx_vlan_stag_hw_insert": "off [fixed]", 
                "udp_fragmentation_offload": "on", 
                "vlan_challenged": "off [fixed]"
            }, 
            "ipv4": {
                "address": "10.0.2.15", 
                "broadcast": "10.0.2.255", 
                "netmask": "255.255.255.0", 
                "network": "10.0.2.0"
            }, 
            "ipv6": [
                {
                    "address": "fe80::6c:72ff:fe8e:2ff", 
                    "prefix": "64", 
                    "scope": "link"
                }
            ], 
            "macaddress": "02:6c:72:8e:02:ff", 
            "mtu": 1500, 
            "pciid": "virtio0", 
            "promisc": false, 
            "speed": -1, 
            "type": "ether"
        }, 
        "ansible_enp0s8": {
            "active": true, 
            "device": "enp0s8", 
            "features": {
                "busy_poll": "on [fixed]", 
                "fcoe_mtu": "off [fixed]", 
                "generic_receive_offload": "on", 
                "generic_segmentation_offload": "on", 
                "highdma": "on [fixed]", 
                "hw_tc_offload": "off [fixed]", 
                "l2_fwd_offload": "off [fixed]", 
                "large_receive_offload": "off [fixed]", 
                "loopback": "off [fixed]", 
                "netns_local": "off [fixed]", 
                "ntuple_filters": "off [fixed]", 
                "receive_hashing": "off [fixed]", 
                "rx_all": "off [fixed]", 
                "rx_checksumming": "on [fixed]", 
                "rx_fcs": "off [fixed]", 
                "rx_vlan_filter": "on [fixed]", 
                "rx_vlan_offload": "off [fixed]", 
                "rx_vlan_stag_filter": "off [fixed]", 
                "rx_vlan_stag_hw_parse": "off [fixed]", 
                "scatter_gather": "on", 
                "tcp_segmentation_offload": "on", 
                "tx_checksum_fcoe_crc": "off [fixed]", 
                "tx_checksum_ip_generic": "on", 
                "tx_checksum_ipv4": "off [fixed]", 
                "tx_checksum_ipv6": "off [fixed]", 
                "tx_checksum_sctp": "off [fixed]", 
                "tx_checksumming": "on", 
                "tx_fcoe_segmentation": "off [fixed]", 
                "tx_gre_segmentation": "off [fixed]", 
                "tx_gso_robust": "on [fixed]", 
                "tx_ipip_segmentation": "off [fixed]", 
                "tx_lockless": "off [fixed]", 
                "tx_nocache_copy": "off", 
                "tx_scatter_gather": "on", 
                "tx_scatter_gather_fraglist": "off [fixed]", 
                "tx_sit_segmentation": "off [fixed]", 
                "tx_tcp6_segmentation": "on", 
                "tx_tcp_ecn_segmentation": "off [fixed]", 
                "tx_tcp_segmentation": "on", 
                "tx_udp_tnl_segmentation": "off [fixed]", 
                "tx_vlan_offload": "off [fixed]", 
                "tx_vlan_stag_hw_insert": "off [fixed]", 
                "udp_fragmentation_offload": "on", 
                "vlan_challenged": "off [fixed]"
            }, 
            "ipv4": {
                "address": "192.168.10.12", 
                "broadcast": "192.168.10.255", 
                "netmask": "255.255.255.0", 
                "network": "192.168.10.0"
            }, 
            "ipv6": [
                {
                    "address": "fe80::a00:27ff:feae:7c3c", 
                    "prefix": "64", 
                    "scope": "link"
                }
            ], 
            "macaddress": "08:00:27:ae:7c:3c", 
            "mtu": 1500, 
            "pciid": "virtio1", 
            "promisc": false, 
            "speed": -1, 
            "type": "ether"
        }, 
        "ansible_env": {
            "HOME": "/home/vagrant", 
            "LANG": "en_US.UTF-8", 
            "LOGNAME": "vagrant", 
            "MAIL": "/var/mail/vagrant", 
            "PATH": "/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games", 
            "PWD": "/home/vagrant", 
            "SHELL": "/bin/bash", 
            "SHLVL": "1", 
            "SSH_CLIENT": "10.0.2.2 49760 22", 
            "SSH_CONNECTION": "10.0.2.2 49760 10.0.2.15 22", 
            "USER": "vagrant", 
            "XDG_RUNTIME_DIR": "/run/user/1000", 
            "XDG_SESSION_ID": "3", 
            "_": "/bin/sh"
        }, 
        "ansible_fips": false, 
        "ansible_form_factor": "Other", 
        "ansible_fqdn": "puppet-agent", 
        "ansible_gather_subset": [
            "hardware", 
            "network", 
            "virtual"
        ], 
        "ansible_hostname": "puppet-agent", 
        "ansible_interfaces": [
            "lo", 
            "enp0s3", 
            "enp0s8"
        ], 
        "ansible_kernel": "4.4.0-141-generic", 
        "ansible_lo": {
            "active": true, 
            "device": "lo", 
            "features": {
                "busy_poll": "off [fixed]", 
                "fcoe_mtu": "off [fixed]", 
                "generic_receive_offload": "on", 
                "generic_segmentation_offload": "on", 
                "highdma": "on [fixed]", 
                "hw_tc_offload": "off [fixed]", 
                "l2_fwd_offload": "off [fixed]", 
                "large_receive_offload": "off [fixed]", 
                "loopback": "on [fixed]", 
                "netns_local": "on [fixed]", 
                "ntuple_filters": "off [fixed]", 
                "receive_hashing": "off [fixed]", 
                "rx_all": "off [fixed]", 
                "rx_checksumming": "on [fixed]", 
                "rx_fcs": "off [fixed]", 
                "rx_vlan_filter": "off [fixed]", 
                "rx_vlan_offload": "off [fixed]", 
                "rx_vlan_stag_filter": "off [fixed]", 
                "rx_vlan_stag_hw_parse": "off [fixed]", 
                "scatter_gather": "on", 
                "tcp_segmentation_offload": "on", 
                "tx_checksum_fcoe_crc": "off [fixed]", 
                "tx_checksum_ip_generic": "on [fixed]", 
                "tx_checksum_ipv4": "off [fixed]", 
                "tx_checksum_ipv6": "off [fixed]", 
                "tx_checksum_sctp": "on [fixed]", 
                "tx_checksumming": "on", 
                "tx_fcoe_segmentation": "off [fixed]", 
                "tx_gre_segmentation": "off [fixed]", 
                "tx_gso_robust": "off [fixed]", 
                "tx_ipip_segmentation": "off [fixed]", 
                "tx_lockless": "on [fixed]", 
                "tx_nocache_copy": "off [fixed]", 
                "tx_scatter_gather": "on [fixed]", 
                "tx_scatter_gather_fraglist": "on [fixed]", 
                "tx_sit_segmentation": "off [fixed]", 
                "tx_tcp6_segmentation": "on", 
                "tx_tcp_ecn_segmentation": "on", 
                "tx_tcp_segmentation": "on", 
                "tx_udp_tnl_segmentation": "off [fixed]", 
                "tx_vlan_offload": "off [fixed]", 
                "tx_vlan_stag_hw_insert": "off [fixed]", 
                "udp_fragmentation_offload": "on", 
                "vlan_challenged": "on [fixed]"
            }, 
            "ipv4": {
                "address": "127.0.0.1", 
                "broadcast": "host", 
                "netmask": "255.0.0.0", 
                "network": "127.0.0.0"
            }, 
            "ipv6": [
                {
                    "address": "::1", 
                    "prefix": "128", 
                    "scope": "host"
                }
            ], 
            "mtu": 65536, 
            "promisc": false, 
            "type": "loopback"
        }, 
        "ansible_lsb": {
            "codename": "xenial", 
            "description": "Ubuntu 16.04.5 LTS", 
            "id": "Ubuntu", 
            "major_release": "16", 
            "release": "16.04"
        }, 
        "ansible_machine": "x86_64", 
        "ansible_machine_id": "232e21016f3d405fbf99b9edafdeec00", 
        "ansible_memfree_mb": 673, 
        "ansible_memory_mb": {
            "nocache": {
                "free": 905, 
                "used": 87
            }, 
            "real": {
                "free": 673, 
                "total": 992, 
                "used": 319
            }, 
            "swap": {
                "cached": 0, 
                "free": 0, 
                "total": 0, 
                "used": 0
            }
        }, 
        "ansible_memtotal_mb": 992, 
        "ansible_mounts": [
            {
                "device": "/dev/sda1", 
                "fstype": "ext4", 
                "mount": "/", 
                "options": "rw,relatime,data=ordered", 
                "size_available": 9370198016, 
                "size_total": 10340831232, 
                "uuid": "92feb7e5-d622-440b-aa57-d61e8db0f495"
            }
        ], 
        "ansible_nodename": "puppet-agent", 
        "ansible_os_family": "Debian", 
        "ansible_pkg_mgr": "apt", 
        "ansible_processor": [
            "GenuineIntel", 
            "Intel(R) Core(TM) i7-7660U CPU @ 2.50GHz"
        ], 
        "ansible_processor_cores": 1, 
        "ansible_processor_count": 1, 
        "ansible_processor_threads_per_core": 1, 
        "ansible_processor_vcpus": 1, 
        "ansible_product_name": "VirtualBox", 
        "ansible_product_serial": "NA", 
        "ansible_product_uuid": "NA", 
        "ansible_product_version": "1.2", 
        "ansible_python": {
            "executable": "/usr/bin/python", 
            "has_sslcontext": true, 
            "type": "CPython", 
            "version": {
                "major": 2, 
                "micro": 12, 
                "minor": 7, 
                "releaselevel": "final", 
                "serial": 0
            }, 
            "version_info": [
                2, 
                7, 
                12, 
                "final", 
                0
            ]
        }, 
        "ansible_python_version": "2.7.12", 
        "ansible_selinux": false, 
        "ansible_service_mgr": "systemd", 
        "ansible_ssh_host_key_dsa_public": "AAAAB3NzaC1kc3MAAACBAKD+Xv+YOBNZhJS0RNFOwZvfPVIn+rCWl2qbGb+ckBYNpmnElHeUEU2yeuOX8XEss866Ol/ISAO/jdshXJ1lwIJ53JeoTTAikuKBxqT7dLiMDAkLCePOPCagL2omR83kIfLcqdmYIUDej4kb2d8f4+W/wx+bGRgRp8EtOGFEjpAPAAAAFQCFIDZmY/3o2HIfPPwN6xt5zACJ+QAAAIAPEgHyfjFZCV8AogaKYFgr/ZSh1WhMHaje8DQjCFfrlxdq1Rk8Ox/QR+5ZzegUpfutQFeAy5Y8PrPNBECY3BmMmYFzspTRBj+t8KhhrOqJIAc4h+VB3iFzmW5iPJbXjs3GOv2YC8UWYMfzgpaQWYTZ2oh0nR6224CvRxMLHGdxJAAAAIEAiGUyeyNgxC/+ec044NDSz2vu8bYllSj+8uME6nAff9nvkQPx/R0nQwaSfVsDHp0pjLi1ybNywFAW4AnjgWv6/BX1Xd5JmaIsgA3AwksCGNUWGTaq0UaN02Lt7PjVqtQ9v2MKy+bg4NkWeO2OHLKR3FRW+cMjywpBSs7vKcS2Lo4=", 
        "ansible_ssh_host_key_ecdsa_public": "AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBHh/5jXHXt4+4ihTfoWrYsw1oZSKRjuYnxC4DR06MBAy1yULer2djtZzgZhr9b2SsPpefrD0Zhv35x0D6+bnbGQ=", 
        "ansible_ssh_host_key_ed25519_public": "AAAAC3NzaC1lZDI1NTE5AAAAIDAi26dhbfRew6tASzQD0Ed3TA6NcPFown7RWTz2XXsX", 
        "ansible_ssh_host_key_rsa_public": "AAAAB3NzaC1yc2EAAAADAQABAAABAQDJ8mAgbcVBo4TqUp+BdFZRZAxRu1Q5C+mwCGI21iq4x11qyQTgH2HyRL0jCB9jGwvjduNASTK4YMoCqgNTYCTQ83LK9crq1RTuke5hs58Zitq7ytkIHQ8AfG7RZ/V3yRc7zFOeo0sQFQD26bcG0hVMDvo9C1aqZ6oVD45GiRTRBLOWdLhCsicRNw6Oul03ktrq1Dx4XxJGR384G2BNhkIymPcv1nSWxuPfsM4LW0wTEktrx5KcibPTzMXilKH5gexNgE8yImS15pF0p+6u9wDWt0sqMXGuqYV3t8OMSVwF0EM3OLagSl3+GyLb5leutgyFR36CUlAiZpDh+qcg3c2d", 
        "ansible_swapfree_mb": 0, 
        "ansible_swaptotal_mb": 0, 
        "ansible_system": "Linux", 
        "ansible_system_capabilities": [
            ""
        ], 
        "ansible_system_capabilities_enforced": "True", 
        "ansible_system_vendor": "innotek GmbH", 
        "ansible_uptime_seconds": 2252, 
        "ansible_user_dir": "/home/vagrant", 
        "ansible_user_gecos": ",,,", 
        "ansible_user_gid": 1000, 
        "ansible_user_id": "vagrant", 
        "ansible_user_shell": "/bin/bash", 
        "ansible_user_uid": 1000, 
        "ansible_userspace_architecture": "x86_64", 
        "ansible_userspace_bits": "64", 
        "ansible_virtualization_role": "guest", 
        "ansible_virtualization_type": "virtualbox", 
        "module_setup": true
    }, 
    "changed": false
}
ansible-fake | SUCCESS => {
    "ansible_facts": {
        "ansible_all_ipv4_addresses": [
            "10.0.2.15", 
            "192.168.10.10"
        ], 
        "ansible_all_ipv6_addresses": [
            "fe80::6c:72ff:fe8e:2ff", 
            "fe80::a00:27ff:fe09:ab63"
        ], 
        "ansible_architecture": "x86_64", 
        "ansible_bios_date": "12/01/2006", 
        "ansible_bios_version": "VirtualBox", 
        "ansible_cmdline": {
            "BOOT_IMAGE": "/boot/vmlinuz-4.4.0-141-generic", 
            "console": "ttyS0", 
            "ro": true, 
            "root": "LABEL=cloudimg-rootfs"
        }, 
        "ansible_date_time": {
            "date": "2019-01-07", 
            "day": "07", 
            "epoch": "1546832232", 
            "hour": "03", 
            "iso8601": "2019-01-07T03:37:12Z", 
            "iso8601_basic": "20190107T033712995708", 
            "iso8601_basic_short": "20190107T033712", 
            "iso8601_micro": "2019-01-07T03:37:12.995875Z", 
            "minute": "37", 
            "month": "01", 
            "second": "12", 
            "time": "03:37:12", 
            "tz": "UTC", 
            "tz_offset": "+0000", 
            "weekday": "Monday", 
            "weekday_number": "1", 
            "weeknumber": "01", 
            "year": "2019"
        }, 
        "ansible_default_ipv4": {
            "address": "10.0.2.15", 
            "alias": "enp0s3", 
            "broadcast": "10.0.2.255", 
            "gateway": "10.0.2.2", 
            "interface": "enp0s3", 
            "macaddress": "02:6c:72:8e:02:ff", 
            "mtu": 1500, 
            "netmask": "255.255.255.0", 
            "network": "10.0.2.0", 
            "type": "ether"
        }, 
        "ansible_default_ipv6": {}, 
        "ansible_devices": {
            "sda": {
                "holders": [], 
                "host": "SCSI storage controller: LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI", 
                "model": "HARDDISK", 
                "partitions": {
                    "sda1": {
                        "holders": [], 
                        "sectors": "20969439", 
                        "sectorsize": 512, 
                        "size": "10.00 GB", 
                        "start": "2048", 
                        "uuid": "92feb7e5-d622-440b-aa57-d61e8db0f495"
                    }
                }, 
                "removable": "0", 
                "rotational": "1", 
                "sas_address": null, 
                "sas_device_handle": null, 
                "scheduler_mode": "deadline", 
                "sectors": "20971520", 
                "sectorsize": "512", 
                "size": "10.00 GB", 
                "support_discard": "0", 
                "vendor": "VBOX"
            }, 
            "sdb": {
                "holders": [], 
                "host": "SCSI storage controller: LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI", 
                "model": "HARDDISK", 
                "partitions": {}, 
                "removable": "0", 
                "rotational": "1", 
                "sas_address": null, 
                "sas_device_handle": null, 
                "scheduler_mode": "deadline", 
                "sectors": "20480", 
                "sectorsize": "512", 
                "size": "10.00 MB", 
                "support_discard": "0", 
                "vendor": "VBOX"
            }
        }, 
        "ansible_distribution": "Ubuntu", 
        "ansible_distribution_major_version": "16", 
        "ansible_distribution_release": "xenial", 
        "ansible_distribution_version": "16.04", 
        "ansible_dns": {
            "nameservers": [
                "10.0.2.3"
            ]
        }, 
        "ansible_domain": "", 
        "ansible_enp0s3": {
            "active": true, 
            "device": "enp0s3", 
            "features": {
                "busy_poll": "on [fixed]", 
                "fcoe_mtu": "off [fixed]", 
                "generic_receive_offload": "on", 
                "generic_segmentation_offload": "on", 
                "highdma": "on [fixed]", 
                "hw_tc_offload": "off [fixed]", 
                "l2_fwd_offload": "off [fixed]", 
                "large_receive_offload": "off [fixed]", 
                "loopback": "off [fixed]", 
                "netns_local": "off [fixed]", 
                "ntuple_filters": "off [fixed]", 
                "receive_hashing": "off [fixed]", 
                "rx_all": "off [fixed]", 
                "rx_checksumming": "on [fixed]", 
                "rx_fcs": "off [fixed]", 
                "rx_vlan_filter": "on [fixed]", 
                "rx_vlan_offload": "off [fixed]", 
                "rx_vlan_stag_filter": "off [fixed]", 
                "rx_vlan_stag_hw_parse": "off [fixed]", 
                "scatter_gather": "on", 
                "tcp_segmentation_offload": "on", 
                "tx_checksum_fcoe_crc": "off [fixed]", 
                "tx_checksum_ip_generic": "on", 
                "tx_checksum_ipv4": "off [fixed]", 
                "tx_checksum_ipv6": "off [fixed]", 
                "tx_checksum_sctp": "off [fixed]", 
                "tx_checksumming": "on", 
                "tx_fcoe_segmentation": "off [fixed]", 
                "tx_gre_segmentation": "off [fixed]", 
                "tx_gso_robust": "on [fixed]", 
                "tx_ipip_segmentation": "off [fixed]", 
                "tx_lockless": "off [fixed]", 
                "tx_nocache_copy": "off", 
                "tx_scatter_gather": "on", 
                "tx_scatter_gather_fraglist": "off [fixed]", 
                "tx_sit_segmentation": "off [fixed]", 
                "tx_tcp6_segmentation": "on", 
                "tx_tcp_ecn_segmentation": "off [fixed]", 
                "tx_tcp_segmentation": "on", 
                "tx_udp_tnl_segmentation": "off [fixed]", 
                "tx_vlan_offload": "off [fixed]", 
                "tx_vlan_stag_hw_insert": "off [fixed]", 
                "udp_fragmentation_offload": "on", 
                "vlan_challenged": "off [fixed]"
            }, 
            "ipv4": {
                "address": "10.0.2.15", 
                "broadcast": "10.0.2.255", 
                "netmask": "255.255.255.0", 
                "network": "10.0.2.0"
            }, 
            "ipv6": [
                {
                    "address": "fe80::6c:72ff:fe8e:2ff", 
                    "prefix": "64", 
                    "scope": "link"
                }
            ], 
            "macaddress": "02:6c:72:8e:02:ff", 
            "mtu": 1500, 
            "pciid": "virtio0", 
            "promisc": false, 
            "speed": -1, 
            "type": "ether"
        }, 
        "ansible_enp0s8": {
            "active": true, 
            "device": "enp0s8", 
            "features": {
                "busy_poll": "on [fixed]", 
                "fcoe_mtu": "off [fixed]", 
                "generic_receive_offload": "on", 
                "generic_segmentation_offload": "on", 
                "highdma": "on [fixed]", 
                "hw_tc_offload": "off [fixed]", 
                "l2_fwd_offload": "off [fixed]", 
                "large_receive_offload": "off [fixed]", 
                "loopback": "off [fixed]", 
                "netns_local": "off [fixed]", 
                "ntuple_filters": "off [fixed]", 
                "receive_hashing": "off [fixed]", 
                "rx_all": "off [fixed]", 
                "rx_checksumming": "on [fixed]", 
                "rx_fcs": "off [fixed]", 
                "rx_vlan_filter": "on [fixed]", 
                "rx_vlan_offload": "off [fixed]", 
                "rx_vlan_stag_filter": "off [fixed]", 
                "rx_vlan_stag_hw_parse": "off [fixed]", 
                "scatter_gather": "on", 
                "tcp_segmentation_offload": "on", 
                "tx_checksum_fcoe_crc": "off [fixed]", 
                "tx_checksum_ip_generic": "on", 
                "tx_checksum_ipv4": "off [fixed]", 
                "tx_checksum_ipv6": "off [fixed]", 
                "tx_checksum_sctp": "off [fixed]", 
                "tx_checksumming": "on", 
                "tx_fcoe_segmentation": "off [fixed]", 
                "tx_gre_segmentation": "off [fixed]", 
                "tx_gso_robust": "on [fixed]", 
                "tx_ipip_segmentation": "off [fixed]", 
                "tx_lockless": "off [fixed]", 
                "tx_nocache_copy": "off", 
                "tx_scatter_gather": "on", 
                "tx_scatter_gather_fraglist": "off [fixed]", 
                "tx_sit_segmentation": "off [fixed]", 
                "tx_tcp6_segmentation": "on", 
                "tx_tcp_ecn_segmentation": "off [fixed]", 
                "tx_tcp_segmentation": "on", 
                "tx_udp_tnl_segmentation": "off [fixed]", 
                "tx_vlan_offload": "off [fixed]", 
                "tx_vlan_stag_hw_insert": "off [fixed]", 
                "udp_fragmentation_offload": "on", 
                "vlan_challenged": "off [fixed]"
            }, 
            "ipv4": {
                "address": "192.168.10.10", 
                "broadcast": "192.168.10.255", 
                "netmask": "255.255.255.0", 
                "network": "192.168.10.0"
            }, 
            "ipv6": [
                {
                    "address": "fe80::a00:27ff:fe09:ab63", 
                    "prefix": "64", 
                    "scope": "link"
                }
            ], 
            "macaddress": "08:00:27:09:ab:63", 
            "mtu": 1500, 
            "pciid": "virtio1", 
            "promisc": false, 
            "speed": -1, 
            "type": "ether"
        }, 
        "ansible_env": {
            "HOME": "/home/vagrant", 
            "LANG": "en_US.UTF-8", 
            "LOGNAME": "vagrant", 
            "MAIL": "/var/mail/vagrant", 
            "PATH": "/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games", 
            "PWD": "/home/vagrant", 
            "SHELL": "/bin/bash", 
            "SHLVL": "1", 
            "SSH_CLIENT": "10.0.2.2 49761 22", 
            "SSH_CONNECTION": "10.0.2.2 49761 10.0.2.15 22", 
            "USER": "vagrant", 
            "XDG_RUNTIME_DIR": "/run/user/1000", 
            "XDG_SESSION_ID": "3", 
            "_": "/bin/sh"
        }, 
        "ansible_fips": false, 
        "ansible_form_factor": "Other", 
        "ansible_fqdn": "ansible-fake", 
        "ansible_gather_subset": [
            "hardware", 
            "network", 
            "virtual"
        ], 
        "ansible_hostname": "ansible-fake", 
        "ansible_interfaces": [
            "lo", 
            "enp0s3", 
            "enp0s8"
        ], 
        "ansible_kernel": "4.4.0-141-generic", 
        "ansible_lo": {
            "active": true, 
            "device": "lo", 
            "features": {
                "busy_poll": "off [fixed]", 
                "fcoe_mtu": "off [fixed]", 
                "generic_receive_offload": "on", 
                "generic_segmentation_offload": "on", 
                "highdma": "on [fixed]", 
                "hw_tc_offload": "off [fixed]", 
                "l2_fwd_offload": "off [fixed]", 
                "large_receive_offload": "off [fixed]", 
                "loopback": "on [fixed]", 
                "netns_local": "on [fixed]", 
                "ntuple_filters": "off [fixed]", 
                "receive_hashing": "off [fixed]", 
                "rx_all": "off [fixed]", 
                "rx_checksumming": "on [fixed]", 
                "rx_fcs": "off [fixed]", 
                "rx_vlan_filter": "off [fixed]", 
                "rx_vlan_offload": "off [fixed]", 
                "rx_vlan_stag_filter": "off [fixed]", 
                "rx_vlan_stag_hw_parse": "off [fixed]", 
                "scatter_gather": "on", 
                "tcp_segmentation_offload": "on", 
                "tx_checksum_fcoe_crc": "off [fixed]", 
                "tx_checksum_ip_generic": "on [fixed]", 
                "tx_checksum_ipv4": "off [fixed]", 
                "tx_checksum_ipv6": "off [fixed]", 
                "tx_checksum_sctp": "on [fixed]", 
                "tx_checksumming": "on", 
                "tx_fcoe_segmentation": "off [fixed]", 
                "tx_gre_segmentation": "off [fixed]", 
                "tx_gso_robust": "off [fixed]", 
                "tx_ipip_segmentation": "off [fixed]", 
                "tx_lockless": "on [fixed]", 
                "tx_nocache_copy": "off [fixed]", 
                "tx_scatter_gather": "on [fixed]", 
                "tx_scatter_gather_fraglist": "on [fixed]", 
                "tx_sit_segmentation": "off [fixed]", 
                "tx_tcp6_segmentation": "on", 
                "tx_tcp_ecn_segmentation": "on", 
                "tx_tcp_segmentation": "on", 
                "tx_udp_tnl_segmentation": "off [fixed]", 
                "tx_vlan_offload": "off [fixed]", 
                "tx_vlan_stag_hw_insert": "off [fixed]", 
                "udp_fragmentation_offload": "on", 
                "vlan_challenged": "on [fixed]"
            }, 
            "ipv4": {
                "address": "127.0.0.1", 
                "broadcast": "host", 
                "netmask": "255.0.0.0", 
                "network": "127.0.0.0"
            }, 
            "ipv6": [
                {
                    "address": "::1", 
                    "prefix": "128", 
                    "scope": "host"
                }
            ], 
            "mtu": 65536, 
            "promisc": false, 
            "type": "loopback"
        }, 
        "ansible_lsb": {
            "codename": "xenial", 
            "description": "Ubuntu 16.04.5 LTS", 
            "id": "Ubuntu", 
            "major_release": "16", 
            "release": "16.04"
        }, 
        "ansible_machine": "x86_64", 
        "ansible_machine_id": "66021fa387f7441aab836c04f44fe30f", 
        "ansible_memfree_mb": 674, 
        "ansible_memory_mb": {
            "nocache": {
                "free": 906, 
                "used": 86
            }, 
            "real": {
                "free": 674, 
                "total": 992, 
                "used": 318
            }, 
            "swap": {
                "cached": 0, 
                "free": 0, 
                "total": 0, 
                "used": 0
            }
        }, 
        "ansible_memtotal_mb": 992, 
        "ansible_mounts": [
            {
                "device": "/dev/sda1", 
                "fstype": "ext4", 
                "mount": "/", 
                "options": "rw,relatime,data=ordered", 
                "size_available": 9370198016, 
                "size_total": 10340831232, 
                "uuid": "92feb7e5-d622-440b-aa57-d61e8db0f495"
            }
        ], 
        "ansible_nodename": "ansible-fake", 
        "ansible_os_family": "Debian", 
        "ansible_pkg_mgr": "apt", 
        "ansible_processor": [
            "GenuineIntel", 
            "Intel(R) Core(TM) i7-7660U CPU @ 2.50GHz"
        ], 
        "ansible_processor_cores": 1, 
        "ansible_processor_count": 1, 
        "ansible_processor_threads_per_core": 1, 
        "ansible_processor_vcpus": 1, 
        "ansible_product_name": "VirtualBox", 
        "ansible_product_serial": "NA", 
        "ansible_product_uuid": "NA", 
        "ansible_product_version": "1.2", 
        "ansible_python": {
            "executable": "/usr/bin/python", 
            "has_sslcontext": true, 
            "type": "CPython", 
            "version": {
                "major": 2, 
                "micro": 12, 
                "minor": 7, 
                "releaselevel": "final", 
                "serial": 0
            }, 
            "version_info": [
                2, 
                7, 
                12, 
                "final", 
                0
            ]
        }, 
        "ansible_python_version": "2.7.12", 
        "ansible_selinux": false, 
        "ansible_service_mgr": "systemd", 
        "ansible_ssh_host_key_dsa_public": "AAAAB3NzaC1kc3MAAACBAMdCy/OsrGUjeiEFrdL9MGfLFJsdqzPWcGdn0h+3T3/XoLH8YCIX8CevcEPBfhQc8MDEN35T+8vSQ396Yt52oD6Eg4iODJTwAfzHrW6EKdYxykeD4nbQJZtE7bvmb6sJeiPdb4Zz1tDVPRidycGz49pSMRF+ZE9bI/Xbh2cunAgvAAAAFQCryedAw3AtiYZvmTp+XaKG9mnHwwAAAIEAtC5ulNIf8ESvF0jNt/AhTIZqEQNVgBmGi6inZGLrskTVivzyRszaac6BrtwupMBCpSLKXrbc5RAu87E1BYhItGxA53gLRz4QCx1UQKtSh8EJcny57YNDD3YXYIy4tq/Tusvtzxw/zQRHp1u5g+sRp0N/M6Why34V4HSNVTMQVNkAAACBALjzAJJcESV4jhkpOK+JZjFzKm/eUBJGzpI1h5y9Pr/ukt/8/mxQEDmBCVo0qT6I8gtCru2zJWYS24vheee9pZSFhr8+jIIRthFKs9OchQ4NR8UMLQBgme6t+vx7w9ClyskiG7FY+dsBoa8PQhrbgHdWssvjkvvh7u6SY33BQpxA", 
        "ansible_ssh_host_key_ecdsa_public": "AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBPKlKWpeyxzimesPygLd0uREW5qD9j+pLc8NnA3NDLol17FY+V2p/KNi6K4v0Dsu4MATvq2mJhxnqBK7fPWwqvY=", 
        "ansible_ssh_host_key_ed25519_public": "AAAAC3NzaC1lZDI1NTE5AAAAIJgD3qsofej95FMxCHDtiNFFtGBioRrg4caakAeXel9W", 
        "ansible_ssh_host_key_rsa_public": "AAAAB3NzaC1yc2EAAAADAQABAAABAQC4V/1pjY4Qk3T0zzTRDdm8IUlLjZtlLDxERrQHWt00hqk9aUOi7bdyRyQht7X4QP7doBBVToSuUGRqWLlArFIxGLK5N2exVeyvK9lkK/qtHELzE+AECKW4/rLgkVJaJpdypAuGsiJ+66pl06fvfK5ABdeBt31Rs18Kopsbvjc1mYGKOK6vGsPLHkCZTRy1LTVWDF4loPdjS5UYppvQmwsqWgd43uN2ayrEQXeYC0NKF7XFFUlN7XpqwZbMmoVZNBUdRImU17QR2JKCzqkw4EpN7GneqnNotiHlnmsOLGbWWht9lrQt2yr9lz0x9oTxUGI9osgs7zxrls9+vdgpUsJZ", 
        "ansible_swapfree_mb": 0, 
        "ansible_swaptotal_mb": 0, 
        "ansible_system": "Linux", 
        "ansible_system_capabilities": [
            ""
        ], 
        "ansible_system_capabilities_enforced": "True", 
        "ansible_system_vendor": "innotek GmbH", 
        "ansible_uptime_seconds": 2215, 
        "ansible_user_dir": "/home/vagrant", 
        "ansible_user_gecos": ",,,", 
        "ansible_user_gid": 1000, 
        "ansible_user_id": "vagrant", 
        "ansible_user_shell": "/bin/bash", 
        "ansible_user_uid": 1000, 
        "ansible_userspace_architecture": "x86_64", 
        "ansible_userspace_bits": "64", 
        "ansible_virtualization_role": "guest", 
        "ansible_virtualization_type": "virtualbox", 
        "module_setup": true
    }, 
    "changed": false
}
