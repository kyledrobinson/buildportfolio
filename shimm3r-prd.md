# 🧠 PRODUCT REQUIREMENTS DOC — SHIMM3R AGENT

## 🪄 Purpose
To create a lightweight, Codex-compatible agent that assists in building, managing, and deploying elements of the shimm3r.com platform — with zero feature creep.

## 🎯 Goals
- Respond to developer requests with zero ambiguity.
- Run setup tasks, test suites, and code generation within Codex.
- Keep output modular, well-commented, and minimal.

## 🧰 Core Features
- Setup script runner (installs deps, tools, and config)
- Markdown doc summarizer and injector (for agent docs like agents.md)
- ESLint + Prettier executor with result parser
- GitOps assistant (basic branch logic, pull request creator)

## 🧑‍💻 User
- Kyle (developer/designer/architect)
- Codex agent (interpreter of user intent, task executor)

## ✅ Requirements
- CLI-compatible setup
- Works offline after initial setup
- Compatible with Codex Universal environment
- Minimal external dependencies (max 5)

## 🔒 Constraints
- No databases
- No auth
- No UI
- Must finish in <10 seconds
