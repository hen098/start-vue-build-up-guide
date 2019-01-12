# Vue 프로젝트 시작 안내서

Vue로 개발하려는 초보자들을 위한 가이드 문서입니다.  

> 유영창 : frog@falinux.com

## 들어가며

Vue 와 관련 소개글을 읽으면, 쉽다는 생각이 듭니다. 도전 의지도 마구 마구 생깁니다.  

맞습니다. 남들이 하는 거 보면 쉽습니다!  

내가 하며? 어렵습니다. 

> 왜?  
> 처음에 어떻게 시작해야 할지 막막하기 때문입니다.  

그래서 처음 하시는 분들이 따라 하도록 문서를 만들어 봤습니다. 그동안 최신 트랜드에 따라가기 위해 제가 했던 삽질을 여러분이 하면 안되잖아요?

그리고 생각보다 초기 개발 환경 빌드 과정은 쉽습니다!

### 최소 필요 지식

이 글을 읽고 따라하시려면 우분투와 도커는 아셔야 합니다. 

* ubuntu(mint 포함) 명령 사용법
* docker 와 docker-compose 사용법

전문가 수준이 필요한 것이 아닙니다. 필요할 때 구글 검색하면서 배워 가실 정도면 됩니다.

### 개발 환경

개인적으로 저는 민트를 씁니다. 우분투 기반이라 우분투와 호환되면서 GUI 환경이 좋습니다. 윈도우를 쓰시는 분들은 말리고 싶습니다. 맥은? 부럽습니다. 

이 후에 실행될 명령들은 모두 리눅스 명령입니다. 

### 도커를 알아야 하는 이유 

프런트 앤드를 개발자로 사시려면 도커를 학습할 것을 강력하게 권장합니다.  

그 이유는 자신의 PC 를 보호하기 하기 위한 것이고, 개발 과정에서 필수적으로 요구 되기 때문입니다. 

프런트앤드 개발을 하시면 다양한 공개 소프트웨어와 툴들을 사용하실 겁니다. 공개 소프트는 반드시 필요한 패키지가 있습니다. 각 요구 버전도 다릅니다.

그래서 여러분의 개발 PC 는 언젠가는 너덜 너덜 해 집니다. 결국 PC 초기화를 하시는 자신의 모습을 보시게 될 겁니다. 이런것이 싫으면 도커 컨테이너로 개발 환경을 구축하는 것이 수명 연장의 지름길입니다. 

프런트엔드 개발자지만 필수적으로 백 엔드도 다루게 됩니다. 

개발 단계를 따라가거나 자동화를 쫒다보면 반드시 도커 컨테이너를 알아야 할 것이고 결국 쿠버네티스를 만나 큐브를 만지작 거리는 자신을 발견하게 되실 겁니다.

반드시! 도커 공부하십시오.




