<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 054 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 054

### 하나의 기억을 주인공과 서로 다른 여섯 조각으로 나누기

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EF805E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-4AA1AE?style=flat-square)](#)

<a href="README.md">简体中文</a> 선택적 기억 · 주인공 · 여섯 스티커 · 무광 인쇄 · 공기감 있는 파랑

사진을 이야기를 맡는 하나의 주인공과 크기와 위계가 다른 정확히 여섯 개의 기억 스티커로 압축합니다. 무광 과슈, 종이 오리기, 리소그래프와 실크스크린 질감으로 아이콘 목록이 아닌 고요한 독립 출판 수집 페이지를 만듭니다.

## 이 Skill이 필요한 이유

이 스타일은 원본에 의존하며 내용을 바꿔 끼우는 장식 프리셋이 아닙니다. 다음 변환 인과를 따릅니다:

```text
lock identity, silhouette, posture, and relation → preserve three cues → compress into three to six large shapes → build one main visual → select exactly six source-specific fragments → vary sticker scale, angle, overlap, and hierarchy → unify matte gouache and print texture → retain airy blue whitespace → add minimal copy
```

무관한 사진으로 바꿔도 주인공, 여섯 조각, 형태, 위계, 색, 간격과 문구가 실질적으로 달라지지 않는다면 이 Panel의 결과가 아닙니다.

## 시각적 원칙

- 실루엣, 비례, 자세, 동작, 구조, 색, 재료, 관계에서 원본 고유 단서를 세 가지 이상 보존합니다.
- 세 개에서 여섯 개의 큰 형태로 뚜렷한 주인공을 만들고 원본에 근거한 기억 조각을 정확히 여섯 개 고릅니다.
- 여섯 스티커는 크기와 위계를 다르게 하고 비대칭으로 회전, 겹침, 가장자리 이탈을 사용합니다. 목록, 육분할, 같은 크기 아이콘으로 만들지 않습니다.
- 주인공과 스티커를 무광 과슈, 종이 오리기, 리소그래프 또는 실크스크린으로 통일하고 공기감 있는 파랑, 옅은 중성색, 극소량의 탁한 분홍을 사용합니다.
- 크기 대비, 양음형, 겹침, 넓고 고요한 바탕으로 초점을 하나만 유지합니다.

전체 미적 제약과 금지 항목은 Skill과 생성 프롬프트에 있습니다. 원문 미학을 보존하지만 역사적인 3:4 화면을 숨은 기본값으로 만들지 않습니다. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-054-prompt.en.md)

## 예시 · X에서

> [샤오샤오둥（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091539410533691899) · 2026년 8월 23일<br>
> GPT2 × 스티커 × 오래된 감성 × 시각 단서 × 미학 프롬프트 × VOL.054

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091539410533691899"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 054 예시 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091539410533691899"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 054 예시 2"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091539410533691899">원문 게시물과 전체 프롬프트 보기 →</a></p>

이 예시는 054의 미학적 의도를 보여 줄 뿐이며, 예시의 주제, 구성, 색상, 문구, 이전 캔버스 비율은 생성 참고나 현재 기본값이 되지 않습니다.

## 조합 가능한 네 가지 출력

`1`, `1+3`, `1,2,4`, `전체`로 하나 또는 여러 모드를 선택할 수 있으며 `전체`는 원본당 독립 PNG 7개를 만듭니다. 모드 선택 뒤, 생성 전에 완성 이미지 전체의 화면비를 반드시 확인합니다: 원래 프롬프트의 `3:4`, 명시적인 원본 비율, 일반 비율, 사용자 지정 비율／정확한 픽셀입니다. 원본 크기를 묵시적으로 적용하지 않습니다.

| 모드 | 화면비 규칙 | 결과물 |
| --- | --- | --- |
| `top-bottom` | 사용자가 확인한 전체 캔버스 | 완성 캔버스를 한 번에 생성: 위에 고충실도 원본, 아래에 054 디자인, 약 50/50 |
| `left-right` | 사용자가 확인한 전체 캔버스 | 완성 캔버스를 한 번에 생성: 왼쪽에 고충실도 원본, 오른쪽에 054 디자인, 약 50/50 |
| `design-only` | 사용자가 확인한 전체 캔버스 | 054 디자인이 전체를 채우며 원본 사진은 보이지 않음 |
| `wallpaper-pack` | 기기별 확인 | 휴대전화, iPad, 데스크톱, 어린이용 스마트워치 PNG 개별 출력 |

이중 패널 모드는 원본을 고충실도 편집／참조 입력으로 사용하고 완전한 스타일 프롬프트 한 세트로 최종 화면을 직접 생성합니다. 사진, 디자인, 색, 빛, 타이포그래피와 의미가 하나로 이어지게 하기 위해서입니다. 결정적 합성은 전체 캔버스 재시도 후에도 실패한 경우, 원본의 픽셀 완전 보존을 명시한 경우, 현재 경로가 목표 화면비를 만들 수 없는 경우, 또는 무손실 최종 픽셀 조정이 필요한 경우에만 사용합니다.

