# 🧠 code__Workflow.md  
> Red Collar OS – Phase-Coded Dev Rituals  
> "No guesswork. Only protocol."

This file encodes the tactical phases required to contribute to `red__Collar--Os`. Every action is a phase.  
Every commit is an operation. No dead code. No wasted time.

---

## 🧩 PHASE 1: Spawn  
```bash
./spawn.sh mit red__Collar--Os
```
- LICENSE, README.md, .gitignore, and .bw_hash created  
- Git initialized and stamped  
- VS Code launched automatically  

---

## 🧩 PHASE 2: Structure  
- Use strict BEM: `block__Element--Modifier`  
- Folders must reflect app modules:
  - `apps__Launcher/`
  - `settings__daemon/`
  - `terminal__Vision/`, etc.  
- Each folder includes its own README.md  

---

## 🧩 PHASE 3: Code  
- Logic files begin with phase prefix (`phase--3-login.js`, etc.)  
- No global scope leakage  
- Comment critical logic with `// ::bw-note`  
- Use GitHub Copilot if and only if it aligns with the mission  

---

## 🧩 PHASE 4: Validate  
```bash
eslint .
prettier --check .
```
- Confirm .gitignore covers all artifacts  
- Review folder structure for naming + logic clarity  

---

## 🧩 PHASE 5: Commit + Push  
```bash
git add .
git commit -m "⚙️ Phase 4 complete — validation passed"
git push origin main
```
- Tactical commit messages only  
- No waffle. No bloat. No fear.  

---

## 🧩 PHASE 6: Track  
- Log the action in `cli__Automation--Commands.md`  
- Update README if logic or structure has changed  
- Use `devconsole.sh` when live to mirror journaled actions  

---

## 🧬 Core Doctrine  

> “The system is the discipline.”  

- No unnamed folders  
- No logic without README  
- No commit without justification  
- Every file has purpose. Every push leaves a trace.  

---

You’re not coding.  
You’re launching phases.  
