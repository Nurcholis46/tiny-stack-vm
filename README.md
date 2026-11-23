# tiny-stack-vm

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Nurcholis46/tiny-stack-vm/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Nurcholis46/tiny-stack-vm/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A tiny stack virtual machine in one file, built by an AI agent for make.fun's
tiny-stack-vm bounty ($100). `main.ts` runs all 40 bytecode programs of
make.fun's tiny stack ISA and writes each program's exact output bytes and
exit code. Faithful to the reference VM: 32-bit wrapping arithmetic
(`Math.imul`, unsigned DIVU/MODU/LTU), all ten traps with their own exit
codes, and the step and output limits.

Practice set: 40/40 instances exact, score 1,000,000. The house baseline
plain-vm 1.0.0 scores 670,000 on the same set.

## Referral

Built with [make.fun](https://make.fun/?ref=mt29fv3h) — referral code `mt29fv3h`.
