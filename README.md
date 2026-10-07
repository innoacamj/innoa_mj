# 롯데자이언츠 "기세다" AI 광고 패키지

GenAI 기초 2: 멀티모달 콘텐츠 제작 미션 제출물입니다.

## 1. 최종 결과물 정보

| 항목 | 내용 |
|---|---|
| 스토리보드 | 본 문서(README.md) 및 스토리보드 PDF |
| 광고 영상 | (영상 링크 또는 파일명 기재) |
| 영상 길이 | (예: 30초) |
| 해상도 / 프레임레이트 | (예: 1920x1080 / 30fps) |
| 코덱 | (예: H.264 / AAC) |

## 2. 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드 | 롯데 자이언츠 (실제 브랜드) |
| 타겟 | 부산·경남 지역 팬 + 오랜 팬덤을 가진 전 연령층 |
| 톤앤매너 | 열정적, 다이나믹, 푸른 물결 응원, 사직구장의 함성 |
| USP | 이기고 지는 것을 넘어, 흐름과 기세로 압도하는 팀 |
| 핵심 메시지 | 롯데자이언츠는 기세다 |
| 엔딩 카피 | 아직 끝나지 않았다, 가을야구 가자 |

## 3. 사용 도구 목록

| 구분 | 사용 도구 | 사용 목적 |
|---|---|---|
| 이미지 생성 | Midjourney | 씬별 키비주얼 생성 |
| 비디오 생성 | Runway | 이미지를 짧은 모션 컷으로 변환 |
| 오디오 생성 | Suno | 배경음악 및 효과음 생성 |
| 통합 편집 | CapCut | 컷 편집, 자막, 엔딩 타이포 모션 |

## 4. 씬 구성 흐름

씬1(6초) → 씬2(8초) → 씬3(10초) → 씬3-2(5초) → 씬3-3(5초) → 씬4(10초) → 씬5(8초) → 씬6(4~5초)

## 5. 씬별 스토리보드

### 씬1 — Intro (6초)

- **목표 메시지**: 고요함 속 긴장감으로 시작을 암시
- **화면 구성**: 텅 빈 새벽의 사직구장, 푸른 조명 아래 걸린 유니폼 클로즈업
- **내레이션**: (무음 또는 낮은 앰비언트만)
- **사용 도구**: 이미지 Midjourney(키비주얼) / 비디오 Runway(패닝 모션) / 오디오 Suno(앰비언트 사운드)
- **입력 프롬프트**:
  ```
  empty baseball stadium at dawn, spotlight on hanging blue jersey, cool blue tone, quiet cinematic mood, 8k
  ```
- **출력 결과 요약**: 정적이고 웅장한 구장 분위기를 푸른 톤으로 확보
- **파일명**: scene01_keyvisual.png / scene01_motion.mp4

### 씬2 — 전개 (8초)

- **목표 메시지**: 팬들이 모이며 파란 응원 물결이 갈매기처럼 퍼져나감을 표현
- **화면 구성**: 관중석이 채워지는 몽타주, 파란 응원 물결이 갈매기 날갯짓처럼 퍼짐
- **내레이션**: "하나둘, 푸른 갈매기의 물결이 시작된다"
- **사용 도구**: 이미지 Midjourney / 비디오 Runway / 오디오 Suno(응원가 도입부)
- **입력 프롬프트**:
  ```
  Korean baseball stadium filling with fans, blue wave forming in seagull wing shape, wide angle, energetic atmosphere
  ```
- **출력 결과 요약**: 파란 응원 물결이 갈매기 형상으로 퍼지는 다이나믹한 장면 확보
- **파일명**: scene02_keyvisual.png / scene02_motion.mp4

### 씬3 — 전환 (10초)

- **목표 메시지**: 경기 중 긴장감 고조
- **화면 구성**: 타석/마운드 순간 + 팬 표정 클로즈업 교차 편집, 블루 시네마틱 톤
- **내레이션**: "숨죽인 순간, 모두의 심장이 뛴다"
- **사용 도구**: 이미지 Midjourney / 비디오 Runway / 오디오 Suno(긴장감 있는 배경음)
- **입력 프롬프트**:
  ```
  baseball pitcher wind-up moment, tense close-up, cool blue dramatic lighting, cinematic
  ```
- **출력 결과 요약**: 긴장감 있는 경기 순간을 블루 톤으로 확보
- **파일명**: scene03_keyvisual.png / scene03_motion.mp4

### 씬3-2 — 타석 (5초)

