<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,40:0a1628,100:00d2ff&height=220&section=header&text=rupusu-sudo&fontColor=00d2ff&fontSize=60&fontAlignY=36&desc=Automation%20Engineer%20%7C%20Control%20Systems%20%7C%20Craiova%2C%20RO&descAlignY=58&descSize=15&descColor=8b949e&animation=fadeIn" width="100%"/>

<div align="right">

[![Visitors](https://komarev.com/ghpvc/?username=rupusu-sudo&color=00d2ff&style=flat-square&label=visitors)](https://github.com/rupusu-sudo)
![Status](https://img.shields.io/badge/status-building-00d2ff?style=flat-square)

</div>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&pause=1100&color=00D2FF&center=true&vCenter=true&width=750&lines=Automation+%26+Applied+Informatics+%E2%86%92+UCv+Craiova;Industrial+Robots+%7C+Conveyor+Systems+%7C+PLC+Logic;PID+Controllers+%7C+LabWindows%2FCVI+%7C+MATLAB;React+%7C+Node.js+%7C+Full-Stack+Web+Engineering;Code.+Optimize.+Repeat." alt="Typing SVG" />


<table>
<tr>
<td valign="top" width="52%">

## `~/whoami`

```bash
$ cat engineer.yaml
```

```yaml
name      : Ionut-Marian (ruppz)
alias     : rupusu-sudo
role      : Automation Engineering Student
uni       : Universitatea din Craiova
faculty   : Automatică, Calculatoare și Electronică
location  : Craiova, România 🇷🇴

interests :
  - Industrial Robots & Conveyor Automation
  - PID Control & Process Engineering
  - HMI / SCADA Interface Design
  - Full-Stack Web Development
  - Public Sector Digitalization

currently : 2 active projects in development
motto     : "Code. Optimize. Repeat."
```

</td>
<td valign="top" width="48%">

## `~/stack`

**⚙️ Control & Industrial**

![MATLAB](https://img.shields.io/badge/MATLAB-EF7C00?style=flat-square&logo=mathworks&logoColor=white)
![LabWindows](https://img.shields.io/badge/LabWindows%2FCVI-FFD700?style=flat-square&logo=ni&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**🌐 Web Engineering**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**🔧 Tools & Scripting**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</td>
</tr>
</table>

---

## `~/robotics` — how it works

```
  CONVEYOR SORTING SYSTEM — AUTOMATED PIPELINE
  ─────────────────────────────────────────────────────────────────────

   FEED        DETECTION          DECISION           ACTUATION
   ZONE          ZONE               ZONE               ZONE

  [====]──▶  ──[📷 CAM]──  ──[🧠 PLC/MCU]──  ──[🦾 ROBOT ARM]──▶ [BIN A]
  [====]         │                  │                  │
  [====]    vision / sensor    classify object    pick & place    ──▶ [BIN B]
  [====]         │                  │                  │
  ════════════◎══╧══════════════════╧══════════════════╧══════════════▶
              ▲                                                   ──▶ [BIN C]
         encoder /
         speed ctrl

  Every object on the belt is detected → classified → sorted in <200ms.
  The PID loop controls belt speed. The robot arm gets XYZ coordinates
  from the vision system. No object passes unsorted.
```

---

## `~/projects`

<table>
<tr>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/PROJECT_01-IN_DEV-00d2ff?style=for-the-badge&labelColor=0d1117"/>

### ⚙️ PID Control Interface
**LabWindows/CVI + MATLAB**

Real-time graphical interface for PID tuning and process visualization — the kind of system that would sit behind a conveyor belt's speed controller or a robotic arm's motion loop.

```
setpoint ──▶ [ Σ ] ──▶ [  PID  ] ──▶ plant
                ▲                       │
                └──────── feedback ◀────┘

 Kp=1.20  Ki=0.45  Kd=0.08   [TUNING]
 ─────────────────────────────────────
 Error:  0.03   Output: 72.4%   ● LIVE
```

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-EF7C00?style=flat-square&logo=mathworks&logoColor=white)
![LabWindows](https://img.shields.io/badge/LabWindows/CVI-FFD700?style=flat-square)

</td>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/PROJECT_02-IN_DEV-00d2ff?style=for-the-badge&labelColor=0d1117"/>

### 🏛️ Portal Digital Primărie
**React + Node.js**

Full-stack web platform to digitalize and automate internal workflows in public institutions — same systems-thinking behind industrial automation, applied to public services.

```
citizen ──▶ portal ──▶ request engine
               │              │
         role-based     document store
           auth ▼              │
         admin panel ◀── workflow engine

  Roles: citizen / admin / superadmin
  Status tracking · Audit trail · Notify
```

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</td>
</tr>
</table>

---

## `~/stats`

<div align="center">

<img height="155" src="https://github-readme-stats.vercel.app/api?username=rupusu-sudo&show_icons=true&theme=github_dark&hide_border=true&title_color=00d2ff&icon_color=00d2ff&text_color=ffffff&bg_color=0d1117&rank_icon=github&include_all_commits=true&count_private=true"/>
&nbsp;
<img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rupusu-sudo&layout=compact&theme=github_dark&hide_border=true&title_color=00d2ff&text_color=ffffff&bg_color=0d1117&langs_count=7"/>

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=rupusu-sudo&theme=github-dark-blue&hide_border=true&stroke=0d1117&ring=00d2ff&fire=00d2ff&currStreakLabel=00d2ff&sideLabels=ffffff&currStreakNum=ffffff&sideNums=ffffff&dates=8b949e" width="58%"/>

</div>

---

## `~/roadmap`

```
  2024 ──────────────────────────────────────────────────── 2026+

  ██ C / C++                    ░░ STM32 / Embedded Systems
  ██ MATLAB & Control Theory    ░░ PLC Programming (IEC 61131-3)
  ██ React · Node.js · Web      ░░ SCADA / HMI Systems
  ██ Git · Linux                ░░ Industrial Fieldbus (Modbus/CAN)
  ▓▓ PID Interface (LW / CVI)   ░░ Robot Kinematics & Path Planning
  ▓▓ Primărie Web Platform      ░░ Computer Vision (sorting systems)
  ░░ ROS2 (Robot OS)            ░░ Real industrial automation project

  ██ done   ▓▓ in progress   ░░ next target
```

---

## `~/connect`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ionut--marian--falcoi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ionut-marian-falcoi-303510331)
[![Instagram](https://img.shields.io/badge/Instagram-ruppz1-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/ruppz1)
[![Reddit](https://img.shields.io/badge/Reddit-ruppz1337-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://reddit.com/user/ruppz1337)

<br/>

*Open to collabs, automation projects & engineering conversations.*

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d2ff,50:0a1628,100:0d0d0d&height=130&section=footer" width="100%"/>
