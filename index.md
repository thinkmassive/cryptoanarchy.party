## Getting Started with DLCs

Refer to [Executing A DLC with Bitcoin-S](https://bitcoin-s.org/docs/wallet/dlc) for a complete walkthough.

## DLC Oracle Events

### Taproot Adoption

Taproot actived at block 709632. Every 2016 blocks this oracle creates a new attestation:
```
(number of transactions in past 2016 blocks with at least one P2TR input)
-------------------------------------------------------------------------
         (total number of transactions in past 2016 blocks)
```
The numeric value represents **hundredths of a percent**, with a range from 0 to 10000 (e.g., 4.2% is `420`)

- [block 733824](https://oracle.suredbits.com/announcement/131b1ab7acf248003fbec0884e9c71378d0797595fc76623f5da5b606a455a09) (estimated 2022 Apr 28)
- block 735840 (estimated 2022 May 12)
- block 737856 (estimated 2022 May 26)
- block 739872 (estimated 2022 Jun 9)
- block 741888 (estimated 2022 Jun 23)

## External References

For detailed data on taproot adoption, visit [txstats.com](https://txstats.com/dashboard/db/taproot-statistics?orgId=1)

<script data-goatcounter="https://cryptoanarchyparty.goatcounter.com/count" async src="//gc.zgo.at/count.js"></script>
