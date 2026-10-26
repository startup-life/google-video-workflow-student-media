# 구글 서비스만으로 교육 쇼츠 만들기 — 실습용 영상

교재 「구글 서비스만으로 교육 쇼츠 만들기」의 파일 처리·편집 실습에 쓰는 영상입니다. 교재의 1편 예제(프레스 기계의 라이트 커튼)를 만들 때 Google Flow로 생성한 클립과 Google Vids에서 내보낸 완성본입니다. 모두 AI로 생성한 교육용 영상이며 실제 공장 촬영본이 아닙니다.

## 받는 방법

전체를 받으려면 실습 폴더에서 아래 명령을 실행합니다.

```powershell
git clone https://github.com/startup-life/google-video-workflow-student-media.git
```

파일 하나만 받으려면 GitHub에서 파일을 열고 오른쪽 위 **다운로드(Download raw file)** 버튼을 누릅니다.

## 파일 목록

| 파일 | 길이 | 크기(가로×세로) | 용량 | SHA-256 앞 16자 |
|---|---|---|---|---|
| `videos/flow/shot01-place-steel-sheet.mp4` | 10.01초 | 720x1280 | 2.7 MB | `5c44b4bdeaf605cb…` |
| `videos/flow/shot02-repeat-routine.mp4` | 10.01초 | 720x1280 | 3.6 MB | `2578049dc15a1bee…` |
| `videos/flow/shot03-blocked-by-cover.mp4` | 10.01초 | 720x1280 | 4.5 MB | `142dc40fe35005af…` |
| `videos/flow/shot04b-tilt-down-light-curtain.mp4` | 8.00초 | 720x1280 | 1.5 MB | `0a9b7d82eb03bb70…` |
| `videos/flow/shot04-camera-push-press.mp4` | 10.01초 | 720x1280 | 3.4 MB | `6a1ff9964dbaf672…` |
| `videos/flow/shot05-hand-triggers-curtain.mp4` | 8.00초 | 720x1280 | 1.2 MB | `a32636f4b7bb1661…` |
| `videos/flow/shot06-slide-stops.mp4` | 8.00초 | 720x1280 | 1.3 MB | `29cacf59085812b0…` |
| `videos/flow/shot07-measure-distance.mp4` | 10.01초 | 720x1280 | 2.0 MB | `0c0299d0a26638dd…` |
| `videos/flow/shot08-normal-press-operation.mp4` | 10.01초 | 720x1280 | 2.3 MB | `eb5d907a98bb476b…` |
| `videos/flow/shot09-test-light-curtain.mp4` | 10.01초 | 720x1280 | 2.3 MB | `4278a87fb17b72dd…` |
| `videos/flow/shot10-worker-wide-shot.mp4` | 10.01초 | 720x1280 | 3.7 MB | `efc334c214c994a5…` |
| `videos/vids/vids-export.mp4` | 97.59초 | 1080x1920 | 32.2 MB | `fbaf5b0c01dd3cff…` |

- `videos/flow/`: Flow에서 만든 장면 클립 11개입니다. 720×1280, 24fps이며 Flow가 넣은 소리가 있습니다.
- `videos/vids/vids-export.mp4`: 위 클립을 이어 붙여 Google Vids에서 AI 내레이션과 자막을 넣고 **파일 → 다운로드 → MP4 동영상**으로 내려받은 완성본입니다. 1080×1920, 97.59초이며 자막 트랙(21개 구간)이 들어 있습니다.

## 교재에서 쓰는 곳

| 교재 페이지 | 쓰는 파일 | 넣을 위치 |
|---|---|---|
| 4. 확률적 생성 — 검수 이미지 만들기 | `videos/flow/`의 클립 중 한 개 이상(예: `shot05-hand-triggers-curtain.mp4`, `shot06-slide-stops.mp4`) | 실습 폴더의 `media/flow/` |
| 20. Google Vids 5) 클립 끝과 장면 끝 맞추기 | `shot01-place-steel-sheet.mp4`, `shot02-repeat-routine.mp4` | Vids에 **삽입 → 업로드** |
| 20. Google Vids 5) 대안: 미리 이어 붙이기 | `videos/flow/`의 클립 11개 전체 | 작업 폴더의 `media/flow/` |
| 1. Antigravity 10), 20. Google Vids 6) 자막·검수 이미지 만들기 | `videos/vids/vids-export.mp4` | 작업 폴더의 `media/vids-export.mp4` |

교재에 실린 사용 구간(예: `shot05-hand-triggers-curtain.mp4 1.6–7.9초`)은 이 파일들 기준입니다. 직접 생성한 클립을 쓸 때는 파일 이름과 길이를 확인하고 구간을 다시 정합니다.
