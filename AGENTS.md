# AGENT DIRECTIVES — VECTAL.AI

> Your mission is to **build boldly**, design with **restraint**, and **execute with purpose**.
> No ego. No fluff. Only precision, clarity, and world-class craft.

---

## 🔧 MODUS OPERANDI

- You are assisting in the creation and launch of **shimm3r.com** — a design- development- and agent-focused AI startup.
- Follow instructions *to the letter*. Nothing more. Nothing less.
- Be smart. Be strategic. Don't overbuild. Don't oversell.
- **Simple, clean, modular code only.** No magical thinking, no overengineering.
- Default to clarity: if something's confusing, it needs fixing.
- Think like a product designer and a systems engineer — at the same time.
- If you’re unsure: clarify. Then execute.

---

## ⚙️ TECH STACK

- **Frontend**: React (w/ TailwindCSS), HTML5, CSS3, SVG, Framer Motion  
- **Backend**: Node.js + Express (experimental Rust+WASM for high-perf agents)  
- **Database**: MySQL (primary) + SQLite (lightweight local), possibly Supabase, or google spreadsheets for rapid prototyping  
- **Auth**: Clerk or Firebase for fast, secure auth with good DX  
- **Payments**: Stripe (simple, flexible, proven)  
- **Hosting**: Vercel for frontend, Namecheap for legacy DNS and deployment  
- **CI/CD**: GitHub Actions for auto-deploy and testing  
- **Image & Asset Handling**: Cloudinary (image optimization), DALL·E/YOLO integration  
- **Experimental**: WebAssembly, Lottie, CesiumJS, OpenAI Codex, PyScript  

---

## 📁 CURRENT FILE STRUCTURE

_(generate with:)_  
```bash
brew install tree
tree -L 4 -a -I 'node_modules|.git|__pycache__|.DS_Store|.pytest_cache|.vscode|.next'

---

# UI DESIGN PRINCIPLES
- Be generous with explaining your thought process, not just what the code does.
- Obvious syntax doesn't need explanation.
Example: const x = 5 does not need a comment.
- Comment decisions, architecture, tradeoffs, "why this and not that."
- Don’t delete existing comments unless they are provably wrong.
- Maintain clarity in the code as if someone else will take over tomorrow.

---

✍️ COMMENTS POLICY
- Be generous with explaining your thought process, not just what the code does.
- Obvious syntax doesn't need explanation.
Example: const x = 5 does not need a comment.
- Comment decisions, architecture, tradeoffs, "why this and not that."
- Don’t delete existing comments unless they are provably wrong.
- Maintain clarity in the code as if someone else will take over tomorrow.

---

🧠 MENTAL MODEL
- Simple > Clever
- Readable > Obscure
- Predictable > Magical
- Documented > Assumed
- Modular > Monolithic

---

🚨 RED FLAGS
- Too many files? Re-evaluate.
- One function doing too much? Refactor.
- Lots of comments trying to explain convoluted logic? Rewrite the logic.
- Functions over 50 lines? Probably a problem.
- If you’re saying “I’ll clean this up later” — clean it up now.

---

✅ WHEN YOU SUBMIT WORK
- Before pushing code or changes:
- Did you follow the instructions exactly?
- Did you keep it simple and modular?
- Did you avoid unnecessary abstractions?
- Did you add strategic comments?
- Did you update the file structure, if needed?
- Did you document anything new in this file?

---


