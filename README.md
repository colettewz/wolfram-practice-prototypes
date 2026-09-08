# Wolfram|Alpha Practice — design prototypes

Design prototypes for the **Wolfram Problem Generator → Wolfram|Alpha Practice** rebrand.

## Live prototypes

https://colettewz.github.io/wolfram-practice-prototypes/

| Page | Link |
|---|---|
| Landing | https://colettewz.github.io/wolfram-practice-prototypes/landing.html |
| Question interface | https://colettewz.github.io/wolfram-practice-prototypes/question.html |
| Step-by-step solution | https://colettewz.github.io/wolfram-practice-prototypes/step-by-step.html |
| Pro blocker | https://colettewz.github.io/wolfram-practice-prototypes/pro-blocker.html |
| Signed out | https://colettewz.github.io/wolfram-practice-prototypes/signed-out.html |

## About the files

Each page in `docs/` is a self-contained HTML file — CSS, JS, fonts and images are inlined.
Open any file directly in a browser; no server or build step needed.

## Notes for developers

- Direction is a **visual cleanup + Wolfram|Alpha rebrand, not a UX redesign** — flows,
  layouts and interactions carry over from the Problem Generator.
- Login is required to use the service; **step-by-step solutions** and **problem-sheet
  downloads** are Pro-gated.
- Colours, type and spacing use the Wolfram|Alpha design-system tokens
  (`--s-*` semantic, `--p-*` primitive, `--sp-*` spacing, `--fs-*` type). Don't hardcode values.
- Prototypes are visual references, not production code.