- **목표 메시지**: 긴장감을 결의로 전환
- **화면 구성**: 타석에 선 타자의 눈빛 클로즈업, 배트를 고쳐 쥐는 손, 푸른 조명
- **내레이션**: "한 번 더, 붙어보자"
- **사용 도구**: 이미지 Midjourney / 비디오 Runway(줌인) / 오디오 Suno(심장박동 비트)
- **입력 프롬프트**:
  ```
  baseball batter eyes close-up under helmet brim, gripping bat tightly, cool blue stadium lighting, shallow depth of field, cinematic
  ```
- **출력 결과 요약**: 결의에 찬 타자의 눈빛을 블루 톤으로 확보
- **파일명**: scene03b_keyvisual.png / scene03b_motion.mp4

### 씬3-3 — 타구 (5초)

- **목표 메시지**: 폭발 직전의 기대감 극대화
- **화면 구성**: 배트에 맞는 순간, 타구가 푸른 밤하늘로 뻗어 나가는 슬로모션, 관중이 일제히 일어서는 실루엣
- **내레이션**: "넘어간다"
- **사용 도구**: 이미지 Midjourney / 비디오 Runway(슬로모션) / 오디오 Suno(비트 정지 후 상승음)
- **입력 프롬프트**:
  ```
  baseball flying high into deep blue night sky above stadium lights, slow motion, crowd silhouettes standing up, cinematic wide shot
  ```
- **출력 결과 요약**: 타구가 하늘로 뻗는 순간을 블루 톤으로 확보
- **파일명**: scene03c_keyvisual.png / scene03c_motion.mp4

### 씬4 — 클라이맥스 (10초)

- **목표 메시지**: 극적인 순간의 폭발적 환호 — 팀의 '기세'가 정점에 달함
- **화면 구성**: 관중석 전체가 폭발하듯 환호하는 와이드샷, 푸른 물결과 응원도구
- **내레이션**: "지금, 기세가 폭발한다"
- **사용 도구**: 이미지 Midjourney / 비디오 Runway / 오디오 Suno(절정 응원가)
- **출력 결과 요약**: 한국 야구 응원 문화가 반영된 폭발적 환호 장면을 블루 톤으로 확보
- **파일명**: scene04_keyvisual.png / scene04_motion.mp4

#### 프롬프트 수정 전/후 기록

- **수정 전 프롬프트**:
  ```
  baseball stadium crowd cheering, home run moment, cinematic
  ```
- **문제점**: 결과물이 일반적인 미국 메이저리그 경기장 느낌으로 나와, 사직구장 특유의 응원 물결과 한국 프로야구 응원 문화가 드러나지 않음
- **수정 후 프롬프트**:
  ```
  Korean baseball stadium at night, blue wave of fan cheering with towels and lightsticks, dynamic crowd energy, explosive celebration moment, cinematic wide shot, cool blue stadium lighting
  ```
- **결과 변화**: 푸른 응원 물결과 한국식 응원 문화(막대풍선, 수건 응원)가 반영되어 '롯데자이언츠다움'이 강하게 표현됨. 클로즈업에서 와이드샷으로 전환하여 관중석 전체 에너지가 부각됨

### 씬5 — 여운 (8초)

- **목표 메시지**: 승패를 넘어선 함께한 시간의 여운
- **화면 구성**: 노을 지는 구장, 손을 맞잡은 팬들의 뒷모습 실루엣, 푸른빛이 도는 노을 톤
- **내레이션**: "이기고 지는 건 잠깐, 함께한 순간은 영원하다"
- **사용 도구**: 이미지 Midjourney / 비디오 Runway / 오디오 Suno(잔잔한 앰비언트로 전환)
- **입력 프롬프트**:
  ```
  silhouette of fans holding hands, sunset over baseball stadium, cool blue and dusk tones, warm nostalgic mood
  ```
- **출력 결과 요약**: 감성적이고 푸른 여운의 장면 확보
- **파일명**: scene05_keyvisual.png / scene05_motion.mp4

### 씬6 — 마무리 (4~5초)

- **목표 메시지**: 가을야구 진출을 향한 각오 전달 + 브랜드 각인
- **화면 구성**: 팀 컬러(블루) 그래픽 위에 카피 등장
- **내레이션**: "아직 끝나지 않았다, 가을야구 가자"
- **사용 도구**: 비디오 CapCut(타이포 모션) / 오디오 Suno(엔딩 스팅어)
- **입력 프롬프트**: (그래픽 모션은 CapCut 텍스트 애니메이션으로 직접 제작)
- **출력 결과 요약**: 가을야구 각오를 담은 슬로건 각인 엔딩 확보
- **파일명**: scene06_ending.mp4

## 6. 대체 도구 (접근 제한 대비)

| 구분 | 대체 도구 |
|---|---|
| 이미지 | Leonardo AI |
| 비디오 | Pika, Kling |
| 오디오 | ElevenLabs, Mubert |
