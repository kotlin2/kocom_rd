## About
Kocom Wallpad with RS485 in RD

## Update Log
1. 24/12/25 => 팬 : 꺼지지 않는 현상 수정
2. 24/12/25 => 난방 : 최소온도 수정
3. 24/12/27 => 난방 : 외출 모드 추가(송풍 버튼)
4. 24/12/27 => 엘레베이터 : Discovery(자동추가) 로직 수정

## Installation

1. 홈어시스턴트의 Hass.io > ADD-ON STORE에서 Add new repository by URL에 https://github.com/kotlin2/kocom_rd 를 입력한 다음 ADD 버튼을 누릅니다.
2. ADD-ON STORE 페이지 하단에서 "Kocom Wallpad with RS485" 클릭합니다.
3. "INSTALL" 버튼을 누르면 애드온이 설치됩니다. 최대 약 10분 정도 소요. 
4. INSTALL 버튼위에 설치 애니메이션이 동작하는데 이것이 멈추더라도 REBUILD, START 버튼이 나타나지 않는 경우가 있습니다.
5. 이 애드온은 이미지를 내려받는 것이 아니라 직접 여러분의 Hassio에서 이미지를 만듭니다.
6. INSTALL 버튼을 누른다음 설치 애니메이션이 실행되면 제대로 설치중인 것입니다.
7. share/kocom/ 폴더에 있는 kocom.conf 파일을 본인의 환경에 맞게 수정합니다.
8. "START" 버튼으로 애드온을 실행합니다.

만일 kocom.py 파일을 수정하시려면 한번 실행한 후 애드온을 Stop 하시고
share/kocom/ 폴더에 있는 파일을 알맞게 수정하신 다음에
애드온을 Start 하시면 이후부터는 수정된 파일을 적용합니다.
