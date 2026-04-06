# SZ-Novel AI Deep Learning Long-Form Novel Expert

[![中文](https://img.shields.io/badge/中文-README-red)](README.md) [![English](https://img.shields.io/badge/English-README-green)](README_EN.md)

## 📖 Project Overview

**SZ-Novel** is a deep-learning novel writing assistant designed for long-form fiction. It uses a "learn first, write later" approach to extract writing style, character logic, and world-building rules from reference material, then generate coherent, high-quality, pure Chinese chapters.

## 🎯 Key Features

- Smart learning from reference content
- Pure Chinese output with zero tolerance for non-Chinese elements
- Real-time multi-dimensional quality checks
- Chapter continuity and gap filling
- De-AI writing strategies based on `DEAIFY.md`
- Automatic file persistence and chapter management

## 🚀 How to Use

### New Creation
Start writing directly to enter new creation mode.

### Continue Creation
Send `Continue creation` to enter continue mode. The system will scan the project directory, load the latest chapter, and continue writing.

## 🔧 Workflow

### 0. Startup Detection and Mode Selection

- If the input contains "Continue creation", enter continue mode.
- Otherwise, enter new creation mode.

### Continue Creation Mode

- Scan the project root for the latest `.txt` chapter file
- Extract last chapter number, scene, characters, foreshadowing, and timeline
- If no issues are found, continue writing immediately
- If missing chapters, wrong sequence, or file issues are detected, repair them first

### New Creation Mode

1. Environment Scan: verify `references/` directory and assess available reference files
2. Learning Phase: analyze reference material style, pacing, character logic, and world rules
3. Content Creation: generate chapters according to the writing standard
4. Persistence: perform final checks and save the chapter

## ✅ Writing Rules

- Chapter length: 2000–4000 Chinese characters
- Confirm chapter sequence before writing
- Do not skip chapter numbers
- Real-time checks every 50 characters
- Fix issues immediately and continue writing
- Do not stop at a seemingly complete point
- If missing chapters are found, fill them before saving

## 📊 Quality Standards

### 6 Dimensions of Quality Checking

1. Story clarity and pacing
2. Character consistency and growth
3. Internal world consistency
4. Intelligence and conflict rationality
5. Basic information consistency
6. Cause-and-effect logic

### De-AI Strategies

- Add irrelevant detail and environment texture
- Introduce logic jumps and emotional roughness
- Avoid neat parallelism, emotional label verbs, and overly perfect conclusions
- Add character quirks and imperfect expressions
- Use `DEAIFY.md` for guidance

## 📁 File Structure

```
sz-novel/
├── SKILL.md
├── README.md
├── README_EN.md
├── DEAIFY.md
├── assets/
├── references/
└── scripts/
```

- Recommended output filename: `[Volume Name]_第X章_[Chapter Title].txt`
- Filenames and titles must be pure Chinese
- Automatic chapter number management ensures no missing chapters

## ⚠️ Important Notes

### Prohibited Items

- Any non-Chinese text
- Missing or skipped chapter numbers
- Setting drift or character inconsistency
- Obvious AI writing patterns
- Meta-narrative commentary or reader-facing expressions
- Foreshadowing that is never resolved

### Recommended Practices

- Prepare reference material before writing
- Write 1–3 chapters at a time for coherence
- Review previous chapters regularly for consistency
- Perform full quality checks after each chapter

## 📈 Verification Process

1. Real-time checks every 50 characters
2. Chapter-level quality validation
3. Cross-chapter continuity review
4. Final save confirmation

## 🤝 Contribution

Contributions are welcome for improving process, quality rules, and de-AI strategies.

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