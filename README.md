# pro-kit-packs

[프로킷(pro-kit)](https://github.com/roadkwon-ai/pro-kit)의 프리셋 팩을 올려 두는 저장소예요. 프리셋 팩은 프리셋을 만들 때 쓴 글, 예시 데이터, 그림, 페이지별 스크린샷을 zip 하나로 묶은 거예요. 팩 파일은 git에 넣지 않고 팩마다 릴리스 `pack-<이름>`에 `<이름>-pack.zip` 하나로 첨부해요.

## 받기

pro-kit 폴더에서 이렇게 받아요.

```bash
node scripts/pack.mjs <이름>
```

pro-kit의 `tutorials/packs.json`에 적힌 주소에서 zip을 받아 sha256을 확인한 뒤 `packs/<이름>/`에 풀어요. 직접 받으려면 아래 표의 릴리스에서 zip을 내려받으면 돼요.

## 팩 목록

| 이름 | 프리셋 | 릴리스 | 크기 |
|---|---|---|---|
| `nextflix` | [넷플릭스 같은 영상 구독 서비스 (튜토리얼)](https://github.com/roadkwon-ai/pro-kit/blob/main/tutorials/01-nextflix/README.md) | [pack-nextflix](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-nextflix) | 7.2MB |
| `claudle` | [Claude 같은 AI 대화 서비스 (튜토리얼)](https://github.com/roadkwon-ai/pro-kit/blob/main/tutorials/02-claudle/README.md) | [pack-claudle](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-claudle) | 1.0MB |
| `goru` | [고루](https://roadkwon-ai.github.io/pro-kit/goru/) | [pack-goru](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-goru) | 2.9MB |
| `ullim` | [울림](https://roadkwon-ai.github.io/pro-kit/ullim/) | [pack-ullim](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-ullim) | 11.3MB |
| `studyday` | [하루공부](https://roadkwon-ai.github.io/pro-kit/studyday/) | [pack-studyday](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-studyday) | 3.6MB |
| `afterglow` | [AFTERGLOW](https://roadkwon-ai.github.io/pro-kit/afterglow/) | [pack-afterglow](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-afterglow) | 21.5MB |
| `fitslot` | [핏슬롯](https://roadkwon-ai.github.io/pro-kit/fitslot/) | [pack-fitslot](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-fitslot) | 10.6MB |
| `jecheol` | [제철상자](https://roadkwon-ai.github.io/pro-kit/jecheol/) | [pack-jecheol](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-jecheol) | 18.2MB |
| `pacecrew` | [PACECREW](https://roadkwon-ai.github.io/pro-kit/pacecrew/) | [pack-pacecrew](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-pacecrew) | 16.6MB |
| `uptrail` | [Uptrail](https://roadkwon-ai.github.io/pro-kit/uptrail/) | [pack-uptrail](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-uptrail) | 3.2MB |
| `olgot` | [올곧](https://roadkwon-ai.github.io/pro-kit/olgot/) | [pack-olgot](https://github.com/roadkwon-ai/pro-kit-packs/releases/tag/pack-olgot) | 29.9MB |

프리셋은 [프로킷 사이트](https://prokit-web.vercel.app/)에서 볼 수 있어요. 팩마다 릴리스는 최신판 하나뿐이고, 팩을 바꾸면 같은 이름으로 다시 올려요. 올리는 절차는 pro-kit의 `AGENTS.md`에 있어요.
