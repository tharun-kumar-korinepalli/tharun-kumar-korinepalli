<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0c0c0c,50:166534,100:4ade80&height=200&section=header&text=Tharun%20Kumar&fontSize=52&fontColor=ffffff&fontAlignY=34&animation=fadeIn&desc=Turning%20research%20into%20systems%20that%20actually%20ship&descAlignY=54&descSize=16" />

<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=500&size=22&pause=1200&color=4ADE80&center=true&vCenter=true&width=680&lines=Mechanical+engineer+who+went+looking+for+intelligence.;Now+I+put+neural+networks+on+factory+floors.;LLMs+that+answer+from+your+documents%2C+not+the+internet.;Vision+models+small+enough+to+live+on+a+Jetson." alt="Typing SVG" /></a>

<br/>

<a href="https://www.linkedin.com/in/tharun-kumar-korine-palli/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://medium.com/@korinetharunkumarpalli"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
<a href="mailto:korinetharunkumarpalli@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://ttz-kt.thws.de/"><img src="https://img.shields.io/badge/TTZ_Kitzingen-4ADE80?style=for-the-badge&logo=googlescholar&logoColor=black" alt="TTZ"/></a>

</div>

---

### `whoami`

```python
class Tharun:
    """AI Researcher, TTZ Kitzingen — a THWS technology transfer centre."""

    location   = "Würzburg, Germany 🇩🇪"
    education  = "M.Sc. Artificial Intelligence, THWS"
    began_as   = "Mechanical Engineer (B.Tech, Gold Medal)"
    speaks     = ["Telugu", "English", "German (…allegedly)"]

    def working_on(self):
        return {
            "llm":    "RAG over messy industrial documentation",
            "vision": "quality-control detection on the line",
            "edge":   "TensorRT until it fits on a Jetson",
        }

    @property
    def thesis(self):
        return "A model that can't run in production is just a hypothesis."
```

---

### The long way round

I didn't start in AI. I started with lathes and tolerances, and that turns out to be
the useful part — I think about latency, memory and heat before I think about accuracy.

```
   ┌──────────────┐      ┌──────────────┐      ┌──────────────┐
   │  MECHANICAL  │ ───▶ │   MACHINE    │ ───▶ │     EDGE     │
   │ ENGINEERING  │      │   LEARNING   │      │  DEPLOYMENT  │
   └──────────────┘      └──────────────┘      └──────────────┘
    Diploma → B.Tech       M.Sc. @ THWS         TTZ Kitzingen
      2015 – 2021           2023 – 2025            2025 → now
     "how things move"    "how things learn"   "how things survive
                                                  the factory floor"
```

<div align="center">
<img src="https://img.shields.io/badge/LLMs_%26_RAG-4ADE80?style=flat-square&labelColor=0c0c0c" />
<img src="https://img.shields.io/badge/Computer_Vision-818CF8?style=flat-square&labelColor=0c0c0c" />
<img src="https://img.shields.io/badge/Edge_Inference-F472B6?style=flat-square&labelColor=0c0c0c" />
<img src="https://img.shields.io/badge/Industrial_AI-F59E0B?style=flat-square&labelColor=0c0c0c" />
</div>

---

### Toolbox

<table>
<tr><td><b>Modelling</b></td><td>
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv" height="42" />
<img src="https://cdn.simpleicons.org/huggingface/FFD21E" height="42" />
</td></tr>
<tr><td><b>LLM&nbsp;&amp;&nbsp;serving</b></td><td>
<img src="https://cdn.simpleicons.org/langchain/4ADE80" height="42" />
<img src="https://skillicons.dev/icons?i=fastapi" height="42" />
</td></tr>
<tr><td><b>Edge</b></td><td>
<img src="https://cdn.simpleicons.org/nvidia/76B900" height="42" />
<img src="https://skillicons.dev/icons?i=cpp,docker,linux,bash" height="42" />
</td></tr>
<tr><td><b>Daily&nbsp;drivers</b></td><td>
<img src="https://cdn.simpleicons.org/numpy/4DABCF" height="42" />
<img src="https://cdn.simpleicons.org/pandas/E70488" height="42" />
<img src="https://cdn.simpleicons.org/jupyter/F37626" height="42" />
<img src="https://skillicons.dev/icons?i=git,latex,vscode" height="42" />
</td></tr>
</table>

<sub>NVIDIA badge covers TAO Toolkit, TensorRT and Jetson — three things, one logo, sorry.</sub>

---

### Things I built

| | |
|---|---|
| **🔍 Detection on the line**<br/>Quality-control models trained with NVIDIA TAO, quantised and squeezed through TensorRT until they hit frame rate on a Jetson. The accuracy was the easy half. | **📹 [Multi-camera tracking](https://github.com/tharun-kumar-korinepalli/camera_based_person_detection)**<br/>Following one person across cameras that never agree on lighting, angle or colour. Re-identification is where it gets interesting. |
| **🦴 [Motion forecasting](https://github.com/tharun-kumar-korinepalli/Future-Pose-Predictive-Modeling-of-Human-Motion-Dynamics-using-Skeleton-Data)**<br/>Predicting where a body goes next from skeleton data alone. Recurrent models, surprisingly small, surprisingly good. | **🧩 [Sudoku by gradient descent](https://github.com/tharun-kumar-korinepalli/Artificial-Neural-Networks---Suduko-Solver)**<br/>Teaching a network to solve a problem that has a perfectly good algorithm. Pointless, instructive, fun. |

---

### Things I wrote

<table>
<tr>
<td width="50%">

📐 **[From RNNs to Attention](https://medium.com/@korinetharunkumarpalli/from-rnns-to-attention-bahdanau-attention-explained-9314b151d24e)**
<sub>Bahdanau attention, derived slowly enough to actually follow.</sub>

⚡ **[Fast inference on edge devices](https://medium.com/@korinetharunkumarpalli/optimizing-deep-learning-models-for-fast-inference-on-edge-devices-1c0e853ddf21)**
<sub>What you give up, and what you get back.</sub>

</td>
<td width="50%">

🛠️ **[The NVIDIA TAO Toolkit](https://medium.com/@korinetharunkumarpalli/nvidia-tao-toolkit-27dfcc2b4e8a)**
<sub>A complete guide, written because I couldn't find one.</sub>

🔁 **[xLSTM](https://medium.com/@korinetharunkumarpalli/xlstm-reinventing-recurrent-networks-for-the-era-of-large-language-models-e2243b774dc5)**
<sub>Recurrence returns, with something to prove.</sub>

</td>
</tr>
</table>

---

### The numbers

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=tharun-kumar-korinepalli&show_icons=true&theme=tokyonight&hide_border=true&border_radius=10&icon_color=4ADE80&title_color=4ADE80&count_private=true" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tharun-kumar-korinepalli&layout=compact&theme=tokyonight&hide_border=true&border_radius=10&title_color=4ADE80&langs_count=8" />

<img width="94%" src="https://github-readme-activity-graph.vercel.app/graph?username=tharun-kumar-korinepalli&theme=tokyo-night&hide_border=true&radius=10&color=4ADE80&line=4ADE80&point=FFFFFF&area=true&area_color=166534" />

</div>

---

<div align="center">

**Working on something at the awkward edge of research and production?**
That's my favourite place to be — [say hello](mailto:korinetharunkumarpalli@gmail.com).

<img src="https://komarev.com/ghpvc/?username=tharun-kumar-korinepalli&style=flat-square&color=4ADE80&label=visitors" alt="Profile Views" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4ade80,50:166534,100:0c0c0c&height=120&section=footer" />
