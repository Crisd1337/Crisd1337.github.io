# crisd1337.github.io

The GitHub Pages **user site** for this account. It does two things and nothing else:

1. `/` redirects to the revision quiz at [`/quiz/`](https://crisd1337.github.io/quiz/).
2. A handful of one-letter aliases point at the same site, so links are short enough to type on a phone:

| path | goes to |
|---|---|
| `/a` | mixed paper (all 428 questions) |
| `/r` | mistake book |
| `/k` | shop |
| `/e` `/c` `/m` `/m5` `/h` `/g` `/p` | English · Science · Maths P · Maths 5.3 · History · Geography · PDHPE |

Each alias is a tiny HTML file with a `meta refresh`, a `location.replace` fallback and a manual link — no JavaScript framework, no build step.

The quiz itself lives in the [`quiz`](https://github.com/Crisd1337/quiz) repository.
