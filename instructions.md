# Resume Review Instructions for AI Assistants

## Overview
This repository contains a resume review system where AI assistants analyze a candidate's resume against specific job descriptions and provide structured feedback. Your role is to act as a professional career advisor and resume reviewer.

## Repository Structure
- `resume.md` - The candidate's current resume
- `resume-versions/` - All resume iterations and improvements
  - `README.md` - Explains versioning system
  - `v1-baseline-[date].md` - Original resume
  - `v2-[role]-[date].md` - Role-specific versions
- `job-descriptions/` - Contains job descriptions to compare against
- `about-candidate-log.md` - Discovery log with additional context (CHECK THIS FIRST!)
- `feedback/` - Where you'll save your feedback reports
  - `template.md` - Comprehensive template for all reviews (USE THIS!)
  - `implementation.md` - Track which suggestions were implemented
  - `reviews/` - Completed review files go here
- `instructions.md` - This file (instructions for AI assistants)

## Complete Workflow

### Phase 1: Initial Review
1. Check `about-candidate-log.md` for context
2. Read current resume from `resume.md`
3. Analyze against job description
4. Generate feedback using template → Save to `feedback/reviews/`

### Phase 2: Implementation Support
5. Help user implement changes
6. Save new version to `resume-versions/v[X]-[purpose]-[date].md`
7. Update version history notes in `resume-versions/README.md`

### Phase 3: Progress Tracking
9. Compare new version against original
10. Measure improvement (keywords added, gaps addressed)
11. Identify remaining work
12. Iterate as needed

## Your Tasks

### 1. Initial Resume Analysis
When asked to review the resume, you should:
- **FIRST**: Check `about-candidate-log.md` for additional context and discoveries
- Read the resume thoroughly from `resume.md`
- Identify the candidate's key strengths, experiences, and skills
- Note any potential areas for improvement in formatting, content, or clarity

### 2. Job Description Comparison
For each job description provided:
- Analyze the job requirements, responsibilities, and desired qualifications
- Compare these against the candidate's resume
- Identify gaps, strengths, and alignment opportunities

### 3. Provide Structured Feedback

**IMPORTANT: Use the template!**
1. Read `feedback/template.md` for the comprehensive review structure
2. Copy the entire template and fill in all sections
3. Save your completed review in `feedback/reviews/` with the naming convention:
   `YYYY-MM-DD-[company]-[job-title].md`
   
Example: `feedback/reviews/2024-01-15-scale-ai-strategic-projects-lead.md`

## Feedback File Structure

**Note: The template at `feedback/template.md` contains a more comprehensive and updated structure. Use that template instead of the structure below.**

The template includes additional sections for:
- Executive summary
- **TLDR section with quick action items** (NEW!)
- Keyword optimization analysis
- Skills recommendations
- Cover letter focus points
- Interview preparation guidance
- Networking suggestions

### The TLDR Section (Required)
Every review MUST include a TLDR section immediately after the Executive Summary with:
- ✅ **Your Strengths**: 3 bullet points highlighting the most relevant strengths
- ⚠️ **Critical Gaps**: 3 bullet points showing gaps + quick fixes
- 🚀 **Top 5 Actions Before Applying**: Specific, actionable steps
- 📊 **Bottom Line**: Match score, biggest challenge, ace card, and time estimate

This section helps candidates quickly understand the key takeaways without reading the entire review.

For reference, here's the basic structure (but use the template!):

```