# UE4 Dedicated Server기반 멀티 게임 MultiMazeRunner
### [Preview Youtube Link](https://www.youtube.com/watch?v=7MpnQJNhdzQ)

## 개요
### 알 수 없는 이유로 미로에 갇힌 2명의 플레이어가 AI 로봇들을 물리치며 골인 지점까지 도달하지만 그 끝에 있는 것은…
![image](https://user-images.githubusercontent.com/70702088/116786919-43166400-aadc-11eb-99e5-b110005b948a.png)

## 구현 기술 & 특징
### 멀티플레이
![image](https://user-images.githubusercontent.com/70702088/116786938-5d504200-aadc-11eb-85f4-8e47ccb15229.png)
![image](https://user-images.githubusercontent.com/70702088/116787647-3dbb1880-aae0-11eb-8bc4-8833e140a010.png)
### 블루프린트
![image](https://user-images.githubusercontent.com/70702088/116787374-925d9400-aade-11eb-97bd-66df78ec17d1.png)
![image](https://user-images.githubusercontent.com/70702088/116786990-9c7e9300-aadc-11eb-8ede-f04d17988b91.png)
![image](https://user-images.githubusercontent.com/70702088/116786997-a0aab080-aadc-11eb-8870-789394a6865e.png)

### AI
![image](https://user-images.githubusercontent.com/70702088/116787110-3d6d4e00-aadd-11eb-9ba7-d8f3962cf53a.png)
![image](https://user-images.githubusercontent.com/70702088/116787037-d2237c00-aadc-11eb-85cc-7e2a5a474121.png)
![image](https://user-images.githubusercontent.com/70702088/116787031-cb950480-aadc-11eb-95d7-bb918f87c7b7.png)
![image](https://user-images.githubusercontent.com/70702088/116787038-d8b1f380-aadc-11eb-9870-dd01b3e69667.png)

### 게임 디자인
![image](https://user-images.githubusercontent.com/70702088/116787078-0860fb80-aadd-11eb-8c65-bf13aaa76f98.png)
![image](https://user-images.githubusercontent.com/70702088/116787081-0bf48280-aadd-11eb-868a-e83021d69938.png)
![image](https://user-images.githubusercontent.com/70702088/116787070-0434de00-aadd-11eb-9c7d-38f8eaa75414.png)

### 애니메이션
![image](https://user-images.githubusercontent.com/70702088/116787599-e0bf6280-aadf-11eb-88b5-1812ac36c26d.png)
- 애니메이션 몽타주 설정

- 캐릭터의 무기 타격 범위 조정

- 노티파이 타임라인 설정을 통해서 해당 공격 애니메이션 실행 시에 Deal Damage 블루프린트를 통해 타격 범위 및 시간을 적절히 조정


## 조작법
- 두 명의 플레이어가 맵의 시작 지점에 스폰되어 쫓아오는 AI 몹을 피해 먼저 미로를 빠져나가는 것이 목표입니다.
- W,A,S,D 를 통해 앞, 왼쪽, 뒤, 오른쪽으로 움직일 수 있으며 Shift키를 통해서 달리기가 가능합니다.
- 마우스 좌 클릭으로 공격이 가능합니다.

## 참고사항
언리얼엔진 Ver.4.23.1을 서버용으로 재빌드하여 제작하였습니다.

실행 시에 Server를 우선적으로 실행한 후 서버에 접속해야 합니다.

AWS EC2 가상서버 위에서 서버 구동 및 원활한 접속이 가능합니다.

## 개발
김재혁
- 게임 맵 제작
- AI Enemy제작
- 게임 기획

홍현준
- 서버-클라이언트 구조 적용
- 애니메이션 적용
- 게임 기획
