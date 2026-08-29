<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B2E1A,50:1B7F4B,100:00E676&height=200&section=header&text=chogang&fontColor=ffffff&fontSize=64&fontAlignY=34&desc=필요한%20도구는%20직접%20만듭니다&descSize=17&descAlignY=54" width="100%" />

### 🦎 크레스티드 게코 · 리키에너스 브리더

파충류를 키우다가, 도구를 만들게 됐습니다.

<img src="https://img.shields.io/badge/의존성-0개-00E676?style=for-the-badge&labelColor=0B2E1A" />
<img src="https://img.shields.io/badge/직접_만든_코드-10만_줄-1B7F4B?style=for-the-badge&labelColor=0B2E1A" />
<img src="https://img.shields.io/badge/매일_쓰는_도구-4개-FF7043?style=for-the-badge&labelColor=0B2E1A" />

</div>

<br>

## 시작은 수첩이었습니다

개체가 늘어나면서 무게와 산란일을 수첩에 적는 일이 한계에 왔습니다.

엑셀로 옮겼더니 사진이 안 붙었습니다.
앱을 찾아봤더니 한국 브리더가 쓸 만한 건 없었습니다.
해외 서비스는 크레스티드 게코의 모프도, 누대 표기도 우리 방식과 달랐습니다.

**그래서 직접 만들었습니다.** 지금은 매일 여는 도구 네 개가 됐습니다.

<br>

## 만든 것

<br>

### 🦎 클러치 — 파충류 관리

> `72,735줄` · HTML 21 · JavaScript 44 · Python 7

개체 하나하나의 무게 이력, 부모와 누대, 모프와 유전 조합, 산란과 부화, 분양과 가계부까지
브리딩에서 벌어지는 모든 걸 한 곳에서 다룹니다.

사진이 핵심이라 원본은 디스크에, 표시용 900px은 브라우저 안에 따로 두고
폰과 PC가 같은 기록을 보도록 동기화까지 직접 짰습니다.

분양글 일괄 생성, 카드뉴스 렌더링, 라벨 출력, 예상 부화일 계산 —
브리더가 반복하던 손일을 하나씩 없애는 중입니다.

<br>

### ✍️ 애드센스 스튜디오

> `24,351줄` · Python · 바닐라 JS

블로그 여덟 곳의 글을 쓰고, 검수하고, 발행하고, 성과를 되짚습니다.
어떤 글이 통했는지 실측해서 다음 글의 규칙을 스스로 고쳐 나갑니다.

<br>

### 🧵 스레드 스튜디오

> `1,730줄` · 스레드 공식 API

SNS 글을 쓰고 예약 발행합니다.
잘 된 글과 안 된 글의 차이를 숫자로 남겨서, 말투와 길이를 데이터로 다듬습니다.

<br>

### ⌨️ 덱

> `2,428줄` · Python

매크로패드 36키와 단축어를 코드 한 곳에서 정의합니다.
자주 여는 화면과 반복 작업을 버튼 하나로 줄였습니다.

<br>

## 어떻게 만드나

<div align="center">

<img src="https://img.shields.io/badge/JavaScript-바닐라-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Python-표준_라이브러리만-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-2E7D32?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-2E7D32?style=flat-square&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/IndexedDB-오프라인_우선-1B7F4B?style=flat-square" />
<img src="https://img.shields.io/badge/PWA-폰에서도-1B7F4B?style=flat-square" />

</div>

<br>

**프레임워크를 쓰지 않습니다.** React도, Django도, 패키지 매니저도 없습니다.
`package.json`도 `requirements.txt`도 아예 없고, 서버는 파이썬 표준 라이브러리만으로 돕니다.

거창한 신념이 있어서는 아닙니다.
혼자 만들고 혼자 고치는 도구라서, **1년 뒤에도 내가 열어볼 수 있는 코드**가 제일 중요했습니다.
버전이 깨져서 못 여는 도구는 없는 도구니까요.

인터넷이 끊겨도 돌아가야 합니다. 사육장에서 폰으로 무게를 적는 순간에 로딩이 필요하면 안 되니까요.

<br>

## 지나온 길

```
2023.02   React 강의를 따라 치던 시절          movie_app-2023
2023.03   인생 네컷 웹앱                       Four-cuts-of-my-life
2024.03   졸업작품                             Graduation-work
2025.08   파충류 사이트 첫 시도                 crested-gecko-breeding
2026.08   매일 쓰는 도구 네 개                  clutch · adsense-studio
                                              threads-studio · deck
```

강의를 따라 치던 사람이 **자기 문제를 푸는 사람**이 되기까지 3년 걸렸습니다.

가장 크게 배운 건 기술이 아니라 이거였습니다.
만드는 것보다 **계속 쓰이는 게 훨씬 어렵다**는 것.
그래서 요즘은 새 기능을 붙이기 전에 지난달에 만든 걸 내가 실제로 썼는지부터 봅니다.

<br>

---

<div align="center">

**파충류 이야기든 코드 이야기든 편하게 연락 주세요.**

<a href="https://github.com/xhy0808s"><img src="https://img.shields.io/badge/GitHub-0B2E1A?style=for-the-badge&logo=github&logoColor=white" /></a>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E676,50:1B7F4B,100:0B2E1A&height=120&section=footer" width="100%" />

</div>
