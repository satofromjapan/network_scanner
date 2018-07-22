# Network Scanner

A simple tool to help you scan networks and find the ip and MAC addresses connected on the same network.

## Basic Usage

Run the file using python or python3 and specify a range with the `-t` or `--target` flags.

Example

```python network_scanner.py -t 10.0.2.1/24```

or 

```python3 network_scanner.py -t 10.0.2.1/24```

If you are using python3, make sure to install the scapy module:

```pip3 install scapy-python3```
