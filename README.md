# ipfreely

## About:
ipfreely is a simple bash script to scan for unused IPs in a given subnet.

## Usage
Give ipfreely the first three octets of an IPv4 range like in the example below.

```bash
ipfreely 10.0.0
```

if the [`prog` shell script](https://github.com/dev-dull/prog) is found in your `PATH` then it will display a nice progress bar. Otherwise, it will echo the last octet as it is tested.
