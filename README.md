# PoC_cve_list
PoC_cve_list

test

<b>Palo Alto Networks Pan-OS</b></br>
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

