# VideoDB Launch Content Generator

> 🚀 Generate comprehensive social media launch content for VideoDB features and products in the voice of a technical founder who builds in public.

## Overview

This skill generates ready-to-publish content for all major platforms from a single launch brief. It creates naturally-written content that sounds like a real developer talking to their community, not AI-generated marketing copy.

## ✨ Features

- **Multi-Platform Content**: Twitter/X threads, LinkedIn posts, HackerNews submissions, Reddit posts, Discord announcements, cold DMs, UGC scripts, and blog outlines
- **Natural Human Voice**: Uses advanced humanization techniques to avoid AI-generated patterns
- **Developer-Focused**: Technical founder voice that builds in public
- **Platform-Native Tones**: Adapts style for each platform while maintaining consistency
- **Image Briefs**: Includes descriptions for visual content with brand guidelines
- **Copy-Paste Ready**: Clean markdown output ready for immediate use

## 🎯 What It Generates

From a single launch brief, get:

| Platform | Content Type | Optimized For |
|----------|-------------|---------------|
| **Twitter/X** | 5-7 tweet thread + 3 variations | Engagement, hooks, viral potential |
| **LinkedIn** | Professional post with structure | Developer professionals, decision makers |
| **HackerNews** | Show HN submission | Technical depth, humble tone |
| **Reddit** | r/programming + custom subreddit | Community value, no promotion |
| **Discord** | Community announcement | Quick updates, casual tone |
| **Cold DMs** | 2 personalized templates | Developer outreach, community leaders |
| **UGC Script** | 30-60 second video script | Demo content, social proof |
| **Blog** | Technical deep-dive outline | SEO, technical authority |
| **Images** | Platform-specific briefs | Visual consistency, brand alignment |

## 🚀 Quick Start

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/videodb-launch-generator.git
cd videodb-launch-generator
```

2. If using with Claude Code CLI:
```bash
# Add to your Claude skills directory
cp -r videodb-launch-generator ~/.claude/skills/
```

### Usage

#### With Claude Code

Simply trigger the skill with natural language:

```
"Generate launch content for Scene Indexing API"
"Create launch materials for our Python SDK"
"VideoDB launch for Langchain integration"
```

#### Standalone Usage

Provide a launch brief with these details:

```markdown
**Product/Feature Name:** Scene Indexing API
**What It Is:** Automatically understand video content with one API call
**Technical Details:** CLIP for vision, Whisper for audio, 5x real-time
**Key Benefits:** Replace 47 lines of code with 3 lines
**Target Audience:** Developers building video applications
**Differentiation:** Single API vs 4 separate services
**Pricing:** Free tier: 10 hours/month, Pro: $0.01/minute
**Call to Action:** Try the API with your own video
**Links:** docs.videodb.io, demo.videodb.io, github.com/videodb
```

## 📁 Directory Structure

```
videodb-launch-generator/
├── SKILL.md                    # Main skill configuration
├── README.md                   # This file
├── references/                 # Core prompts and guidelines
│   ├── system-prompt.md        # Generation system and rules
│   ├── voice-guidelines.md     # Natural voice and style guide
│   ├── platform-templates.md   # Platform-specific templates
│   ├── natural-writing-examples.md  # Before/after examples
│   └── example-outputs.md      # Complete example output
├── examples/                   # Sample launch briefs
│   ├── feature-launch.md       # Scene indexing example
│   ├── product-launch.md       # SDK release example
│   └── integration-launch.md   # Partner integration example
└── assets/                     # Templates and resources
    └── output-template.md      # Output markdown structure
```

## 🎨 Natural Writing System

This skill uses advanced humanization techniques to avoid AI-generated patterns:

### Two-Pass Writing Process

1. **Pass 1: Write Naturally**
   - Write as if explaining to a friend
   - Use personal experience and specific examples
   - Include opinions and uncertainty

2. **Pass 2: Remove AI Patterns**
   - Delete formulaic transitions ("Additionally", "Furthermore")
   - Replace vague claims with specifics
   - Remove significance inflation
   - Fix awkward constructions

### Examples of Natural Writing

| ❌ AI-Generated | ✅ Natural Human |
|-----------------|------------------|
| "In today's fast-paced digital landscape..." | "Here's what happened:" |
| "This revolutionary solution transforms..." | "We built this because X sucked" |
| "Additionally, it's important to note..." | "Also, here's the thing:" |
| "Numerous benefits including..." | "Saves 6 hours and $50K/month" |

## 🔧 Customization

### Modify Voice and Tone

Edit `references/voice-guidelines.md` to adjust:
- Voice characteristics
- Banned words and phrases
- Platform-specific tones
- Natural writing patterns

### Add New Platforms

1. Add template to `references/platform-templates.md`
2. Update generation rules in `references/system-prompt.md`
3. Add example in `references/example-outputs.md`

### Customize for Your Brand

- Replace VideoDB references with your company
- Adjust color schemes in image briefs
- Modify voice to match your founder style
- Add company-specific examples

## 📚 Examples

### Input: Simple Feature Launch

```
Generate launch content for Scene Indexing API
```

### Output: Complete Content Package

- Twitter thread with viral hooks
- LinkedIn post for professional audience
- HackerNews submission with technical depth
- Reddit posts for multiple communities
- Discord announcement for developer servers
- Cold DM templates for outreach
- UGC script for video content
- Blog outline for SEO
- Image briefs for all platforms

See `examples/` directory for complete launch brief examples.

## 🏆 Best Practices

1. **Provide Complete Launch Briefs**: More detail yields better content
2. **Include Real Metrics**: "Processes 1080p at 5x speed" not "fast processing"
3. **Specify Technical Details**: Architecture decisions, benchmarks, trade-offs
4. **Know Your Audience**: Helps tailor messaging appropriately
5. **Be Honest About Limitations**: Builds trust with developer audience

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Areas for improvement:

- Additional platform templates
- More natural writing patterns
- Industry-specific customizations
- Localization for different markets

## 📝 License

MIT License - feel free to use this for your own product launches!

## 🙏 Acknowledgments

- Inspired by the [humanizer](https://github.com/blader/humanizer) skill for natural writing techniques
- Built for the VideoDB team but useful for any technical product launch
- Examples based on real VideoDB product launches

## 💬 Support

- **Issues**: Please open an issue for bugs or feature requests
- **Discussions**: Share your launch success stories or customizations
- **Contact**: Reach out to the VideoDB team for questions

---

**Built with ❤️ for developers who build in public**

*Note: This skill generates content in the voice of a technical founder. Adjust the voice guidelines for different brand personalities.*