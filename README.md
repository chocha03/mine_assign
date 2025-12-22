# 지뢰 찾기 게임에 추가된 기능

## 1. 숫자별로 다른 색 기능
<img width="547" height="616" alt="기능1" src="https://github.com/user-attachments/assets/5ef8e0cd-8081-49af-b081-8deec8ad57c8" />

* 공개된 칸 중 지뢰가 아닌 칸의 인접 8칸에 있는 지뢰 개수 별로 숫자가 나오고 숫자별로 색이 다르게 나옵니다.
* 숫자는 config.py에서 Number font가 추가되어 폰트를 변경할 수 있습니다.


## 2. 난이도 기능
<img width="325" height="388" alt="기능2-easy" src="https://github.com/user-attachments/assets/c1a406b6-4966-4da0-a8b7-53410f81d4c3" />

이지 난이도 (가로: 9칸 / 세로: 9칸 / 지뢰 개수: 10개)

<img width="543" height="612" alt="기능2-normal" src="https://github.com/user-attachments/assets/73074993-ed51-42fb-887a-35d00646a1c0" />

노말 난이도 (가로: 16칸 / 세로: 16칸 / 지뢰 개수: 40개)

<img width="992" height="614" alt="기능2-hard" src="https://github.com/user-attachments/assets/c88e7789-e25f-4b7c-b1b0-7a8f9b3db492" />

하드 난이도 (가로: 30칸 / 세로: 16칸 / 지뢰 개수: 60개)


* 키보드 1, 2, 3으로 각각 easy, normal, hard 모드로 변경할 수 있습니다.


## 3. 힌트 기능
<img width="544" height="617" alt="기능3" src="https://github.com/user-attachments/assets/3453b0ad-18ba-49ee-a2c9-2b75948c6445" />

* 공개되지 않은 지뢰가 아닌 칸을 하나 공개합니다.
* 키보드의 h키를 눌러 힌트를 사용할 수 있습니다.
* 사용 가능한 힌트의 개수는 3개입니다.


## 4. 최고 기록 표출 기능
<img width="544" height="612" alt="기능4-게임화면" src="https://github.com/user-attachments/assets/bd99002c-8219-4231-861b-5b3ef415e594" />

* 게임 화면 가운데에 최소 시간으로 클리어한 기록이 표출됩니다.
* 게임을 클리어하거나 게임오버 시에도 최고 기록이 표출됩니다.


<img width="863" height="266" alt="기능4-json파일" src="https://github.com/user-attachments/assets/77a63d37-61ee-443a-b7eb-adddcdbd8259" />

* 최고기록은 highscore.json 파일에 저장되며 해당 파일이 존재하지 않을 시 자동으로 생성하여 기록합니다.

## 5. 게임 진행 시간 표시 기능
<img width="542" height="613" alt="기능5" src="https://github.com/user-attachments/assets/65fcbdcd-afd2-424e-b68f-08abd06916dc" />

* 칸 하나를 클릭하여 게임 시작 시 게임화면 오른쪽 위에 진행시간이 흐르게 됩니다.
* 5분이 지나면 진행시간이 빨간색으로 표시됩니다.
