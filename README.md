# XBRL Extraction Workflow

This repository contains an automated XULE-based extraction workflow for SEC BDC filings.

## File Structure

- extract-fact-data-Loop.ipynb  
  Main notebook that:
  1. Compiles XULE rules
  2. Loops over BDC CIKs
  3. Executes Arelle extraction
  4. Saves output files to the specified directory

## Notes

- The workflow is adapted from the XBRL US sample code.
- The single sample URL has been replaced with a loop over BDC CIKs and filings.
- Output files are stored in the local BASE_PATH directory.

## Output Sample
<img width="1394" height="752" alt="image" src="https://github.com/user-attachments/assets/46ff6b3b-888a-415b-b921-83a31c02723d" />

