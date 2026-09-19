# UNIST Destroyer

UNIST 캠퍼스 파괴 시뮬레이터. OpenStreetMap 실측 건물 외곽선 위에 three.js로 만든 브라우저 게임입니다.

## 플레이

| 파일 | 용도 |
|---|---|
| `index.html` | PC 버전 (마우스·키보드) |
| `mobile.html` | 모바일 버전 (터치 UI) |
| `test/pc.html`, `test/mobile.html` | 테스트 채널 — fps 패널, 오류 박스, 날짜 배지 포함 |
| `legacy/2d-satellite.html` | 초기 2D 위성 뷰 버전 |

GitHub Pages를 켜면 `https://<계정>.github.io/<저장소>/` 가 PC판, `/mobile.html` 이 모바일판입니다.
three.js는 cdnjs에서 불러오므로 인터넷 연결이 필요합니다.

## 조작 (PC)

| 입력 | 동작 |
|---|---|
| 좌클릭 | 무기 발동 (괴수·레이저·토네이도는 드래그) |
| 우클릭 드래그 | 카메라 회전 |
| Shift+드래그 / 휠클릭 | 카메라 이동 |
| 휠 | 줌 |
| `1`-`9` | 무기 선택 |
| `C` / `T` / `L` / `R` / `ESC` | 카메라 모드 / 슬로모션 / 라벨 / 복구 / 일시정지 |

## 데이터 출처

- 건물 외곽선·도로·수계·다리·주차장·잔디·숲·운동장: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, ODbL
- 층수: OSM `building:levels` 태그 우선, 없으면 공개 자료 참조
- 캠퍼스 외곽 지형은 절차적 생성이며 실측이 아닙니다

## 라이선스

게임 코드는 MIT. 지도 데이터는 ODbL을 따릅니다. 순수 오락용이며 실제 시설·인물과 무관합니다.

패치노트: [PATCHNOTES.md](PATCHNOTES.md)
