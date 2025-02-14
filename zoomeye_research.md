**Title:** Exploring Exposed IoT Devices on the Internet Using ZoomEye

**Abstract:**
The rapid proliferation of Internet of Things (IoT) devices has introduced significant cybersecurity risks. Many IoT devices are inadvertently exposed to the internet, making them potential targets for cyberattacks. This research leverages the ZoomEye search engine to identify publicly accessible IoT devices, analyze their security posture, and provide recommendations to mitigate risks. By using advanced ZoomEye queries, we uncover misconfigured or unprotected devices and discuss their implications for cybersecurity.

**1. Introduction**
IoT devices, such as smart cameras, industrial control systems (ICS), and home automation tools, are increasingly deployed worldwide. However, poor security configurations often leave these devices accessible over the internet, making them vulnerable to attacks like unauthorized access, botnet infections, and data breaches. This research aims to investigate exposed IoT devices using ZoomEye, a specialized search engine for internet-connected assets.

**2. Methodology**
ZoomEye is a cybersecurity search engine that indexes internet-facing devices by analyzing banners, open ports, and services. To conduct this research, we used the following queries:
- `app:"webcam"` - Identifies publicly accessible webcams.
- `app:"SCADA"` - Searches for exposed industrial control systems.
- `port:23` - Finds Telnet-enabled devices with potentially weak authentication.
- `country:"US"`` port:3389` - Filters exposed Remote Desktop Protocol (RDP) services in the US.

The search results were analyzed to determine the types of devices, their geographical distribution, and potential security misconfigurations.

**3. Results & Discussion**
Using ZoomEye, we discovered numerous exposed IoT devices worldwide. Key findings include:
- **Publicly Accessible Webcams:** Many webcams lack authentication, allowing unrestricted viewing.
- **SCADA/ICS Systems:** Industrial systems were found exposed without proper security controls.
- **Default Login Credentials:** Several devices were accessible using default or weak passwords.

These exposures pose serious security risks, including unauthorized surveillance, industrial sabotage, and exploitation by botnets like Mirai.

**4. Conclusion**
Our research highlights the importance of securing IoT devices against internet exposure. Organizations and individuals must:
- Disable unnecessary remote access.
- Enforce strong authentication mechanisms.
- Regularly update firmware and security settings.
- Conduct periodic security assessments using tools like ZoomEye.

**5. References**
- ZoomEye. (2025). Retrieved from [https://www.zoomeye.org](https://www.zoomeye.org)
- Kolias, C., Kambourakis, G., Stavrou, A., & Voas, J. (2017). DDoS in the IoT: Mirai and other botnets. *Computer*, 50(7), 80-84.
- Wang, P., Lu, W., & Ye, Z. (2018). An overview of security research in the Internet of Things. *Journal of Computer Science & Technology*, 33(4), 791-804.

