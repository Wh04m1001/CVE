# CVE

### Update

MITRE assigned CVE [CVE-2022-45697](https://cve.report/CVE-2022-45697) for this vulnerability.

### This repo contains description of vulnerability i have found in Razer Central before v7.8.0.381 

The vulnerability is in Razer Central service which does not check for symbolic links during login of user which leads to arbitrary file delete vulnerability and escalation of privileges.

The Razer team allowed CVE filing but did not allow publishing any PoC.

![image](https://user-images.githubusercontent.com/44291883/221176206-2fee5c92-4627-4047-bb0d-150cfaf313e9.png)


#### Disclosure timeline

- 8/09/2022 - Initial discovery
- 8/10/2022 - Contacted Razer Team on Twitter 
- 8/11/2022 - Razer team emailed me and gave me instructions to create a report on their BB program
- 8/11/2022 - Report created on Inspective platform
- 8/19/2022 - Inspective confirmed vulnerability
- 11/15/2022 - Inspective informed me that fix is released
- 11/17/2022 - Filing for CVE
