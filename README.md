# PoC_cve_list
PoC_cve_list

<b>CVE-2025-0108 : Palo Alto Networks Pan-OS</b></br>
Palo Alto Networks Pan-OS 소프트웨어의 인증 우회는 관리 웹 인터페이스에 대한 네트워크 액세스가있는 무단 공격자가 Pan-OS  
관리 웹 인터페이스에 필요한 인증을 우회하고 특정 PHP 스크립트를 호출 할 수 있습니다.이러한 PHP 스크립트를 호출한다고해서 원격 코드 실행
이 가능하지는 않지만 Pan-OS의 무결성과 기밀성에 부정적인 영향을 줄 수 있습니다.

권장 모범 사례 배포 가이드 라인 https://live.paloaltonetworks.com/t5/tips-logs/tips-amp에 따라 관리 웹 인터페이스에 대한 신뢰할 수있는 
내부 IP 주소로만 관리 웹 인터페이스에 대한 액세스를 제한 하여이 문제의 위험을 크게 줄일 수 있습니다.

references site :</br>
https://security.paloaltonetworks.com/CVE-2025-0108 </br>
https://github.com/iSee857/CVE-2025-0108-PoC </br>
https://slcyber.io/blog/nginx-apache-path-confusion-to-auth-bypass-in-pan-os/ </br>
https://www.bleepingcomputer.com/news/securitypalo-alto-networks-tags-new-firewall-bug-as-exploited-in-attacks/</br>
https://www.darkreading.com/remote-workforce/patch-now-cisa-researchers-warn-palo-alto-flaw-exploited-wild</br>
https://www.securityweek.com/palo-alto-networks-confirms-exploitation-of-firewall-vulnerability/</br>
https://www.krcert.or.kr/kr/bbs/view.do?searchCnd=&bbsId=B0000133&searchWrd=&menuNo=205020&pageIndex=1&categoryCode=&nttId=71664</br>


Poc github </br>
https://github.com/iSee857/CVE-2025-0108-PoC</br>
https://github.com/FOLKS-iwd/CVE-2025-0108-PoC</br>
https://github.com/becrevex/CVE-2025-0108 </br>
https://github.com/sohaibeb/CVE-2025-0108 </br>
https://github.com/fr4nc1stein/CVE-2025-0108-SCAN </br>
https://github.com/barcrange/CVE-2025-0108-Authentication-Bypass-checker </br>



<b>CVE-2017-10271 : Vulnerability in the Oracle WebLogic Server(WEBLOGIC RCE)</b></br>

 Oracle Fusion Middleware의 Oracle Weblogic 서버 구성 요소의 취약성 (하위 구성 요소 : WLS 보안).영향을받는 지원 버전은 10.3.6.0.0, 12.1.3.0.0, 12.2.1.1.0 및 12.2.1.2.0입니다.쉽게 활용할 수있는 취약점을 통해 T3을 통해 네트워크  액세스를 통해 무단 공격자가 Oracle Weblogic 서버를 손상시킬 수 있습니다.이 취약성에 대한 성공적인 공격은 Oracle Weblogic 서버를 인수 할 수 있습니다.CVSS 3.0 기본 점수 7.5 (가용성 영향).CVSS 벡터 : (CVSS : 3.0/AV : N/AC : L/PR : N/UI : N/S : U/C : N/I : N/A : H).

 원문:  Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS Security). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.1.0 and 12.2.1.2.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3 to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 7.5 (Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H).


<b>references:</b></br>
http://www.oracle.com/technetwork/security-advisory/cpuoct2017-3236626.html</br>
http://www.securityfocus.com/bid/101304</br>
http://www.securitytracker.com/id/1039608</br>
https://github.com/c0mmand3rOpSec/CVE-2017-10271</br>
https://www.exploit-db.com/exploits/43458/</br>
https://www.exploit-db.com/exploits/43924/</br>
http://www.oracle.com/technetwork/security-advisory/cpuoct2017-3236626.html</br>
http://www.securityfocus.com/bid/101304</br>
http://www.securitytracker.com/id/1039608</br>
https://github.com/c0mmand3rOpSec/CVE-2017-10271</br>
https://www.exploit-db.com/exploits/43458/</br>
https://www.exploit-db.com/exploits/43924/</br>


<b>POC</b> </br>
1. https://github.com/UGF0aWVudF9aZXJv/Atlassian-Jira-pentesting</br>
2. https://github.com/ColdFusionX/CVE-2021-26086</br>
3. https://github.com/UGF0aWVudF9aZXJv/Atlassian-Jira-pentesting

<b>Mitigation</b> <bR>
https://confluence.atlassian.com/jirakb/workaround-for-cve-2019-15004-979416164.html</br>



<b>CVE-2025-27636(Apache Camel vul)</b></br>

<b>POC</b> </br>
https://github.com/akamai/CVE-2025-27636-Apache-Camel-PoC<bR>


<b>CVE-2024-23897:Jenkins CLI arbitrary read (CVE-2024-23897 applies to versions below 2.442 and LTS 2.426.3)</b></br>

<b>POC</b> </br>
https://github.com/gquere/pwn_jenkins<bR>



 <b>Jenkins 취약점 / DDoS 관련 CVE 목록<b><bR>
CVE-2020-2100:UDP multicast 기능을 이용한 DDoS 증폭 공격 가능</br>
CVE-2023-27898:	과도한 URL 요청 시 Jenkins가 과부하로 다운될 수 있음</br>
CVE-2022-45389:	Jenkins 플러그인에서 자원 고갈 유발 가능</br>
CVE-2021-21670:	API 호출 시 메모리 누수로 인한 서비스 거부 가능</br>
CVE-2020-1983	:Jenkins CLI 처리에서 과다 요청 시 자원 소모 발생</br>
CVE-2019-10475	:build-monitor-plugin 플러그인의 과도한 요청으로 인한 DoS</br>
<b>POC</b> </br>
https://github.com/vesche/CVE-2019-10475</br>


CVE-2019-1003000:	경로 우회를 통한 과도한 요청 가능성</br>
CVE-2018-1999002:	XStream deserialization 취약점으로 인한 자원 소모 가능</br>
<b>POC</b> </br>
https://github.com/adamyordan/cve-2019-1003000-jenkins-rce-poc</br>

CVE-2017-1000353:	Jenkins CLI에 대한 대량 요청으로 서비스 중단 유발 가능</br>
<b>POC</b> </br>
https://github.com/vulhub/CVE-2017-1000353</br>

CVE-2015-5310	:Jenkins slave 연결 시 대량 요청으로 DoS 유발 가능</br>