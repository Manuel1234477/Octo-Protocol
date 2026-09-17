# Working on Octo

These apply to every task, across this Rust backend and the Next.js frontend.

## 1. Engineering quality
Use sound design and engineering practice in both codebases. Prefer patterns already established
here over inventing new ones.

## 2. Security first
Consider security *before* starting a task, not as a review afterwards. Octo is non-custodial and
moves real money — treat the threat model as live, not theoretical. `docs/threat-model.md` is the
reference.

## 3. Then scalability and clarity
Once a change is secure, make sure it scales and is easy to understand. Favour the version a new
engineer can follow over the clever one.

## 4. Actively hunt for exploitable gaps
On every task, look for gaps or vulnerabilities a malicious actor could exploit. If you find one,
prevent it and report it — even when it falls outside the scope you were asked to work on.

## 5. Comment style
One line of comment per block. No bloated code.