배경화면은 연결형 또는 독립형입니다. 연결형은 iPad 기준 작품 하나를 승인한 뒤 다른 기기를 원본＋같은 기준 작품에서 각각 재구성합니다. 독립형은 각 기기가 원본만 참조합니다. 어느 쪽도 다른 기기 결과를 자르거나 파생 결과를 연쇄 참조하지 않습니다.

## 문구와 언어

생성 전에 자동 문구, 정확한 사용자 문구, 무문자 중 하나를 확정합니다. 언어는 명령문이 아니라 대상 독자를 따르며 완성 문구는 그대로 유지합니다.

이 프로젝트의 문구 규칙: 주체, 동작, 환경, 감정, 소리, 기억 또는 문화적 맥락에 강하게 묶인 한 단어, 짧은 구절 또는 극히 짧은 제목만 추출해 여백, 스티커 사이, 주인공 가장자리에 작고 가볍게 배치하며 각 스티커에 라벨을 붙이지 않습니다.

## 완성 캔버스 우선과 래스터 경계

이미지 모델이 완성 화면 전체의 미학적 재구성을 담당하며 이중 패널도 완성 캔버스 한 장의 직접 생성을 기본으로 합니다. `scripts/compose_panel.py`는 조건부 복구, 무손실 픽셀 조정, 읽기 전용 검수에만 사용하고 매번 사전 계획하거나 미학적 성공을 판단하지 않습니다.

모든 결과물은 PNG 래스터이며 호출마다 `~/Desktop/xxd/`에 새 작업을 만듭니다. 설정된 이미지 경로는 비식별 상태만 반환하며 제공자, 엔드포인트, 인증 정보, 헤더, 프롬프트, 응답, 계정 정보를 공개하지 않습니다. SVG, HTML, Canvas, 도표와 프로그램 그림은 최종 작품을 대신할 수 없습니다.

## 이미지 모델 우선순위

GPT Image 2를 기본 최우선 모델로 사용합니다. 고충실도 원본 참조, 생성 전 완성 캔버스 확인, 이중 패널의 완성 화면 일괄 생성, 조건이 충족될 때만 사용하는 스크립트 합성이라는 기존 흐름은 그대로 유지합니다.

현재 도구 또는 설정된 경로에서 실제로 사용할 수 있고 원본 충실도, 완성 화면비, 대상 언어의 문자, 연결형 배경화면의 다중 참조 요구를 충족할 때는 Seedance 5.0 Pro, Nano Banana Pro(Gemini Image Pro), Nano Banana 2(Gemini Image Flash) 또는 다른 호환 비트맵 모델도 사용할 수 있습니다. 대체 모델은 생성 경로만 바꾸며 모드, 캔버스, 문구, 언어, 배경화면 관계와 완성 캔버스 우선 전략을 바꾸지 않습니다.

적합한 경로가 없으면 이미지 생성 도구를 활성화하거나 API Key를 제공하도록 사용자에게 요청합니다. 사용자가 제공한 인증 정보는 현재 작업에 사용할 수 있지만 답변이나 로그에 다시 표시·기록·노출하지 않습니다. 사용자가 명시적으로 요청하지 않는 한 장기 저장하거나 제공자, 계정, 결제 또는 전역 경로 설정을 변경하지 않습니다.

## 시작하기

```bash
git clone https://github.com/nevertoday/xxd-panel-054.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-054" ~/.codex/skills/xxd-panel-054
```

Claude Code 사용자는 같은 폴더를 다음 위치에 연결할 수 있습니다: `~/.claude/skills/xxd-panel-054`. 설치 후 에이전트 세션을 다시 시작하세요.

```text
$xxd-panel-054
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

전체 사양: [Skill 워크플로](SKILL.md) · [원본 스타일 자료](references/054-source.md) · [영문 생성 프롬프트](references/xxd-panel-054-prompt.en.md) · [중문 생성 프롬프트](references/xxd-panel-054-prompt.zh-CN.md)

## XXD 소개

XXD는 Xiaoxiaodong 브랜드 이름의 약자입니다. 제작 및 유지관리: [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 지원과 멤버십

### 심층 상담 · 시간당 CNY 299

Skills 사용과 워크플로에 관한 일대일 심층 상담입니다. WeChat으로 Xiaoxiaodong에게 문의하세요. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills 사용자 교류 그룹 · CNY 99

한 번의 결제로 Skills 사용자 교류 그룹에 참여합니다. 시간제 일대일 상담은 별도입니다.

### Knowledge Planet＋회원 프롬프트 라이브러리 · 연 CNY 699

Knowledge Planet과 회원 프롬프트 라이브러리는 하나의 연간 멤버십입니다. 어느 한쪽에서 가입한 뒤 WeChat으로 연락하면 다른 쪽도 열립니다.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>기억은 여섯 아이콘이 아니라 위계가 있는 수집입니다.</strong></div>

---

<div align="center">

## ☕ 오픈 소스 프로젝트 후원

중국어판 이외에는 Buy Me a Coffee를 이용할 수 있습니다. 후원은 선택 사항이며 오픈 소스 접근 권한을 바꾸지 않습니다.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
