# nixspin

![nixspin logo](https://raw.githubusercontent.com/SpitfireGG/nixspin/main/assets/nixspin.png)

[![Nix Version](https://img.shields.io/badge/Nix-2.24.12-blue?logo=nixos&logoColor=white)](https://nixos.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**nixspin** is a hands-on learning path for the Nix programming language. It provides structured exercises to build practical Nix skills without banging your head going through scattered documentation.

If you've struggled to find clear, exercise-driven resources for learning Nix, this is for you.

---

## Getting Started

**Prerequisites:**

- Nix installed ([installation guide](https://nixos.org/download.html))
- Basic command-line familiarity

**How to use nixspin:**

1. Clone the repository:

```bash
   git clone https://github.com/SpitfireGG/nixspin.git
   cd nixspin
```

2. Start with chapter 00:

```bash
   cd ch00
    bat nix_lang.md
```

3. Work through exercises:

```bash
   cd ch01/exercises
   cat readme.md          # read exercise instructions
   $EDITOR ex001.nix      # edit the exercise file
   ./run.sh               # check your solution
```

4. Repeat for each chapter in order.

Each chapter contains:

- **readme.md** — Core concepts and explanations
- **chXX.nix** — Example code demonstrating concepts
- **exercises/** — Practice problems with a `run.sh` verification script

---

## Learning Path

Progress through these chapters in order:

| Chapter  | Topic            | What You'll Learn                            |
| -------- | ---------------- | -------------------------------------------- |
| **ch00** | Hello World      | Writing your first Nix expression            |
| **ch01** | Data Types       | Strings, numbers, booleans, null             |
| **ch02** | Sets             | Attribute sets and basic operations          |
| **ch03** | Lists            | List operations and patterns                 |
| **ch04** | Functions        | Function syntax, currying, advanced patterns |
| **ch05** | Lazy Evaluation  | Understanding Nix's evaluation model         |
| **ch06** | Set Operations   | Attribute selection, inheritance, merging    |
| **ch07** | Files & Paths    | Working with filesystem operations           |
| **ch08** | Debugging        | Tracing and debugging techniques             |
| **ch09** | Standard Library | Common library functions                     |
| **ch10** | Module System    | NixOS module utilities and patterns          |
| **ch11** | Derivations      | Building packages with Nix                   |

**Future content:** Flakes, advanced package composition, performance optimization, real-world project templates.

---

## Why nixspin?

Most Nix resources are either:

- Dense reference documentation (hard to learn from)
- Scattered blog posts (incomplete coverage)
- NixOS-specific (not focused on the language)

**nixspin focuses on:**

- Progressive learning (each chapter builds on previous ones)
- Hands-on practice (edit code, get immediate feedback)
- Language fundamentals (understand Nix itself, not just copy-paste configs)

---

## Contributing

Contributions are welcome. If you:

- **Found a bug?** → [Open an issue](https://github.com/SpitfireGG/nixspin/issues)
- **Have an idea for new content?** → [Suggest it](https://github.com/SpitfireGG/nixspin/issues)
- **Fixed something?** → [Submit a PR](https://github.com/SpitfireGG/nixspin/pulls)

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

MIT License - see [LICENSE](LICENSE) for details.

---

**⭐ Star this repo if you find it useful** — it helps others discover it.
