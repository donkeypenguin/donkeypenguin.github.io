**Currency**
- Symbol:  ツ 
- Code:  GRIN
- Precision:  10^−9
- Subunits: follows SI prefix scheme[^1].
  - Milligrin, a thousandth of a grin
  - Microgrin, a thousandth of a milligrin
  - Nanogrin, smallest unit, takes a billion nanogrin to make a grin
- Exchange rate:  US$0.03 (2024)
- Initial distribution:  No presale of any kind.
- Circulating supply:  ~ツ187,000,000 (December 2024)
- Inflation rate: ~ツ32,400,000 minted each year.
- Supply limit:  No limit (ツ1/sec, forever)

**Ledger**
- Timestamping scheme:  Proof-of-work (MimbleWimble)
- Hash function:  Cuckatoo32
- Difficulty Adjustment: [Damped Weighted Moving Average](https://github.com/mimblewimble/grin/blob/master/core/src/consensus.rs#L174)
- Genesis block: 2019-01-15 16:01:26 UTC
- Block reward:  ツ60
- Block time: [1 minute](https://github.com/mimblewimble/grin/blob/master/core/src/consensus.rs#L36-L40)
- Block size limit: [~1.5MB](https://github.com/mimblewimble/grin/blob/master/core/src/consensus.rs#L110C1-L122C42)
- Average Transaction Size: ~1.76KB
- Max Transaction Throughput: ~15 transactions per second

**Development**
- Original author(s):  Ignotus Peverell
- Initial release:  v1.0.0 / January 15th, 2019
- Latest release:  v5.3.3 / September 16th, 2024
- Website:  [https://grin.mw/](https://grin.mw/)
- Code repository:  [https://github.com/mimblewimble/grin](https://github.com/mimblewimble/grin)
- Development status:  Active
- Project Codebase:  Original MimbleWimble implementation, not a derivative work. 
- Programming Language:  Rust
- Operating system:  Windows, OS X, Linux
- Developer(s):  Grin Core Development Team
- Source model:  Open source
- Software License:  Apache License Version 2.0


[^1]: Consensus.rs: https://github.com/mimblewimble/grin/blob/master/core/src/consensus.rs#L36-L40
