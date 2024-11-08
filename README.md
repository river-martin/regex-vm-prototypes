# Regex VM Prototypes

This repository contains prototypes for virtual machines designed to execute regular expressions.

## Overview

The Regex VM Prototypes project aims to explore different approaches to implementing a virtual machine that can process regular expressions.

### Submodules

Here's a breakdown of each submodule:

- **lockstep-vm**: Lockstep-scheduled VM with state caching and copy-on-write capture memory.
- **memo-rvm**: Spencer-scheduled VM with a buggy memoisation instruction.
- **rasm**: A script that generates a C program that implements a particular Spencer-scheduled VM program.
- **simple-re2-vm**: A minimal Python implementation of RE2's DFA simulator.
