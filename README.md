<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:4C1D95,50:6D28D9,100:312E81&text=Nadira%20Yakupbayeva&fontColor=ffffff&fontSize=46&fontAlignY=38&desc=Software%20Engineer&descAlignY=60&animation=fadeIn"
    width="100%"
  />
</p>
<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=800&lines=Building+AI%2FML+and+Web+Projects;Exploring+Intelligent+Software+Products;Always+Learning.+Always+Building."
    alt="Typing SVG"
  />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/B.Sc.-Software%20Engineering-6D28D9?style=flat-square" />
  <img src="https://img.shields.io/badge/Bahçeşehir%20University-Honour%20Graduate-4F46E5?style=flat-square" />
  <img src="https://img.shields.io/badge/CGPA-3.20%20%2F%204.00-7C3AED?style=flat-square" />
  <img src="https://img.shields.io/badge/Location-Istanbul%2C%20Türkiye-5B21B6?style=flat-square" />
</p>
<p align="center">
  <a href="https://github.com/nadiraya1">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>


Featured Projects

<details open>
<summary><b>🧬 CellPredict — Tissue-Specific Cell Type Prediction Platform</b></summary>
<br>

A machine-learning software platform developed as a university capstone project for predicting cell types from single-cell RNA sequencing data using tissue-specific models.

The system brings biological-data preprocessing, model inference, dimensionality reduction, explainability and downstream analysis into an interactive application.

Area	Details
Language	Python
Interface	Streamlit
ML	scikit-learn
Data	AnnData / single-cell RNA-seq
Supported Tissues	PBMC / Blood, Pancreas
Analysis	PCA, UMAP, SHAP, Differential Gene Expression
Inputs	.h5ad, .csv, .mtx
My Focus	GUI development, integration, validation flow and results presentation

What I Worked On

* Developed the interactive Streamlit interface.
* Designed the tissue-selection and prediction workflow.
* Integrated file-validation feedback into the UI.
* Connected the frontend to the machine-learning pipeline.
* Implemented prediction progress feedback.
* Presented prediction summaries and cell-type results.
* Integrated PCA and UMAP visualization outputs.
* Integrated SHAP explainability results.
* Added differential gene expression and volcano-plot outputs.
* Built a Model Info interface for presenting model metadata and metrics.
* Worked with a modular architecture connecting the interface, backend and ML pipeline.

The Bigger Idea

CellPredict explores an important software-engineering challenge in applied AI:

How do we turn a complex machine-learning workflow into a system that a user can understand and operate?

Rather than exposing individual preprocessing scripts, models and analysis modules, the platform connects them through one user-facing workflow.

</details>

⸻

<details>
<summary><b>🚗 Highway-RL Agent — Deep Q-Network for Autonomous Driving</b></summary>
<br>

A reinforcement-learning project exploring autonomous driving in dense highway traffic as a multi-objective control problem.

The central challenge:

Drive fast — without sacrificing safety or stability.

Repository

github.com/nadiraya1/highway_driving_dqn

Area	Details
Language	Python
Algorithm	Deep Q-Network (DQN)
Environment	highway-fast-v0
Observation	Kinematics
Actions	Discrete driving actions
Experiments	2-lane & 4-lane environments
Training	100K+ timesteps explored
Focus	Reward shaping, RL behavior and failure analysis

Agent Actions

The DQN agent learns to choose between high-level driving commands:

* Change lane left
* Change lane right
* Accelerate
* Decelerate
* Maintain its current behavior

Reward Engineering

The reward function balances several competing objectives:

speed       → encourage efficient driving
collision   → strongly penalize crashes
lane change → discourage unnecessary oscillation
road        → reward stable driving

Experimentation

We experimented with both 4-lane dense traffic and a simplified 2-lane environment.

The 4-lane environment created a significantly more difficult learning problem because the agent encountered more traffic interactions, overtaking possibilities and opportunities for collisions.

The 2-lane version helped us evaluate whether the reward function and basic learning behavior were working correctly in a simpler environment.

Challenges

One interesting failure mode was zig-zag lane behavior.

The agent sometimes discovered that repeatedly changing lanes could produce short-term advantages. We introduced a small lane-change penalty to discourage unnecessary switching and encourage smoother behavior.

We also observed cases where the trained agent reacted too late after entering a lane with another vehicle nearby.

The final model improved considerably over the untrained agent but did not achieve consistently reliable driving — an important reminder that increasing training time alone does not necessarily produce a better policy.

</details>

⸻

<details>
<summary><b>🌿 Kimaya Carvalho — Responsive Practitioner Website</b></summary>
<br>

A modern responsive website designed and developed for a Somatic Experiencing® and BodyMind Therapy practitioner.

Links

View Repository •
Live Website

Area	Details
Framework	React
Language	TypeScript
Build Tool	Vite
Styling	CSS
Deployment	GitHub Pages
Design	Responsive / Mobile-Friendly

Features

* Responsive user interface
* Practitioner introduction
* Services presentation
* Contact section
* Smooth navigation
* Mobile-friendly design
* GitHub Pages deployment

This project gave me practical experience turning a real person’s requirements into a complete web presence — from structure and interface decisions to development and deployment.

</details>

⸻

Experience

Software Engineering & Digital Product Work

My experience spans software development and digital-production environments where technical execution, user experience, communication and creative problem-solving intersect.

Areas I’ve worked with:

Software Engineering Machine Learning Web Development UI Development Digital Products Technical Collaboration

⸻

Education & Achievements

<div align="center">

Recognition	Details
🎓 B.Sc. Software Engineering	Bahçeşehir University
🏅 Honour Graduate	CGPA 3.20 / 4.00
🧬 Capstone Project	ML-based single-cell RNA-seq classification platform
🚗 Reinforcement Learning	DQN agent for highway-driving simulation
🌍 International Education	Undergraduate education completed abroad in English

</div>

⸻

Current Focus

learning:
  - Applied Artificial Intelligence
  - Machine Learning Engineering
  - Data Science
  - Full-Stack Development
building:
  - Portfolio Projects
  - AI-Enabled Applications
  - Practical Software Products
exploring:
  - Graduate Study
  - AI + Software Engineering
  - Intelligent Automation
open_to:
  - Software Engineering Opportunities
  - AI / ML Projects
  - International Opportunities

⸻

GitHub Analytics

<p align="center">
  <img
    height="180"
    src="https://github-readme-stats.vercel.app/api?username=nadiraya1&show_icons=true&hide_border=true&theme=midnight-purple"
  />
</p>
<p align="center">
  <img
    height="180"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=nadiraya1&layout=compact&hide_border=true&theme=midnight-purple"
  />
</p>
<p align="center">
  <img
    src="https://streak-stats.demolab.com?user=nadiraya1&theme=midnight-purple&hide_border=true"
  />
</p>

⸻

GitHub Trophies

<p align="center">
  <img
    src="https://github-profile-trophy.vercel.app/?username=nadiraya1&theme=discord&no-frame=true&no-bg=true&margin-w=8&column=6"
  />
</p>

⸻

Contribution Activity

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=nadiraya1&bg_color=0d1117&color=a78bfa&line=7c3aed&point=c4b5fd&area=true&hide_border=true"
    width="100%"
  />
</p>

⸻

Connect

<p align="center">
  <a href="https://github.com/nadiraya1">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

⸻

<p align="center">
  <i>Building software with curiosity, purpose, and room to keep learning.</i>
</p>
<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:312E81,50:6D28D9,100:4C1D95"
    width="100%"
  />
</p>
```
:::
