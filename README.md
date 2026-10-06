# DevAgent Bug Test Repository

This repository intentionally contains one deterministic bug.

## Expected behavior

`calculate_total(price, tax)` should return the price plus tax.

## Known buggy behavior

The current implementation subtracts tax instead of adding it.

The test in `test_app.py` should fail until the bug is fixed.

This repository is intentionally created for testing DevAgent's bug-fix
workflow and should not be treated as a production project.
