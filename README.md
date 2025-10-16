# SCP_EXODUS

# ⚠️ SCP EXODUS: The Emergency Escape Process

<p align="center">
  <img src="https://github.com/user-attachments/assets/ad8d4c69-baa9-48c8-bf69-5d6a1ef872d1" alt="SCP EXODUS Main Menu Banner" width="900"/>
</p>

---
[**▶️ SCP EXODUS: 상세 기획 및 개발 문서 (Notion 이동)**](https://www.notion.so/SPC_EXODUS_MAIN-27ae919330e38018a680c656bb14dda3)

## 🛑 프로젝트 개요: 폭파된 돌연변이 연구기지에서의 신속한 탈출 (Project Overview)

**SCP EXODUS**는 시간 제한과 자원 관리에 초점을 맞춘 **Third-Person Survival Horror (TPS)** 게임입니다. 플레이어는 유독성 안개로 인해 고립된 D-3 연구 시설의 **지하 2층**에서 시작하여, **제한된 자원을** 사용해 옥상의 탈출 지점에 도달해야 합니다.

모든 움직임과 총알 한 발은 생존 시간과 직결되며, 플레이어는 이 모든 상황이 **더 큰 임무(Major Twist)**의 일부였음을 종국에 깨닫게 됩니다.

### 📌 핵심 컨셉

| 항목 | 내용 |
| :--- | :--- |
| **장르** | **Third-Person Survival Horror (Time-Attack)** |
| **목표** |  옥상 헬기장에 도달 및 탈출. |
| **난이도** | 탄약 고갈 및 누적 대미지 기반의 **느린 소모(Attrition)** 공포. |
| **시점** | 3인칭 (TPS) |

---

## 🕹️ 게임플레이 및 시스템 (Gameplay & Systems)

### 몬스터 위협 요소 (Keter Threats)

<table>
  <thead>
    <tr>
      <th>몬스터</th>
      <th>유형</th>
      <th>특징 및 역할</th>
      <th>소모 탄약 (HP 5 DMG 기준)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>**Snork**</td>
      <td>기본형</td>
      <td>플레이어와 유사한 속도로 추격하는 표준 위협. (4발 처치 시 초기 탄창 5개 소모)</td>
      <td>4발 (20 HP)</td>
    </tr>
    <tr>
      <td>**Creep**</td>
      <td>고방어 탱커</td>
      <td>느리지만 처치에 12발(초기 탄창 60%)이 필요한 **자원 게이트** 역할.</td>
      <td>12발 (60 HP)</td>
    </tr>
    <tr>
      <td>**GoreTex**</td>
      <td>고대미지 엘리트</td>
      <td>공격력(30 DMG)이 높아 4대 피격 시 사망. 최우선 제거 대상.</td>
      <td>8발 (40 HP)</td>
    </tr>
  </tbody>
</table>

### 조작 프로토콜 (Controls)

| 기능 | 키 바인딩 | 설명 (SCP 보안 사령부 지침) |
| :--- | :--- | :--- |
| **재장전** | `R` | 표준 재장전 절차. |
| **수류탄** | `G` | 격리 파기 상황에서 다수 개체 처리를 위한 고위험 자원 사용. |
| **체력 회복** | `Q` | 응급 주사(Morphine Syringe) 투여. (Health의 H) |
| **이동** | `WASD` | 격리 구역 내 표준 이동. |

---

## 🚀 개발 정보 및 기술 스택 (Dev & Tech Stack)

* **게임 엔진:** Unreal Engine 5.4
* **개발 기간:** 3 Weeks
* **개발 팀:** 3인 (PM/기획, 수석 프로그래머, 테크니컬 아티스트)
* **주요 기능:** 미디어 플레이어 체인, IK Retargeting, Sound Cue 랜덤 재생 시스템.

### 개발 팀 구성

| 역할 | 담당자 |
| :--- | :--- |
| **수석 프로그래머** (Lead Programmer) | **[박재홍]** |
| **테크니컬 아티스트 / 레벨 디자인** (Tech Artist / Level Designer) | **[유상우]** |
| **프로젝트 매니저 / 기획** (PM / Design) | **[정윤성]** |

---

## 📜 라이선스 및 저작권 고지 (Licensing & Attribution)

**SCP EXODUS**는 SCP 재단 세계관을 기반으로 제작되었습니다. **CC BY-SA 3.0** 라이선스 요구 사항을 준수합니다.

### **저작권 라이선스 선언**
All SCP-related concepts and content are licensed under the **Creative Commons Attribution-ShareAlike 3.0 (CC BY-SA 3.0)** license.

### **출처 표기**
This work is derived from materials found at the **[SCP Foundation Wiki (www.scp-wiki.net)](http://www.scp-wiki.net/)** and its contributors.

### **게임 라이선스**
This game, **SCP EXODUS**, is also released under the **CC BY-SA 3.0** license.

**© 2025 [연세IT미래교육원] All Rights Reserved.**


