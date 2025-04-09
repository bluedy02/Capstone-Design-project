# Capstone-Design-project
[ 2025 - 1학기 캡스톤디자인 프로젝트 ]

□ 프로젝트 주제
   - HTTP 기반 문자열 공격 대응을 위한 유무선 라우터 설계 및 구현

□ 프로젝트 분야
   - 네트워크 보안
     
     => Firewall(방화벽), IPS(침입 방지 시스템)

   - 취약점 분석(모의해킹)
     
     => Web Hacking

□ 요약
  인터넷 기술과 IoT 기술의 발전으로 인해, IoT 기기를 사용하는 사람들이 증가하고 있으며, 그에따라 댜앙한 사이버 위협 공격이 생겨나고 있는 추세이다. 
내부 네트워크의 IoT 기기는 원격 제어를 위해, 유무선 공유기의 포트포워드로 외부 네트워크에서의 직접적인 접근을 허용하는 구조를 이루고 있지만, 비인가자 및 비정상 통신에 대한 제어는 마련되어 있지 않은 실정이다.
본 프로젝트에서는 외부 네트워크에서 내부 IoT 기기를 대상으로 수행 가능한 사이버 위협 공격과 대응 방안에 대해 분석하고, 리눅스 방화벽인 iptables가 탑재된 Raspberry Pi 기반 유무선 공유기를 제작하여, 외부로부터의 비정상 통신을 화이트리스트 기법으로 차단하고자 한다.
