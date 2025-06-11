# Cursor CV - AI-Powered Resume Optimization System

A systematic approach to resume optimization using AI assistants and version control. This repository provides templates and workflows for getting high-quality resume feedback and tracking improvements over time.

## What is Cursor CV?

Cursor CV is a structured system that helps job seekers:
- Get detailed, objective feedback on their resumes from AI assistants
- Track resume versions and improvements over time
- Tailor resumes to specific job descriptions
- Maintain a log of insights and learnings throughout the job search

## Features

- **Structured Review Templates**: Comprehensive templates for analyzing resume-job fit
- **Version Control**: Track how your resume evolves with each application
- **AI-Optimized Instructions**: Clear guidelines for AI assistants to provide actionable feedback
- **Implementation Tracking**: Keep track of which suggestions you've implemented
- **Discovery Logging**: Document insights about your career narrative

## Quick Start

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/cursor-cv.git
   cd cursor-cv
   ```

2. **Set up your personal information**
   - Copy `resume-template.md` to `resume.md` and fill in your information (or just paste your resume as .md)
   - Copy `about-candidate-log.md` and rename it with your name

3. **Add a job description**
   - Create a new file in `job-descriptions/` with the role you're applying for

4. **Get AI feedback**
   - Use the `instructions.md` file with your preferred AI assistant (Claude, ChatGPT, etc.)
   - The AI will create a detailed review using the templates provided

5. **Implement changes**
   - Use `feedback/implementation.md` to track which suggestions you implement
   - Save new versions in `resume-versions/` with descriptive names

## Repository Structure

```
cursor-cv/
├── README.md                    # This file
├── instructions.md              # Instructions for AI assistants
├── about-candidate-log.md       # Template for tracking insights
├── resume-template.md           # Starting resume template
├── resume.md                    # Your current resume (create from template)
├── feedback/
│   ├── template.md             # Review template
│   ├── implementation.md       # Implementation tracking
│   └── reviews/                # Store completed reviews here
├── job-descriptions/           # Target job descriptions
│   └── [company-role].md
└── resume-versions/            # Version history
    ├── README.md              # Version control best practices
    └── v1-baseline-[date].md
```

## How It Works

### 1. Prepare Your Materials
- Add your current resume
- Add job descriptions you're targeting
- Review the templates to understand the analysis structure

### 2. Run AI Analysis
The AI assistant will:
- Score your resume across multiple dimensions
- Identify keyword matches and gaps
- Suggest specific improvements
- Highlight strengths to emphasize

### 3. Implement Feedback
- Review suggestions systematically
- Update your resume based on priorities
- Save versions before major changes
- Track what changes had the most impact

### 4. Iterate and Improve
- Run new analyses for each application
- Build a library of optimized versions
- Learn what works for different role types
- Refine your career narrative

## Best Practices

### For Resume Versions
- Always save a version before major changes
- Use descriptive filenames: `v2-product-manager-focus-2024-01-15.md`
- Document why you made specific changes
- Keep a "master" version with all experiences

### For AI Feedback
- Be specific about the role and company
- Include the full job description
- Ask for examples when suggestions are vague
- Get multiple perspectives on major changes

### For Implementation
- Prioritize changes that address "High Priority Gaps"
- Make one type of change at a time to measure impact
- Keep technical accuracy when adding keywords
- Maintain authenticity while optimizing

## Tips for Success

1. **Keyword Optimization**: The system helps identify missing keywords without keyword stuffing
2. **Quantification**: AI will suggest where to add metrics and specific achievements
3. **Narrative Building**: Use the discovery log to refine your career story
4. **Version Testing**: A/B test different versions for similar roles

## Contributing

We welcome contributions! Please see our contributing guidelines (coming soon) for:
- Additional templates for different industries
- Improved AI prompting strategies
- Success stories and case studies
- Integration tools and scripts

## Privacy Note

This repository is designed to work with your personal data locally. Never commit sensitive information like:
- Phone numbers
- Email addresses
- Physical addresses
- References' contact information

Use the template placeholders and keep personal data in `.gitignore`'d files.

## License

MIT License - See LICENSE file for details

## Acknowledgments

Created to help job seekers leverage AI tools effectively while maintaining control over their career narratives.

---

**Remember**: AI feedback is a tool, not a replacement for human judgment. Always review suggestions critically and maintain your authentic voice.