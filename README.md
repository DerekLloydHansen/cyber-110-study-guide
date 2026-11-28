# CYBER 110 Study Guide

An interactive practice site for **CYBER 110: Intro to Cybersecurity** at BYU. Students work through multiple-choice, true/false, select-all, matching, and short-answer questions drawn from the course quizzes and lecture slides. Every question explains why the correct answer is right.

**Use it:** open the site, pick a module, and answer at your own pace. You can skip questions, come back to them, and review explanations at any time.

## What's inside

211 questions in 12 modules, in course order:

| Module | Covers |
|---|---|
| Quiz 1 · Security Foundations | CIA triad and security services, information states, risk, the attack model, Secure by Design |
| Quiz 2 · Operating Systems & the Command Line | OS security jobs, trust boundaries, hardening, CLI commands, file permissions, virtual machines |
| Quiz 3 · Ethics, Privacy & AI | What ethics is, ethical frameworks, codes of ethics, privacy laws, GDPR, AI challenges |
| Quiz 4 · Secure & Usable Design | Dark patterns, account enumeration, PHI disclosure, Secure by Design, prototyping |
| Quiz 5 · Networks, the Internet & the Web | OSI model, MAC and IP addresses, packets, parts of a URL, Internet vs. Web |
| Oct 9 slides · Finding & Evaluating Information | Search skills, library databases, disinformation, evaluating sources, citing |
| Quiz 6 · Computer Hardware | Components, connectors, firmware, hardware attacks like Rowhammer and Spectre |
| Quiz 7 · Cryptography | Symmetric vs. asymmetric keys, signatures, hashing, HTTPS vs. E2EE, steganography |
| Quiz 8 · AI & Machine Learning Security | How LLMs work, poisoning, evasion, model extraction, prompt injection |
| Quiz 9 · HTML, CSS & JavaScript | Page structure, selectors, classes vs. IDs, comments, cross-site scripting |
| Quiz 10 · Malware & Staying Safe Online | Infection vectors, security controls, DNS, typosquatting, lookalike links |
| Nov 20 slides · Security Controls | Risk terms, control classifications, defense in depth, baselines, NIST and CIS |

Questions taken directly from a class quiz are tagged **"From Quiz N"**. Every question also has a short ID (such as `c5` or `w1`) shown on the question card.

## How scoring works

- Each score is **correct out of answered**.
- Short-answer questions show a model answer, and students mark their own answer right or wrong.
- Progress is saved in the student's own browser only. Nothing is sent to a server, and clearing browser data resets it.

## Running it

The whole site is one self-contained file, `index.html`. There is no build step and nothing to install.

- **Locally:** double-click `index.html` to open it in a browser.
- **On GitHub Pages:** in the repository on GitHub.com, go to **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save. The site will appear at `https://<username>.github.io/cyber-110-study-guide/`.

## Updating questions

All questions live in the `MODULES` array inside `index.html`. Each question has an `id`, a `type` (`mc`, `tf`, `multi`, `matching`, or `short`), the question text, its answer choices or pairs, the correct answer, and an explanation. For short answers, there is also a model answer.
