# AnyPS5 — AMD64 converter test on Termux

Date: 2026-10-14
Branch: main
Source commit: a31043146e70a3e17232d6b1df4d6e993791d73b
Environment: Android / Termux / AArch64
Build target: amd64_only_converter_tests
Build directory: ~/.cache/anyps5-converter-tests

## Result

Command:
ctest --test-dir "$HOME/.cache/anyps5-converter-tests" --output-on-failure -R '^amd64_only_converter$'

Result: PASS
Tests passed: 1/1
Tests failed: 0
Reported test time: 0.09 seconds

Executable:
tests/amd64_only_converter_tests
Reported size: 5.8 MiB

Source integrity:
- CMakeLists.txt restored to its original condition.
- git status was clean before creating this evidence file.

Scope:
This validates only the amd64_only_converter unit test.
It does not establish full PS5 compatibility or successful game execution.
