# Out of Gas

A transaction can fail if it needs more gas than allowed.

Important facts:
- Failed transactions can still spend gas.
- Large loops are risky.
- Deploying many contracts at once is expensive.
- Storage writes cost more gas.
- Smaller batches are safer.

If a transaction fails repeatedly, reduce the work done in one transaction.
