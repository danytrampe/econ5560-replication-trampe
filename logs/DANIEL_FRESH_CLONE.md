# Independent Fresh-Clone Verification

Verified November 9, 2026 by Daniel Trampe.

Repository: https://github.com/danytrampe/econ5560-replication-trampe

The repository was cloned into a new folder on my Mac, separate from the original downloaded replication project.

I created a Python 3.12 virtual environment, installed the project's requirements, removed previously generated output files, and executed the complete pipeline from Terminal.

Command: `python run_all.py > logs/run_log.txt 2>&1`

The command exited with status 0. All eight pipeline stages passed validation and regenerated 39 output files.

Environment: Python 3.12.10, macOS 14.4 arm64.

Measured runtime: 505.94 seconds (approximately 8 minutes 26 seconds).

Package versions: NumPy 1.26.4, pandas 2.3.3, SciPy 1.13.1, statsmodels 0.14.6, Matplotlib 3.9.4.

The original replication code was developed by Team 3, with Matthew Suban responsible for the primary coding implementation. His original verification record is preserved in `logs/FRESH_CLONE.md`.

Limitations: Some reproduced results differ from published values, and mixed-logit estimates are sensitive to simulation draws. Successful execution does not imply exact numerical reproduction of every published result.
