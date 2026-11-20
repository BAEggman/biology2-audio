# biology2-audio

[biology2 레슨](https://baeggman.github.io/biology2/lesson/index.html)의 낭독 음성(Gemini 녹음)만 담는 저장소다. 레슨 화면이 이 파일들을 불러 정거장마다 저절로 이어 읽는다.

- 주소: `https://baeggman.github.io/biology2-audio/<과>_<sid>_v<판>.mp3` (예: `L07e_s1_v1.mp3`)
- 어느 구간에 어느 파일을 틀지는 본 저장소의 `lesson/audio/manifest.json` 이 정한다(`src` 에 위 주소 · `text` 가 지금 대본과 글자까지 같을 때만 튼다 — 다르면 기기 음성으로 읽는다).
- 검수 기록은 본 저장소의 `lesson/audio/reviews/`.
- **올린 파일의 이름을 바꾸거나 지우지 않는다** — 재생이 끊긴다. 다시 녹음하면 판 번호를 올린 새 이름으로 올리고 manifest 의 `src` 를 바꾼다(옛 파일은 manifest 에서 빠진 뒤에 정리한다).
- 원본 WAV 는 여기 두지 않는다(사용자 컴퓨터 `~/Downloads/b2audio/raw/`).
- 왜 따로 두나: GitHub Pages 한 사이트의 한도가 1 GB 인데, 그림 · 작업 파일이 있는 본 저장소에 낭독 전체(약 0.7 GB)까지 얹으면 넘친다. 같은 주소(baeggman.github.io) 아래라 브라우저에는 같은 사이트다 — 재생 · 자동 넘김이 그대로 된다.
