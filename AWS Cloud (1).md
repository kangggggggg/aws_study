### AWS의 이점
#### 다양한 서비스 제공
- AWS는 컴퓨팅, 스토리지, 네트워크 보안 도구 같은 기본 요소부터 블록체인, 기계 학습, 인공지능, 로봇 개발 플랫폼 같은 복잡한 솔루션까지 다양한 서비스를 제공한다.
#### 종량 과금제
- 필요한 만큼만 사용하고 사용한 만큼만 지불할 수 있다.

### 온디맨드식 제공과 클라우드 배포의 차이점 
#### 온디맨드식 제공

- 필요한 만큼만 자원을 사용하고, 사용한 만큼만 비용을 지불하는 방식.
AWS에서는 사용자에게 필요한 IT 리소스를 필요한 순간에 제공한다. 가상 서버 몇 백개가 갑자기 필요할 때 클릭 몇 번만으로 바로 시작할 수 있고, 수 천 TB의 스토리지가 필요할 때도 마찬가지로 즉시 사용할 수 있다. 또한, 더 이상 필요하지 않은 리소스는 반환하여 비용 지불을 중단할 수 있다. 이러한 **유연성**은 직접 운영하는 데이터 센터에서는 어렵다.

**_ex)_** 바리스타가 필요할 때만 근무하고 근무한 시간에 대해서만 급여를 받는 것과 같다. 손님이 몰릴 때는 바리스타를 더 많이 두고, 한가할 때는 적게 두어 비용을 최적화할 수 있다.

#### 클라우드 배포

- 클라우드 환경에서 애플리케이션과 서비스를 배포하는 방식. 필요한 자원을 신속하게 추가하거나 제거할 수 있다. AWS를 사용하면 서버를 바로 생성하거나 종료할 수 있어, 변화하는 비즈니스 요구에 빠르게 대응할 수 있다. 또한 설치, 백업 등 반복적이고 시간이 오래 걸리는 작업을 대신 관리해줘, 사용자가 차별화 요소에만 집중할 수 있게 해줄 수 있다.

- **클라우드 배포 모델**
  - **클라우드 기반 배포**
  애플리케이션의 모든 부분을 클라우드에서 실행하는 모델
  
  - **온프레미스 배포(프라이빗 클라우드 배포)**
  기존 애플리케이션을 클라우드로 마이그레이션하지 않고 온프레미스 데이터 센터에서 실행하는 모델
  
  - **하이브리드 배포**
  클라우드 기반 리소스를 온프레미스 인프라에 연결하는 모델
	

### 종량 과금제 모델
- 사용한 자원에 대해서만 비용을 지불하는 모델.
AWS에서는 인스턴스가 필요하면 생성하고, 필요 없으면 종료하여 사용한 만큼만 비용을 지불할 수 있다.
**_ex)_** 바리스타가 일한 시간만큼만 급여를 받는 것과 같다.

### AWS에서의 클라이언트-서버 모델
AWS에서 서버는 일종의 가상 서버인 Amazon Elastic Compute Cloud(Amazon EC2)와 같은 서비스이고, 요청을 처리하는 역할을 한다. 클라이언트는 사용자나 애플리케이션이 될 수 있다.
클라이언트가 서버에 요청을 보내면, 서버는 요청을 검증하고 적절한 응답을 반환한다.

**_ex)_** 고객(클라이언트)이 바리스타(서버)에게 커피를 요청한다. 바리스타는 요청을 확인하고(돈이 지불되었는지 확인), 요청에 따라 커피를 제공한다.
