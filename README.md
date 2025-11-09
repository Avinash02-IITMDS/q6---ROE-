# Matrix Build CI Example (e42a001)
Email : 25ds3000131@ds.study.iitm.ac.in
This repository demonstrates a GitHub Actions matrix build that:
- Runs a matrix over Node versions 14, 16, and 18.
- Produces and uploads one artifact per matrix job.
- Artifact names are prefixed with `build-e42a001-<variant>`.

## Workflow
File: `.github/workflows/matrix-build.yml`

## Artifacts
After a successful run, you should see artifacts in the Actions run:
- `build-e42a001-v14`
- `build-e42a001-v16`
- `build-e42a001-v18`

Each artifact contains a small text file with build metadata.

## Contact
For questions contact: your-email@example.com
