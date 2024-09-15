# CVE-2024-29847
PoC for Ivanti Endpoint Manager AgentPortal Deserialization of Untrusted Data Remote Code Execution Vulnerability (CVE-2024-29847)


A root cause analysis of the vulnerability can be found on my blog:

https://summoning.team/blog/ivanti-epm-CVE-2024-29847-deserialization-RCE/

[![POC](CVE-2024-29847-poc.jpg)](https://summoning.team/blog/ivanti-epm-CVE-2024-29847-deserialization-RCE/)



## Usage
```
CVE-2024-29847.exe --uselease --installdir "C:\Program Files\LANDesk\ManagementSuite\LANDesk\ManagementSuite\Core\Core.Webservices" tcp://192.168.0.200:49669/LDSM exec test
```

## Mitigations
Update to the latest version or mitigate by following this link
* https://forums.ivanti.com/s/article/Security-Advisory-EPM-September-2024-for-EPM-2024-and-EPM-2022?language=en_US

## Follow Us on Twitter(X) for the latest security research:
*  [SinSinology](https://x.com/SinSinology)
*  [SummoningTeam](https://x.com/SummoningTeam)

## Disclaimer
This software has been created purely for the purposes of academic research and for the development of effective defensive techniques, and is not intended to be used to attack systems except where explicitly authorized. Project maintainers are not responsible or liable for misuse of the software. Use responsibly.

