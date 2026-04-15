# 💪 운동 기록 PWA

## 기능
- 달력 탭: 운동한 날 점으로 표시, 날짜 클릭 → 오늘 탭으로 이동
- 오늘 탭: 운동 종목 추가 / 세트별 중량·횟수 입력
- 기록 탭: 과거 운동 목록 확인
- 연속 운동일 뱃지 (🔥)
- 총 운동일 / 세트 / 볼륨 통계
- 오프라인 동작 (PWA)
- 데이터는 기기 localStorage에 저장

---

## GitHub Pages 배포 방법 (무료, 5분)

1. **GitHub 레포 생성**
   - github.com 에서 새 레포 만들기 (예: `workout-tracker`)
   - Public으로 설정

2. **파일 업로드**
   ```
   index.html
   manifest.json
   sw.js
   ```
   세 파일 모두 루트에 업로드

3. **Pages 활성화**
   - Settings → Pages → Source: main branch / root
   - Save 누르면 1~2분 후 배포 완료

4. **접속 주소**
   ```
   https://{github아이디}.github.io/workout-tracker/
   ```

5. **폰 홈 화면 추가**
   - Safari(iOS) / Chrome(Android)로 접속
   - 공유 버튼 → "홈 화면에 추가"
   - 아이콘 탭하면 앱처럼 전체화면으로 열림!

---

## 아이콘 추가 (선택)
`icon-192.png`, `icon-512.png` 파일을 같은 폴더에 넣으면 앱 아이콘이 생겨요.
없어도 기본 아이콘으로 동작합니다.
