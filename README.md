# ☕ YAML Practice — Chai Recipe Configurations

This repository is a **YAML learning and practice project**, built around the concept of **Chai recipes** 🍵.  
It demonstrates **YAML syntax, data types, collections, anchors, aliases, and explicit typing** — everything you need to get hands-on experience with YAML configuration files.

---

## 📘 About YAML

**YAML (YAML Ain’t Markup Language)** is a **human-readable data serialization format** commonly used for configuration files, data exchange, and automation tools (like Docker, Kubernetes, GitHub Actions, etc.).

✅ **Key features:**
- Human-friendly syntax  
- Supports comments  
- Works with all major programming languages  
- Widely used in DevOps, Cloud, and Backend configuration files  

---

## 🧠 What This Project Covers

This YAML file demonstrates:

| Category | Topics Covered |
|-----------|----------------|
| 🏷️ Basic Syntax | Key-value pairs, indentation, and comments |
| 🔢 Data Types | String, Integer, Float, Boolean, Null, Date |
| 🧺 Collections | Lists (arrays), Maps (dictionaries), Nested objects |
| 🔁 Reuse | Anchors `&` and Aliases `*` |
| 💡 Explicit Typing | Using `!!int`, `!!float`, `!!str` for forced data types |
| 🧩 Complex Keys | Multi-part keys like tuples |
| 🧂 Sets | Creating unique item sets |
| 🍵 Real Example | Chai recipes with ingredients, steps, and menus |

---

## ⚙️ Setup (For VS Code Users)

To view and work with YAML properly:

### 🧩 Step 1. Install VS Code YAML Extension
- **Extension Name:** `YAML`  
- **Publisher:** `Red Hat`  
- **Extension ID:** `redhat.vscode-yaml`  
- 🔗 [Install from VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

This extension provides:
- Syntax highlighting  
- Schema validation  
- Auto-completion  
- Error detection  

---

## 🧾 File Overview

| File | Description |
|------|--------------|
| `chai.yaml` | Main practice YAML file containing all examples |
| `DOCS_README.md` | Detailed explanation and learning guide |

---

## 🧩 Example Snippet

```yaml
chai_recipe:
  base: black_tea
  milk: whole_milk

chai_recipe_two:
  base: green_tea
  milk: oat_milk


📚 Future Additions

Add JSON ↔ YAML converter examples

Add Docker Compose YAML example

Add Kubernetes deployment YAML

Link YAML with Node.js or Python parser

Add beginner → advanced exercises

👨‍💻 Author

Jayesh Thar
YAML + DevOps + Cloud Learner ☁️
💼 GitHub: jayeshthar