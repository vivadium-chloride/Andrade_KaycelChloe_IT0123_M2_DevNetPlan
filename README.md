# IT0123 DevNet Resource Validation Plan

## Student and Project

- Name: Andrade, Kaycel Chloe B.
- Section: BSCSAI - TA31
- Repository name: `Andrade_KaycelChloe_IT0123_M2_DevNetPlan`

## Purpose

Explain in 2-3 sentences why selecting the correct DevNet resource matters before beginning a network-automation task.

- Selecting the correct DevNet resource matters before beginning a network-automation task is important because the resources are the ones that will help the developer build the task itself. These tools are created to make the developer's life easier, and it can also be useful when the developer wants to know more on the development process while he or she is doing it along the way.

## Validated Resource Decisions

Summarize your four selections from `student_plan.json`. For each use case, state the selected resource, the most important requirement, and the official Cisco evidence used.

UC1: Always-on Sandbox
Most Important Requirement: immediate access + shared environment + read-only privileges
Cisco Evidence: https://developer.cisco.com/docs/sandbox/

UC2: Reservation Sandbox
Most Important Requirement: private/isolation + administrative access
Cisco Evidence: https://developer.cisco.com/docs/sandbox/

UC3: Learning Labs
Most Important Requirement: structured, step-by-step instruction
Cisco Evidence: https://developer.cisco.com/learning/

UC4: Code Exchange
Most Important Requirement: Cisco-maintained code repositories
Cisco Evidence: https://developer.cisco.com/codeexchange/

## AI Evaluation

Identify at least one AI recommendation that you accepted, rejected, or modified. Explain the evidence behind your decision.
- The main concern I had with the AI is that no matter what I say to it to not make up fake URLs, it will still either come up with those, or cite something that is not related to the context it is giving; I was able to catch this since most of the resources I was able to diagnose immediately were the ones that it got wrong.

## Validation Evidence

- Validator result: 

PASS: JSON file loaded
PASS: student and AI disclosure completed
PASS: all four scenario IDs present
PASS: resource classifications match scenario requirements
PASS: official Cisco evidence URLs supplied
PASS: AI verification statuses are valid
PASS: rationales are sufficiently detailed
PASS: AI recommendations are summarized in the student's own words
PASS: no credential-like fields detected

VALIDATION COMPLETE: 9/9 checks passed.

- Command used: py validate_plan.py

- Official Cisco pages reviewed:
~ https://developer.cisco.com/docs/sandbox/
~ https://developer.cisco.com/networking-platform/
~ https://developer.cisco.com/codeexchange/

## Git Evidence

- Initial commit message: "Add student_plan.json file"
- Validation commit message: "Filled up resource types and validated explanations stated by AI"
- Output of `git log --oneline`:
~ 9a05a45 Filled up resource types and validated explanations stated by AI
~ f341d76 Add student_plan.json file
~ ff57b40 Update README_template.md
~ b596764 Add files via upload

## AI-Use Disclosure

State the AI tool used, the type of assistance received, what was independently checked, and what you revised.

- AI Tool Used: ChatGPT
- Type of Assistance: Help with understanding the instructions of the activity + verifying the resources needed for different case scenarios.
- What was independently checked: the content of each resource and whether it fit the use case problem
- Revised Content: URLs given

