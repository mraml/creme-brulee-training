---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_8-3.4
      description: Rule for pcidss_4_8-3.4
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_8-03.04
---

# pcidss_4_8-3.4 - \[REPLACE_ME\] Invalid Authentication Attempts Are Limited.

## Control Statement

- Locking out the user ID after not more than 10 attempts.
- Setting the lockout duration to a minimum of 30 minutes or until the user's identity is
confirmed.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_8-3.4 -->

### Rules:

  - rule-pcidss_4_8-3.4

### Implementation Status: planned

______________________________________________________________________
