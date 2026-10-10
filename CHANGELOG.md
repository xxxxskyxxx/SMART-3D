# Changelog

## v1.1 — 2026-10

### English
- **Animation** — timeline, ● REC auto key, ＋ Key (K), Space to play, keys for move · rotate · scale · object/modifier parameters · cameras, Smooth/Linear/Ease/Step interpolation, box-select / move (Alt copy) / delete keys, RAM preview
- **Export** — video (MP4/WebM), PNG sequence (.zip), GLB transform animation
- **Unified AI Render** — [Image | Video] × [Google | Higgsfield API | Higgsfield Login], Google Veo video, Higgsfield account login (plan credits, exe only), automatic model lists and options, animation capture as first/last frame and reference clip, continue from the last frame
- **Copy options** — after Shift+drag: “Fill between / More at same spacing” with a count
- **Help** — Help ▸ Feature guide (with pictures), separate HTML help
- **Windows executable** — SMART3D.exe that runs without installation (Korean / English)
- **Speed Attach** (View menu) — splines become one Modify Spline, 3D objects one Modify Poly
- **Modify Poly modifier** — works on closed splines (Selection ▸ auto-connect points)
- **Projection Spline** — points at spline-to-spline crossings + Delete (inside · outside / A · B pieces); corner-point Weld when projecting onto 3D (no new points on edges)
- **Import / Export windows** — File ▸ Import… / Export… pick a format in one window (several files sorted automatically), **PLY** import · export added
- **Pattern ▸ Surface tiling** — plane · cylinder (+ caps) · sphere · box surfaces divided into same-size triangle · quad (uniform / zig-zag) · hexagon cells, each filled with a panel or the picked object (ratio kept)
- Pattern **Conform to quad corners** — on quad faces / quad cells the pattern corners sit on the corners (no gaps); fixed missing cells on spheres
- AI Render — newer Google image models such as **Nano Banana 2.1** (gemini-nano-banana-2.1) appear in the list automatically; the newest is the default; a newly opened window starts clean (capture · results · history · references · extra notes reset, settings kept)
- **Quad Align** — while re-picking polygons, faces of other Selects show 50% red with their Select number, the current Select orange with its number; the same source can be picked again for another Select
- **FloorGen** — works on closed splines (outline = floor)
- Lathe modifier removed from the menus (old scenes still open)
- Camera create — the tool ends after one camera; switching to Geometry / Shapes or another panel cancels it
- **On Surface** modifier — lay an object onto a picked surface along X / Y / Z or the surface normal: All points · Keep volume · Select only with Falloff, Edge Blend
- **R Clone** modifier — radial copies around X / Y / Z (pivot or a picked object), count, angle, radius, Weld
- **Add Objects** (Create ▸ Geometry) — keep your own objects in a list; drag in the view to size them (100% = original), click or right-click = 100%
- Create: Shift = square (Box · Plane · Rectangle, cube on the Box height) / flat side down (NGon) · Ctrl = turn toward the mouse (Angle Snap steps)
- Object name shown on mouse hover
- Selection Lock moved to Shift+Space

### 한국어
- **애니메이션** — 타임라인, ● REC 자동 키, ＋ Key(K), Space 재생, 이동·회전·크기·물체/모디파이어 파라미터·카메라 키, Smooth/Linear/Ease/Step 보간, 키 드래그 다중 선택·이동(Alt 복사)·Delete, RAM 미리보기
- **내보내기** — 영상(MP4/WebM), PNG 시퀀스(.zip), GLB 트랜스폼 애니메이션
- **AI Render 통합** — [이미지 | 영상] × [Google | Higgsfield API | Higgsfield 로그인], Google Veo 영상, Higgsfield 계정 로그인(구독 크레딧, exe 전용), 모델 목록·옵션 자동 로드, 애니메이션 캡처를 첫·끝 프레임과 참고 영상으로 사용, 끝 프레임으로 이어 만들기
- **복사 옵션** — Shift+드래그 후 “사이에 채우기 / 같은 간격으로 더” 개수 지정
- **도움말** — Help ▸ 기능 가이드 (그림 도움말), 별도 HTML 도움말
- **Windows 실행 파일** — 설치 없이 실행되는 SMART3D.exe (한국어 / English)
- **Speed Attach** (View 메뉴) — 스플라인들은 하나의 Modify Spline, 3D 물체들은 하나의 Modify Poly로
- **Modify Poly 모디파이어** — 닫힌 스플라인에 적용 가능 (Selection ▸ 점 자동 연결)
- **Projection Spline** — 스플라인끼리 교차점에 점 만들기 + Delete(안쪽·바깥쪽 / A·B쪽 조각 지우기), 3D 투영 시 모서리 점 Weld(엣지 위 새 점 없음)
- **가져오기 · 내보내기 창** — File ▸ Import… / Export… 하나의 창에서 형식 선택(여러 파일 자동 인식), **PLY** 가져오기·내보내기 추가
- **Pattern ▸ 표면 타일링** — 평면 · 원기둥(+뚜껑) · 구 · 박스 표면을 같은 크기의 삼각 · 사각(균일/지그재그) · 육각 셀로 나눠 패널 또는 Pick한 물체를 비율 유지로 배치
- Pattern **4각 모서리에 맞춤** — 사각 면 · 사각 셀에서 패턴의 모서리를 꼭짓점에 맞춰 빈틈 없이 배치, 구 표면의 빈 셀 문제 수정
- AI Render — Google의 **Nano Banana 2.1**(gemini-nano-banana-2.1) 등 새 이미지 모델이 목록에 자동으로 보이고 가장 새 버전을 기본으로 선택, 창을 새로 열면 이전 작업(캡처 · 결과 · 기록 · 참고 이미지 · 추가 지시)이 리셋 — 설정은 유지
- **Quad Align** — 폴리곤 다시 고를 때 다른 Select의 면은 50% 빨강 + Select 번호, 지금 Select는 주황 + 번호 / 같은 소스를 다른 Select에 다시 Pick 가능
- **FloorGen** — 닫힌 스플라인에도 적용 (윤곽 = 바닥)
- Lathe 모디파이어 메뉴에서 제거 (예전 장면은 그대로 열림)
- Camera 만들기 — 하나 만들면 도구가 끝나고, Geometry/Shapes나 다른 패널로 가면 자동 취소
- **On Surface** 모디파이어 — 고른 표면에 X/Y/Z 또는 표면 노말 방향으로 붙이기: 모든 점 · 부피 유지 · 선택 영역만(Falloff), Edge Blend
- **R Clone** 모디파이어 — X/Y/Z 축(Pivot 또는 고른 물체) 기준 회전 복사, 개수 · 각도 · 반지름 · Weld
- **Add Objects** (Create ▸ Geometry) — 내 물체를 목록에 모아 두고 뷰에서 드래그로 크기 조절(100% = 원래 크기), 클릭·우클릭 = 100%
- Create: Shift = 정사각(Box·Plane·Rectangle, Box 높이에서 정육면체) / 평평한 면이 아래(NGon) · Ctrl = 마우스 방향으로 회전(Angle Snap 단위)
- 물체 위에 마우스를 올리면 이름 표시
- Selection Lock 단축키가 Shift+Space로 바뀜

## v1.0
- 첫 공개 버전 / First public version
