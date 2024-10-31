# redacted-submission

As you can see this repo contains no code. That's because we have a load of code and they are seperated into a load of different repos for ease of viewing. Here is a list of all repos that are included as part of our hackathon submission, some repos were started before the hackathon since this is a pre-existing project but we will make it obvious what was added during the hackathon! Please see our devpost for details on each element and why betVEX as a whole is an awesome project!

Demo https://youtu.be/-7H39i4q2ug

The project is hosted at https://betvex.vercel.app/

- [Betting and staking system](https://github.com/vex-labs/vex-contract), during the hackathon the staking system was added in [this PR](https://github.com/vex-labs/vex-contract/pull/26).
- [Frontend](https://github.com/vex-labs/vex-frontend), most of the frontend was added during the hackathon but there was some pre-existing code, code was added from [this commit](https://github.com/vex-labs/vex-frontend/commit/30646d3f5ad8555b4f5f100aba6ac5de2ba8a621) onwards.
- [near-relay](https://github.com/SurgeCode/near-relay), a pre-existing library that received significant upgrades during the hackathon to support password-based key management, customizable account creation, and sub-accounts, this has now become a fully featured account system that can be used in any app to abstract away on-chain accounts, making it a flexible solution for integrating secure account management and recovery across various applications., as demonstrated in commit 1 and commit 2. 
[commit 1](https://github.com/SurgeCode/near-relay/commit/c358a6847ef07b5e8a6f069250c88f727bd1f481) and [commit 2](https://github.com/SurgeCode/near-relay/commit/ecd43307356f74343bcfc55dbd2550df594f0816).
- [Database](https://github.com/vex-labs/vex-database) fully created during in this hackathon.
- [Ref finance in contract full swap example](https://github.com/PiVortex/ref-swap-example) fully created during this hackathon.
- [Wallet recovery starter example](https://github.com/PiVortex/mpc-proxy-transaction) using MPC to recover accounts, fully created during this hackathon.

