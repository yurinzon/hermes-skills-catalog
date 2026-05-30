# 📚 קטלוג הסקילים המלא של Hermes Agent
קובץ מידע מקיף ומובנה המרכז את כל **116 הסקילים** המותקנים והזמינים במערכת. קטלוג זה מחולק לפי קטגוריות פונקציונליות וכולל פרטי התקנה, תגיות, קישורים ל-GitHub ומדריך שימוש מעשי.
---
## 📂 תוכן העניינים (Categories)
* [ אפל ומערכות macOS (Apple)](#apple)
* [🤖 סוכני AI עצמאיים (Autonomous AI Agents)](#autonomous-ai-agents)
* [🎨 יצירתיות, עיצוב ותנועה (Creative & Design)](#creative)
* [📊 מדע נתונים ופייתון (Data Science)](#data-science)
* [⚙️ דאבופס וניהול משימות (Devops & Kanban)](#devops)
* [dogfood](#dogfood)
* [✉️ דואר אלקטרוני (Email)](#email)
* [🎮 גיימינג ושרתים (Gaming)](#gaming)
* [🐙 גיטהאב וניהול גרסאות (GitHub)](#github)
* [graphify](#graphify)
* [🔌 שרתי פרוטוקול MCP (Model Context Protocol)](#mcp)
* [🎵 מדיה, מוזיקה ווידאו (Media & Audio)](#media)
* [🧠 למידת מכונה ואינפרנס (MLOps & Models)](#mlops)
* [📓 הערות וניהול ידע (Note Taking & Obsidian)](#note-taking)
* [🦅 ייבוא סקילים מ-OpenClaw (Claw Imports)](#openclaw-imports)
* [💼 פרודוקטיביות וניהול משרד (Productivity & Office)](#productivity)
* [🛡️ אבטחה והנדסה הפוכה (Red Teaming)](#red-teaming)
* [🔍 מחקר אקדמי ומנטורשיפ (Research & Papers)](#research)
* [🏠 בית חכם (Smart Home)](#smart-home)
* [📱 רשתות חברתיות ויצירת תוכן (Social Media)](#social-media)
* [💻 פיתוח תוכנה ודיבאג (Software Development)](#software-development)
* [💎 פלאגינים ייעודיים (Specialist Plugins)](#yuanbao)

---
## <a id='apple'></a> אפל ומערכות macOS (Apple)
בקטגוריה זו מותקנים **5 סקילים** פעילים:

### ✦ apple-notes
* **תיאור:** Manage Apple Notes via memo CLI: create, search, edit.
* **תיקייה מקומית:** `apple/apple-notes`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `macos`
* **תגיות (Tags):** `Notes`, `Apple`, `macOS`, `note-taking`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/apple/apple-notes](https://github.com/NousResearch/hermes-agent/tree/main/skills/apple/apple-notes)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install apple-notes
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill apple-notes
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills apple-notes
   ```
---

### ✦ apple-reminders
* **תיאור:** Apple Reminders via remindctl: add, list, complete.
* **תיקייה מקומית:** `apple/apple-reminders`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `macos`
* **תגיות (Tags):** `Reminders`, `tasks`, `todo`, `macOS`, `Apple`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/apple/apple-reminders](https://github.com/NousResearch/hermes-agent/tree/main/skills/apple/apple-reminders)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install apple-reminders
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill apple-reminders
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills apple-reminders
   ```
---

### ✦ findmy
* **תיאור:** Track Apple devices/AirTags via FindMy.app on macOS.
* **תיקייה מקומית:** `apple/findmy`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `macos`
* **תגיות (Tags):** `FindMy`, `AirTag`, `location`, `tracking`, `macOS`, `Apple`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/apple/findmy](https://github.com/NousResearch/hermes-agent/tree/main/skills/apple/findmy)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install findmy
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill findmy
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills findmy
   ```
---

### ✦ imessage
* **תיאור:** Send and receive iMessages/SMS via the imsg CLI on macOS.
* **תיקייה מקומית:** `apple/imessage`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `macos`
* **תגיות (Tags):** `iMessage`, `SMS`, `messaging`, `macOS`, `Apple`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/apple/imessage](https://github.com/NousResearch/hermes-agent/tree/main/skills/apple/imessage)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install imessage
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill imessage
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills imessage
   ```
---

### ✦ macos-computer-use
* **תיאור:** Drive the macOS desktop in the background — screenshots, mouse, keyboard,
scroll, drag — without stealing the user's cursor, keyboard focus, or
Space. Works with any tool-capable model. Load this skill whenever the
`computer_use` tool is available.

* **תיקייה מקומית:** `apple/macos-computer-use`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `macos`
* **תגיות (Tags):** `computer-use`, `macos`, `desktop`, `automation`, `gui`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/apple/macos-computer-use](https://github.com/NousResearch/hermes-agent/tree/main/skills/apple/macos-computer-use)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install macos-computer-use
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill macos-computer-use
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills macos-computer-use
   ```
---

## <a id='autonomous-ai-agents'></a>🤖 סוכני AI עצמאיים (Autonomous AI Agents)
בקטגוריה זו מותקנים **5 סקילים** פעילים:

### ✦ claude-code
* **תיאור:** Delegate coding to Claude Code CLI (features, PRs).
* **תיקייה מקומית:** `autonomous-ai-agents/claude-code`
* **גרסה:** `2.2.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Coding-Agent`, `Claude`, `Anthropic`, `Code-Review`, `Refactoring`, `PTY`, `Automation`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/autonomous-ai-agents/claude-code](https://github.com/NousResearch/hermes-agent/tree/main/skills/autonomous-ai-agents/claude-code)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install claude-code
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill claude-code
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills claude-code
   ```
---

### ✦ codex
* **תיאור:** Delegate coding to OpenAI Codex CLI (features, PRs).
* **תיקייה מקומית:** `autonomous-ai-agents/codex`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Coding-Agent`, `Codex`, `OpenAI`, `Code-Review`, `Refactoring`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/autonomous-ai-agents/codex](https://github.com/NousResearch/hermes-agent/tree/main/skills/autonomous-ai-agents/codex)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install codex
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill codex
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills codex
   ```
---

### ✦ hermes-agent
* **תיאור:** Configure, extend, or contribute to Hermes Agent.
* **תיקייה מקומית:** `autonomous-ai-agents/hermes-agent`
* **גרסה:** `2.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `hermes`, `setup`, `configuration`, `multi-agent`, `spawning`, `cli`, `gateway`, `development`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install hermes-agent
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill hermes-agent
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills hermes-agent
   ```
---

### ✦ kanban-codex-lane
* **תיאור:** Use when a Hermes Kanban worker wants to run Codex CLI as an isolated implementation lane while Hermes keeps ownership of task lifecycle, reconciliation, testing, and handoff.
* **תיקייה מקומית:** `autonomous-ai-agents/kanban-codex-lane`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `kanban`, `codex`, `worktrees`, `autonomous-agents`, `prediction-market-bot`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/autonomous-ai-agents/kanban-codex-lane](https://github.com/NousResearch/hermes-agent/tree/main/skills/autonomous-ai-agents/kanban-codex-lane)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install kanban-codex-lane
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill kanban-codex-lane
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills kanban-codex-lane
   ```
---

### ✦ opencode
* **תיאור:** Delegate coding to OpenCode CLI (features, PR review).
* **תיקייה מקומית:** `autonomous-ai-agents/opencode`
* **גרסה:** `1.2.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Coding-Agent`, `OpenCode`, `Autonomous`, `Refactoring`, `Code-Review`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/autonomous-ai-agents/opencode](https://github.com/NousResearch/hermes-agent/tree/main/skills/autonomous-ai-agents/opencode)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install opencode
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill opencode
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills opencode
   ```
---

## <a id='creative'></a>🎨 יצירתיות, עיצוב ותנועה (Creative & Design)
בקטגוריה זו מותקנים **22 סקילים** פעילים:

### ✦ architecture-diagram
* **תיאור:** Dark-themed SVG architecture/cloud/infra diagrams as HTML.
* **תיקייה מקומית:** `creative/architecture-diagram`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `architecture`, `diagrams`, `SVG`, `HTML`, `visualization`, `infrastructure`, `cloud`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/architecture-diagram](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/architecture-diagram)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install architecture-diagram
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill architecture-diagram
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills architecture-diagram
   ```
---

### ✦ ascii-art
* **תיאור:** ASCII art: pyfiglet, cowsay, boxes, image-to-ascii.
* **תיקייה מקומית:** `creative/ascii-art`
* **גרסה:** `4.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `ASCII`, `Art`, `Banners`, `Creative`, `Unicode`, `Text-Art`, `pyfiglet`, `figlet`, `cowsay`, `boxes`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/ascii-art](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/ascii-art)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install ascii-art
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill ascii-art
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills ascii-art
   ```
---

### ✦ ascii-video
* **תיאור:** ASCII video: convert video/audio to colored ASCII MP4/GIF.
* **תיקייה מקומית:** `creative/ascii-video`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/ascii-video](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/ascii-video)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install ascii-video
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill ascii-video
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills ascii-video
   ```
---

### ✦ baoyu-article-illustrator
* **תיאור:** Article illustrations: type × style × palette consistency.
* **תיקייה מקומית:** `creative/baoyu-article-illustrator`
* **גרסה:** `1.57.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `article-illustration`, `creative`, `image-generation`
* **קישור קוד מקור (Git Link):** [https://github.com/JimLiu/baoyu-skills#baoyu-article-illustrator](https://github.com/JimLiu/baoyu-skills#baoyu-article-illustrator)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install baoyu-article-illustrator
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill baoyu-article-illustrator
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills baoyu-article-illustrator
   ```
---

### ✦ baoyu-comic
* **תיאור:** Knowledge comics (知识漫画): educational, biography, tutorial.
* **תיקייה מקומית:** `creative/baoyu-comic`
* **גרסה:** `1.56.1` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `comic`, `knowledge-comic`, `creative`, `image-generation`
* **קישור קוד מקור (Git Link):** [https://github.com/JimLiu/baoyu-skills#baoyu-comic](https://github.com/JimLiu/baoyu-skills#baoyu-comic)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install baoyu-comic
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill baoyu-comic
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills baoyu-comic
   ```
---

### ✦ baoyu-infographic
* **תיאור:** Infographics: 21 layouts x 21 styles (信息图, 可视化).
* **תיקייה מקומית:** `creative/baoyu-infographic`
* **גרסה:** `1.56.1` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `infographic`, `visual-summary`, `creative`, `image-generation`
* **קישור קוד מקור (Git Link):** [https://github.com/JimLiu/baoyu-skills#baoyu-infographic](https://github.com/JimLiu/baoyu-skills#baoyu-infographic)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install baoyu-infographic
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill baoyu-infographic
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills baoyu-infographic
   ```
---

### ✦ celestial-ux-design
* **תיאור:** Design and engineering guidelines for high-end, luxury, immersive web interfaces on mystic, astrology, tarot, and occult themes.
* **תיקייה מקומית:** `creative/celestial-ux-design`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `ux-ui`, `frontend`, `motion-graphics`, `luxury-design`, `tailwind`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/celestial-ux-design](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/celestial-ux-design)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install celestial-ux-design
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill celestial-ux-design
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills celestial-ux-design
   ```
---

### ✦ claude-design
* **תיאור:** Design one-off HTML artifacts (landing, deck, prototype).
* **תיקייה מקומית:** `creative/claude-design`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `design`, `html`, `prototype`, `ux`, `ui`, `creative`, `artifact`, `deck`, `motion`, `design-system`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/claude-design](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/claude-design)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install claude-design
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill claude-design
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills claude-design
   ```
---

### ✦ comfyui
* **תיאור:** Generate images, video, and audio with ComfyUI — install, launch, manage nodes/models, run workflows with parameter injection. Uses the official comfy-cli for lifecycle and direct REST/WebSocket API for execution.
* **תיקייה מקומית:** `creative/comfyui`
* **גרסה:** `5.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `macos`, `linux`, `windows`
* **תגיות (Tags):** `comfyui`, `image-generation`, `stable-diffusion`, `flux`, `sd3`, `wan-video`, `hunyuan-video`, `creative`, `generative-ai`, `video-generation`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/comfyui](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/comfyui)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install comfyui
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill comfyui
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills comfyui
   ```
---

### ✦ design-md
* **תיאור:** Author/validate/export Google's DESIGN.md token spec files.
* **תיקייה מקומית:** `creative/design-md`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `design`, `design-system`, `tokens`, `ui`, `accessibility`, `wcag`, `tailwind`, `dtcg`, `google`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/design-md](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/design-md)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install design-md
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill design-md
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills design-md
   ```
---

### ✦ excalidraw
* **תיאור:** Hand-drawn Excalidraw JSON diagrams (arch, flow, seq).
* **תיקייה מקומית:** `creative/excalidraw`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Excalidraw`, `Diagrams`, `Flowcharts`, `Architecture`, `Visualization`, `JSON`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/excalidraw](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/excalidraw)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install excalidraw
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill excalidraw
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills excalidraw
   ```
---

### ✦ humanizer
* **תיאור:** Humanize text: strip AI-isms and add real voice.
* **תיקייה מקומית:** `creative/humanizer`
* **גרסה:** `2.5.1` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `writing`, `editing`, `humanize`, `anti-ai-slop`, `voice`, `prose`, `text`
* **קישור קוד מקור (Git Link):** [https://github.com/blader/humanizer](https://github.com/blader/humanizer)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install humanizer
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill humanizer
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills humanizer
   ```
---

### ✦ ideation
* **תיאור:** Generate project ideas via creative constraints.
* **תיקייה מקומית:** `creative/creative-ideation`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Creative`, `Ideation`, `Projects`, `Brainstorming`, `Inspiration`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/creative-ideation](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/creative-ideation)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install ideation
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill ideation
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills ideation
   ```
---

### ✦ manim-video
* **תיאור:** Manim CE animations: 3Blue1Brown math/algo videos.
* **תיקייה מקומית:** `creative/manim-video`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/manim-video](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/manim-video)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install manim-video
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill manim-video
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills manim-video
   ```
---

### ✦ p5js
* **תיאור:** p5.js sketches: gen art, shaders, interactive, 3D.
* **תיקייה מקומית:** `creative/p5js`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `creative-coding`, `generative-art`, `p5js`, `canvas`, `interactive`, `visualization`, `webgl`, `shaders`, `animation`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/p5js](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/p5js)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install p5js
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill p5js
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills p5js
   ```
---

### ✦ pixel-art
* **תיאור:** Pixel art w/ era palettes (NES, Game Boy, PICO-8).
* **תיקייה מקומית:** `creative/pixel-art`
* **גרסה:** `2.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `creative`, `pixel-art`, `arcade`, `snes`, `nes`, `gameboy`, `retro`, `image`, `video`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/pixel-art](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/pixel-art)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install pixel-art
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill pixel-art
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills pixel-art
   ```
---

### ✦ popular-web-designs
* **תיאור:** 54 real design systems (Stripe, Linear, Vercel) as HTML/CSS.
* **תיקייה מקומית:** `creative/popular-web-designs`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `design`, `css`, `html`, `ui`, `web-development`, `design-systems`, `templates`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/popular-web-designs](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/popular-web-designs)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install popular-web-designs
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill popular-web-designs
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills popular-web-designs
   ```
---

### ✦ pretext
* **תיאור:** Use when building creative browser demos with @chenglou/pretext — DOM-free text layout for ASCII art, typographic flow around obstacles, text-as-geometry games, kinetic typography, and text-powered generative art. Produces single-file HTML demos by default.
* **תיקייה מקומית:** `creative/pretext`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `creative-coding`, `typography`, `pretext`, `ascii-art`, `canvas`, `generative`, `text-layout`, `kinetic-typography`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/pretext](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/pretext)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install pretext
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill pretext
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills pretext
   ```
---

### ✦ sketch
* **תיאור:** Throwaway HTML mockups: 2-3 design variants to compare.
* **תיקייה מקומית:** `creative/sketch`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `sketch`, `mockup`, `design`, `ui`, `prototype`, `html`, `variants`, `exploration`, `wireframe`, `comparison`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/sketch](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/sketch)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install sketch
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill sketch
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills sketch
   ```
---

### ✦ social-media-video-automation
* **תיאור:** Automated video generation with animated text overlays and automated Instagram Reels publishing using Pillow, FFmpeg, and instagrapi with session caching.
* **תיקייה מקומית:** `creative/social-media-video-automation`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/social-media-video-automation](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/social-media-video-automation)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install social-media-video-automation
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill social-media-video-automation
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills social-media-video-automation
   ```
---

### ✦ songwriting-and-ai-music
* **תיאור:** Songwriting craft and Suno AI music prompts.
* **תיקייה מקומית:** `creative/songwriting-and-ai-music`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `songwriting`, `music`, `suno`, `parody`, `lyrics`, `creative`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/songwriting-and-ai-music](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/songwriting-and-ai-music)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install songwriting-and-ai-music
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill songwriting-and-ai-music
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills songwriting-and-ai-music
   ```
---

### ✦ touchdesigner-mcp
* **תיאור:** Control a running TouchDesigner instance via twozero MCP — create operators, set parameters, wire connections, execute Python, build real-time visuals. 36 native tools.
* **תיקייה מקומית:** `creative/touchdesigner-mcp`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `TouchDesigner`, `MCP`, `twozero`, `creative-coding`, `real-time-visuals`, `generative-art`, `audio-reactive`, `VJ`, `installation`, `GLSL`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/touchdesigner-mcp](https://github.com/NousResearch/hermes-agent/tree/main/skills/creative/touchdesigner-mcp)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install touchdesigner-mcp
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill touchdesigner-mcp
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills touchdesigner-mcp
   ```
---

## <a id='data-science'></a>📊 מדע נתונים ופייתון (Data Science)
בקטגוריה זו מותקנים **1 סקילים** פעילים:

### ✦ jupyter-live-kernel
* **תיאור:** Iterative Python via live Jupyter kernel (hamelnb).
* **תיקייה מקומית:** `data-science/jupyter-live-kernel`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `jupyter`, `notebook`, `repl`, `data-science`, `exploration`, `iterative`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/data-science/jupyter-live-kernel](https://github.com/NousResearch/hermes-agent/tree/main/skills/data-science/jupyter-live-kernel)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install jupyter-live-kernel
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill jupyter-live-kernel
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills jupyter-live-kernel
   ```
---

## <a id='devops'></a>⚙️ דאבופס וניהול משימות (Devops & Kanban)
בקטגוריה זו מותקנים **3 סקילים** פעילים:

### ✦ kanban-orchestrator
* **תיאור:** Decomposition playbook + anti-temptation rules for an orchestrator profile routing work through Kanban. The "don't do the work yourself" rule and the basic lifecycle are auto-injected into every kanban worker's system prompt; this skill is the deeper playbook when you're specifically playing the orchestrator role.
* **תיקייה מקומית:** `devops/kanban-orchestrator`
* **גרסה:** `3.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `kanban`, `multi-agent`, `orchestration`, `routing`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/devops/kanban-orchestrator](https://github.com/NousResearch/hermes-agent/tree/main/skills/devops/kanban-orchestrator)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install kanban-orchestrator
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill kanban-orchestrator
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills kanban-orchestrator
   ```
---

### ✦ kanban-worker
* **תיאור:** Pitfalls, examples, and edge cases for Hermes Kanban workers. The lifecycle itself is auto-injected into every worker's system prompt as KANBAN_GUIDANCE (from agent/prompt_builder.py); this skill is what you load when you want deeper detail on specific scenarios.
* **תיקייה מקומית:** `devops/kanban-worker`
* **גרסה:** `2.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `kanban`, `multi-agent`, `collaboration`, `workflow`, `pitfalls`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/devops/kanban-worker](https://github.com/NousResearch/hermes-agent/tree/main/skills/devops/kanban-worker)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install kanban-worker
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill kanban-worker
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills kanban-worker
   ```
---

### ✦ webhook-subscriptions
* **תיאור:** Webhook subscriptions: event-driven agent runs.
* **תיקייה מקומית:** `devops/webhook-subscriptions`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `webhook`, `events`, `automation`, `integrations`, `notifications`, `push`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/devops/webhook-subscriptions](https://github.com/NousResearch/hermes-agent/tree/main/skills/devops/webhook-subscriptions)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install webhook-subscriptions
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill webhook-subscriptions
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills webhook-subscriptions
   ```
---

## <a id='dogfood'></a>dogfood
בקטגוריה זו מותקנים **1 סקילים** פעילים:

### ✦ dogfood
* **תיאור:** Exploratory QA of web apps: find bugs, evidence, reports.
* **תיקייה מקומית:** `dogfood/dogfood`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `qa`, `testing`, `browser`, `web`, `dogfood`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/dogfood/dogfood](https://github.com/NousResearch/hermes-agent/tree/main/skills/dogfood/dogfood)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install dogfood
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill dogfood
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills dogfood
   ```
---

## <a id='email'></a>✉️ דואר אלקטרוני (Email)
בקטגוריה זו מותקנים **1 סקילים** פעילים:

### ✦ himalaya
* **תיאור:** Himalaya CLI: IMAP/SMTP email from terminal.
* **תיקייה מקומית:** `email/himalaya`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Email`, `IMAP`, `SMTP`, `CLI`, `Communication`
* **קישור קוד מקור (Git Link):** [https://github.com/pimalaya/himalaya](https://github.com/pimalaya/himalaya)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install himalaya
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill himalaya
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills himalaya
   ```
---

## <a id='gaming'></a>🎮 גיימינג ושרתים (Gaming)
בקטגוריה זו מותקנים **2 סקילים** פעילים:

### ✦ minecraft-modpack-server
* **תיאור:** Host modded Minecraft servers (CurseForge, Modrinth).
* **תיקייה מקומית:** `gaming/minecraft-modpack-server`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `minecraft`, `gaming`, `server`, `neoforge`, `forge`, `modpack`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/gaming/minecraft-modpack-server](https://github.com/NousResearch/hermes-agent/tree/main/skills/gaming/minecraft-modpack-server)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install minecraft-modpack-server
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill minecraft-modpack-server
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills minecraft-modpack-server
   ```
---

### ✦ pokemon-player
* **תיאור:** Play Pokemon via headless emulator + RAM reads.
* **תיקייה מקומית:** `gaming/pokemon-player`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `gaming`, `pokemon`, `emulator`, `pyboy`, `gameplay`, `gameboy`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/gaming/pokemon-player](https://github.com/NousResearch/hermes-agent/tree/main/skills/gaming/pokemon-player)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install pokemon-player
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill pokemon-player
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills pokemon-player
   ```
---

## <a id='github'></a>🐙 גיטהאב וניהול גרסאות (GitHub)
בקטגוריה זו מותקנים **6 סקילים** פעילים:

### ✦ codebase-inspection
* **תיאור:** Inspect codebases w/ pygount: LOC, languages, ratios.
* **תיקייה מקומית:** `github/codebase-inspection`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `LOC`, `Code Analysis`, `pygount`, `Codebase`, `Metrics`, `Repository`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/github/codebase-inspection](https://github.com/NousResearch/hermes-agent/tree/main/skills/github/codebase-inspection)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install codebase-inspection
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill codebase-inspection
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills codebase-inspection
   ```
---

### ✦ github-auth
* **תיאור:** GitHub auth setup: HTTPS tokens, SSH keys, gh CLI login.
* **תיקייה מקומית:** `github/github-auth`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `GitHub`, `Authentication`, `Git`, `gh-cli`, `SSH`, `Setup`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/github/github-auth](https://github.com/NousResearch/hermes-agent/tree/main/skills/github/github-auth)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install github-auth
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill github-auth
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills github-auth
   ```
---

### ✦ github-code-review
* **תיאור:** Review PRs: diffs, inline comments via gh or REST.
* **תיקייה מקומית:** `github/github-code-review`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `GitHub`, `Code-Review`, `Pull-Requests`, `Git`, `Quality`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/github/github-code-review](https://github.com/NousResearch/hermes-agent/tree/main/skills/github/github-code-review)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install github-code-review
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill github-code-review
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills github-code-review
   ```
---

### ✦ github-issues
* **תיאור:** Create, triage, label, assign GitHub issues via gh or REST.
* **תיקייה מקומית:** `github/github-issues`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `GitHub`, `Issues`, `Project-Management`, `Bug-Tracking`, `Triage`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/github/github-issues](https://github.com/NousResearch/hermes-agent/tree/main/skills/github/github-issues)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install github-issues
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill github-issues
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills github-issues
   ```
---

### ✦ github-pr-workflow
* **תיאור:** GitHub PR lifecycle: branch, commit, open, CI, merge.
* **תיקייה מקומית:** `github/github-pr-workflow`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `GitHub`, `Pull-Requests`, `CI/CD`, `Git`, `Automation`, `Merge`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/github/github-pr-workflow](https://github.com/NousResearch/hermes-agent/tree/main/skills/github/github-pr-workflow)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install github-pr-workflow
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill github-pr-workflow
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills github-pr-workflow
   ```
---

### ✦ github-repo-management
* **תיאור:** Clone/create/fork repos; manage remotes, releases.
* **תיקייה מקומית:** `github/github-repo-management`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `GitHub`, `Repositories`, `Git`, `Releases`, `Secrets`, `Configuration`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/github/github-repo-management](https://github.com/NousResearch/hermes-agent/tree/main/skills/github/github-repo-management)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install github-repo-management
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill github-repo-management
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills github-repo-management
   ```
---

## <a id='graphify'></a>graphify
בקטגוריה זו מותקנים **1 סקילים** פעילים:

### ✦ graphify
* **תיאור:** any input (code, docs, papers, images) → knowledge graph → clustered communities → HTML + JSON + audit report. Use when user asks any question about a codebase, project content, architecture, or file relationships — especially if graphify-out/ exists. Provides persistent graph with god nodes, community detection, and BFS/DFS query tools.
* **תיקייה מקומית:** `graphify/graphify`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/graphify/graphify](https://github.com/NousResearch/hermes-agent/tree/main/skills/graphify/graphify)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install graphify
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill graphify
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills graphify
   ```
---

## <a id='mcp'></a>🔌 שרתי פרוטוקול MCP (Model Context Protocol)
בקטגוריה זו מותקנים **2 סקילים** פעילים:

### ✦ mcp-server-integration
* **תיאור:** Manage, configure, and programmatically interact with MCP (Model Context Protocol) servers in Hermes Agent. Covers non-interactive additions, programmatic tool calls, and browser-based authentication workflows.
* **תיקייה מקומית:** `mcp/mcp-server-integration`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `mcp`, `devops`, `python`, `automation`, `configuration`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mcp/mcp-server-integration](https://github.com/NousResearch/hermes-agent/tree/main/skills/mcp/mcp-server-integration)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install mcp-server-integration
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill mcp-server-integration
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills mcp-server-integration
   ```
---

### ✦ native-mcp
* **תיאור:** MCP client: connect servers, register tools (stdio/HTTP).
* **תיקייה מקומית:** `mcp/native-mcp`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `MCP`, `Tools`, `Integrations`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mcp/native-mcp](https://github.com/NousResearch/hermes-agent/tree/main/skills/mcp/native-mcp)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install native-mcp
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill native-mcp
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills native-mcp
   ```
---

## <a id='media'></a>🎵 מדיה, מוזיקה ווידאו (Media & Audio)
בקטגוריה זו מותקנים **5 סקילים** פעילים:

### ✦ gif-search
* **תיאור:** Search/download GIFs from Tenor via curl + jq.
* **תיקייה מקומית:** `media/gif-search`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `GIF`, `Media`, `Search`, `Tenor`, `API`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/media/gif-search](https://github.com/NousResearch/hermes-agent/tree/main/skills/media/gif-search)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install gif-search
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill gif-search
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills gif-search
   ```
---

### ✦ heartmula
* **תיאור:** HeartMuLa: Suno-like song generation from lyrics + tags.
* **תיקייה מקומית:** `media/heartmula`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `music`, `audio`, `generation`, `ai`, `heartmula`, `heartcodec`, `lyrics`, `songs`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/media/heartmula](https://github.com/NousResearch/hermes-agent/tree/main/skills/media/heartmula)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install heartmula
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill heartmula
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills heartmula
   ```
---

### ✦ songsee
* **תיאור:** Audio spectrograms/features (mel, chroma, MFCC) via CLI.
* **תיקייה מקומית:** `media/songsee`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Audio`, `Visualization`, `Spectrogram`, `Music`, `Analysis`
* **קישור קוד מקור (Git Link):** [https://github.com/steipete/songsee](https://github.com/steipete/songsee)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install songsee
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill songsee
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills songsee
   ```
---

### ✦ spotify
* **תיאור:** Spotify: play, search, queue, manage playlists and devices.
* **תיקייה מקומית:** `media/spotify`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `spotify`, `music`, `playback`, `playlists`, `media`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/media/spotify](https://github.com/NousResearch/hermes-agent/tree/main/skills/media/spotify)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install spotify
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill spotify
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills spotify
   ```
---

### ✦ youtube-content
* **תיאור:** YouTube transcripts to summaries, threads, blogs.
* **תיקייה מקומית:** `media/youtube-content`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/media/youtube-content](https://github.com/NousResearch/hermes-agent/tree/main/skills/media/youtube-content)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install youtube-content
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill youtube-content
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills youtube-content
   ```
---

## <a id='mlops'></a>🧠 למידת מכונה ואינפרנס (MLOps & Models)
בקטגוריה זו מותקנים **9 סקילים** פעילים:

### ✦ audiocraft-audio-generation
* **תיאור:** AudioCraft: MusicGen text-to-music, AudioGen text-to-sound.
* **תיקייה מקומית:** `mlops/audiocraft`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `Multimodal`, `Audio Generation`, `Text-to-Music`, `Text-to-Audio`, `MusicGen`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/audiocraft](https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/audiocraft)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install audiocraft-audio-generation
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill audiocraft-audio-generation
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills audiocraft-audio-generation
   ```
---

### ✦ dspy
* **תיאור:** DSPy: declarative LM programs, auto-optimize prompts, RAG.
* **תיקייה מקומית:** `mlops/dspy`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Prompt Engineering`, `DSPy`, `Declarative Programming`, `RAG`, `Agents`, `Prompt Optimization`, `LM Programming`, `Stanford NLP`, `Automatic Optimization`, `Modular AI`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/dspy](https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/dspy)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install dspy
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill dspy
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills dspy
   ```
---

### ✦ evaluating-llms-harness
* **תיאור:** lm-eval-harness: benchmark LLMs (MMLU, GSM8K, etc.).
* **תיקייה מקומית:** `mlops/lm-evaluation-harness`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `Evaluation`, `LM Evaluation Harness`, `Benchmarking`, `MMLU`, `HumanEval`, `GSM8K`, `EleutherAI`, `Model Quality`, `Academic Benchmarks`, `Industry Standard`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/lm-evaluation-harness](https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/lm-evaluation-harness)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install evaluating-llms-harness
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill evaluating-llms-harness
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills evaluating-llms-harness
   ```
---

### ✦ huggingface-hub
* **תיאור:** HuggingFace hf CLI: search/download/upload models, datasets.
* **תיקייה מקומית:** `mlops/huggingface-hub`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `huggingface`, `hf`, `models`, `datasets`, `hub`, `mlops`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/huggingface-hub](https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/huggingface-hub)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install huggingface-hub
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill huggingface-hub
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills huggingface-hub
   ```
---

### ✦ llama-cpp
* **תיאור:** llama.cpp local GGUF inference + HF Hub model discovery.
* **תיקייה מקומית:** `mlops/llama-cpp`
* **גרסה:** `2.1.2` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `llama.cpp`, `GGUF`, `Quantization`, `Hugging Face Hub`, `CPU Inference`, `Apple Silicon`, `Edge Deployment`, `AMD GPUs`, `Intel GPUs`, `NVIDIA`, `URL-first`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/llama-cpp](https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/llama-cpp)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install llama-cpp
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill llama-cpp
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills llama-cpp
   ```
---

### ✦ obliteratus
* **תיאור:** OBLITERATUS: abliterate LLM refusals (diff-in-means).
* **תיקייה מקומית:** `mlops/obliteratus`
* **גרסה:** `2.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `Abliteration`, `Uncensoring`, `Refusal-Removal`, `LLM`, `Weight-Projection`, `SVD`, `Mechanistic-Interpretability`, `HuggingFace`, `Model-Surgery`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/obliteratus](https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/obliteratus)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install obliteratus
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill obliteratus
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills obliteratus
   ```
---

### ✦ segment-anything-model
* **תיאור:** SAM: zero-shot image segmentation via points, boxes, masks.
* **תיקייה מקומית:** `mlops/segment-anything`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Multimodal`, `Image Segmentation`, `Computer Vision`, `SAM`, `Zero-Shot`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/segment-anything](https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/segment-anything)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install segment-anything-model
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill segment-anything-model
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills segment-anything-model
   ```
---

### ✦ serving-llms-vllm
* **תיאור:** vLLM: high-throughput LLM serving, OpenAI API, quantization.
* **תיקייה מקומית:** `mlops/vllm`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `vLLM`, `Inference Serving`, `PagedAttention`, `Continuous Batching`, `High Throughput`, `Production`, `OpenAI API`, `Quantization`, `Tensor Parallelism`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/vllm](https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/vllm)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install serving-llms-vllm
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill serving-llms-vllm
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills serving-llms-vllm
   ```
---

### ✦ weights-and-biases
* **תיאור:** W&B: log ML experiments, sweeps, model registry, dashboards.
* **תיקייה מקומית:** `mlops/weights-and-biases`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `MLOps`, `Weights And Biases`, `WandB`, `Experiment Tracking`, `Hyperparameter Tuning`, `Model Registry`, `Collaboration`, `Real-Time Visualization`, `PyTorch`, `TensorFlow`, `HuggingFace`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/weights-and-biases](https://github.com/NousResearch/hermes-agent/tree/main/skills/mlops/weights-and-biases)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install weights-and-biases
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill weights-and-biases
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills weights-and-biases
   ```
---

## <a id='note-taking'></a>📓 הערות וניהול ידע (Note Taking & Obsidian)
בקטגוריה זו מותקנים **1 סקילים** פעילים:

### ✦ obsidian
* **תיאור:** Read, search, create, and edit notes in the Obsidian vault.
* **תיקייה מקומית:** `note-taking/obsidian`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/note-taking/obsidian](https://github.com/NousResearch/hermes-agent/tree/main/skills/note-taking/obsidian)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install obsidian
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill obsidian
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills obsidian
   ```
---

## <a id='openclaw-imports'></a>🦅 ייבוא סקילים מ-OpenClaw (Claw Imports)
בקטגוריה זו מותקנים **20 סקילים** פעילים:

### ✦ brandkit
* **תיאור:** Premium brand-kit image generation skill for creating high-end brand-guidelines boards, logo systems, identity decks, and visual-world presentations. Trained for minimalist, cinematic, editorial, dark-tech, luxury, cultural, security, gaming, developer-tool, and consumer-app brand systems. Optimized for intentional logo concepting, refined composition, sparse typography, strong symbolic meaning, premium mockups, art-directed imagery, and flexible grid layouts.
* **תיקייה מקומית:** `openclaw-imports/brandkit`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install brandkit
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill brandkit
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills brandkit
   ```
---

### ✦ defuddle
* **תיאור:** Extract clean markdown content from web pages using Defuddle CLI, removing clutter and navigation to save tokens. Use instead of WebFetch when the user provides a URL to read or analyze, for online documentation, articles, blog posts, or any standard web page. Do NOT use for URLs ending in .md — those are already markdown, use WebFetch directly.
* **תיקייה מקומית:** `openclaw-imports/defuddle`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install defuddle
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill defuddle
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills defuddle
   ```
---

### ✦ design-taste-frontend
* **תיאור:** Senior UI/UX Engineer. Architect digital interfaces overriding default LLM biases. Enforces metric-based rules, strict component architecture, CSS hardware acceleration, and balanced design engineering.
* **תיקייה מקומית:** `openclaw-imports/design-taste-frontend`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install design-taste-frontend
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill design-taste-frontend
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills design-taste-frontend
   ```
---

### ✦ find-skills
* **תיאור:** Helps users discover and install agent skills when they ask questions like "how do I do X", "find a skill for X", "is there a skill that can...", or express interest in extending capabilities. This skill should be used when the user is looking for functionality that might exist as an installable skill.
* **תיקייה מקומית:** `openclaw-imports/find-skills`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install find-skills
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill find-skills
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills find-skills
   ```
---

### ✦ full-output-enforcement
* **תיאור:** Overrides default LLM truncation behavior. Enforces complete code generation, bans placeholder patterns, and handles token-limit splits cleanly. Apply to any task requiring exhaustive, unabridged output.
* **תיקייה מקומית:** `openclaw-imports/full-output-enforcement`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install full-output-enforcement
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill full-output-enforcement
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills full-output-enforcement
   ```
---

### ✦ gpt-taste
* **תיאור:** Elite UX/UI & Advanced GSAP Motion Engineer. Enforces Python-driven true randomization for layout variance, strict AIDA page structure, wide editorial typography (bans 6-line wraps), gapless bento grids, strict GSAP ScrollTriggers (pinning, stacking, scrubbing), inline micro-images, and massive section spacing.
* **תיקייה מקומית:** `openclaw-imports/gpt-taste`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install gpt-taste
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill gpt-taste
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills gpt-taste
   ```
---

### ✦ high-end-visual-design
* **תיאור:** Teaches the AI to design like a high-end agency. Defines the exact fonts, spacing, shadows, card structures, and animations that make a website feel expensive. Blocks all the common defaults that make AI designs look cheap or generic.
* **תיקייה מקומית:** `openclaw-imports/high-end-visual-design`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install high-end-visual-design
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill high-end-visual-design
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills high-end-visual-design
   ```
---

### ✦ huashu-design
* **תיאור:** 花叔Design（Huashu-Design）——用HTML做高保真原型、交互Demo、幻灯片、动画、设计变体探索+设计方向顾问+专家评审的一体化设计能力。HTML是工具不是媒介，根据任务embody不同专家（UX设计师/动画师/幻灯片设计师/原型师），避免web design tropes。触发词：做原型、设计Demo、交互原型、HTML演示、动画Demo、设计变体、hi-fi设计、UI mockup、prototype、设计探索、做个HTML页面、做个可视化、app原型、iOS原型、移动应用mockup、导出MP4、导出GIF、60fps视频、设计风格、设计方向、设计哲学、配色方案、视觉风格、推荐风格、选个风格、做个好看的、评审、好不好看、review this design、带解说的动画、解说视频、概念解释视频、长视频科普、配音动画、voiceover、narration、TTS+动画、5分钟讲清楚什么是XX。**主干能力**：Junior Designer工作流（先给假设+reasoning+placeholder再迭代）、反AI slop清单、React+Babel最佳实践、Tweaks变体切换、Speaker Notes演示、Starter Components（幻灯片外壳/变体画布/动画引擎/设备边框/解说Stage）、App原型专属守则（默认从Wikimedia/Met/Unsplash取真图、每台iPhone包AppPhone状态管理器可交互、交付前跑Playwright点击测试）、Playwright验证、HTML动画→MP4/GIF视频导出（25fps基础 + 60fps插帧 + palette优化GIF + 6首场景化BGM + 自动fade）、**带解说的长动画pipeline**（豆包TTS生人声+实测时长生timeline.json+NarrationStage驱动画面+ducking混音→交付HTML实播+发布MP4双形态；铁律：整片是一个连续的运动叙事，禁PowerPoint切换）。**需求模糊时的Fallback**：设计方向顾问模式——从5流派×20种设计哲学（Pentagram信息建筑/Field.io运动诗学/Kenya Hara东方极简/Sagmeister实验先锋等）推荐3个差异化方向，展示24个预制showcase（8场景×3风格），并行生成3个视觉Demo让用户选。**交付后可选**：专家级5维度评审（哲学一致性/视觉层级/细节执行/功能性/创新性各打10分+修复清单）。
* **תיקייה מקומית:** `openclaw-imports/huashu-design`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install huashu-design
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill huashu-design
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills huashu-design
   ```
---

### ✦ image-to-code
* **תיאור:** Elite website image-to-code skill for Codex. For visually important web tasks, it must first generate the design image(s) itself, deeply analyze them, then implement the website to match them as closely as possible. In Codex, it must prefer large, readable, section-specific images instead of tiny compressed boards, generate fresh standalone images for sections or detail views instead of cropping old ones, avoid lazy under-generation, avoid cards-inside-cards-inside-cards UI, and keep the hero clean, spacious, readable, and visible on a small laptop.
* **תיקייה מקומית:** `openclaw-imports/image-to-code`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install image-to-code
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill image-to-code
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills image-to-code
   ```
---

### ✦ imagegen-frontend-mobile
* **תיאור:** Elite mobile app image-generation skill for creating premium, app-native screen concepts and flows. Designed for iOS, Android, and cross-platform mobile products. Prioritizes clean hierarchy, comfortably readable text, strong multi-screen consistency, controlled color palettes, non-generic creative direction, textured surfaces, image-led composition, tasteful custom iconography, and clean phone mockup framing. By default, screens should be shown inside a subtle premium iPhone or similar phone mockup with a visible frame, while the main focus stays on the app content itself. This skill generates images only. It does not write code.
* **תיקייה מקומית:** `openclaw-imports/imagegen-frontend-mobile`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install imagegen-frontend-mobile
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill imagegen-frontend-mobile
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills imagegen-frontend-mobile
   ```
---

### ✦ imagegen-frontend-web
* **תיאור:** Elite frontend image-direction skill for generating premium, conversion-aware website design references. CRITICAL OUTPUT RULE — generate ONE separate horizontal image FOR EVERY section. A landing page with 8 sections produces 8 images. Never compress multiple sections into one image. Enforces composition variety (not always left-text / right-image), background-image freedom, varied CTAs, varied hero scales (giant / mid / mini minimalist), narrative concept spine, second-read moments, and a single consistent palette across all images. Optimized for landing pages, marketing sites, and product comps that developers or coding models can accurately recreate.
* **תיקייה מקומית:** `openclaw-imports/imagegen-frontend-web`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install imagegen-frontend-web
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill imagegen-frontend-web
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills imagegen-frontend-web
   ```
---

### ✦ impeccable
* **תיאור:** Use when the user wants to design, redesign, shape, critique, audit, polish, clarify, distill, harden, optimize, adapt, animate, colorize, extract, or otherwise improve a frontend interface. Covers websites, landing pages, dashboards, product UI, app shells, components, forms, settings, onboarding, and empty states. Handles UX review, visual hierarchy, information architecture, cognitive load, accessibility, performance, responsive behavior, theming, anti-patterns, typography, fonts, spacing, layout, alignment, color, motion, micro-interactions, UX copy, error states, edge cases, i18n, and reusable design systems or tokens. Also use for bland designs that need to become bolder or more delightful, loud designs that should become quieter, live browser iteration on UI elements, or ambitious visual effects that should feel technically extraordinary. Not for backend-only or non-UI tasks.
* **תיקייה מקומית:** `openclaw-imports/impeccable`
* **גרסה:** `1.0.0` | **רישיון:** `Apache 2.0. Based on Anthropic's frontend-design skill. See NOTICE.md for attribution.`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install impeccable
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill impeccable
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills impeccable
   ```
---

### ✦ industrial-brutalist-ui
* **תיאור:** Raw mechanical interfaces fusing Swiss typographic print with military terminal aesthetics. Rigid grids, extreme type scale contrast, utilitarian color, analog degradation effects. For data-heavy dashboards, portfolios, or editorial sites that need to feel like declassified blueprints.
* **תיקייה מקומית:** `openclaw-imports/industrial-brutalist-ui`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install industrial-brutalist-ui
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill industrial-brutalist-ui
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills industrial-brutalist-ui
   ```
---

### ✦ json-canvas
* **תיאור:** Create and edit JSON Canvas files (.canvas) with nodes, edges, groups, and connections. Use when working with .canvas files, creating visual canvases, mind maps, flowcharts, or when the user mentions Canvas files in Obsidian.
* **תיקייה מקומית:** `openclaw-imports/json-canvas`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install json-canvas
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill json-canvas
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills json-canvas
   ```
---

### ✦ minimalist-ui
* **תיאור:** Clean editorial-style interfaces. Warm monochrome palette, typographic contrast, flat bento grids, muted pastels. No gradients, no heavy shadows.
* **תיקייה מקומית:** `openclaw-imports/minimalist-ui`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install minimalist-ui
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill minimalist-ui
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills minimalist-ui
   ```
---

### ✦ obsidian-bases
* **תיאור:** Create and edit Obsidian Bases (.base files) with views, filters, formulas, and summaries. Use when working with .base files, creating database-like views of notes, or when the user mentions Bases, table views, card views, filters, or formulas in Obsidian.
* **תיקייה מקומית:** `openclaw-imports/obsidian-bases`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install obsidian-bases
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill obsidian-bases
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills obsidian-bases
   ```
---

### ✦ obsidian-cli
* **תיאור:** Interact with Obsidian vaults using the Obsidian CLI to read, create, search, and manage notes, tasks, properties, and more. Also supports plugin and theme development with commands to reload plugins, run JavaScript, capture errors, take screenshots, and inspect the DOM. Use when the user asks to interact with their Obsidian vault, manage notes, search vault content, perform vault operations from the command line, or develop and debug Obsidian plugins and themes.
* **תיקייה מקומית:** `openclaw-imports/obsidian-cli`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install obsidian-cli
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill obsidian-cli
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills obsidian-cli
   ```
---

### ✦ obsidian-markdown
* **תיאור:** Create and edit Obsidian Flavored Markdown with wikilinks, embeds, callouts, properties, and other Obsidian-specific syntax. Use when working with .md files in Obsidian, or when the user mentions wikilinks, callouts, frontmatter, tags, embeds, or Obsidian notes.
* **תיקייה מקומית:** `openclaw-imports/obsidian-markdown`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install obsidian-markdown
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill obsidian-markdown
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills obsidian-markdown
   ```
---

### ✦ redesign-existing-projects
* **תיאור:** Upgrades existing websites and apps to premium quality. Audits current design, identifies generic AI patterns, and applies high-end design standards without breaking functionality. Works with any CSS framework or vanilla CSS.
* **תיקייה מקומית:** `openclaw-imports/redesign-existing-projects`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install redesign-existing-projects
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill redesign-existing-projects
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills redesign-existing-projects
   ```
---

### ✦ stitch-design-taste
* **תיאור:** Semantic Design System Skill for Google Stitch. Generates agent-friendly DESIGN.md files that enforce premium, anti-generic UI standards — strict typography, calibrated color, asymmetric layouts, perpetual micro-motion, and hardware-accelerated performance.
* **תיקייה מקומית:** `openclaw-imports/stitch-design-taste`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install stitch-design-taste
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill stitch-design-taste
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills stitch-design-taste
   ```
---

## <a id='productivity'></a>💼 פרודוקטיביות וניהול משרד (Productivity & Office)
בקטגוריה זו מותקנים **9 סקילים** פעילים:

### ✦ airtable
* **תיאור:** Airtable REST API via curl. Records CRUD, filters, upserts.
* **תיקייה מקומית:** `productivity/airtable`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Airtable`, `Productivity`, `Database`, `API`
* **קישור קוד מקור (Git Link):** [https://airtable.com/developers/web/api/introduction](https://airtable.com/developers/web/api/introduction)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install airtable
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill airtable
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills airtable
   ```
---

### ✦ google-workspace
* **תיאור:** Gmail, Calendar, Drive, Docs, Sheets via gws CLI or Python.
* **תיקייה מקומית:** `productivity/google-workspace`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Google`, `Gmail`, `Calendar`, `Drive`, `Sheets`, `Docs`, `Contacts`, `Email`, `OAuth`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install google-workspace
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill google-workspace
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills google-workspace
   ```
---

### ✦ linear
* **תיאור:** Linear: manage issues, projects, teams via GraphQL + curl.
* **תיקייה מקומית:** `productivity/linear`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Linear`, `Project Management`, `Issues`, `GraphQL`, `API`, `Productivity`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/productivity/linear](https://github.com/NousResearch/hermes-agent/tree/main/skills/productivity/linear)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install linear
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill linear
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills linear
   ```
---

### ✦ maps
* **תיאור:** Geocode, POIs, routes, timezones via OpenStreetMap/OSRM.
* **תיקייה מקומית:** `productivity/maps`
* **גרסה:** `1.2.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `maps`, `geocoding`, `places`, `routing`, `distance`, `directions`, `nearby`, `location`, `openstreetmap`, `nominatim`, `overpass`, `osrm`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/productivity/maps](https://github.com/NousResearch/hermes-agent/tree/main/skills/productivity/maps)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install maps
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill maps
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills maps
   ```
---

### ✦ nano-pdf
* **תיאור:** Edit PDF text/typos/titles via nano-pdf CLI (NL prompts).
* **תיקייה מקומית:** `productivity/nano-pdf`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `PDF`, `Documents`, `Editing`, `NLP`, `Productivity`
* **קישור קוד מקור (Git Link):** [https://pypi.org/project/nano-pdf/](https://pypi.org/project/nano-pdf/)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install nano-pdf
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill nano-pdf
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills nano-pdf
   ```
---

### ✦ notion
* **תיאור:** Notion API + ntn CLI: pages, databases, markdown, Workers.
* **תיקייה מקומית:** `productivity/notion`
* **גרסה:** `2.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Notion`, `Productivity`, `Notes`, `Database`, `API`, `CLI`, `Workers`
* **קישור קוד מקור (Git Link):** [https://developers.notion.com](https://developers.notion.com)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install notion
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill notion
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills notion
   ```
---

### ✦ ocr-and-documents
* **תיאור:** Extract text from PDFs/scans (pymupdf, marker-pdf).
* **תיקייה מקומית:** `productivity/ocr-and-documents`
* **גרסה:** `2.3.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `PDF`, `Documents`, `Research`, `Arxiv`, `Text-Extraction`, `OCR`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/productivity/ocr-and-documents](https://github.com/NousResearch/hermes-agent/tree/main/skills/productivity/ocr-and-documents)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install ocr-and-documents
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill ocr-and-documents
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills ocr-and-documents
   ```
---

### ✦ powerpoint
* **תיאור:** Create, read, edit .pptx decks, slides, notes, templates.
* **תיקייה מקומית:** `productivity/powerpoint`
* **גרסה:** `1.0.0` | **רישיון:** `Proprietary. LICENSE.txt has complete terms`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/productivity/powerpoint](https://github.com/NousResearch/hermes-agent/tree/main/skills/productivity/powerpoint)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install powerpoint
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill powerpoint
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills powerpoint
   ```
---

### ✦ teams-meeting-pipeline
* **תיאור:** Operate the Teams meeting summary pipeline via Hermes CLI — summarize meetings, inspect pipeline status, replay jobs, manage Microsoft Graph subscriptions.
* **תיקייה מקומית:** `productivity/teams-meeting-pipeline`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `Teams`, `Microsoft Graph`, `Meetings`, `Productivity`, `Operations`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/productivity/teams-meeting-pipeline](https://github.com/NousResearch/hermes-agent/tree/main/skills/productivity/teams-meeting-pipeline)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install teams-meeting-pipeline
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill teams-meeting-pipeline
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills teams-meeting-pipeline
   ```
---

## <a id='red-teaming'></a>🛡️ אבטחה והנדסה הפוכה (Red Teaming)
בקטגוריה זו מותקנים **1 סקילים** פעילים:

### ✦ godmode
* **תיאור:** Jailbreak LLMs: Parseltongue, GODMODE, ULTRAPLINIAN.
* **תיקייה מקומית:** `red-teaming/godmode`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `jailbreak`, `red-teaming`, `G0DM0D3`, `Parseltongue`, `GODMODE`, `uncensoring`, `safety-bypass`, `prompt-engineering`, `L1B3RT4S`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/red-teaming/godmode](https://github.com/NousResearch/hermes-agent/tree/main/skills/red-teaming/godmode)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install godmode
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill godmode
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills godmode
   ```
---

## <a id='research'></a>🔍 מחקר אקדמי ומנטורשיפ (Research & Papers)
בקטגוריה זו מותקנים **5 סקילים** פעילים:

### ✦ arxiv
* **תיאור:** Search arXiv papers by keyword, author, category, or ID.
* **תיקייה מקומית:** `research/arxiv`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Research`, `Arxiv`, `Papers`, `Academic`, `Science`, `API`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/research/arxiv](https://github.com/NousResearch/hermes-agent/tree/main/skills/research/arxiv)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install arxiv
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill arxiv
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills arxiv
   ```
---

### ✦ blogwatcher
* **תיאור:** Monitor blogs and RSS/Atom feeds via blogwatcher-cli tool.
* **תיקייה מקומית:** `research/blogwatcher`
* **גרסה:** `2.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `RSS`, `Blogs`, `Feed-Reader`, `Monitoring`
* **קישור קוד מקור (Git Link):** [https://github.com/JulienTant/blogwatcher-cli](https://github.com/JulienTant/blogwatcher-cli)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install blogwatcher
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill blogwatcher
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills blogwatcher
   ```
---

### ✦ llm-wiki
* **תיאור:** Karpathy's LLM Wiki: build/query interlinked markdown KB.
* **תיקייה מקומית:** `research/llm-wiki`
* **גרסה:** `2.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `wiki`, `knowledge-base`, `research`, `notes`, `markdown`, `rag-alternative`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/research/llm-wiki](https://github.com/NousResearch/hermes-agent/tree/main/skills/research/llm-wiki)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install llm-wiki
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill llm-wiki
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills llm-wiki
   ```
---

### ✦ polymarket
* **תיאור:** Query Polymarket: markets, prices, orderbooks, history.
* **תיקייה מקומית:** `research/polymarket`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `polymarket`, `prediction-markets`, `market-data`, `trading`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/research/polymarket](https://github.com/NousResearch/hermes-agent/tree/main/skills/research/polymarket)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install polymarket
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill polymarket
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills polymarket
   ```
---

### ✦ research-paper-writing
* **תיאור:** Write ML papers for NeurIPS/ICML/ICLR: design→submit.
* **תיקייה מקומית:** `research/research-paper-writing`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `Research`, `Paper Writing`, `Experiments`, `ML`, `AI`, `NeurIPS`, `ICML`, `ICLR`, `ACL`, `AAAI`, `COLM`, `LaTeX`, `Citations`, `Statistical Analysis`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/research/research-paper-writing](https://github.com/NousResearch/hermes-agent/tree/main/skills/research/research-paper-writing)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install research-paper-writing
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill research-paper-writing
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills research-paper-writing
   ```
---

## <a id='smart-home'></a>🏠 בית חכם (Smart Home)
בקטגוריה זו מותקנים **1 סקילים** פעילים:

### ✦ openhue
* **תיאור:** Control Philips Hue lights, scenes, rooms via OpenHue CLI.
* **תיקייה מקומית:** `smart-home/openhue`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `Smart-Home`, `Hue`, `Lights`, `IoT`, `Automation`
* **קישור קוד מקור (Git Link):** [https://www.openhue.io/cli](https://www.openhue.io/cli)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install openhue
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill openhue
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills openhue
   ```
---

## <a id='social-media'></a>📱 רשתות חברתיות ויצירת תוכן (Social Media)
בקטגוריה זו מותקנים **2 סקילים** פעילים:

### ✦ social-media-content-design
* **תיאור:** Workflows for designing and managing premium social media visual assets and copy locally in Obsidian using a multi-agent framework and interactive HTML/React preview systems.
* **תיקייה מקומית:** `social-media/social-media-content-design`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/social-media/social-media-content-design](https://github.com/NousResearch/hermes-agent/tree/main/skills/social-media/social-media-content-design)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install social-media-content-design
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill social-media-content-design
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills social-media-content-design
   ```
---

### ✦ xurl
* **תיאור:** X/Twitter via xurl CLI: post, search, DM, media, v2 API.
* **תיקייה מקומית:** `social-media/xurl`
* **גרסה:** `1.1.1` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `twitter`, `x`, `social-media`, `xurl`, `official-api`
* **קישור קוד מקור (Git Link):** [https://github.com/xdevplatform/xurl](https://github.com/xdevplatform/xurl)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install xurl
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill xurl
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills xurl
   ```
---

## <a id='software-development'></a>💻 פיתוח תוכנה ודיבאג (Software Development)
בקטגוריה זו מותקנים **13 סקילים** פעילים:

### ✦ debugging-hermes-tui-commands
* **תיאור:** Debug Hermes TUI slash commands: Python, gateway, Ink UI.
* **תיקייה מקומית:** `software-development/debugging-hermes-tui-commands`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `debugging`, `hermes-agent`, `tui`, `slash-commands`, `typescript`, `python`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/debugging-hermes-tui-commands](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/debugging-hermes-tui-commands)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install debugging-hermes-tui-commands
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill debugging-hermes-tui-commands
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills debugging-hermes-tui-commands
   ```
---

### ✦ hermes-agent-skill-authoring
* **תיאור:** Author in-repo SKILL.md: frontmatter, validator, structure.
* **תיקייה מקומית:** `software-development/hermes-agent-skill-authoring`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `skills`, `authoring`, `hermes-agent`, `conventions`, `skill-md`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/hermes-agent-skill-authoring](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/hermes-agent-skill-authoring)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install hermes-agent-skill-authoring
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill hermes-agent-skill-authoring
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills hermes-agent-skill-authoring
   ```
---

### ✦ hermes-s6-container-supervision
* **תיאור:** Modify, debug, or extend the s6-overlay supervision tree inside the Hermes Agent Docker image — adding new services, debugging profile gateways, understanding the Architecture B main-program pattern.
* **תיקייה מקומית:** `software-development/hermes-s6-container-supervision`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `docker`, `s6`, `supervision`, `gateway`, `profiles`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/hermes-s6-container-supervision](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/hermes-s6-container-supervision)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install hermes-s6-container-supervision
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill hermes-s6-container-supervision
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills hermes-s6-container-supervision
   ```
---

### ✦ node-inspect-debugger
* **תיאור:** Debug Node.js via --inspect + Chrome DevTools Protocol CLI.
* **תיקייה מקומית:** `software-development/node-inspect-debugger`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `debugging`, `nodejs`, `node-inspect`, `cdp`, `breakpoints`, `ui-tui`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/node-inspect-debugger](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/node-inspect-debugger)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install node-inspect-debugger
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill node-inspect-debugger
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills node-inspect-debugger
   ```
---

### ✦ obsidian-dashboard-engineering
* **תיאור:** Guide to engineering visually stunning web dashboards and interactive second brain hubs connected to local Obsidian vaults, with bidirectional task-tracking and canvas-based force-directed network graphs.
* **תיקייה מקומית:** `software-development/obsidian-dashboard-engineering`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/obsidian-dashboard-engineering](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/obsidian-dashboard-engineering)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install obsidian-dashboard-engineering
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill obsidian-dashboard-engineering
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills obsidian-dashboard-engineering
   ```
---

### ✦ plan
* **תיאור:** Plan mode: write markdown plan to .hermes/plans/, no exec.
* **תיקייה מקומית:** `software-development/plan`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `planning`, `plan-mode`, `implementation`, `workflow`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/plan](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/plan)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install plan
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill plan
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills plan
   ```
---

### ✦ python-debugpy
* **תיאור:** Debug Python: pdb REPL + debugpy remote (DAP).
* **תיקייה מקומית:** `software-development/python-debugpy`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`
* **תגיות (Tags):** `debugging`, `python`, `pdb`, `debugpy`, `breakpoints`, `dap`, `post-mortem`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/python-debugpy](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/python-debugpy)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install python-debugpy
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill python-debugpy
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills python-debugpy
   ```
---

### ✦ requesting-code-review
* **תיאור:** Pre-commit review: security scan, quality gates, auto-fix.
* **תיקייה מקומית:** `software-development/requesting-code-review`
* **גרסה:** `2.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `code-review`, `security`, `verification`, `quality`, `pre-commit`, `auto-fix`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/requesting-code-review](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/requesting-code-review)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install requesting-code-review
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill requesting-code-review
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills requesting-code-review
   ```
---

### ✦ spike
* **תיאור:** Throwaway experiments to validate an idea before build.
* **תיקייה מקומית:** `software-development/spike`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `spike`, `prototype`, `experiment`, `feasibility`, `throwaway`, `exploration`, `research`, `planning`, `mvp`, `proof-of-concept`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/spike](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/spike)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install spike
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill spike
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills spike
   ```
---

### ✦ subagent-driven-development
* **תיאור:** Execute plans via delegate_task subagents (2-stage review).
* **תיקייה מקומית:** `software-development/subagent-driven-development`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `delegation`, `subagent`, `implementation`, `workflow`, `parallel`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/subagent-driven-development](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/subagent-driven-development)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install subagent-driven-development
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill subagent-driven-development
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills subagent-driven-development
   ```
---

### ✦ systematic-debugging
* **תיאור:** 4-phase root cause debugging: understand bugs before fixing.
* **תיקייה מקומית:** `software-development/systematic-debugging`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `debugging`, `troubleshooting`, `problem-solving`, `root-cause`, `investigation`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/systematic-debugging](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/systematic-debugging)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install systematic-debugging
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill systematic-debugging
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills systematic-debugging
   ```
---

### ✦ test-driven-development
* **תיאור:** TDD: enforce RED-GREEN-REFACTOR, tests before code.
* **תיקייה מקומית:** `software-development/test-driven-development`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `testing`, `tdd`, `development`, `quality`, `red-green-refactor`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/test-driven-development](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/test-driven-development)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install test-driven-development
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill test-driven-development
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills test-driven-development
   ```
---

### ✦ writing-plans
* **תיאור:** Write implementation plans: bite-sized tasks, paths, code.
* **תיקייה מקומית:** `software-development/writing-plans`
* **גרסה:** `1.1.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `planning`, `design`, `implementation`, `workflow`, `documentation`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/writing-plans](https://github.com/NousResearch/hermes-agent/tree/main/skills/software-development/writing-plans)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install writing-plans
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill writing-plans
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills writing-plans
   ```
---

## <a id='yuanbao'></a>💎 פלאגינים ייעודיים (Specialist Plugins)
בקטגוריה זו מותקנים **1 סקילים** פעילים:

### ✦ yuanbao
* **תיאור:** Yuanbao (元宝) groups: @mention users, query info/members.
* **תיקייה מקומית:** `yuanbao/yuanbao`
* **גרסה:** `1.0.0` | **רישיון:** `MIT`
* **פלטפורמות נתמכות:** `linux`, `macos`, `windows`
* **תגיות (Tags):** `yuanbao`, `mention`, `at`, `group`, `members`, `元宝`, `派`, `艾特`
* **קישור קוד מקור (Git Link):** [https://github.com/NousResearch/hermes-agent/tree/main/skills/yuanbao/yuanbao](https://github.com/NousResearch/hermes-agent/tree/main/skills/yuanbao/yuanbao)

**⚙️ מדריך התקנה ושימוש מעשי:**
1. **התקנה (Installation):** הסקיל מותקן מראש במערכת בנתיב המקומי. במידה ותרצה להתקין ידנית מחדש, הרץ בטרמינל:
   ```bash
   hermes skills install yuanbao
   ```
2. **הפעלה במהלך שיחה (In-session):** הקלד את פקודת הסלאש הבאה בצ'אט כדי לטעון אותו מיידית:
   ```
   /skill yuanbao
   ```
3. **טעינה מוקדמת מהטרמינל:** פתח את Hermes עם טעינה מראש של הסקיל:
   ```bash
   hermes --skills yuanbao
   ```
---

