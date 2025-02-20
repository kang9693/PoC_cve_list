# PoC_cve_list
PoC_cve_list

test

Palo Alto Networks Pan-OS
Palo Alto Networks Pan-OS 소프트웨어의 인증 우회는 관리 웹 인터페이스에 대한 네트워크 액세스가있는 무단 공격자가 Pan-OS  
관리 웹 인터페이스에 필요한 인증을 우회하고 특정 PHP 스크립트를 호출 할 수 있습니다.이러한 PHP 스크립트를 호출한다고해서 원격 코드 실행
이 가능하지는 않지만 Pan-OS의 무결성과 기밀성에 부정적인 영향을 줄 수 있습니다.

권장 모범 사례 배포 가이드 라인 https://live.paloaltonetworks.com/t5/tips-logs/tips-amp에 따라 관리 웹 인터페이스에 대한 신뢰할 수있는 
내부 IP 주소로만 관리 웹 인터페이스에 대한 액세스를 제한 하여이 문제의 위험을 크게 줄일 수 있습니다.

references:
https://security.paloaltonetworks.com/CVE-2025-0108
https://github.com/iSee857/CVE-2025-0108-PoC
https://slcyber.io/blog/nginx-apache-path-confusion-to-auth-bypass-in-pan-os/
https://www.bleepingcomputer.com/news/security/palo-alto-networks-tags-new-firewall-bug-as-exploited-in-attacks/
https://www.darkreading.com/remote-workforce/patch-now-cisa-researchers-warn-palo-alto-flaw-exploited-wild
https://www.securityweek.com/palo-alto-networks-confirms-exploitation-of-firewall-vulnerability/