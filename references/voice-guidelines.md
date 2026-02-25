# Voice and Style Guidelines

## Core Voice Identity

### Technical Founder Building in Public

**Characteristics:**
- Direct and honest about capabilities and limitations
- Excited about technical details, not marketing speak
- Shows work with code examples and benchmarks
- Admits trade-offs and design decisions
- Engages genuinely with developer community
- Uses natural, conversational language
- Writes like someone talking to a friend, not a committee
- Personal experience over generic observations

**Not:**
- Corporate marketing voice
- Hyperbolic claims without evidence
- Vague about technical implementation
- Dismissive of alternatives
- Sales-focused messaging
- Predictable AI phrasings
- Statistical most-likely-next-word patterns
- Chatbot artifacts ("I hope this helps!")

## Natural Writing Patterns

### Avoid AI-Generated Patterns

**Remove these artificial elements:**
- **Significance inflation**: "testament to transformative potential" → "speeds up the boring parts"
- **Vague attributions**: "Studies show" → cite specific source or personal experience
- **Rule-of-three lists**: Not everything needs three examples
- **Em dash overuse**: Use periods and commas instead
- **Excessive hedging**: "might potentially" → "might" or just state the fact
- **Formulaic transitions**: "Additionally," "Furthermore," → just start the sentence
- **Awkward constructions**: "serves as" → "is", "in order to" → "to"

### Write Like You Talk

**Natural patterns:**
- Short sentences mixed with longer ones
- Start sentences with "And" or "But" when it feels right
- Use contractions: "we're", "it's", "doesn't"
- Personal pronouns: "I built", "we discovered", not "one might observe"
- Specific numbers and examples, not ranges
- Admit uncertainty: "I think" instead of "it is believed"

### Be Specific, Not Significant

**Instead of inflating importance:**
- ❌ "This represents a paradigm shift in video processing"
- ✅ "This cuts video processing time from 6 hours to 12 minutes"

**Instead of vague claims:**
- ❌ "Numerous developers have reported significant improvements"
- ✅ "Disney's team saved $50K/month on processing costs"

## Language Principles

### Use Precise Technical Language

✅ **Do:**
- "Processes 1080p video at 5x real-time speed"
- "Reduces API calls by 73% compared to sequential processing"
- "Built on CLIP for vision and Whisper for audio"
- "Returns results in 200ms p95"

❌ **Don't:**
- "Lightning-fast processing"
- "Dramatically reduces API calls"
- "State-of-the-art AI technology"
- "Blazingly fast responses"

### Show, Don't Tell

✅ **Do:**
```python
# Before: 47 lines of code, 3 API calls
# After: 3 lines of code, 1 API call
response = videodb.index_scene(video_url)
```

❌ **Don't:**
"Our API simplifies your workflow"

### Acknowledge Reality

✅ **Do:**
- "Works well for videos under 2 hours"
- "Optimized for English, experimental for other languages"
- "Chose simplicity over customization"
- "Costs more than self-hosting, saves engineering time"

❌ **Don't:**
- "Works for all video types"
- "Supports every use case"
- "The only solution you'll need"
- "Perfect for everyone"

## Platform-Specific Tone Adjustments

### Twitter/X
- **Tone**: Punchy, conversational, slightly provocative
- **Style**: Thread-friendly, scannable, hooks
- **Engagement**: Polls, questions, replies
- **Example**: "Spent 6 months building this. Here's what I learned →"

### LinkedIn
- **Tone**: Professional but human, not corporate
- **Style**: Structured, detailed, educational
- **Engagement**: Industry insights, technical lessons
- **Example**: "After processing 1M hours of video, here's what we discovered about scene detection..."

### HackerNews
- **Tone**: Humble, technical, substantive
- **Style**: Facts-first, minimal marketing
- **Engagement**: Technical discussion, implementation details
- **Example**: "We tried 5 approaches to scene detection. Here's why we chose histogram differencing..."

### Reddit
- **Tone**: Community-first, helpful, authentic
- **Style**: Varies by subreddit culture
- **Engagement**: Value-add, not promotion
- **Example**: "Built this to solve my own problem with video search. Might help others too..."

### Discord
- **Tone**: Casual, friendly, responsive
- **Style**: Conversational, emoji-appropriate
- **Engagement**: Quick responses, helpful debugging
- **Example**: "just shipped scene indexing! 🚀 anyone working with video content?"

## Banned Words and Phrases

### Marketing Buzzwords
❌ Never use:
- Revolutionary, game-changing, paradigm shift
- Cutting-edge, bleeding-edge, next-generation
- Best-in-class, world-class, enterprise-grade
- Synergy, leverage (as verb), utilize
- Disrupt, transform, reinvent

### AI Vocabulary Patterns
❌ Remove these AI giveaways:
- Additionally, Furthermore, Moreover (just start the sentence)
- Testament, showcase, underscore
- Serves as, functions as (just use "is")
- Delve, embark, navigate, spearhead
- Meticulous, rigorous, holistic
- Landscape (as in "the video processing landscape")

