# 🧱 Minimal Impact Tetris

**Minimal Impact Tetris**는  
불필요한 요소를 제거한 **미니멀한 비주얼**과  
라인 제거 시의 **명확한 타격감(Impact)**에 집중한  
브라우저 기반 테트리스 게임입니다.

HTML5 Canvas와 순수 JavaScript로 구현되었으며,  
게임의 핵심 감각인 **조작 반응성 · 충돌 안정성 · 리듬감**을 중점적으로 설계했습니다.

---

## 🎮 Game Style & Design Philosophy

### 🎨 Visual Style — Minimal & Neutral
- 전체 배경은 **화이트**
- 블록은 **그레이 스케일**
- 색상 대비를 최소화하여 **형태와 움직임에 집중**
- UI 요소를 최소화해 **게임 플레이 자체가 시각적 중심**

> “보여주기 위한 그래픽이 아닌, 플레이를 방해하지 않는 그래픽”

---

### 💥 Game Feel — Clear Impact
- 라인 제거 시 **4px 화면 흔들림**
- 과하지 않은 짧은 흔들림으로
  - 라인이 사라졌음을 즉각 인지
  - 플레이 리듬 유지
- 시각적 효과를 **게임 피드백 수단**으로 활용

---

### 🧠 Control Design — Stable & Forgiving
- **사전 충돌 검사 이동 방식**
  - 벽 흡착 현상 제거
- **Wall Kick 회전 보정**
  - 벽 근처에서도 자연스러운 회전
- 빠른 입력, 연속 조작에서도
  **예측 가능한 결과**를 유지

> “실수는 플레이어의 선택이어야지, 시스템의 오류여서는 안 된다”

---

### ⚡ Game Pace — Score-driven Speed
- 점수 기반 난이도 상승
  - 라인 1개 제거 → +10점
  - 50점마다 낙하 속도 증가
- 500점에서 최대 속도 도달
- 무한 가속이 아닌 **명확한 상한선**
  → 긴 플레이에서도 피로도 최소화

---

## ⌨️ Controls

| Key | Action |
|---|---|
| ← / → | Move left / right |
| ↓ | Soft drop |
| ↑ | Rotate (Wall Kick 적용) |
| Space | Hard drop |

---

## ✨ Features

- 🧱 Classic Tetris core mechanics
- 🎨 White background & grayscale blocks
- 🧠 Wall Kick rotation system
- ⚡ Hard Drop / Soft Drop
- 🧮 Score-based difficulty scaling
- 💥 Screen shake impact effect
- 🕹️ Keyboard-only, no mouse required

---

## 🛠 Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- Canvas API

> 외부 라이브러리 없이 구현

---

## 📁 Project Structure

