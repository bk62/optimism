# @eth-optimism/teleportr

## 0.0.5

### Patch Changes

- 44c293d8: Fix confs_remaining calculation to prevent underflow

## 0.0.4

### Patch Changes

- 7a320e22: Use L2 gas price in driver

## 0.0.3

### Patch Changes

- 160f4c3d: Update docker image to use golang 1.18.0

## 0.0.2

### Patch Changes

- f101d38b: Add metrics for balances

## 0.0.1

### Patch Changes

- 172c3d74: Add SuggestGasTipCap fallback
- 6856b215: Count reverted transactions in failed_submissions
- f4f3054a: Add teleportr API server
- 3e57f559: Bump `go-ethereum` to `v1.10.16`
- bf1cc8f4: Restructure Deposit and CompletedTeleport to use struct embeddings
- bced4fa9: Add LoadInTeleport method to database
- e5732d97: Add btree index on deposit.txn_hash and deposit.address
