# Personal Homepage Content

## About Me
```yaml
about:
  content:
    Hi!👋

    I am a 3rd-year undergraduate student at <strong>Beijing University of Posts and Telecommunications</strong> <img src="images/bupt.png" alt="BUPT Logo" style="height:3em; vertical-align:middle;">.

    My research interests lie in developing <strong>Trustworthy and Easy-to-use AI</strong>.

    <strong>🔥 I'm seeking Ph.D. opportunity for 2026 Fall!</strong>
```

## Research Interests
```yaml
research:
  items:
    - keyword: "Large Language Models"
      description: "Safety, Reasoning, Multimodal, etc."
    - keyword: "LLM-based Agent"
      description: "Security, MAS, etc."
    - keyword: "Knowledge Mechanisms in Models"
      description: "Model Editing, Interpretability, etc."
```

## Interns
```yaml
interns:
  items:
    - period: "2025.05 - "
      degree: "Research Intern"
      school: "National University of Singapore"
      # school_logo: "images/tju.png"
      advisor:
        name: "Prof. Jiaheng Zhang"
        url: "https://zjhzjh123.github.io/"
    - period: "2024.11 - 2025.04"
      degree: "Research Intern"
      school: "University of Science and Technology of China"
      # school_logo: "images/tju.png"
      advisor:
        name: "Prof. Xiang Wang"
        url: "https://xiangwang1223.github.io/"
    - period: "2024.01 - 2024.10"
      degree: "Research Intern"
      school: "Beijing University of Posts and Telecommunications"
      # school_logo: "images/tju.png"
      advisor:
        name: "Prof. Sen Su"
        url: "https://scholar.google.com/citations?user=JaDhAfsAAAAJ"
```

## Publications & Preprint
```yaml
publications:
  items:
    - year: "2025"
      title: "Goal-Aware Identification and Rectification of Misinformation in Multi-Agent Systems"
      authors: "<u>Zherui Li</u>, Yan Mi, Zhenhong Zhou, Houcheng Jiang, Guibin Zhang, Kun Wang, Junfeng Fang"
      journal: "Preprint, arXiv 2025"
      venue: "Preprint"
      tldr: "We introduce MisinfoTask, a dataset to assess the impact of misinformation injection on Multi-Agent Systems, and ARGUS, a universal and adaptive framework designed to defend against this threat."
      image: "images/ARGUS.png"
      links:
        paper: "https://arxiv.org/abs/2506.00509"
        code: "https://github.com/zhrli324/ARGUS"
    - year: "2025"
      title: "Reinforced Lifelong Editing for Language Models"
      authors: "<u>Zherui Li</u>*, Houcheng Jiang*, Hao Chen, Baolong Bi, Zhenhong Zhou, Fei Sun, Junfeng Fang†, Xiang Wang†"
      journal: "International Conference on Machine Learning (ICML), 2025"
      venue: "ICML'25"
      tldr: "We propose RLEdit, a hypernetwork-based lifelong model editing method that achieves both effectiveness and efficiency."
      image: "images/RLEdit.png"
      links:
        paper: "https://arxiv.org/abs/2502.05759"
        code: "https://github.com/zhrli324/RLEdit"
        # project: "https://dripnowhy.github.io/MIS/"
    - year: "2025"
      title: "CORBA: Contagious Recursive Blocking Attacks on Multi-Agent Systems Based on Large Language Models"
      authors: "Zhenhong Zhou*, <u>Zherui Li</u>*, Jie Zhang, Yuanhe Zhang, Kun Wang, Yang Liu, Qing Guo†"
      journal: "Preprint, arXiv 2025"
      venue: "Preprint"
      tldr: "We present a blocking attack against an LLM-based multi-agent system that can degrade its availability and reveal vulnerabilities in the existing framework."
      image: "images/Corba.png"
      links:
        paper: "https://arxiv.org/abs/2502.14529"
        code: "https://github.com/zhrli324/Corba"
        # project: "https://dripnowhy.github.io/ETA.html"
    - year: "2024"
      title: "Speak Out of Turn: Safety Vulnerability of Large Language Models in Multi-turn Dialogue"
      authors: "Zhenhong Zhou, Jiuyang Xiang, Haopeng Chen, <u>Zherui Li</u>, Ting Yang, Quan Liu, Sen Su†"
      journal: "Preprint, arXiv 2025"
      venue: "Preprint"
      tldr: "This paper expose vulnerabilities of LLMs in complex scenarios involving multi-turn dialogue."
      image: "images/Multi-Turn.png"
      links:
        paper: "https://arxiv.org/abs/2402.17262"
```

## Education
```yaml
education:
  items:
    - period: "2022.09 - 2026.06"
      degree: "B.S."
      school: "School of Future, Beijing University of Posts and Telecommunications"
      school_logo: "images/bupt_raw.png"
```

## Contact
```yaml
contact:
  items:
    - type: "email"
      icon: "fas fa-envelope"
      content: "zhrli324@gmail.com\nzhrli@bupt.edu.cn"
    - type: "location"
      icon: "fas fa-map-marker-alt"
      content: "Beijing, China"
```

## Usage Guide

1. All content is organized in YAML format for easy parsing
2. Each section has a clear structure and categorization
3. Content can be easily added or modified
4. Supports Markdown formatting for text content

### How to Update Content

1. Edit the `content.md` file directly
2. Maintain proper YAML format
3. Ensure correct indentation
4. Use Markdown syntax for text formatting

### Notes

1. Date Format: Use YYYY-MM-DD format
2. Links: Ensure all links are complete URLs
3. Icons: Use Font Awesome icon class names
4. Indentation: Use 2 spaces for indentation 

## GitHub Repositories
```yaml
github_repos:
  username: "zhrli324"
  auto_sync: true # 自动同步，无需手动维护仓库列表
``` 