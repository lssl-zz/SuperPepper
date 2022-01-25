# SuperPepper
## 1.인트로
![타이틀](https://user-images.githubusercontent.com/12422388/150919305-6893ae98-5ba1-43c8-bd19-7fb2fffd8bc9.gif)<br>
- 타이틀 영상입니다.
- 뒤끝 - 클라우드 서버를 이용하여 닉네임, 게임데이터를 처리합니다.
<br />

## 2.로비-1
![로비-스테이지맵](https://user-images.githubusercontent.com/12422388/150920360-33e6d75c-f549-4514-8ef2-444ff429e4b2.gif)<br>
- UI패널 이동시 페이드 연출을 합니다.
- 스테이지 챕터 분리와 Lock 처리를 통해 순처적인 챕터 클리어를 유도합니다.
- 씬매니저를 통해서 씬이동을 합니다.

## 3.로비-2
![로비-캐릭터](https://user-images.githubusercontent.com/12422388/150921631-85fefa1f-7c96-4288-a7fb-ab6c71f86f9c.gif)<br>
- 스크롤 스냅 기능으로 캐릭터를 표기합니다.

## 4.로비-3
![로비-말풍선](https://user-images.githubusercontent.com/12422388/150922493-6e1238ef-5b2d-4840-9a6c-6129197ca2db.gif)<br>
- Text 길이 및 개행에 맞춰서 말풍선 앵커 처리를 합니다.

## 5.전투
![전투](https://user-images.githubusercontent.com/12422388/150923369-6c3393f0-abf6-483b-97e6-9a64cb7cb2e0.gif)<br>
- 반자동 시스템으로 유저 Input이 없으면 특정시간(ex 0.5초)만큼 지연후 자동 공격을 합니다.
- 몬스터의 배치는 총 3곳으로 앞에서부터 순차적으로 몬스터를 공격합니다.
- 보스몬스터는 제한 시간안에 처치해야하는데, DPS가 부족하면 패배하게 됩니다.