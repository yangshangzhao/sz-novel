# SZ-Novel AI Deep Learning Long-Form Novel Expert

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com)
[![Language](https://img.shields.io/badge/language-English-green.svg)](https://github.com)
[![Quality](https://img.shields.io/badge/quality-★★★-green.svg)](https://github.com)

## 📖 Project Introduction

**SZ-Novel** is a deep learning-based long-form novel creation expert system powered by Claude AI. It adopts an innovative "learn first, write later" working paradigm, supporting multi-volume, multi-chapter long-form novel creation, automatically ensuring story coherence and quality standards.

### 🎯 Core Features

- **Intelligent Learning System**: Deep learning from reference materials to master writing style, character logic, and world-building settings
- **Pure Chinese Creation**: Zero tolerance for non-Chinese content, ensuring language purity
- **Quality Assurance System**: 6-dimensional quality checks + real-time error correction mechanism
- **Coherence Guarantee**: Prevents chapter omissions, setting drift, and character inconsistencies
- **De-AI Processing**: 5 anti-detection strategies to avoid recognition by AI detection tools
- **Automated Persistence**: Intelligent file management, automatic saving by volume and chapter

## 🚀 Quick Start

### Environment Requirements

- Claude AI environment
- Project root directory permissions
- Reference materials directory (optional)

### Basic Usage

1. **New Creation**:
   ```
   Start creating directly, the system will automatically enter new creation mode
   ```

2. **Continue Creation**:
   ```
   Continue creation
   ```
   The system will automatically scan the project directory, read the last creation content, and continue writing

## 📋 Workflow

### 🔄 New Creation Mode

1. **Environment Scanning** → Verify reference materials directory
2. **Deep Learning** → Analyze reference materials style
3. **Content Creation** → Generate high-quality chapters
4. **Automated Persistence** → Intelligent file saving

### 🔄 Continue Creation Mode

1. **Context Retrieval** → Scan project directory to read previous content
2. **Context Learning** → Extract character, setting, and foreshadowing information
3. **Coherence Assurance** → Ensure new chapters seamlessly connect with previous content
4. **Exception Repair** → Automatically fill in missing chapters

## 📊 Quality Standards

### 6-Dimensional Quality Check System

#### 📖 Dimension 1: Story Clarity and Pacing
- ✅ Clear main storyline, explicit story progression
- ✅ Balanced pacing with alternating tension and relaxation
- ✅ Reasonable suspense and foreshadowing layout, no "bury without reveal"

#### 👥 Dimension 2: Character Consistency and Development
- ✅ Character actions align with personality, background, and motivations
- ✅ Reasonable and dynamic character relationships
- ✅ Complete and believable protagonist growth arc

#### 🌍 Dimension 3: Internal Consistency
- ✅ Strict adherence to world-building rules
- ✅ No contradictions (e.g., "exhausting true qi leads to death" but character survives unscathed)
- ✅ Consistent logic for special mechanisms (magic, time travel, technology)

#### 🧠 Dimension 4: Character Intelligence and Conflict Rationality
- ✅ Antagonists are sufficiently powerful and intelligent, posing real threats
- ✅ Protagonist victory based on effort and wisdom, not plot armor or deus ex machina
- ✅ All conflicts have reasonable cause and effect

#### 📝 Dimension 5: Basic Information Consistency
- ✅ Unified character information (eye color, family background, etc.)
- ✅ Accurate timeline (yesterday was Monday, today can't be Wednesday)
- ✅ Consistent location and scene descriptions

#### 🔗 Dimension 6: Causality Rationality
- ✅ Major plot twists have sufficient internal reasons and external catalysts
- ✅ Character decisions based on current information and personality
- ✅ No unexplained position changes

### 🛡️ De-AI Strategies

- ✅ **Invalid Details**: Insert irrelevant trivial information
- ✅ **Logic Jumps**: Occasional awkward scene transitions
- ✅ **Emotional Rough Edges**: Incomplete or uncertain emotional expressions
- ✅ **Deliberate Rule-Breaking**: Break perfect parallelism, awkward word combinations
- ✅ **Personal Quirks**: Catchphrases, unconventional aesthetic perspectives

## 📁 File Structure

```
sz-novel/
├── SKILL.md              # Core skill specification document
├── README.md             # Project description document (this file)
├── README_EN.md          # English version of README
├── references/           # Reference materials directory
│   ├── Ming Dynasty Stories.epub    # Example novel file
│   ├── Grave Robbery Notes.txt      # Style reference materials
│   └── ...              # Other reference files
├── assets/               # Resource files directory
└── scripts/              # Auxiliary scripts directory
```

### Output File Format

- **File Name Format**: `[Volume Name]_Chapter X_[Chapter Title].txt`
- **Pure Chinese Naming**: Volume names and titles must use pure Chinese
- **Automatic Serial Number Management**: Ensure 100% chapter continuity

## ⚙️ Technical Specifications

### Creation Parameters

| Parameter             | Specification                 |
| --------------------- | ----------------------------- |
| Chapter Length        | 2000～4000 characters         |
| Book Scale            | 10～30 chapters/volume        |
| Language Requirements | Pure Chinese (zero tolerance) |
| Save Format           | UTF-8 text file               |

### Quality Control

- **Real-time Scanning**: Automatic check every 50 characters
- **Auto Correction**: Immediate correction upon issue detection
- **Triple Verification**: Generation → Completion → Pre-save verification
- **Zero Tolerance Policy**: Any quality issues must be resolved before saving

## 🔧 Advanced Features

### Chapter Serial Number Management

The system adopts an **absolute zero tolerance** serial number management mechanism:

```
Existing chapters: 1, 2, 3, 5, 6, 8, 9
↓
Missing detection: Missing chapters 4 and 7 detected
↓
Auto completion: Generate chapter 4 first, then chapter 7
↓
Quality verification: Complete checks for each completed chapter
↓
Continuity confirmation: Re-verify serial number completeness after all completions
```

### Context Continuation

**Continue Creation Mode** automatically executes:
- 📖 Scan project directory to read previous content
- 🧠 Extract key information (characters, settings, foreshadowing)
- 🔗 Ensure new chapters seamlessly connect
- ⚡ Exception repair (fill in missing chapters)

## ⚠️ Important Notes

### Prohibited Items

- ❌ **Non-Chinese Content**: Any English or other language mixing
- ❌ **Missing Chapters**: Cannot skip any planned chapters
- ❌ **Setting Drift**: Character and world-building contradictions
- ❌ **Obvious AI Characteristics**: Overly perfect parallelism, antithesis
- ❌ **Meta Narrative Comments**: Author voice intruding into the story
- ❌ **Forgotten Foreshadowing**: Suspense that is buried but never revealed

### Best Practices

- 📚 **Prepare Reference Materials**: Place in `references/` directory for learning
- 🔄 **Batch Creation**: Recommend completing 1-3 chapters at a time for coherence
- ✅ **Quality Confirmation**: Carefully check quality reports before each save
- 📝 **Pure Chinese Environment**: Ensure all input and output are pure Chinese

## 📈 Quality Assurance

### Verification Process

1. **Real-time Check**: Scan every 50 characters during creation
2. **Chapter Verification**: Quality check after single chapter completion
3. **Continuity Verification**: Check serial numbers and setting consistency for multiple chapters
4. **Save Verification**: Final confirmation of no issues

### Error Handling

- **Auto Correction**: Stop and correct immediately upon issue detection
- **Completion Mechanism**: Automatically generate and fill missing chapters
- **Verification Failure**: Cannot save if standards not met, must be fixed

## 🤝 Contribution Guidelines

### Improvement Suggestions

Welcome submissions for improvements in the following areas:
- 📖 Reference materials expansion
- 🎯 Quality standards optimization
- ⚡ Performance improvements
- 🐛 Bug fixes

### Usage Feedback

If you encounter issues or have suggestions, please:
1. Check the specifications in SKILL.md
2. Confirm operations comply with quality standards
3. Provide detailed problem descriptions and environment information

## 📄 License

This project uses the MIT License. See LICENSE file for details.

## 🔗 Related Links

- [Claude AI Official Documentation](https://docs.anthropic.com/claude/docs)
- [Novel Writing Techniques Reference](https://example.com)
- [Chinese Writing Standards](https://example.com)

---

**Last Updated: April 4, 2026**

*Automatically generated high-quality long-form novel creation tool by SZ-Novel AI system*