# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20230203 | ESET发布2022年最后一个季度APT活动总结报告 | https://github.com/blackorbird/APT_REPORT/blob/master/summary/2023/eset_apt_activity_report_t32022.pdf| 
| 20230203 | WithSecure发布的关于lazarus APT活动各个阶段的分析与总结 | http://labs.withsecure.com/content/dam/labs/docs/WithSecure-Lazarus-No-Pineapple-Threat-Intelligence-Report-2023.pdf| 
| 20230203 | chrome v8的WebAssembly中的UAF漏洞，可在32位的Pixel中实现RCE | https://bugs.chromium.org/p/chromium/issues/detail?id=1377816| 
| 20230203 | 使用机器学习方法（随机森林）帮助完善IDA分析结果，例如用来识别函数段、识别switch跳转表、区分 Arm 和 Thumb 代码段，识别代码中的函数指针等 | http://research.checkpoint.com/2019/thumbs-up-using-machine-learning-to-improve-idas-analysis/| 
| 20230203 | Linux Netfilter 本地提权漏洞 PoC 公开，CVE-2023-0179 | http://securityonline.info/researcher-publishes-poc-exploit-for-privilege-escalation-flaw-cve-2023-0179-in-linux-kernel/| 
| 20230203 | OpenSSH server 9.1中存在一个无需身份认证的double free漏洞，但考虑到权限限制和沙箱保护等因素其可利用性较差。 | http://www.openwall.com/lists/oss-security/2023/02/02/2| 
| 20230203 | 介绍包括CVE-2022-25365在内的多个Docker漏洞，通过攻击命名管道实现权限提升，以及一个辅助分析工具PipeViewer | https://www.cyberark.com/resources/threat-research-blog/breaking-docker-named-pipes-systematically-docker-desktop-privilege-escalation-part-1| 
| 20230203 | Google Chrome 在验证命令解码器时产生的缓冲区溢出漏洞 | https://googleprojectzero.github.io/0days-in-the-wild//0day-RCAs/2022/CVE-2022-4135.html| 
| 20230203 | 介绍了一些简单的2FA的bypass方法。不过这类方法估计很难在实际中奏效。 | https://thegrayarea.tech/bug-hunting-101-multi-factor-authentication-otp-bypass-79f03b554df6?gi=3e094ba14e0a| 
| 20230203 | CVE-2022-44268:ImageMagick任意文件读取PoC | https://sec.today/pulses/1dfde550-81c4-4a03-9228-7ad6037f7143/| 
| 20230203 | CVE-2022-44268:ImageMagick任意文件读取PoC | https://github.com/duc-nt/CVE-2022-44268-ImageMagick-Arbitrary-File-Read-PoC| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20230203T13:16:28Z | CVE-2023-0549 | A vulnerability, which was classified as problematic, has been found in YAFNET up to 3.1.10. This issue affects some unknown processing of the file /forum/PostPrivateMessage of the component Private Message Handler. The manipulation of the argument subject/message leads to cross site scripting. The attack may be initia CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-0549 | | 
| 20230203T12:07:56Z | CVE-2023-25139 | sprintf in the GNU C Library (glibc) 2.37 has a buffer overflow (out-of-bounds write) in some situations with a correct buffer size. This is unrelated to CWE-676. It may write beyond the bounds of the destination buffer when attempting to write a padded, thousands-separated string representation of a number, if the buf CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-25139 | | 
| 20230203T12:07:52Z | CVE-2023-25136 | OpenSSH server (sshd) 9.1 introduced a double-free vulnerability during options.kex_algorithms handling. This is fixed in OpenSSH 9.2. The double free can be triggered by an unauthenticated attacker in the default configuration; however, the vulnerability discoverer reports that "exploiting this vulnerability will not  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-25136 | | 
| 20230203T12:07:48Z | CVE-2022-48074 | An issue in NoMachine before v8.2.3 allows attackers to execute arbitrary commands via a crafted .nxs file. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-48074 | | 
| 20230203T12:07:36Z | CVE-2022-2327 | io_uring use work_flags to determine which identity need to grab from the calling process to make sure it is consistent with the calling process when executing IORING_OP. Some operations are missing some types, which can lead to incorrect reference counts which can then lead to a double free. We recommend upgrading the CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-2327 | | 
| 20230203T11:46:41Z | CVE-2022-44268 | An information disclosure vulnerability that could be exploited to read arbitrary files from a server when parsing an image in Image Magic. | https://github.com/Ashifcoder/CVE-2022-44268-automated-poc | | 
| 20230203T10:00:37Z | CVE-2022-44268 | The vulnerable recurrence docker environment for CVE-2022-44268 | https://github.com/y1nglamore/CVE-2022-44268-ImageMagick-Vulnerable-Docker-Environment | | 
| 20230203T09:03:47Z | CVE-2022-46604 | Responsive FileManager v.9.9.5 vulnerable to CVE-2022–46604. | https://github.com/galoget/ResponsiveFileManager-CVE-2022-46604 | | 
| 20230203T08:41:37Z | CVE-2022-31144 | CVE-2022-31144 dos pt redis, not finished yet or too soon, this can be turned into rce but oh well if you smart enough | https://github.com/SpiralBL0CK/CVE-2022-31144 | | 
| 20230203T06:37:54Z | CVE-2020-12673 | In Dovecot before 2.3.11.3, sending a specially formatted NTLM request will crash the auth service because of an out-of-bounds read. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2020-12673 | | 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T10:32:47Z | Collection of Kicad 6.0 symbols, footprints and 3D models useful in keyboard creation | https://github.com/crides/kleeb | 73 | 6| 
| 20230203T01:31:43Z | Null | https://github.com/LuiKlee/LuiKlee.github.io | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T12:22:54Z | Этот скрипт является тренировочным. Он предназначен для извлечения данных с сайта rapid7.com. В данном проекте используются две основные библиотеки bs4 и selenium. Скрипт запускался на операционной системе Windows. | https://github.com/mishaniahomi/scraping_vulnerability_and_exploit | 0 | 0| 
| 20230203T12:07:52Z | OpenSSH server (sshd) 9.1 introduced a double-free vulnerability during options.kex_algorithms handling. This is fixed in OpenSSH 9.2. The double free can be triggered by an unauthenticated attacker in the default configuration; however, the vulnerability discoverer reports that %exploiting this vulnerability will not  CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2023-25136 | 0 | 0| 
| 20230203T11:56:47Z | Null | https://github.com/HmiBlackHat/DominExploit | 0 | 0| 
| 20230203T11:46:41Z | An information disclosure vulnerability that could be exploited to read arbitrary files from a server when parsing an image in Image Magic. | https://github.com/Ashifcoder/CVE-2022-44268-automated-poc | 0 | 0| 
| 20230203T10:38:37Z | An Exploit made by XenoExploitz | https://github.com/xenoExploits/Sapphire.WRD | 0 | 0| 
| 20230203T09:28:25Z | An advanced cross-platform tool that automates the process of detecting and exploiting SQL injection security flaws | https://github.com/r0oth3x49/ghauri | 612 | 82| 
| 20230203T02:53:41Z | ICLR paper %Exploring and Exploiting Decision Boundary Dynamics for Adversarial Robustness% by Yuancheng Xu, Yanchao Sun, Micah Goldblum, Tom Goldstein and  Furong Huang | https://github.com/Yuancheng-Xu/Dynamics-Aware-Robust-Training | 0 | 0| 
| 20230203T02:36:48Z | Gather and update all available and newest CVEs with their PoC. | https://github.com/trickest/cve | 3979 | 495| 
| 20230203T02:06:06Z | IBM Tivoli Workload Scheduler 9.4, 9.5, and 10.1 is vulnerable to an XML External Entity Injection (XXE) attack when processing XML data. A remote attacker could exploit this vulnerability to expose sensitive information or consume memory resources. IBM X-Force ID: 233975. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-38389 | 0 | 0| 
| 20230203T02:06:03Z | IBM Tivoli Workload Scheduler 9.4, 9.5, and 10.1 is vulnerable to an XML External Entity Injection (XXE) attack when processing XML data. A remote attacker could exploit this vulnerability to expose sensitive information or consume memory resources. IBM X-Force ID: 226328. CVE project by @Sn0wAlice | https://github.com/Live-Hack-CVE/CVE-2022-22486 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T09:24:04Z | A shell script that mimics sudo and sends you back the password | https://github.com/nisay759/sudo-backdoor | 18 | 7| 
| 20230203T04:30:13Z | Ferramenta que Mescla Backdoor Metasploit em Apps Android | https://github.com/Cyber-Root0/JoinePayload | 1 | 0| 
| 20230203T04:28:58Z | [ICLR2023] Distilling Cognitive Backdoor Patterns within an Image | https://github.com/HanxunH/CognitiveDistillation | 6 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T13:05:16Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 619 | 111| 
| 20230203T04:02:58Z | Quiver-Based Symbolic Execution | https://github.com/LostBitset/quiver_se | 1 | 0| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T10:28:34Z | A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS). | https://github.com/gnipping/Awesome-ML-SP-Papers | 27 | 2| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20230203T13:40:48Z | Samochód sterowany logiką rozmytą  | https://github.com/MarcinZabielski/fuzzyCar | 0 | 0| 
| 20230203T13:08:30Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 1249 | 168| 
| 20230203T12:54:08Z | Null | https://github.com/rithwiksivadasan/Fuzzymatching-strings | 0 | 0| 
| 20230203T12:45:07Z | uriel_fernade | https://github.com/Ulegom17/fuzzy-adventure | 0 | 0| 
| 20230203T11:45:37Z | Fast web fuzzer written in Go | https://github.com/ffuf/ffuf | 8565 | 964| 
| 20230203T11:20:18Z | cli tool for searching cloudtrail events using fuzzy search | https://github.com/paololazzari/cloudtrail-event-fuzzy-viewer | 0 | 0| 
| 20230203T10:41:25Z | Null | https://github.com/yayomu/fuzzy-octo-dollop | 0 | 0| 
| 20230203T04:39:50Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 8323 | 1814| 
| 20230203T02:36:05Z | REcollapse is a helper tool for black-box regex fuzzing to bypass validations and discover normalizations in web applications | https://github.com/0xacb/recollapse | 385 | 32| 
| 20230203T02:23:54Z | Fuzz Introspector -- introspect, extend and optimise fuzzers | https://github.com/ossf/fuzz-introspector | 237 | 34| 



# 日更新程序
