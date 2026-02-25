---
name: videodb-launch-generator
description: Generate comprehensive social media launch content for VideoDB features and products
version: 1.0.0
author: VideoDB Team
tags: [content-generation, marketing, social-media, product-launch]
triggers:
  - "generate launch content"
  - "create launch materials"
  - "videodb launch"
  - "social media content for launch"
  - "launch brief"
  - "launch content for github.com"
  - "create launch for https://github.com"
  - "launch content based on video"
  - "generate content from script"
  - "create launch from demo video"
---

# VideoDB Launch Content Generator

Generate comprehensive social media launch content for VideoDB features and products in the voice of a technical founder who builds in public.

## Quick Start

You can generate launch content by:

### Option 1: Provide a GitHub Repository
```
Generate launch content for https://github.com/video-db/focusd
```

### Option 2: Use a Video or Script
```
Generate launch content from this demo video: /path/to/demo.mp4
Create launch materials based on this script: /path/to/script.md
```

### Option 3: Provide a Launch Brief
- **Product/Feature Name**: What you're launching
- **What It Is**: 1-2 line description
- **Technical Details**: How it works
- **Key Benefits**: What problems it solves
- **Target Audience**: Who should care
- **Differentiation**: What makes it unique
- **Pricing**: If applicable
- **Call to Action**: What users should do

## Generated Content

The skill generates ready-to-publish content for:

### Primary Channels
- **Twitter/X**: Thread (5-7 tweets) + single tweet variations
- **LinkedIn**: Professional developer-focused post
- **HackerNews**: Show HN submission
- **Reddit**: r/programming and relevant subreddit posts

### Community & Outreach
- **Discord**: Announcement for developer servers
- **Cold DM Templates**: Personalized outreach messages
- **UGC Scripts**: For user-generated content
- **Blog Outline**: Technical deep-dive structure

### Visual Assets
- **Image Briefs**: Descriptions for each platform's visuals
- **GIF/Video Concepts**: Motion content ideas

## Core Workflow

1. **Parse Launch Brief**
   - Extract key information from user input
   - Identify missing elements and use defaults
   - Determine launch type (feature/product/integration)

2. **Apply Voice Guidelines**
   - Technical founder tone: direct, precise, developer-focused
   - No marketing fluff or buzzwords
   - Platform-native adjustments

3. **Generate Platform Content**
   - Follow character limits and format constraints
   - Include relevant technical details
   - Add appropriate CTAs and links

4. **Create Image Briefs**
   - VideoDB purple (#7C3AED) on dark backgrounds
   - Terminal/code aesthetic
   - Platform-specific dimensions

5. **Format Output**
   - Clean markdown structure
   - Copy-paste ready sections
   - Clear platform headers

## Voice Characteristics

**Core Voice:**
- Technical founder who builds in public
- Direct and precise language
- Developer-focused messaging
- No corporate speak or marketing jargon
- Natural, conversational tone (like talking to a friend)
- Personal experience over generic observations
- Specific examples and real numbers

**Natural Writing Patterns:**
- Mix short and long sentences
- Use contractions naturally ("we're", "it's", "doesn't")
- Start sentences simply, avoid "Additionally" or "Furthermore"
- Include uncertainty when real ("I think", "probably", "might")
- Personal pronouns ("I built", "we discovered")

**Banned Words:**
- Revolutionary, game-changing, cutting-edge
- Leverage, synergy, paradigm
- Seamless, robust, scalable (unless technically accurate)
- Empower, transform, innovate
- Additionally, Furthermore, Moreover (as openers)
- Testament, underscore, showcase
- Delve, embark, spearhead, navigate

**AI Patterns to Avoid:**
- Significance inflation ("paradigm shift" → "saves 6 hours")
- Vague attributions ("studies show" → cite specific source)
- Rule-of-three lists everywhere
- Em dash overuse
- Chatbot endings ("I hope this helps!")

**Platform Adjustments:**
- Twitter: Punchy, thread-friendly
- LinkedIn: Professional but not corporate
- HackerNews: Technical depth, humility
- Reddit: Community-first, helpful
- Discord: Casual, engaging

## Input Format

```markdown
**Launch Brief**

**Product/Feature Name:** [Name]

**What It Is:** [1-2 line description]

**Technical Details:**
- [Implementation detail 1]
- [Implementation detail 2]
- [Technical architecture notes]

**Key Benefits:**
- [Benefit 1]
- [Benefit 2]
- [Benefit 3]

**Target Audience:** [Primary audience description]

**Differentiation:** [What makes this unique]

**Pricing:** [Pricing model or "Free"]

**Call to Action:** [Primary action for users]

**Links:**
- Documentation: [URL]
- Demo: [URL]
- GitHub: [URL]
```

## Output Structure

The skill generates a single markdown document with:

```markdown
# VideoDB Launch Content: [Product Name]

## 🐦 Twitter/X Thread

### Main Thread (5-7 tweets)
[Thread content with numbering]

### Single Tweet Variations
[3 standalone tweet options]

## 💼 LinkedIn Post
[Full LinkedIn post]

## 🚀 HackerNews Submission
[Title and description]

## 🔴 Reddit Posts

### r/programming
[Post content]

### r/[relevant_subreddit]
[Post content]

## 💬 Discord Announcement
[Server announcement]

## ✉️ Cold DM Templates

### Template 1: Developer Outreach
[Personalized message]

### Template 2: Community Leader
[Personalized message]

## 📹 UGC Script
[30-60 second script]

## 📝 Blog Outline
[Technical blog structure]

## 🎨 Image Briefs
[Descriptions for visual content]
```

## Usage Examples

### Example 1: Feature Launch
```
Generate launch content for VideoDB Scene Indexing feature
```

### Example 2: GitHub Repository
```
Generate launch content for https://github.com/video-db/focusd
```
```
Create launch materials for github.com/video-db/async-recorder
```

### Example 3: Video or Script Based
```
Generate launch content based on this demo video: /path/to/product-demo.mp4
```
```
Create launch materials from this script: /path/to/launch-script.md
```
```
Generate social media content from our product walkthrough video
```

### Example 4: With Brief
```
Generate launch content:
**Product/Feature Name:** Scene Indexing API
**What It Is:** Automatically understand and index video content...
```

## Advanced Options

- **Tone Override**: Adjust formality level
- **Platform Focus**: Generate only specific platforms
- **Technical Depth**: Increase/decrease technical details
- **Audience Variant**: Target different developer segments

## Error Handling

If launch brief is incomplete:
- Use reasonable defaults
- Focus on provided information
- Note missing elements in output comments

## References

Detailed prompts and guidelines:
- `references/system-prompt.md` - Full generation system
- `references/voice-guidelines.md` - Voice and style rules
- `references/platform-templates.md` - Platform-specific templates
- `examples/` - Sample launch briefs and outputs

## Testing

Test with example briefs in `examples/`:
- `feature-launch.md` - Scene indexing feature
- `product-launch.md` - SDK release
- `integration-launch.md` - Partner integration

---

*For updates or customization, modify reference files in `references/` directory.*