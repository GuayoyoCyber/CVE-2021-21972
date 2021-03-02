# CVE-2021-21972
Nmap script to check vulnerability CVE-2021-21972 - vCenter Server RCE

## Vulnerability References:

https://app.howlermonkey.io/vulnerabilities/CVE-2021-21972

https://www.vmware.com/security/advisories/VMSA-2021-0002.html


## Example

nmap -p443 --script cve-2021-21972.nse --script-args vulns.showall IP

![final_603e5630e2c0df009ad51383_569264](https://user-images.githubusercontent.com/63943179/109674961-1c789300-7b56-11eb-891c-abd1078ae5dd.gif)



## Credits

Built on top of the script develop by Alex Hernandez aka [@alt3kx](https://github.com/alt3kx) - [https://github.com/alt3kx/CVE-2021-21972](https://github.com/alt3kx/CVE-2021-21972)
