# Uncommon Python Bug: Silent Failure on Non-Numeric Input

This repository demonstrates a subtle bug in a Python function designed to calculate the average of a list of numbers. The function correctly handles empty lists, but it fails silently when presented with non-numeric input, returning an unexpected result. This bug can be difficult to detect because it doesn't raise an error.