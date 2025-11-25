# shai-hulud-checker
A security scanner that analyzes package-lock.json and pnpm-lock.yaml to detect any npm packages linked to the Shai Hulud 2 Trojan. Parses full dependency trees (including transitive deps) and flags compromised packages. Easy to run locally or in CI to ensure supply-chain safety.
