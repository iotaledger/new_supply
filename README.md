# IOTA New Supply

This repository holds the information around the supply increase on the IOTA Mainnet in 2023. If you are unsure what
this is about checkout https://blog.iota.org/stardust-upgrade-iota-tokenomics/. You can find the genesis snapshot
generated on the 4th of October 2023 [here](https://dbfiles-stardust-mainnet.s3.eu-west-1.amazonaws.com/snapshots/genesis_snapshot.bin).

The blake2b-256 hash of the generated snapshot file
was `bc5d82708151c74fc4983e64728bf8a142f27796d3400be452c0a9299b9de901` while using `global_snapshot-7669900.bin` (aka
the network was upgraded at milestone 7669900).

> The initial unlock is calculated as `INITIAL UNLOCK = (TOKENS*10%) + MOD(TOKENS - (TOKENS*10%), UNLOCK_FREQ)` per
address.

You can find CSVs holding the address/balance pairs plus the specific outputs and their unlock time here (micros
denominated):

| Tokens (micros)     | Vesting Schedule                              | Target                             | File                             |
|---------------------|-----------------------------------------------|------------------------------------|----------------------------------|
| 325,469,717,000,000 | 4-years, 10% initial unlock, bi-weekly unlock | IOTA Foundation                    | [Link](IOTA_Foundation)          |
| 552,000,000,000,000 | 4-years, 10% initial unlock, bi-weekly unlock | Tangle Ecosystem Association (TEA) | [Link](TEA)                      |
| 552,000,000,000,000 | 4-years, 10% initial unlock, bi-weekly unlock | UAE Entity                         | [Link](UAE)                      |
| 162,139,266,508,333 | 2-years, 10% initial unlock, bi-weekly unlock | ASMB Investors                     | [Link](Assembly_Investors)       |
| 14,872,396,957,019  | 2-years, 10% initial unlock, bi-weekly unlock | ASMB IF Members                    | [Link](Assembly_IF_Members)      |
| 161,000,000,000,000 | 2-years, 10% initial unlock, bi-weekly unlock | IOTA Airdrop                       | [Link](IOTA_Airdrop)             |
| 52,988,336,256,887  | 2-years, 10% initial unlock, bi-weekly unlock | New Investors Pool                 | [Link](New_Investors)            |
| 62,560,976,001,027  | None                                          | DAO Treasury                       | [Link](Treasury_DAO)             |
| 175,893,692,656,112 | None                                          | Non-Migrated Legacy Tokens         | [Link](Unmigrated_Legacy_Tokens) |