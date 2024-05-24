# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

Multiple D-link device vulnerabilities are being actively targeted. Many of the Routers and NAS device are end-of-life D-Link devices that does not have any patches available. 

 The **Outbreak Response - D-link Multiple Devices Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/1.1.0/README.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/d-link-multiple-devices-attack) contains information about the outbreak alert **Outbreak Response - D-link Multiple Devices Attack**. 

## Background: 

CVE-2014-100005: D-Link DIR-600 routers contain a Cross-Site Request Forgery (CSRF) vulnerability that allows an attacker to change router configurations by hijacking an existing administrator session.

CVE-2021-40655: D-Link DIR-605 routers Information Disclosure vulnerability that allows attackers to obtain a username and password by forging a post request.

CVE-2022-37055: D-Link Multiple Go-RT Devices are vulnerable to Buffer Overflow vulnerability.

CVE-2024-3272- D-Link Multiple NAS Devices Use of Hard-Coded Credentials vulnerability, the vulnerability relies on the use of a user account presents by default on all the impacted D-Link models.

CVE-2024-3273- D-Link Multiple NAS Devices Command Injection Vulnerability, the vulnerability allows a remote command. By combining with CVE-2024-3272, it is possible to send commands remotely without any authentication, making this attack very dangerous. 

## Announced: 

Fortinet customers remain protected via the IPS signatures available for all the vulnerabilities. FortiGuard Labs continues to see widespread attack attempts targeting these vulnerabilities. The vendor recommends that the D-Link devices that have reached EOL/EOS should be retired and replaced, as there are no patches available for them. Users are recommened to visit D-link website and determine if thier product is affected and follow vendor guidelines for mitigating risks. Please see references section for more information. 

## Latest Developments: 

May 16, 2024: CISA added CVE-2014-100005 and CVE-2021-40655 to to its known exploited catalog (KEV). 

May 22, 2024: FortiGuard Labs observed attack attempts targeting the CVE-2024-3273 and CVE-2024-3272 on up-to 30,000+ unique IPS devices.

May 11, 2024: FortiGuard Labs observed attack attempts targeting the CVE-2022-37055 on up-to 20,000+ unique IPS devices.

April 11, 2024: CISA added CVE-2024-3273 and CVE-2024-3272 to its known exploited catalog (KEV). 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|