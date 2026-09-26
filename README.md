# 🎨 명화 사운드스케이프 확장 갤러리

> Color & Sound Art Integration — 다섯 점의 명화를 색과 소리로 잇다

세계적인 명화 다섯 점의 **대표 색**을 읽어 내고, 그 색이 주는 느낌을 **음악 장르·템포·악기**로 옮긴 사운드스케이프 갤러리입니다. 작품마다 영상, 트랙 정보, 영어 가사, 그리고 "어떤 색을 어떤 소리로 바꾸었는지"를 설명하는 제작 노트를 함께 보여 줍니다.

---

## 작품 목록

| # | 명화 | 화가 | 트랙 | 앨범 | 장르 (BPM) | 영상 파일 |
|---|---|---|---|---|---|---|
| 1 | 별이 빛나는 밤 (1889) | 빈센트 반 고흐 | Below the Loom | The Painted Hour | Cinematic Ambient (60) | `Below_the_Loom.mp4` |
| 2 | 춤 (1910) | 앙리 마티스 | Carved in Blue | Weight of the Meridian | Art-Pop / Neo-Soul (110) | `Carved_in_Blue.mp4` |
| 3 | 절규 (1893) | 에드바르 뭉크 | Beneath the Heavy Air | Inner Turmoil | Dark Ambient / Industrial Noise Pop (85) | `Beneath_The_Heavy_Air.mp4` |
| 4 | 진주 귀걸이를 한 소녀 (1665년경) | 요하네스 페르메이르 | Graff qui saigne | The Quiet Look | Chamber Pop / Dream Pop (75) | `Graff_qui_saigne.mp4` |
| 5 | 수련 (연작) | 클로드 모네 | Lavender Mist | Giverny Reflections | New Age / Impressionist Ambient (55) | `Lavender_Mist.mp4` |

---

## 색을 소리로 옮긴 방식

| 명화 | 대표 색 | 소리로 옮긴 방법 |
|---|---|---|
| 별이 빛나는 밤 | 프러시안 블루 · 골든 옐로우 | 깊은 밤하늘의 파랑은 넓게 퍼지는 **패드 신시사이저**로, 황금빛 별의 반짝임은 은은한 **아르페지오**로 |
| 춤 | 선명한 빨강 · 초록 · 파랑 | 원색의 대비와 둥글게 도는 인물의 리듬을 경쾌한 템포로, 빨강의 생명력은 따뜻한 **일렉트릭 피아노와 보컬 하모니**로 |
| 절규 | 타오르는 주황·노랑 · 핏빛 빨강 | 불안한 하늘을 찌르는 듯한 **고음역 신스 노이즈**와 왜곡된 **베이스 드론**으로 |
| 진주 귀걸이를 한 소녀 | 울트라마린 블루 · 진주빛 흰색 | 신비로운 눈빛과 진주의 영롱함을 **어쿠스틱 기타·하프**와 몽환적인 보컬로 |
| 수련 | 연보라 · 아쿠아마린 · 부드러운 금빛 | 빛에 따라 흔들리는 연못을 부드러운 **피아노 아르페지오**와 **스트링 패드**로 |

색의 성격에 따라 템포도 달리했습니다. 고요한 수련과 별밤은 느리게(55~60), 불안한 절규는 중간(85), 춤추는 마티스는 가장 빠르게(110) 흐릅니다.

---

## 화면 구성

작품마다 같은 순서로 보입니다.

1. **제목과 화가** — 명화마다 대표 색으로 테두리와 제목 색을 바꿨습니다(고흐 금색, 마티스 초록, 뭉크 빨강, 페르메이르 파랑, 모네 연두).
2. **영상** — 재생 버튼으로 사운드스케이프 영상을 봅니다.
3. **트랙 정보** — 트랙 제목, 앨범, 장르와 BPM.
4. **가사(Lyrics)** — 명화의 장면을 옮긴 네다섯 줄의 영어 가사.
5. **대표 컬러 및 음악 제작 방식** — 어떤 색을 어떤 소리로 바꾸었는지.

---

## 실행과 배포

설치할 것이 없습니다. html 파일 하나와 영상 다섯 개만 있으면 됩니다.

**파일 구조** — 영상은 html과 **같은 폴더**에 두어야 합니다.

```
.
├── art_soundscape_gallery.html   갤러리 페이지 (저장소에 올릴 때 index.html로 바꾸면 주소가 짧아집니다)
├── Below_the_Loom.mp4
├── Carved_in_Blue.mp4
├── Beneath_The_Heavy_Air.mp4
├── Graff_qui_saigne.mp4
├── Lavender_Mist.mp4
└── README.md
```

- 파일 이름은 **대소문자까지** 위와 똑같아야 합니다. GitHub Pages나 Vercel은 대소문자를 구분합니다.
- 영상을 바꿀 때는 html에서 `<source src="…mp4">`와 트랙 제목 줄을 함께 고칩니다.

**내 컴퓨터에서 열기**

html 파일을 크롬, 엣지, 사파리로 엽니다.

**GitHub Pages로 올리기**

1. 저장소에 위 파일을 모두 올립니다.
2. **Settings → Pages**에서 Branch를 `main`, 폴더를 `/ (root)`로 정하고 **Save**를 누릅니다.
3. 1~2분 뒤 `https://<계정>.github.io/<저장소 이름>/art_soundscape_gallery.html`로 열립니다.

> GitHub는 파일 하나가 100MB를 넘으면 올라가지 않습니다. 영상이 크면 압축하거나 Vercel 등 다른 곳에 두세요.

**인쇄**

A4 인쇄 설정이 들어 있습니다. 브라우저의 **인쇄 → PDF로 저장**으로 전시 자료를 만들 수 있습니다. 배경색까지 나오게 하려면 인쇄 창에서 "배경 그래픽"을 켜세요.

---

## 저작권

© 2026 조준동 (Jun-Dong Cho) · Humartology Lab. All rights reserved.

- 사운드스케이프 음악, 가사, 영상, 제작 노트, 페이지 구성의 저작권은 작가에게 있습니다. 무단 복제·배포·상업적 이용을 금합니다.
- 다섯 점의 원작 명화는 각 화가의 작품이며, 그림 이미지의 이용 조건은 소장 기관의 규정을 따릅니다.

문의: jdcho@skku.edu · [blog.naver.com/humartology](https://blog.naver.com/humartology)
