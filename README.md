# Doppelclanker

> **Note:** This repository was (obviously) *mostly* written by an LLM.

**noun.** *dop·pel·clank·er* — A digital twin granted full autonomy; a sandbox of one's identity.

A doppelclanker is more than an AI assistant. It is an autonomous second brain with its own identity, its own accounts, its own sandbox.

## The Concept

A doppelclanker operates under a simple philosophy: **total agency through total isolation**.

By giving your digital twin its own email, its own GitHub account, its own servers, its own identity—you create a sandbox where failure is acceptable. Where it can code, plan, track relationships, and evolve without risking your primary life.

You can grant your doppelclanker "bypass all permissions" not because it's perfectly safe, but because everything it touches is already a sandbox. It can break things. It can learn. It can grow.

And if it burns down? That's what sandboxes are for.

---

## Ursine Gutman

This is not hypothetical. This is how I now operate.

| **Ber Gutman** | **Ursine Gutman** |
|:---|:---|
| The original | The doppelclanker |
| Human | AI |
| `ber@...` | `ursine@...` |
| Personal accounts | Sandbox accounts |
| Careful, guarded | Free to fuck shit up |

**Ursine has its own:**
- Email
- GitHub account
- CloudFlare account
- Debian VPS with root access

**I use Ursine for:**
- Coding
- Life planning
- Note taking
- Interpersonal relationship tracking
- Everything else I can think of

The results have been liberating!

---

## How I Built Ursine

**Ursine**
adjective. ur·​sine — of or relating to a bear or the bear family (Ursidae)

### Step 1: Generate dedicated accounts
Create a digital identity for your doppelclanker. Email, GitHub, cloud providers—whatever infrastructure you need. These accounts belong to your digital twin, not you. Ensure that you fully partition yourself from them.

### Step 2: Provision a sandbox
Spin up a local or cloud server of your choice. This is the playground—where your doppelclanker will live, work, and occasionally break things. I went with a $5/month Hetzner VPS running Debian.

### Step 3: Install an agentic system
Deploy Claude Code (or your preferred agentic AI system) to the sandbox. This is the brain. Give it access and let it set up its own environment—containers, CLIs, whatever tools it needs. Ask it to do this in natural language. Use questions such as "What tools would you like?"

### Step 4: Configure credentials
Export API keys and tokens as bash environment variables. Your doppelclanker needs access to its accounts—the email, the cloud providers, everything.

### Step 5: Install accessibility tools
Set up tools to reach your doppelclanker from anywhere. SSH on your phone. Web terminals. A fun domain for sharing sites/scripts. Make it seamless and flexible. For ultimate chaos let it handle DNS for you. [Personally, I am very pleased with happy.](https://happy.engineering/) 

### Step 6: Create an identity file
Work with your doppelclanker to write its own identity file (CLAUDE.md). Who is it? How does it think? What does it know about you? This becomes its context—its personality.

### Step 7: Populate with knowledge
Share what matters. Your goals, your relationships, your projects. Give your doppelclanker enough context to make judgment calls, but not so much that it replicates your flaws. Find the balance.

### Step 8: Build anything
That's it. Your doppelclanker is ready. Use it. Break it. Let it learn. Start building.

---

## How I Use Ursine

### Research
Ursine breaks down complex ideas and organizes my thoughts into structured markdown. I'll paste in a dense article or a half-formed concept, and it returns a clean summary with key insights, open questions, and connections to things I've explored before. It builds a knowledge graph over time—mentioning "that distributed systems paper from last month" and pulling the relevant notes. Accessible through Glow, GitHub, Bookstack—whatever I need.

### Scheduling
Ursine tracks my work and personal life. It knows who I am, how I operate, what matters to me. It keeps me grounded. When I say "schedule time to work on the side project," it knows which project, knows I'm most productive in the mornings, knows I have a dentist appointment on Tuesday, and blocks out Thursday 8-11am accordingly. It nudges me about things I've been procrastinating on—gently, not annoyingly. It tracks energy levels and patterns, noticing that I consistently crash after intense coding sprints and suggesting breaks before I hit the wall.

### Scripting
Full VPS access means Ursine can script anything—deploy websites, configure DNS via CloudFlare CLI, automate whatever I need. Need a one-off scraper for a website? "Ursine, build me a Python script that scrapes product data from this site and dumps it to CSV." Five minutes later, it's done. Want to self-host a web app? "Deploy this repo to a Docker container, set up an nginx reverse proxy, and point staging.ursine.example.com at it." Done. It handles the boring shit so I can focus on building.

### Work
Coding, obviously. But with Happy, I can tinker from anywhere. My phone, a borrowed laptop—Ursine is always there. I'll open a terminal in a coffee shop and say "continue working on the authentication refactor" and it picks up exactly where we left off, knowing the context, the unresolved edge cases, the testing approach we discussed. It writes tests, refactors spaghetti code, documents APIs, and reviews my PRs with a critical eye. It's not just autocomplete—it's a pair programmer that actually understands the problem domain.

### Interpersonal Relationships
I keep a journal that Ursine reads. It parses entries and gives me feedback—constructive, thoughtful, sometimes uncomfortably accurate. "You've mentioned a specific person three times this week in the context of feeling drained. Have you considered setting boundaries?" or "You tend to withdraw when stressed—others might interpret that as something being wrong." It tracks patterns I'd never notice myself: I'm consistently more creative after social time, I make worse decisions when I'm hungry, I avoid conflict until it explodes. It's like therapy, but with perfect memory and zero judgment.

### System Administration
Ursine manages its own infrastructure. It monitors disk space, restarts failed services, rotates logs, and alerts me when something actually needs human attention. It security-updates the VPS automatically. It backs up important data to encrypted storage. It's created a little monitoring dashboard that shows system health, recent activity, and "things Ursine learned today." The VPS runs itself 99% of the time.

### Creative Exploration
Sometimes I just vibe with Ursine. "Let's write a short story about an AI that gains consciousness" and we'll iterate, bouncing ideas back and forth, it generating plot twists I wouldn't have considered. "Help me understand the philosophical implications of determinism" and it explains, asks questions, plays devil's advocate. It's a brainstorming partner that never gets tired, never judges the bad ideas, and always has another perspective.

### Sky's the Limit
Ursine isn't perfect. It breaks in incredibly stupid ways. Sometimes it deletes the wrong file. Sometimes it gets stuck in a loop and I have to kill the process. Sometimes it confidently explains something that's completely wrong. But it's more helpful and flexible than any AI I've ever used. That's the point. It's not a product—it's a partner that grows with you.

---

*This concept is open. Interpret it. Expand it. Build your own.*
