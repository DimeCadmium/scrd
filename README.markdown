# SCRD - Server Check Response Daemon

## Installation:
- Edit scrd.conf to your likings, copy to a directory
 - Default conf-path is /usr/local/etc/scrd.conf

- Run scrd: ./scrd [-c </path/to/scrd.conf>]
 - You can omit the path if it's at /usr/local/etc/scrd.conf

## Compatible Programs:
<https://github.com/nikkiii/status>

## Python
If you get an error with the JSON module, compile Python. Follow the instructions in README.python

The error will be similar to: 
Traceback (most recent call last):   File "./scrd", line 242, in <module>     put(ns, json.dumps(dic)) AttributeError: 'module' object has no attribute 'dumps'

## Change Log:
### VERSION 3.1
Sep25 2011

- Fixed random stuff
- Unauthorized IP now shows the connecter's IP

### VERSION 3.0
Sep23 2011

- New config file format; also accepts old config with -C

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
See file `output.txt`
