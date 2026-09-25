## Mithun Kumar

Data scientist in Bangalore, working on experiment design and causal inference in
lending and collections — mostly the unglamorous half, where you work out whether a
result is real before anyone ships it.

Most of what I build starts from the same problem: the clean experiment isn't
available. The intervention already shipped to everyone, the control group is
contaminated, the effect is smaller than the noise floor, and the decision still has
to be made this quarter.

---

### What I'm building

**[ab-test-collections-early-bounce](https://github.com/mithunk98/ab-test-collections-early-bounce)** — Experiment design for a collections intervention that had already
shipped to 100% of accounts with no control group. Power analysis, stratified
randomisation, dealer-level contamination diagnostics, and a pre-registered analysis
pipeline with a fixed decision rule.

The finding that made it workable: on a binary cure flag, detecting the effect the
business case rested on would have taken 23 months — long enough that portfolio drift
would overtake the test. Measured as a continuous recovery ratio, the same power
arrives in 2.8 months. The repo renders that argument as a figure and fails its own
build if the numbers and the write-up ever disagree.

`python` · `statsmodels` · `scipy`

**[m-track](https://github.com/mithunk98/m-track)** — Local-first task manager with an
LLM brain-dump parser: paste messy notes, get structured tasks back for review before
anything is saved. Data stays in SQLite on the machine.

`react` · `fastapi` · `sqlite` · `groq`

**[claude-snake](https://github.com/mithunk98/claude-snake)** — Something to do while
Claude Code is thinking. Opens a game of snake in a tmux pane when you send a prompt
and tells you in the header when the agent is done. No dependencies, 45 tests.

`python` · `curses` · `tmux`

---

### Tools

Python (pandas · statsmodels · scipy · numpy) · SQL · experiment design and causal
inference · React · FastAPI

### Elsewhere

**[Portfolio and case studies →](https://mithun-portfolio-flame.vercel.app)**

<!-- Add your LinkedIn URL here, then delete this comment:
[LinkedIn](https://www.linkedin.com/in/your-handle)
-->
