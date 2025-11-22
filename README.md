# SocialSim: Towards Socialized Simulation of Emotional Support Conversation

[![Dataset](https://img.shields.io/badge/Dataset-3229_Conversations-blue)](#dataset-overview)
[![License](https://img.shields.io/badge/License-CC_BY--NC_4.0-blue.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

*Copyright © 2025 CoAI Group, Central South University. Licensed under CC BY-NC 4.0.*

## 📖 Overview

The dataset contains **3,229** high-quality emotional support dialogues between seekers and supporters, along with detailed user profiles that provide rich contextual information for each conversation participant. 

Data and codes for AAAI 2025 paper: [SocialSim: Towards Socialized Simulation of Emotional Support Conversation](https://ojs.aaai.org/index.php/AAAI/article/view/32116)

### Key Features

- **3,229 Complete Dialogues**: Each containing multiple turns between seekers and supporters
- **Detailed User Profiles**: Comprehensive demographic and psychological information
- **Emotional Context**: Rich emotional states and coping strategies
- **Supporter Reasoning**: Step-by-step reasoning processes for supporter responses
- **Diverse Scenarios**: Covering various life situations and emotional challenges

## 📊 Dataset Overview

### Dataset Statistics

| Component | Count | Description |
|-----------|-------|-------------|
| **Total Dialogues** | 3,229 | Complete emotional support conversations |
| **User Profiles** | 3,229 | Corresponding user profiles for each dialogue |

### Data Files

- **`SocialSim_SSConv_ESC_dataset_full_3229.json`**: Complete dialogue dataset with emotional support conversations
- **`SocialSim_UserProfile_full_3229.json`**: User profiles with demographic and psychological information

## 🎯 Dataset Components

### 1. Emotional Support Conversations (`SocialSim_SSConv_ESC_dataset_full_3229.json`)

Each dialogue contains:

```json
{
  "ID": 1,
  "Dialogue": [
    {
      "Turn": 1,
      "Seeker": "Initial message from the person seeking help"
    },
    {
      "Turn": 2,
      "Supporter Step by Step Reasoning": "[Detailed reasoning process]",
      "Supporter": "Supportive response with empathy and guidance"
    }
    // ... additional turns
  ]
}
```

**Key Features:**
- **Turn-based Structure**: Alternating seeker and supporter messages
- **Supporter Reasoning**: Explicit step-by-step reasoning process for each supporter response
- **Natural Language**: Realistic, empathetic conversation patterns
- **Emotional Markers**: Natural use of emojis and emotional expressions

### 2. User Profiles (`SocialSim_UserProfile_full_3229.json`)

Each user profile includes:

```json
{
  "ID": 1,
  "Gender": "Female",
  "Age": 18,
  "Occupation": "Student",
  "Personality": "Closedness, Unconscientiousness, Introversion, Neuroticism, Agreeableness",
  "Topic": "Study",
  "Subtopic": "Exam Anxiety Management, Study Method",
  "Situation": "Brief description of the current situation",
  "Event Time": "Morning",
  "Event Location": "School",
  "Event Participants": "Biology teacher, Classmates, Me",
  "Event Description": "Detailed narrative of the situation",
  "Emotional Experience Words": "Fear, Trembling, Scared, Terrified, Anxiety",
  "Coped Strategies and Effects": "Description of current coping mechanisms",
  "Goals and Expectations": "Expected outcomes from the conversation"
}
```

## 🏷️ Topics and Categories

The dataset covers diverse emotional support scenarios including:

- **Academic Stress**: Study pressure, exam anxiety, classroom difficulties
- **Work-related Issues**: Workplace conflicts, career concerns, job stress
- **Relationship Problems**: Family conflicts, friendship issues, romantic relationships
- **Personal Growth**: Self-esteem, confidence building, personal development
- **Mental Health**: Anxiety, depression, stress management
- **Life Transitions**: Major life changes, adaptation challenges
- **Social Situations**: Communication difficulties, social anxiety

## 📄 License

This dataset is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

[![CC BY-NC 4.0](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

**Summary of CC BY-NC 4.0:**
- ✅ **Share** — copy and redistribute the material in any medium or format
- ✅ **Adapt** — remix, transform, and build upon the material
- ✅ **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made
- ❌ **Non-Commercial** — You may not use the material for commercial purposes

**For the full license text**, visit: https://creativecommons.org/licenses/by-nc/4.0/

## 📝 Citation

If you use this dataset or your research is related to our paper, please cite:

```bibtex
@inproceedings{chen2025socialsim,
  title={SocialSim: Towards Socialized Simulation of Emotional Support Conversation},
  author={Chen, Zhuang and Cao, Yaru and Bi, Guanqun and Wu, Jincenzi and Zhou, Jinfeng and Xiao, Xiyao and Chen, Si and Wang, Hongning and Huang, Minlie},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={39},
  number={2},
  pages={1274--1282},
  year={2025}
}
```

## 🤝 Contributing

This dataset is maintained by the CoAI Group at Central South University. For questions, suggestions, or collaboration inquiries, please contact the research group.

## 📞 Contact

- **Research Group**: CoAI Group, Central South University
- **Year**: 2025

---

<!-- *Note: This dataset contains sensitive personal information and emotional content. Researchers are expected to follow ethical guidelines and maintain participant confidentiality when working with this data.* -->
