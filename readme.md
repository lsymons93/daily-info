# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210626T11:27:28Z | CVE-2021-35475 | Writeup for CVE-2021-35475; Stored Cross-Site Scripting(XSS) on SAS® Environment Manager 2.5 | https://github.com/saitamang/CVE-2021-35475 | SAS Environment Manager 2.5 allows XSS through the Name field when creating/editing a server. The XSS will prompt when editing the Configuration Properties.| 
| 20210626T11:25:35Z | CVE-2021-31955 | Null | https://github.com/mavillon1/CVE-2021-31955-POC | Windows Kernel Information Disclosure Vulnerability| 
| 20210626T09:44:57Z | CVE-2021-32537 | PoC for CVE-2021-32537: an out-of-bounds memory access that leads to pool corruption in the Windows kernel. | https://github.com/0vercl0k/CVE-2021-32537 | 未查询到CVE信息| 
| 20210626T09:24:14Z | CVE-2021-27850 | A Proof of concept for CVE-2021-27850 affecting Apache Tapestry and leading to unauthencticated remote code execution. | https://github.com/kahla-sec/CVE-2021-27850_POC | A critical unauthenticated remote code execution vulnerability was found all recent versions of Apache Tapestry. The affected versions include 5.4.5, 5.5.0, 5.6.2 and 5.7.0. The vulnerability I have found is a bypass of the fix for CVE-2019-0195. Recap: Before the fix of CVE-2019-0195 it was possible to download arbitrary class files from the classpath by providing a crafted asset file URL. An attacker was able to download the file `AppModule.class` by requesting the URL `http://localhost:8080/assets/something/services/AppModule.class` which contains a HMAC secret key. The fix for that bug was a blacklist filter that checks if the URL ends with `.class`, `.properties` or `.xml`. Bypass: Unfortunately, the blacklist solution can simply be bypassed by appending a `/` at the end of the URL: `http://localhost:8080/assets/something/services/AppModule.class/` The slash is stripped after the blacklist check and the file `AppModule.class` is loaded into the response. This class usually contains the HMAC secret key which is used to sign serialized Java objects. With the knowledge of that key an attacker can sign a Java gadget chain that leads to RCE (e.g. CommonsBeanUtils1 from ysoserial). Solution for this vulnerability: * For Apache Tapestry 5.4.0 to 5.6.1, upgrade to 5.6.2 or later. * For Apache Tapestry 5.7.0, upgrade to 5.7.1 or later.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T01:59:26Z | Estimation codes for exploration-exploitation research project | https://github.com/cmurai/exp2estimation | 0 | 0| 
| 20210626T01:53:27Z | PwnWiki 数据库搜索命令行工具；该工具有点像 searchsploit 命令，只是搜索的不是 Exploit Database 而是 PwnWiki 条目 | https://github.com/k4yt3x/pwsearch | 1 | 0| 
| 20210626T01:44:54Z | Style Transfer model built exploiting a pre-trained VGG19 model applied on Hassan II mosque and Starry night by Van Gogh. | https://github.com/kingridda/Artistic-Deep-Learning-Style-Transfer | 0 | 0| 
| 20210626T01:39:28Z | exploit-database-papers | https://github.com/offensive-security/exploitdb-papers | 315 | 46| 
| 20210626T01:39:20Z | Style Transfer model built exploiting a pre-trained VGG19 model applied on Hassan II mosque and Starry night by Van Gogh. | https://github.com/kingridda/deep-learning-art-style-transfer | 0 | 0| 
| 20210626T01:37:37Z | Container (Docker) escape exploits | https://github.com/duowen1/Container-escape-exps | 2 | 0| 
| 20210626T01:08:12Z | Patch for Waterfall to improve performance during attacks and fix memory issues. | https://github.com/2lstudios-mc/FlameCord | 42 | 26| 
| 20210626T01:02:51Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 25 | 12| 
| 20210626T01:00:04Z | PwnWiki 数据库搜索命令行工具；该工具有点像 searchsploit 命令，只是搜索的不是 Exploit Database 而是 PwnWiki 条目 | https://github.com/pwnwikiorg/pwsearch | 24 | 1| 
| 20210626T00:51:40Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 17 | 11| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T11:36:01Z | ASP WEBSHELL BYPASS PHP SHELL BACKDOOR UNDETECTED! | https://github.com/webshell-archive/ASP | 1 | 0| 
| 20210626T11:35:46Z | PHP WEBSHELL BYPASS PHP SHELL BACKDOOR UNDETECTED! | https://github.com/webshell-archive/PHP | 1 | 0| 
| 20210626T10:02:30Z | Python backdoor | https://github.com/DianaNeumann/Porte_arriere | 0 | 0| 
| 20210626T09:59:16Z | Null | https://github.com/fmy266/Pytorch-Backdoor-Unlearning | 0 | 0| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T01:49:52Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 143 | 33| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T06:09:11Z | Original implementation of FlowPrint as in the NDSS %20 paper | https://github.com/Thijsvanede/FlowPrint | 49 | 18| 
| 20210626T02:22:29Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 15 | 2| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210626T11:35:46Z | This is tool for fuzzing XSS vulnerabilities based on genetic algorithm. | https://github.com/Timofey21/GoXSSfuzz | 0 | 0| 
| 20210626T11:31:11Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210626T11:28:55Z | Null | https://github.com/AdaLogics/go-fuzz-headers | 2 | 1| 
| 20210626T09:53:40Z | DOM fuzzer | https://github.com/mevid93/domzzer | 0 | 0| 
| 20210626T09:32:26Z | Null | https://github.com/VeriBlock/fuzz-corpus | 1 | 1| 
| 20210626T09:28:43Z | Null | https://github.com/bolpuine/fuzzy-octo-palm-tree | 0 | 0| 
| 20210626T08:42:56Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6417 | 1303| 
| 20210626T08:29:19Z | Null | https://github.com/ukyouz/SublimeText-SimpleFuzzy | 0 | 0| 
| 20210626T07:31:46Z | API fuzz testing generator using swagger document. | https://github.com/namuan/fuzzy-swagger | 5 | 1| 
| 20210626T07:29:38Z | syzkaller is an unsupervised coverage-guided kernel fuzzer | https://github.com/google/syzkaller | 3572 | 830| 



# 日更新程序
