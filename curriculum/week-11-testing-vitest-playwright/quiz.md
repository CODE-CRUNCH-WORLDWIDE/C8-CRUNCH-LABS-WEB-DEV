# Week 11 Quiz

> *Twelve questions. Multiple choice. Aim for 9 or better; below 7 means re-read the lecture(s) the missed questions came from. Each answer is folded under its question.*

---

### 1. The test pyramid is a heuristic for:

A. How many lines of code to write per file.
B. The ratio of unit, component, and end-to-end tests in a healthy suite.
C. The number of engineers needed per testing role.
D. The order in which tests should be authored.

<details>
<summary>Answer</summary>

**B** — the pyramid is about the ratio of test kinds. Lecture 1 §1.

</details>

---

### 2. According to the lecture (and Kent C. Dodds), the "mostly integration" guidance translates in the modern frontend stack to:

A. Mostly unit tests that mock everything.
B. Mostly end-to-end tests in real browsers.
C. Mostly component tests that render real components with real children.
D. Mostly snapshot tests of whole component trees.

<details>
<summary>Answer</summary>

**C** — "integration" here means component tests in the Testing Library sense. Lecture 1 §3.

</details>

---

### 3. The AAA pattern stands for:

A. Authenticate, Authorize, Audit.
B. Assemble, Apply, Approve.
C. Arrange, Act, Assert.
D. Allocate, Assign, Acquire.

<details>
<summary>Answer</summary>

**C** — Arrange, Act, Assert. Lecture 1 §2.

</details>

---

### 4. The Testing Library priority list places `getByTestId` last because:

A. It is the slowest query.
B. It bypasses the accessible tree, so a passing test does not imply a screen-reader-accessible component.
C. It cannot match elements with multiple test IDs.
D. It is deprecated in Testing Library v3.

<details>
<summary>Answer</summary>

**B** — `getByTestId` bypasses the accessible tree. Lecture 2 §4.

</details>

---

### 5. Which of these is the correct way to wait for an element that appears after an async operation?

A. `await new Promise(r => setTimeout(r, 1000)); expect(screen.getByText(...)).toBeInTheDocument()`
B. `expect(screen.getByText(...)).toBeInTheDocument()`
C. `expect(await screen.findByText(...)).toBeInTheDocument()`
D. `expect(screen.queryByText(...)).toBeInTheDocument()`

<details>
<summary>Answer</summary>

**C** — `findBy*` is the async-retrying query. Lecture 2 §8.

</details>

---

### 6. The lecture's position on mocking is:

A. Mock every dependency the unit under test has.
B. Mock the network at the boundary; do not mock React, the router, or child components.
C. Do not mock anything; every test should hit the real backend.
D. Mock only the components you do not own.

<details>
<summary>Answer</summary>

**B** — mock at the network boundary; render everything else for real. Lecture 2 §6.

</details>

---

### 7. Which MSW configuration causes the test to fail if the component fires a request to an undefined URL?

A. `server.listen({ onUnhandledRequest: 'warn' })`
B. `server.listen({ onUnhandledRequest: 'bypass' })`
C. `server.listen({ onUnhandledRequest: 'error' })`
D. `server.listen()` (the default)

<details>
<summary>Answer</summary>

**C** — `'error'` is the strict mode that fails on undefined URLs. Lecture 2 §7.

</details>

---

### 8. Playwright's `trace: 'on-first-retry'` configuration:

A. Records a trace for every test, every run.
B. Records a trace only on the first retry of a failing test.
C. Records a trace only for the first test in each file.
D. Records a trace only when the user passes `--trace` on the command line.

<details>
<summary>Answer</summary>

**B** — `'on-first-retry'` captures a trace exactly when needed (after a flake). Lecture 3 §6.

</details>

---

### 9. Playwright's web-first assertions (`await expect(locator).toBeVisible()`) differ from synchronous assertions because:

A. They run in a worker thread.
B. They automatically retry for up to the configured timeout until the assertion passes.
C. They run only in headless mode.
D. They require an explicit `await page.waitForTimeout` before them.

<details>
<summary>Answer</summary>

**B** — web-first assertions auto-retry up to the timeout. Lecture 3 §3.

</details>

---

### 10. A worker-scoped fixture in Playwright runs:

A. Once per test.
B. Once per file.
C. Once per worker (i.e., once per parallel browser process).
D. Once per CI run.

<details>
<summary>Answer</summary>

**C** — worker-scoped fixtures run once per parallel worker process. Lecture 3 §4.

</details>

---

### 11. The recommended way to keep visual-regression baselines reproducible across local development and CI is:

A. Commit baselines for every platform (macOS, Linux, Windows) and pick the one matching the runner.
B. Commit only the Linux baseline (since CI runs on Linux) and use Playwright's Docker image to regenerate it locally when needed.
C. Disable visual tests in CI and run them only locally.
D. Use a 50% threshold on `maxDiffPixelRatio` so small differences do not matter.

<details>
<summary>Answer</summary>

**B** — Linux baseline as canonical; Docker for local regeneration. Lecture 3 §7 and challenge 2.

</details>

---

### 12. The lecture's coverage-threshold guidance is:

A. Aim for 100% statement coverage; nothing below is acceptable.
B. Aim for 60–80%; the last 20% has sharply diminishing returns and the budget is better spent improving the tests you have.
C. Coverage is meaningless; do not measure it.
D. Drive coverage above 95% even if it means writing tests of trivial getters.

<details>
<summary>Answer</summary>

**B** — 60–80%, then stop. Lecture 2 §11 and lecture 1 §5.

---

</details>

---

## Scoring

- **12 / 12** — read the bonus links in `resources.md`.
- **10–11 / 12** — solid; spot-check the lecture sections you missed.
- **7–9 / 12** — competent; re-read the lectures the missed questions came from.
- **Below 7** — re-read all three lectures before the mini-project.
