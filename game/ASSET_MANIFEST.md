# 에셋 명세 — 창문 달 장면 스틸

- **생성 모델:** Higgsfield GPT Image 2 (`gpt_image_2`), `aspect_ratio 16:9`, `resolution 2k`, `quality high`
- **생성일·호스트:** 2026-08-15, 로컬 Mac (결과는 내려받아 로컬 파일로만 사용, 외부 URL은 HTML에 쓰지 않음)
- **파일 위치:** `game/assets/stills/` (전부 PNG, 2688×1520)
- **공통 톤:** 절제된 다큐멘터리풍 영화 스틸. 저채도 청회색 + 따뜻한 텅스텐 광원, 35mm 감각, 얕은 그레인. 읽을 수 있는 글자·브랜드·로고·워터마크·UI·얼굴 클로즈업 없음. 인물은 얼굴이 보이지 않는 성인 한 명의 뒷모습/손까지만.
- **표시 규칙:** 이미지는 텍스트의 정서를 보조할 뿐 새 사건이나 술래/숨바꼭질 정보를 만들지 않는다. 프롤로그·9턴 기억 지도·10턴 엔딩에는 이미지를 표시하지 않는다.

## 파일과 노드 매핑

| 파일 | 사용 노드(턴) | alt |
|---|---|---|
| `brewery_2008.png` | `1_개입`(1/10), `3_개입`(5/10) | 2008년 공장지대의 작은 양조장 사무실. 쌀 포대와 발효통 곁에 머리에 수건을 두른 사람의 뒷모습 |
| `shared_office_current.png` | `1_현재`(2/10) | 공유 오피스로 리모델링된 옛 양조장 내부. 책상 위에 오래된 라벨 서류철이 놓여 있다 |
| `phone_and_vat.png` | `2_개입`(3/10), `2_현재`(4/10) | 밤의 양조장. 발효통 옆, 어두운 휴대폰 위에 쌀가루 묻은 손이 멈춰 있다 |
| `redevelopment_alley.png` | `3_현재`(6/10) | 푸른 저녁의 공장 골목. 셔터가 반쯤 내려진 작은 양조장과 빈 게시판 |
| `bathhouse_moon.png` | `4_개입`(7/10) | 폐업한 목욕탕 내부. 파란 타일과 높은 창, 빈 탕 바닥에 고인 달빛과 발효 설비 |
| `letter_bottle_night.png` | `4_현재`(8/10) | 밤의 현관 문턱. 등기 봉투와 막걸리 한 병, 희미하게 빛나는 휴대폰 |

이미지 없음: `프롤로그`, `기억지도`(9/10), `엔딩`(10/10).

## 생성 프롬프트 (영어 원문)

### brewery_2008
> Photorealistic cinematic still, South Korea in 2008, a tiny handmade makgeolli brewery at the edge of an industrial district, viewed from a cramped office doorway. Three off-white rice sacks, stainless fermentation vats, fresh unlabeled printing proofs on a metal desk, a young adult worker seen only from the side and back with a white towel around the head, hands dusted with rice flour. Small square window, warm tungsten lamp mixed with cold overcast daylight, muted blue gray palette, 35mm documentary film still, subtle grain, no readable text, no logos, no watermark.

### shared_office_current
> Photorealistic cinematic still of a former small industrial brewery renovated into a quiet contemporary shared office in Seoul. Frosted glass partitions, muted HVAC vents, pale daylight, empty desk with an old paper folder containing abstract circular moon label artwork, a worn stair railing in the background. No people, no readable text, no logos, restrained blue gray and warm beige palette, 35mm film still, subtle grain.

### phone_and_vat
> Photorealistic intimate cinematic still inside a small Korean makgeolli brewery at night. A young adult worker's flour-dusted hand with a faint old steam burn pauses above a dark smartphone beside a stainless fermentation vat; condensation, thermometer paper without legible writing, gentle steam, a white towel visible at the edge of frame. Face not visible, no screen UI, no readable text, no logos, 35mm film still, low tungsten light and cool blue shadows.

### redevelopment_alley
> Photorealistic cinematic still of a narrow Korean industrial neighborhood at blue hour. A tiny brewery storefront behind a partly lowered shutter, weathered concrete, steam vent, a scratched metal stair railing, a blank paper notice on a bulletin board with no readable text. No people, no logos, damp street, low saturation, 35mm documentary film still, subtle grain.

### bathhouse_moon
> Photorealistic cinematic still of an abandoned Korean neighborhood bathhouse being imagined as a small makgeolli brewery. Cracked cobalt-blue tiles, tall ceiling, a small high square window, moonlight reflected across an empty tiled basin, soft steam rising around stainless brewing vessels. No people, no text, no logos, muted blue and warm tungsten accents, 35mm film still, subtle grain.

### letter_bottle_night
> Photorealistic cinematic still in a dim apartment entryway at night. A blank cream registered-letter envelope lies at a door threshold beside one translucent makgeolli bottle with a simple abstract moon mark but no readable label, and a smartphone emitting a soft unreadable message glow. No person, no readable text, no logos, hard streetlamp light with warm indoor spill, restrained 35mm film still, subtle grain.
