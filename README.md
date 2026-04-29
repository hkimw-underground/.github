# Hyunwoo Kim Underground 🔬

> 김현우 지하 개발소  
> 본계정 위에서 일하고, 여기 내려와서 논다.

<p align="center">
  <b>AI · FPGA/NPU · WebGPU · 학교 과제가 어쩌다 커진 것들</b><br/>
  <sub>
    main: <a href="https://github.com/hkimw">hkimw</a> /
    sub: <a href="https://github.com/hwkim-dev">hwkim-dev</a>
  </sub>
</p>

<p align="center">
  <a href="#kr">KR</a> ·
  <a href="#en">EN</a> ·
  <a href="#projects">projects</a> ·
  <a href="#syu">syu</a>
</p>

---

<a id="kr"></a>

## KR

이곳은 작업장 🏗️

본계정 [`hkimw`](https://github.com/hkimw)가 정장이라면, 여긴 츄리닝.  
개발자라면 한 번쯤 *"어 이거 만들어볼까?"* 하고 생각만 하다 마는 사이드 프로젝트들을 생각나는 대로 던져두는 낙서장이다.

본계정은 레포가 너무 커져서 신중하게, 좀 *꼰대스럽게* 개발 중...  
AI는 보조 / 리뷰 / UI 정도로만 쓰고 코어는 직접 짜다 보니 *생산성이 느리다...* 진짜 느림.  
HW 개발은 신뢰가 1순위라 무작정 빠른 것보단 정확도가 먼저고 — *그래도* 요즘 같은 시대에 AI랑 제대로 협업하는 서브 레포 하나쯤은 있어도 되지 않을까...?

지금이 26년 4월. AI 대세라던데 나도 좀 신박하게 써서 big project 한번 굴려보고 싶다.  
챗지피티 채찍질해서 코드 짜게 하는 *책질피티* 같은 거? 🐎

> 어차피 만든 것의 절반은 망함.  
> 살아남는 절반이 다음 시즌 캐릭터가 됨.

깔끔하게 정리해서 자랑하는 곳은 아니다. 만들다 만 것, 만들다 커진 것, 본계정에 올리기엔 아직 거친 것들이 굴러다니는 *그런 곳.* 학교 과제로 시작했다가 어쩌다 진짜로 굴러가게 된 케이스도 꽤 있고, 일단 끝까지 밀어보면 신기하게 뭐라도...

---

## 다루는 거 (a.k.a. 스택 자랑하는 척)

- AI / LLM / local inference
- FPGA · NPU · memory bottleneck
- WebGPU, browser compute
- FastAPI 백엔드
- SystemVerilog / C / CUDA 실험
- 보고서형 GitHub 문서화
- 약간 선 넘은 캡스톤
- 본계정 가기 직전 단계의 프로토타입

입장 조건은 하나. `works on my machine` 뱃지가 붙어있어야 함.

---

<a id="projects"></a>

## 지금 굴러가는 것들

### digital-logic-circuit
디지털 집적 회로 과제로 시작한 AI 도어락. 초기 스코프: *간단한 회로 하나*.  
어쩌다 NFC + PIN + 얼굴 인식 + ESP32-CAM + FastAPI까지 들어감.  
스택은 YOLOv8 · ESP32-CAM · Arduino · FastAPI · SQLite. *교수님 죄송합니다.*

### Latest-Research-Trends-in-AI
AI 연구 동향 보고서. PDF 한 장 제출하고 끝내기 아까워서 XeLaTeX, TikZ/PGFPlots, 발표자료까지 묶어둠. 다음 학기에 또 쓸 수 있음. 재활용은 개발자의 미덕.  
근데 논문 발표 전까지는 private으로 둘련다 — 베끼는 도둑놈 있을지도...? ~~요즘 믿을 사람 하나 없음.~~

### Csharp-Socket-Server
오래된 C# 소켓 서버 실험. *Legacy = 동작하면 그게 레거시.* 코드는 안 본다, 안 만진다.

### datastructure_algorithm
C 자료구조 / 알고리즘. 정리는 거칠지만 — 시험 전날 다시 보면 의외로 도움된다. *미래의 나에게 보내는 편지 같은 거.*

---

## 별(★) 얘기

받고 싶다, 솔직히.  
근데 가짜로는 싫음. 누가 보고 *"이거 나중에 써먹겠는데?"* 싶게 만드는 게 훨씬 가치 있다.

작게 만들고 → 빨리 공개하고 → README부터 박고 → 반응 보고 → 살아남는 것만 더 판다.  
반응 좋은 건 본계정 [`hkimw`](https://github.com/hkimw)로 승급. *(그쪽이 1군, 여긴 2군 farm league.)*

---

<a id="syu"></a>

## SYU / 삼육대 학생들에게

일부 프로젝트는 삼육대 학부 과정에서 시작됐다. 컴공 · AI융합 · 임베디드 · 지능형반도체 학생들이 *"내 GitHub 어떻게 정리하지?"* 싶을 때 참고용으로 봐도 됨.

여기 굴러다니는 것 — 캡스톤 README 구조, Issues/Milestones 운영 방식, 보고서형 프로젝트 문서화, FPGA/NPU/LLM 실험 기록, 교수님이 보기 편한 문서 만드는 법, 학생 프로젝트를 포트폴리오처럼 보이게 만드는 법.

내가 졸업하고 나면 누군가 내 레포 그대로 가져다가 캡스톤 내는 사람 있을지도...?  
*내 거 그대로 내면 수상감인데, ^^;*

<details>
<summary>사실은...</summary>

~~그러라고 Apache 2.0 / MIT 라이센스 걸어둠.~~  
가져가서 쓰는 건 자유. 대신 star나 fork 한 번은 눌러주세요ㅠ

</details>

> 본 계정은 삼육대학교 공식 GitHub 조직이 아니다.  
> 김현우 개인이 굴리는 비공식 학생 프로젝트 아카이브.  
> *(공식이 되고 싶은 마음은 좀 있음.)*

---

## links

| role | link |
| --- | --- |
| main | [hkimw](https://github.com/hkimw) |
| sub | [hwkim-dev](https://github.com/hwkim-dev) |
| lab | [hkimw-underground](https://github.com/hkimw-underground) |

---

<p align="center">
  <b>404 polish not found.</b><br/>
  <sub>but the system still works (on my machine).</sub>
</p>

---

<a id="en"></a>

## EN

This is the workshop. 🏗️

If [`hkimw`](https://github.com/hkimw) is in a suit, this account is in sweatpants.  
It's the scratchpad — the place every *"wait, what if I built…"* idea gets dumped before it has a chance to escape.

The main account got too big and a little *boomer* about it.  
AI is allowed in for review and UI work over there, but the core is hand-written, which means *productivity is, uh… slow.* Painfully slow.  
Hardware dev runs on trust — accuracy beats speed every time — but maybe, just maybe, in 2026 there should be one repo where I actually *collaborate* with the AI instead of supervising it like a junior dev.

It's April 2026. Everyone's saying AI is *the thing*, so I want to use it for one big, slightly weird project.  
Something like *ChatGPT-on-a-leash* — except the leash is also ChatGPT. 🐎

> Half of what gets made here will die.  
> The other half graduates upstairs.

Not a clean shelf. Half-done stuff, sideways-grown stuff, stuff not ready for the main account — all of it lives here. Some started as homework. Some was a 2am idea that somehow still runs in the morning. Push hard enough and *something* shows up. Usually.

---

## Stack (the part where I pretend to flex)

- AI / LLM / local inference
- FPGA · NPU · memory bottlenecks
- WebGPU, browser-side compute
- FastAPI backends
- SystemVerilog / C / CUDA experiments
- Report-style GitHub docs
- Coursework that went too far
- Pre-promotion prototypes

Entry requirement: *it has to actually run.*

---

## Current experiments

**digital-logic-circuit** — Started as a digital IC class project. Original scope: *one small circuit*. Now does NFC + PIN + YOLOv8 face recognition + ESP32-CAM streaming + FastAPI + SQLite. Sorry professor.

**Latest-Research-Trends-in-AI** — AI research trend report. Kept the full XeLaTeX / TikZ / presentation chain instead of just turning in the PDF. Reusable next semester. Recycling is a developer virtue.  
Going private until the paper drops though — ~~people will absolutely yoink this.~~

**Csharp-Socket-Server** — Old C# socket experiment. *Legacy = it still runs, don't touch it.*

**datastructure_algorithm** — C data structures and algorithms. Rough notes that quietly save your life right before midterms.

---

## On stars

Yeah, I want them. No, I won't fake them.  
The good kind is when somebody sees something here and thinks *"I'll need this later."*

Build small → ship fast → README first → watch the reaction → keep what survives → promote the strong ones upstairs. *(This account is the farm league. Big leagues live on the main one.)*

---

## For Sahmyook / SYU students

Some of this started as undergraduate work at Sahmyook University. Possibly useful if you're working on capstones, AI reports, GitHub workflows, FPGA/NPU/LLM experiments, or trying to make coursework look more like a portfolio than homework.

Honestly, after I graduate, somebody's probably going to lift one of these and submit it as their own capstone...  
*Which would actually win an award if they did it right. ^^;*

<details>
<summary>(click) the truth is...</summary>

~~That's literally why I put Apache 2.0 / MIT on these.~~  
Take it, fork it, ship it. Just hit the star button on your way out.

</details>

> Unofficial student archive run by Hyunwoo Kim.  
> Not affiliated with or endorsed by Sahmyook University.  
> *(Wouldn't say no to an affiliation though.)*

---

<p align="center">
  <b>Broken ideas. Working systems.</b><br/>
  <sub>built by <a href="https://github.com/hkimw">hkimw</a></sub>
</p>
