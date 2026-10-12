How to run
Open the notebook and check DATA_ROOT in the CONFIG cell.
Smoke test first (recommended): set QUICK_TEST to true (or start Jupyter with the environment variable FL_QUICK=1). This runs 4 rounds with 3 local steps and confirms the whole pipeline works.
Turn QUICK_TEST off and Run All.

The unit-test cell runs before the experiment. If one of the five tests fails, stop and fix it before waiting on the run.
