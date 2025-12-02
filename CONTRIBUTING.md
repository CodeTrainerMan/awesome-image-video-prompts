# Contributing Guide

<div align="center">

[English](#) | [中文 / Chinese](CONTRIBUTING.zh.md)

Thank you for your interest in contributing to Awesome Image & Video Prompts!

</div>

---

### 🤝 How to Contribute

We welcome all kinds of contributions! Whether you're adding new prompts, improving documentation, fixing bugs, or suggesting new features, your help makes this project better.

### 📋 Ways to Contribute

1. **Add New Prompts**: Share high-quality prompts you've created or found
2. **Improve Organization**: Suggest better categorization or folder structure
3. **Fix Issues**: Report bugs or fix existing problems
4. **Enhance Documentation**: Improve README, add examples, or clarify instructions
5. **Review Pull Requests**: Help review and test contributions from others
6. **Suggest Features**: Propose new ideas or improvements

### 🚀 Getting Started

#### 1. Fork the Repository

Click the "Fork" button on the GitHub repository page to create your own copy.

#### 2. Clone Your Fork

```bash
git clone https://github.com/CodeTrainerMan/awesome-image-video-prompts.git
cd awesome-image-video-prompts
```

#### 3. Create a Branch

```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/your-fix-name
```

#### 4. Make Your Changes

- Add new prompts following the format standards
- Update documentation if needed
- Test your prompts if possible

#### 5. Commit Your Changes

```bash
git add .
git commit -m "Add: description of your changes"
```

**Commit Message Guidelines:**
- Use clear, descriptive messages
- Prefix with type: `Add:`, `Fix:`, `Update:`, `Docs:`, `Refactor:`
- Examples:
  - `Add: landscape photography prompts`
  - `Fix: typo in README`
  - `Update: prompt format standards`
  - `Docs: improve contribution guide`

#### 6. Push to Your Fork

```bash
git push origin feature/your-feature-name
```

#### 7. Create a Pull Request

1. Go to the original repository on GitHub
2. Click "New Pull Request"
3. Select your fork and branch
4. Fill out the pull request template
5. Submit the PR

### 📝 Prompt Contribution Guidelines

#### File Naming Convention

- Format: `category-style-tags.txt` or `category-style-tags.md`
- Use lowercase letters and hyphens
- Examples:
  - `portrait-photorealistic-4k.txt`
  - `landscape-cinematic-sunset.md`
  - `character-anime-fantasy.txt`

#### Prompt File Structure

Each prompt file should follow this structure:

```markdown
# Prompt Title

## Description
Brief description of what this prompt generates.

## Prompt
[Your prompt text here]

## Negative Prompt (Optional)
[What to avoid in the generation]

## Parameters (Optional)
- Aspect Ratio: 16:9
- Model: Stable Diffusion v1.5
- Steps: 50
- CFG Scale: 7

## Usage Notes (Optional)
Any additional notes or tips for using this prompt.

## Tags
photography, landscape, sunset, 4k
```

#### Quality Standards

- ✅ **Clear and Specific**: Prompts should be well-defined
- ✅ **Tested**: If possible, test prompts before submitting
- ✅ **Categorized**: Place prompts in appropriate folders
- ✅ **Documented**: Include descriptions and usage notes
- ✅ **Original or Attributed**: If using prompts from others, provide attribution

#### Categories

Organize prompts in the following structure:

```
prompts/
├── image/
│   ├── artistic/
│   ├── photography/
│   ├── digital-art/
│   ├── product/
│   ├── architecture/
│   └── fashion/
└── video/
    ├── cinematic/
    ├── animation/
    ├── commercial/
    ├── social-media/
    └── educational/
```

### 🔍 Code of Conduct

#### Our Standards

- Be respectful and inclusive
- Welcome newcomers and help them learn
- Focus on constructive feedback
- Respect different viewpoints and experiences

#### Unacceptable Behavior

- Harassment or discriminatory language
- Trolling or insulting comments
- Publishing others' private information
- Other conduct that could reasonably be considered inappropriate

### 📋 Pull Request Process

1. **Update Documentation**: If you're adding features, update the README
2. **Follow Format Standards**: Ensure your prompts follow the naming and structure conventions
3. **Test Your Changes**: Test prompts if possible before submitting
4. **Write Clear Descriptions**: Explain what your PR does and why
5. **Be Patient**: Maintainers will review your PR as soon as possible

#### PR Template

When creating a pull request, please include:

- **Type**: What type of contribution (prompt, docs, fix, etc.)
- **Description**: What does this PR do?
- **Testing**: How was this tested?
- **Checklist**: 
  - [ ] Follows file naming conventions
  - [ ] Includes description and usage notes
  - [ ] Placed in appropriate category
  - [ ] Documentation updated if needed

### 🐛 Reporting Issues

#### Before Reporting

1. Check if the issue already exists
2. Search closed issues for similar problems
3. Ensure you're using the latest version

#### How to Report

1. Use the issue template
2. Provide a clear title and description
3. Include steps to reproduce (if applicable)
4. Add screenshots or examples if helpful
5. Specify your environment (OS, tools, etc.)

### 💡 Suggestions and Feature Requests

We welcome suggestions! When proposing new features:

1. Check if it's already been suggested
2. Explain the use case and benefits
3. Consider implementation complexity
4. Be open to discussion and feedback

### 🎯 Priority Areas

We especially welcome contributions in:

- High-quality, tested prompts
- Prompts for less common AI tools
- Documentation improvements
- Translation and localization
- Bug fixes and optimizations

### ❓ Questions?

- Open an issue for questions
- Check existing issues and discussions
- Be patient for responses

### 🙏 Recognition

Contributors will be:
- Listed in the README (if desired)
- Credited in release notes
- Appreciated by the community!

Thank you for contributing! 🎉

---

<div align="center">

[中文文档 / Chinese Documentation](CONTRIBUTING.zh.md)

</div>
