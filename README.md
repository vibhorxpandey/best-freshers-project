# 100 Projects for First-Year CS Students

![Tier: Easy](https://img.shields.io/badge/projects-easy%2034-90EE90?style=flat-square)
![Tier: Medium](https://img.shields.io/badge/projects-medium%2033-FFD700?style=flat-square)
![Tier: Hard](https://img.shields.io/badge/projects-hard%2033-FF6B6B?style=flat-square)
![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

A **battle-tested, tier-based project progression** for first and second-year CS/engineering students. Stop staring at blank repos—start with a **weekend build**, ship it, and level up deliberately.

## 🎯 Why This Repo Exists

Year one overwhelms most students with the same question: *"What should I build?"* 

This list **removes the guesswork**. Each project teaches a specific skill in isolation, forces you to ship (not just code), and builds a portfolio that recruiters actually care about. By end of year one, you'll have:
- ✅ Real deployed projects
- ✅ Git commit history that shows progression
- ✅ README writing skills (the hidden resume skill)
- ✅ Enough breadth to know what you enjoy building

---

## 📚 Three Tiers, One Clear Path

| Tier | Count | Focus | Time | Ideal For |
|------|-------|-------|------|-----------|
| **[Easy](./Easy)** | 34 | Core fundamentals, CLI tools, solo-language projects | 1-3 days | Weeks 1-4: building confidence |
| **[Medium](./medium)** | 33 | Full CRUD apps, databases, APIs, real integrations | 3-7 days | Weeks 5-12: shipping real systems |
| **[Hard](./Hard)** | 33 | Distributed systems, ML pipelines, low-level code | 5-14 days | Weeks 13+: portfolio standout pieces |

**Total: 100 projects across ~16-20 weeks of deliberate practice.**

---

## 🚀 How to Use This Repo

### If you're **brand new** to coding
1. Open [`Easy`](./Easy) — start with the first 5 projects
2. Each one teaches **one core concept**: loops, functions, file I/O, basic data structures
3. Build the ugliest version that works in 1-2 days
4. Push to GitHub with a real README (this matters more than code quality)
5. Move to the next one — repeat 10 times before looking at Medium

**Red flag:** If a project takes >3 days, you're overthinking it. Finish it, learn from it, move on.

### If you're **comfortable with one language** (and basic APIs/DBs)
1. Skip Easy, jump to [`Medium`](./medium)
2. These are real CRUD apps with integrations—databases, APIs, third-party services
3. Spend 4-5 days per project; focus on **shipping and testing**
4. Write proper READMEs with setup instructions, not just code dumps
5. After 8-10 medium projects, you're ready for Hard

**Stretch goal:** Pick 1-2 medium projects outside your comfort zone (e.g., if you only do backend, build a full-stack app with React + FastAPI).

### If you've **already shipped a few projects**
1. Go straight to [`Hard`](./Hard)
2. These are resume/portfolio pieces: systems programming, ML pipelines, distributed concepts
3. Spend 1-2 weeks per project; focus on **depth and polish**
4. Write a 1-page technical writeup explaining your approach (this is what gets you internships)
5. Link them prominently on your portfolio

**Career accelerator:** By shipping 2-3 hard projects in year one, you're already ahead of 90% of peers.

---

## 💡 Recommended Workflow Per Project

### Step 1: Write a 3-Line Spec (~5 min)
Before any code, answer:
- What does it do? (1 sentence)
- What are the inputs and outputs? (1 sentence)
- How do you know it's done? (acceptance criteria, 1-2 lines)

Example:
```
Build a TODO app that stores tasks in a JSON file.
Input: CLI commands (add, list, delete). Output: persisted to tasks.json.
Done when: (a) tasks persist across runs, (b) all commands work, (c) README has setup + usage.
```

### Step 2: Build the Ugly Version First (~1-3 days)
- Don't overthink architecture
- No premature refactoring
- Get it working end-to-end
- Commit early and often

### Step 3: Push to GitHub with a Real README (~1 hour)
Your README should have:
- **What it does** (1 paragraph, no jargon)
- **How to run it** (copy-paste should work)
- **Tech stack** (languages, frameworks, libraries)
- **What you learned** (2-3 bullets)
- **Next steps** (what you'd add if you had more time)

⚠️ **Pro tip:** Recruiters spend 30 seconds on your repo. 20 of those are reading the README. Make it count.

### Step 4: Only Then Refactor/Polish (~optional, but do it)
- Extract functions, clean up variable names
- Add error handling
- Write a few tests if it's medium+
- Update the README with lessons learned

---

## 🎓 Skills by Tier

### Easy Projects Teach
- Variables, loops, conditionals
- Functions and basic recursion
- File I/O and string manipulation
- Basic data structures (lists, dicts)
- Git + GitHub workflow
- Writing clear README docs

### Medium Projects Teach
- Database design and SQL/NoSQL queries
- RESTful API design and consumption
- Authentication and authorization basics
- Frontend-backend communication
- Error handling and logging
- Testing basics (unit + integration)
- Deployment to free tiers (Render, Vercel, Railway)

### Hard Projects Teach
- Distributed systems concepts (CAP theorem, eventual consistency)
- Performance optimization and profiling
- Advanced data structures and algorithms
- Machine learning pipelines (data → model → inference)
- Message queues and async processing
- Infrastructure as code (Docker, K8s intro)
- Large codebase navigation and contribution
- Technical writing and research papers

---

## 📋 Stack Suggestions (Not Rules)

Each project has suggested stacks—**treat these as starting points, not requirements**. Swap freely:

| Tier | Backend | Frontend | Database | DevOps |
|------|---------|----------|----------|--------|
| **Easy** | Python/JS | CLI or basic HTML | CSV/JSON | Git only |
| **Medium** | Python/Node/Go | React/Vue or HTML+JS | PostgreSQL/MongoDB | Render/Railway |
| **Hard** | Rust/Go | React/Next.js | Postgres + Redis | Docker + GitHub Actions |

**Constraint:** Pick one language per project and stick with it. Switching languages between projects slows learning.

---

## 🔥 Pro Tips for Success

1. **Ship > Perfect**  
   A deployed project with a 60-line README is worth 10x more than an unfinished "perfect" codebase. Push to GitHub today.

2. **Track Learning, Not Hours**  
   Don't measure progress by time spent. Measure by: (a) Does it work? (b) Is it on GitHub? (c) Can someone else run it?

3. **Read Other People's Code**  
   After you ship, find similar projects on GitHub. Read their READMEs, code structure, tests. Steal patterns.

4. **Join the PR Economy**  
   After medium projects, start contributing to open-source. Apply the same shipping discipline to real projects.

5. **Document Your "Aha" Moments**  
   Keep a learning log. When you solve a hard bug or learn a new pattern, write it down. Your future self will thank you.

6. **Don't Skip Tier Levels**  
   Jumping from Easy → Hard because you're "too advanced" is the #1 way to build fragile projects. Do the breadth work first.

---

## 🤝 Contributing

**Found a better project idea?** Discovered a missing fundamental concept? Have a cool project writeup?

Fork this repo and open a PR:
- Link to a completed project with a working repo
- Add a 2-3 sentence writeup explaining what it teaches
- Tag it appropriately (`[Web]`, `[ML]`, `[Systems]`, `[CLI]`, `[Game]`, `[Bot]`, `[Mobile]`)

We'll review and credit you in the contributor list.

---

## 💬 Common Questions

**Q: Can I do projects out of order?**  
A: Yes, but do at least 5 Easy before touching Medium, and 5 Medium before Hard. The progression teaches patterns you'll lean on later.

**Q: I'm stuck on a project.**  
A: (1) Restart from scratch—don't debug for >30min without a reset. (2) Read similar projects on GitHub. (3) Ask on r/learnprogramming with your current code. (4) Pair program with a friend.

**Q: How many should I do per semester?**  
A: Semester 1 (first-year): 15-20 projects (mostly Easy + some Medium).  
Semester 2+: 2-3 Medium/Hard per month.  
Intern period: 1-2 serious Hard projects to make your resume stand out.

**Q: Should I blog about my projects?**  
A: Absolutely. One technical writeup per 5 projects. A 10-minute read on how you built X will get you job offers.

---

## 📈 The 100-Project Payoff

By end of year one:
- **Portfolio:** 10-15 real projects with clean READMEs and deployed links
- **GitHub streak:** Consistent weekly contributions showing you code on your own time
- **Interview confidence:** You've debugged enough to talk through problems without panic
- **Networking:** OSS contributions mean someone in the community knows your work

This **compounds**. Year two, you'll be reviewing peers' code instead of asking how to use loops.

---

## 📞 Let's Build Together

- **Learning stuck?** Drop an issue with your blocker
- **Completed a project?** Open a PR with your repo link—get featured
- **Want a curated version?** Star this repo + share with your cohort

---

## License

MIT — use freely, fork it, make it yours. Credit appreciated but not required.

---

## Built By

[Vibhor Pandey](https://github.com/vibhorxpandey) — Second-year CSE student, prolific builder, believes in learning by shipping.

**Also building:**
- [Veil Research](https://veilresearch.com) — AI research workspace
- [Veil Finance](https://veilfinance.ink) — AI equity research terminal
- [Aurelius MCP](https://github.com/vibhorxpandey/aurelius) — Open-source fact-checking research server

---

**Last updated:** January 2026  
**Stars:** Help others find this by starring ⭐

