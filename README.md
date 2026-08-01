<div align="center">

<img src="assets/header.svg" alt="Aryan Mashalkar" width="100%">

<br>

[![GitHub](https://img.shields.io/badge/github-AryanMashalkar-0D1117?style=flat-square&logo=github&logoColor=C9D1D9&labelColor=0D1117)](https://github.com/AryanMashalkar)
[![Focus](https://img.shields.io/badge/focus-AI_agents_%26_applied_ML-56D4DD?style=flat-square&labelColor=0D1117)](#selected-work)
[![Open to](https://img.shields.io/badge/open_to-collaboration-3FB950?style=flat-square&labelColor=0D1117)](#selected-work)

</div>

---

### About

I like problems where the hard part isn't the model — it's everything around it.
Concurrency, state that survives a restart, and the edge case that only shows up
once you point the thing at a real user.

Most of what I build ends up with a test suite, because that's usually where I
find out I was wrong.

```python
stack = {
    "languages":  ["Python", "TypeScript", "C#", "JavaScript"],
    "working_on": "agents that talk to real people on real channels",
    "learning":   "distributed systems, evaluation harnesses",
    "principle":  "if the demo is mocked, it isn't done",
}
```

---

### Selected work

<table>
<tr>
<td width="50%" valign="top">

#### [Quorum](https://github.com/AryanMashalkar/quorum-consensus-broker)
`Python` · `caspian-sdk` · `Gemini`

An agent that settles group decisions **without a group chat**. It runs a
separate private negotiation with each person on the channel they already use —
email, Telegram — behind one handler.

When no option is unanimous it doesn't report a tie: it goes back to *only* the
person blocking, or promotes someone's counter-proposal and re-opens it.

</td>
<td width="50%" valign="top">

#### [SKIN_AI](https://github.com/AryanMashalkar/SKIN_AI)
`TypeScript` · `MediaPipe` · `CIELAB`

Skin analysis and personal-colour web app — 11 dermatological scores from one
selfie.

sRGB → CIELAB colour engine with a 12-season classifier and a
FaceLandmarker pipeline. CI is gated on model accuracy, so a regression can't
merge.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Wellbore Geology Prediction](https://github.com/AryanMashalkar/wellbore-geology-prediction)
`Python` · `optimisation`

Automated geosteering for the ROGII Kaggle competition. Sparse weighted
least-squares structural inversion plus gamma-ray path refinement.

Pooled RMSE **15.88 → 12.47 (−21.5%)** across 773 wells.

</td>
<td width="50%" valign="top">

#### [PTCG Battle Agent](https://github.com/AryanMashalkar/ptcg-battle-agent)
`Python` · `search` · `MCTS`

A Pokémon TCG rules engine and agent ladder over a 1,267-card pool.

Beam search over turn plans with root determinization and UCB1, an Elo
evaluation harness, and 114 pytest tests holding the rules engine honest.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Gym Coach API](https://github.com/AryanMashalkar/gym-coach-api)
`C#` · `ASP.NET Core 8` · `EF Core`

Layered Web API with JWT refresh-token rotation and RFC 7807 error middleware.

44 xUnit tests running in CI against a live SQL Server container — not a mock.

</td>
<td width="50%" valign="top">

#### [Daily Puzzle Logic Game](https://github.com/AryanMashalkar/daily-puzzle-logic-game)
`JavaScript`

A daily logic puzzle with streak tracking and a heatmap of your history.

Small, but the kind of thing people actually come back to.

</td>
</tr>
</table>

---

### Toolbox

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=0D1117)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white&labelColor=0D1117)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white&labelColor=0D1117)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black&labelColor=0D1117)
<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white&labelColor=0D1117)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white&labelColor=0D1117)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white&labelColor=0D1117)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white&labelColor=0D1117)
<br>
![ASP.NET](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white&labelColor=0D1117)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black&labelColor=0D1117)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white&labelColor=0D1117)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white&labelColor=0D1117)
<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white&labelColor=0D1117)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white&labelColor=0D1117)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white&labelColor=0D1117)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white&labelColor=0D1117)

</div>

---

### Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=AryanMashalkar&show_icons=true&hide_border=true&bg_color=0D1117&title_color=56D4DD&text_color=C9D1D9&icon_color=58A6FF&include_all_commits=true&rank_icon=github" alt="GitHub stats">
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AryanMashalkar&layout=compact&hide_border=true&bg_color=0D1117&title_color=56D4DD&text_color=C9D1D9&langs_count=8" alt="Top languages">

<br><br>

<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=AryanMashalkar&hide_border=true&background=0D1117&stroke=1A222C&ring=56D4DD&fire=58A6FF&currStreakLabel=C9D1D9&sideLabels=8B949E&dates=6E7681&currStreakNum=E6EDF3&sideNums=E6EDF3" alt="Streak">

</div>

---

<div align="center">
<sub>Currently building agents that can reach anyone.</sub>
</div>
