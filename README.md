<img width="1280" height="720" alt="ContentCalendar Builder" src="https://github.com/user-attachments/assets/9a9d9abc-65ec-425f-a209-1051f8410aa0" />

A local-first content calendar builder in HTML with built in voice writing analyzer so users can generate ideas in their own voice.


<H2>Features</H2> 

Calendar Generation
- Niche/Topic input — free-text field for any industry or audience
- Platform selection — LinkedIn, Instagram, TikTok/Reels, YouTube, X (Twitter), Newsletter, Community Post
- Month & year selector — any month from 2024–2030 (plan future months)
- Custom posting days — toggle individual days of the week (Mon–Sun)
- Week start preference — Monday or Sunday
- Pillar frequency sliders — per-pillar weight control for Educate, Story, Authority, Community, Promote
- AI-powered generation — calls your chosen AI provider to produce niche-specific ideas
- Local template fallback — generates from built-in idea banks if no API key is set
- 30-day calendar view — full month grid with post/non-post day distinction

<H2>Post Management (per card)<H2/>

- Inline editing — click any idea to edit it directly on the calendar
- Post locking — lock individual posts to protect them from regeneration
- Status tracking — Draft, Written, Scheduled, Published per post
- Swap idea — cycle to an alternative idea from the pillar's idea bank
- Drag & drop reordering — drag post cards between days to swap them

<H2>Actions Bar<H2/>
  
- Regenerate — get fresh AI ideas for all unlocked posts
- 💾 Save — auto-save current session to localStorage (restores on next open)
- 📚 Save to Library — archive the full calendar (with edits/locks/statuses) to a named library entry
- 🗑 Clear — reset the calendar to empty state
- Download .txt — plain text export
- Copy All — copy all post ideas to clipboard
- PDF — export as printable PDF
- Word Doc — export as .docx
- CSV — export as spreadsheet
- Slides — export as presentation-style slide deck
- iCal — export as .ics for Google Calendar, Notion, or any calendar app

  
<H2>Context / AI Tuning (AI+ row)<H2/>

- Tone — Professional, Casual, Witty, Inspirational, Educational, Bold, Empathetic
- Brand Voice — Expert Authority, Friendly, Playful, Minimalist, Storyteller, Community-First
- Target Audience — Beginners, Intermediate, Advanced, SMB, Entrepreneurs, Corporate, Students
- Content Style — Tips & How-Tos, Question-Based, Behind-the-Scenes, Data-Driven, Story-Driven, Trending Hooks
- Goal — Brand Awareness, Drive Traffic, Build Community, Generate Leads, Sell & Convert, Educate & Inform

<H2>Voice Analyzer<H2/>

- AI Analyze tab — paste 2–5 sample posts; AI detects tone, cadence, voice, audience, style, and goal
- Describe My Voice tab — 6 dropdowns (Tone, Cadence, Brand Voice, Content Style, Audience, Goal) + optional Voice Notes field
- Build My Voice Profile — assembles a profile from manual selections
- Voice trait cards — displays detected/selected attributes as labeled cards
- Apply to Calendar — pushes profile values into the Context row automatically
- 📋 Save to Library — saves the profile with a user-entered name to a persistent voice profile library
- Saved Voice Profiles section — card grid of all saved profiles with Load and Delete per card; shows source badge (🤖 AI or ✍️ Manual)
- Auto-load — restores last saved voice profile on page return

<H2>Saved Calendars<H2/>

- Save to Library — archives any calendar month with a name, niche, platform, post count, and save date
- Saved Calendars page — card grid of all saved months with Load and Delete per entry
- Sidebar badge — shows count of saved calendars in the nav

<H2>API Settings<H2/>

- Claude (Anthropic) — model selection, key storage
- OpenAI — key storage, GPT model selection
- Google Gemini — key storage, model selection
- Test Connection — validates the key before building
- Show/hide key — toggle visibility on all three key fields
- Keys stored locally — never sent anywhere except the chosen AI provider

<H2>App-wide<H2/>

- 6 themes — Sand (light), Arctic (light), Sage (light), Midnight (dark), Obsidian (dark), Plum (dark)
- Session persistence — full state saves to localStorage; restores on return
- Sidebar navigation — Calendar Builder, Voice Analyzer, API Settings, Saved Calendars, How to Use
- How to Use page — built-in reference guide covering all features with Quick Start, step-by-step walkthroughs, and Pro Tips


Responsive layout — adapts down to mobile widths
No build step — single self-contained HTML file, runs directly in the browser
