# AstroFlow – Playwright Automation Exercise

Exercise for the **Senior QA Automation** position.

- **Application under test:** https://astroflow.wingflows.com/
- **Starting point:** this repository

This repo contains one early Playwright test for the "Request a Quote" flow
([tests/demo.spec.ts](tests/demo.spec.ts)). It was written quickly and isn't
finished. Treat it as code you inherited from a teammate.

## Setup

```bash
git clone https://github.com/rsnorona/astroflow-playwright-exercise.git
cd astroflow-playwright-exercise
npm ci
npx playwright install
npx playwright test
```

## Tasks

1. **Finish and harden the existing test.** Complete the Request a Quote flow,
   submit it, and assert the outcome. Make the test reliable and readable.
2. **Improve the framework.** Restructure the project the way you would for a
   suite your team will maintain long-term, for example locator strategy, page
   objects, test data and configuration.
3. **Increase coverage.** Add the tests you think matter most for this site,
   such as form validation, navigation and key content. You don't need to
   cover everything. Pick what you'd prioritize and explain why.
4. **Make it runnable in CI.** For example, add a GitHub Actions workflow that
   runs the suite and keeps the report.
5. **Write a short `NOTES.md`** covering:
   - the decisions you made and the trade-offs
   - what you'd test next with more time
   - any bugs or risks you found in the application

## Guidelines

- Use TypeScript.
- Spend about **3 hours**. We care more about quality and reasoning than about
  how much you finish.
- Keep a meaningful commit history. We'll read it.
- Please don't put real personal data in your test data.

## Submission

Push your work to a **new public repository under your own GitHub account**
(please don't fork this repo), and send us the link by the deadline you were
given.

In the follow-up interview, you'll walk us through your solution, and we may
ask you to extend it live.

Good luck!
