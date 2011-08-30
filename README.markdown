# SCRD - Server Check Response Daemon

## Installation:
- Edit scrd.conf to your likings, copy to a directory
 - Default conf-path is /usr/local/etc/scrd.conf

- Run scrd: ./scrd [-c </path/to/scrd.conf>]
 - You can omit the path if it's at /usr/local/etc/scrd.conf

## Change Log:
### VERSION 2.2
Aug15 2011

- Changed error for PID file to be moar bettar!

### VERSION 2.1
Aug15 2011

- Error for PID file existing
- Error for config not existing

### VERSION 2
Aug15 2011

- Added getopt() - now has options!

### VERSION 1
Aug14 2011

- Initial code

## Output:
Looks like:
	{
			"ps": {
					"runsvc": 1,
					"allsvc": 1,
					"svcs": {
							"/usr/sbin/sshd": true
					},
					"allps": 162
			},
			"ram": {
					"total": 3951,
					"used": 3918,
					"bufcac": 2095,
					"free": 33
			},
			"uplo": {
					"load1": 0.029999999999999999,
					"load15": 0.0,
					"uptime": "30 days",
					"load5": 0.01
			},
			"hostname": "sub.domain.tld",
			"who": {
					"john": 1
			},
			"ips": [
					{
							"ip": "216.245.223.2",
							"host": "2-223-245-216.static.reverse.lstn.net"
					},
					{
							"ip": "10.4.25.182",
							"host": "lsn.local"
					}
			],
			"disk": {
					"single": [
							{
									"fs": "/dev/mapper/unassigned-root",
									"mount": "/",
									"avail": "422G",
									"used": "6.7G",
									"total": "451G",
									"type": "ext3"
							},
							{
									"fs": "/dev/sda1",
									"mount": "/boot",
									"avail": "187M",
									"used": "30M",
									"total": "228M",
									"type": "ext2"
							}
					],
					"total": {
							"avail": "426G",
							"total": "455G",
							"used": "6.8G"
					}
			}
	}
