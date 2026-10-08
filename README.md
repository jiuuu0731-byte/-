# 지유의 고양이 퍼즐 🐾

설치나 빌드가 필요 없는 HTML/CSS/JavaScript 게임입니다. `index.html`을 열면 바로 플레이할 수 있습니다.

## 게임 규칙

- 1~5단계, 단계마다 10판: 총 50판
- 단계별 조각 수: 4, 9, 16, 25, 36개
- 한 판당 120초. 두 조각을 선택하면 서로 자리를 바꿉니다.
- 10판 성공 시 다음 단계가 열립니다. 시간 초과 시 같은 판을 재도전합니다.
- 완료 기록은 현재 브라우저에 저장됩니다. 기기 간 동기화는 없습니다.
- 완료한 단계는 다시 플레이할 수 있습니다. 직접 사진을 넣으면 현재 창에서 적용됩니다.
- 기본 사진 한 장을 사용하며 매 판 조각 순서를 새로 섞습니다.

## GitHub에 올리기

1. GitHub에서 새 저장소를 만듭니다. 예: `jiyu-cat-puzzle`.
2. **uploading an existing file** 또는 **Add file → Upload files**를 선택합니다.
3. 이 폴더 안의 `index.html`, `style.css`, `game.js`, `vercel.json`, `README.md`, `assets` 폴더를 업로드합니다. 폴더 자체를 한 단계 감싸서 올리지 말고 `index.html`이 저장소 맨 위에 있도록 합니다.
4. **Commit changes**로 저장합니다.

## Vercel에 게시하기

1. Vercel에서 **Add New → Project**를 선택합니다.
2. GitHub를 연결한 뒤 해당 저장소를 **Import**합니다.
3. Framework Preset은 **Other**, Root Directory는 저장소 루트를 사용합니다.
4. Build Command와 Install Command는 비워 둡니다. Output Directory는 `.`으로 설정합니다.
5. **Deploy**를 누릅니다. 이후 GitHub에서 변경하면 연결된 프로젝트가 자동 배포됩니다.

## 사진 출처

기본 사진: [PhilCreates — Cat sleeping on bed](https://unsplash.com/photos/cat-sleeping-on-bed-pdALzg0yN-8), [Unsplash License](https://unsplash.com/license). 로컬 파일 `assets/cat.jpg`로 포함했습니다. 사진을 바꾸려면 해당 파일을 자신의 고양이 사진으로 교체하면 됩니다.

사용자가 제안한 Bing 썸네일 대신 공개 사용 라이선스를 확인할 수 있는 Unsplash 사진을 사용했습니다. 별도의 서버, API 키, 환경 변수는 필요하지 않습니다.
