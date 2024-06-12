# CVE-2024-29824: Ivanti EPM SQL Injection Remote Code Execution Vulnerability
Proof of concept exploit to blindly execute commands on vulnerable Ivanti EPM appliances.

## Blog Post
Deep dive and indicators of compromise here:
[https://www.horizon3.ai/attack-research/attack-blogs/cve-2024-29824-deep-dive-ivanti-epm-sql-injection-remote-code-execution-vulnerability](https://www.horizon3.ai/attack-research/attack-blogs/cve-2024-29824-deep-dive-ivanti-epm-sql-injection-remote-code-execution-vulnerability)

## Usage
```
% python CVE-2024-29824.py -h                              
usage: CVE-2024-29824.py [-h] -u URL -c CMD_FILE

options:
  -h, --help            show this help message and exit
  -u URL, --url URL     The base URL of the target
  -c CMD_FILE, --cmd_file CMD_FILE
                        The commands to execute blind
```

## Follow the Horizon3.ai Attack Team on Twitter for the latest security research:
*  [Horizon3 Attack Team](https://twitter.com/Horizon3Attack)
*  [James Horseman](https://twitter.com/JamesHorseman2)
*  [Zach Hanley](https://twitter.com/hacks_zach)

## Disclaimer
This software has been created purely for the purposes of academic research and for the development of effective defensive techniques, and is not intended to be used to attack systems except where explicitly authorized. Project maintainers are not responsible or liable for misuse of the software. Use responsibly.