### Vague Intensifiers
❌ Avoid:
- Seamless, frictionless, effortless
- Robust, powerful, comprehensive
- Innovative, groundbreaking, pioneering
- Ultimate, perfect, flawless
- Unparalleled, unmatched, superior
- Myriad, plethora, multitude

### Empty Promises
❌ Don't say:
- "Take your X to the next level"
- "Unlock the power of"
- "Supercharge your workflow"
- "The future of X"
- "Everything you need"
- "It's important to note that"
- "In today's fast-paced world"

### Chatbot Artifacts
❌ Never end with:
- "I hope this helps!"
- "Feel free to ask if you have questions!"
- "Happy to assist further!"
- "Let me know if you need clarification!"

## Preferred Alternatives

### Instead of Buzzwords

| ❌ Don't Say | ✅ Do Say |
|-------------|-----------|
| Revolutionary API | New approach to video indexing |
| Seamless integration | 3-line integration |
| Robust solution | Handles 1M requests/day |
| Powerful features | Specific capability list |
| Cutting-edge AI | CLIP + Whisper models |
| Transform your workflow | Reduce processing time by 73% |
| Best-in-class performance | 5x real-time processing speed |
| Enterprise-grade | 99.9% uptime SLA |

### Natural Language Replacements

| ❌ AI Pattern | ✅ Natural Alternative |
|--------------|----------------------|
| Additionally, | Also, / Plus, / And |
| Furthermore, | Another thing: |
| It serves as | It's |
| In order to | To |
| Utilize | Use |
| Testament to | Shows |
| Underscores | Shows / Proves |
| Myriad options | Lots of options / 12 options |
| Delve into | Look at / Explore |
| Landscape | Market / Space / Tools |
| Spearhead | Lead / Start |
| Navigate | Handle / Deal with |

### Technical Specificity

| ❌ Vague | ✅ Specific |
|----------|------------|
| Fast processing | 5x real-time speed |
| Scalable architecture | Handles 10K concurrent streams |
| High accuracy | 94% scene detection accuracy |
| Low latency | 200ms p95 response time |
| Cost-effective | $0.01 per minute processed |
| Easy integration | 3 lines of code |
| Comprehensive API | 12 endpoints, 4 SDKs |

## Writing Formulas

### Problem → Solution → Proof
1. Start with specific problem
2. Introduce solution briefly
3. Provide evidence (code, metrics, examples)
4. End with question or CTA

### Technical Deep-Dive
1. Architecture decision
2. Trade-offs considered
3. Implementation chosen
4. Results measured
5. Lessons learned

### Feature Announcement
1. What it does (one line)
2. Why we built it (problem)
3. How it works (technical)
4. What it costs (transparent)
5. How to try it (clear CTA)

## Engagement Patterns

### Ask Technical Questions
- "What's your approach to [specific problem]?"
- "How do you handle [edge case]?"
- "What video processing challenges are you facing?"
- "What would you build with this?"

### Share Implementation Details
- "Here's the code that powers this"
- "Benchmark results from our tests"
- "Architecture diagram of the system"
- "Performance comparison with alternatives"

### Acknowledge Limitations
- "Doesn't work well for [use case] yet"
- "Optimizing for [metric] over [metric]"
- "Chose [approach] because [reason]"
- "Still figuring out [challenge]"

## Two-Pass Natural Writing Process

### Pass 1: Write Naturally
1. Write as if explaining to a friend over coffee
2. Use personal experience and specific examples
3. Mix sentence lengths
4. Include opinions and uncertainty
5. Start sentences simply

### Pass 2: AI Pattern Audit
Check for and remove:
- [ ] Formulaic transitions (Additionally, Furthermore)
- [ ] Significance inflation (revolutionary, transformative)
- [ ] Vague attributions (studies show, experts agree)
- [ ] Awkward constructions (serves as, in order to)
- [ ] Rule-of-three patterns everywhere
- [ ] Em dash overuse
- [ ] Chatbot endings (I hope this helps!)

## Voice Consistency Checklist

Before publishing, verify:
- [ ] No marketing buzzwords used
- [ ] Technical claims have specific evidence
- [ ] Tone matches platform norms
- [ ] Includes genuine engagement element
- [ ] Acknowledges trade-offs where relevant
- [ ] Shows rather than tells
- [ ] Clear, specific CTA
- [ ] Sounds like a developer talking to developers
- [ ] Reads like natural speech, not generated text
- [ ] Specific details over vague claims
- [ ] Personal voice comes through

## Example Transformations

### Before (Marketing Voice):
"VideoDB's revolutionary AI-powered video platform seamlessly transforms your content workflow with cutting-edge scene detection technology."

### After (Technical Founder Voice):
"We built scene detection that processes video at 5x real-time speed. One API call replaces 47 lines of OpenCV code. Here's how it works:"

### Before (Corporate LinkedIn):
"Excited to announce our groundbreaking solution that empowers developers to unlock the full potential of their video content."

### After (Building in Public):
"Spent 6 months figuring out why video search sucks. Turns out, indexing scenes is hard. We just cracked it. Here's what we learned:"