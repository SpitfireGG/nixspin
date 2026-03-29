# Contributing to nixspin

Contributions are welcome from anyone who wants to help others understand Nix and NixOS more deeply.

## Reporting Issues

If you find problems with exercises or documentation that needs clarity, open an issue with:

- A clear description of the problem
- Which chapter/exercise is affected
- If code doesn't evaluate: include the error output and your Nix version (`nix --version`)

## Suggesting Content

If you want a new chapter or topic covered, open an issue with:

- What topic you want covered
- Why it would be valuable
- Where it fits in the learning progression

## Submitting Pull Requests

**Do not submit code you don't understand or didn't write yourself.**

Before submitting:

1. Test your exercises thoroughly with `./run.sh`
2. Verify your documentation is clear
3. Make sure new content fits the chapter's difficulty level

## Exercise Quality Standards

- **Format code** with [Alejandra](https://github.com/kamadorueda/alejandra)
- **Write clear documentation** explaining concepts in the chapter's readme.md
- **Test thoroughly** before submitting — ensure `run.sh` works and gives useful feedback
- **Each exercise should have a clear objective** stated in its readme.md

## Code Style

No strict formatting rules beyond using Alejandra. Focus on:

- Clean, readable code
- Clear explanations
- In-depth coverage of concepts

The goal is to help people learn, not to win style points.
