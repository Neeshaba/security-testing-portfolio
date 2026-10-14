# Security Testing Lab — Memory Safety and Defences

A university security lab exploring stack-based buffer overflows, memory protections, and format-string vulnerabilities in a controlled local environment. This public overview describes a controlled university lab. Full assessment solutions and payloads are kept private.

## Topics covered

| Area | Work documented in the report |
| --- | --- |
| Stack-based buffer overflow | Investigation of an unsafe C string-copy operation and its effect on stack state and control flow. |
| Address-space randomisation | Comparison of behaviour after enabling ASLR and discussion of address predictability. |
| Stack protection | Examination of stack-canary checks and stack-smashing detection. |
| Predictable protection values | Analysis of a hypothetical deterministic canary scheme and why predictability undermines protection. |
| Non-executable stack | Observation of execution failure when stack memory is non-executable and discussion of code-reuse limitations. |
| Format-string vulnerability | Investigation of memory disclosure and modification through uncontrolled format strings. |

## Tools and environment

The report contains C examples, Python payload-generation snippets, shell commands, GDB inspection, GCC compiler options, Linux configuration, and pwntools usage. Parts of the exercise use a 32-bit environment.

## Skills demonstrated

- Inspecting stack memory and interpreting program crashes.
- Comparing memory-protection mechanisms in a controlled lab.
- Relating unsafe input handling to control-flow and data-integrity risks.
- Documenting observations and limitations of defensive mechanisms.

## Evidence and verification

This overview is based on the supplied report. Reported results have not been reproduced during this review, and the report is not an independently validated security audit. No testing of external systems has been performed.


## Publication scope

This repository contains documentation only. Assessment solutions, credentials, personal identifiers, and full project files are excluded.
