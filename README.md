
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=500&lines=NURI+OKUMU%C5%9E;Software+Engineer;Freelancer+%7C+Builder" alt="Typing SVG" />
  <br>
  <sub>Mobile · DevOps · Cloud</sub>
  <br><br>

  <a href="https://nuriokumus.netlify.app/" target="_blank"><img src="https://img.shields.io/badge/-Portfolio-FF5722?style=flat-square&logo=google-chrome&logoColor=white"></a>
  <a href="https://linkedin.com/in/nuri-okumus"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://bionluk.com/nuriokumus"><img src="https://img.shields.io/badge/-Hire_Me-1abc9c?style=flat-square&logo=freelancer&logoColor=white"></a>
  <a href="mailto:nuriokmus@gmail.com"><img src="https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <img src="https://komarev.com/ghpvc/?username=NuriOkumus&style=flat-square&color=blueviolet" alt="Profile Views">

  <br><br>

  <img src="https://streak-stats.demolab.com?user=NuriOkumus&theme=tokyonight&hide_border=true" />


</div>

---

### 🐳 Dockerfile

```dockerfile
FROM human:latest

LABEL maintainer="nuriokmus@gmail.com"
LABEL version="22.0"

WORKDIR /turkey/mugla

RUN apt-get install -y \
    flutter dart swift \
    kubernetes docker argocd \
    nodejs python git

COPY ./ideas    /app/
COPY ./skills   /app/
COPY ./projects /app/

ENV ROLE="Software Engineering Student @ MSKÜ" \
    INTERNSHIP="iOS Developer @ Teknasyon"     \
    DAILY_DRIVER="Linux"                       \
    OPEN_TO_WORK="true"

EXPOSE 4040

CMD ["nuri", "--ship-it", "--then-improve-it"]
```

<details>
<summary><h3><kbd>&nbsp;&nbsp;&nbsp;▶ &nbsp; docker run nuri:latest &nbsp;&nbsp;&nbsp;</kbd></h3></summary>
<br>

| | |
|---|---|
| 👤 **Name** | Nuri Okumuş |
| 📍 **Location** | Muğla, Turkey |
| 🎓 **Role** | Software Engineering Student @ MSKÜ |
| 💼 **Internship** | iOS Developer @ Teknasyon |
| 🔨 **Building** | IDP — K3s + ArgoCD |
| 🐧 **Daily Driver** | Linux |
| 💬 **Motto** | "Ship it, then improve it." |

</details>

---

### ☸️ kubectl describe

```
$ kubectl describe pod nuri-okumus
──────────────────────────────────────────────
Name:         nuri-okumus
Namespace:    software-engineering
Node:         mugla / turkey
Status:       Running ✅

Labels:
  role=mobile+devops+cloud
  internship=iOS@Teknasyon
  available-for=freelance

Containers:
  developer:
    Image:    nuri:latest
    Port:     open-to-opportunities

    Skills:
      📱 Mobile Apps   ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░  90%
      🐳 DevOps        ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░░  80%
      🔧 Backend       ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░░░░░  70%
      🤖 AI            ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░░░░░░  65%

    Limits:
      creativity: unlimited
      coffee:     ∞

Events:
  Currently building → IDP (K3s + ArgoCD + Docker)
  Motto            → "Ship it, then improve it."
──────────────────────────────────────────────
```

<details>
<summary><h3><kbd>&nbsp;&nbsp;&nbsp;▶ &nbsp; kubectl get pod nuri-okumus -o wide &nbsp;&nbsp;&nbsp;</kbd></h3></summary>
<br>

| Skill | Level | Stack |
|---|---|---|
| 📱 Mobile Apps | 90% | Flutter · iOS · Swift |
| 🐳 DevOps | 80% | Docker · K8s · ArgoCD |
| 🔧 Backend | 70% | Node.js · Supabase · Firebase |
| 🤖 AI Integration | 65% | GPT-4o · Vision API |

</details>

---

### 🧰 Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=dart,flutter,swift,xcode,js,nodejs" />
  <br>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,gcp,git,linux,nginx" />
  <br>
  <img src="https://skillicons.dev/icons?i=postgres,firebase,supabase,figma,vscode,github" />
</div>

---

### 🏗️ Projects I'm Proud Of

<table>
<tr>
<td width="50%">

**✅ Rituals — AI Habit Tracker**
> Built with Flutter + Node.js + GPT-4o
>
> AI generates personalized daily routines. Track streaks, build habits.

</td>
<td width="50%">

**☕ Caffeverse — Coffee Price Finder**
> Built with Flutter + Firebase + Maps
>
> Compare coffee prices at nearby cafes. Find the best deal around you.

</td>
</tr>
<tr>
<td width="50%">

**📱 QR Menu — Digital Menu System**
> Built with Flutter + Supabase
>
> Restaurants create digital menus. Customers scan QR to browse.

</td>
<td width="50%">

**🎓 IDP — Internal Developer Platform**
> Built with K3s · ArgoCD · Backstage · Python · LangChain
>
> Hybrid Wasm + Docker platform for a university DevOps lab. GitOps with ArgoCD, security policies via Kubewarden, AI self-healing agent with LangChain, and GreenOps carbon monitoring via Kepler.

</td>
</tr>
</table>

---

### 🐍 Contribution Graph

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NuriOkumus/NuriOkumus/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NuriOkumus/NuriOkumus/output/snake.svg" />
    <img alt="snake animation" src="https://raw.githubusercontent.com/NuriOkumus/NuriOkumus/output/snake.svg" />
  </picture>
</div>

---

<div align="center">
  <sub>💼 Open for freelance work — <a href="https://bionluk.com/nuriokumus">hire me on Bionluk</a></sub>
</div>
