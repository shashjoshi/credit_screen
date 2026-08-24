# credit_screen
Simple Credit Risk/Fundamentals screener
A Python Notebook tool for pulling a company's fundamentals and analyzing a bonds yield against that company's credit profile. 
Built as a personal project using only free, publicly accessible, public APIs and sources
## Usage
1. Open in Jupyter Notebook, Colab, or another service used to run ipynb files.
2. Fill out headers in SETUP
3. Set TICKER in Step 1
4. Run through steps 2-5
5. Look up a real bond from chosen issuer and fill in Step 6
6. Run the rest of the notebook
## Data Sources
SEC EDGAR XBRL API - Automated financials <br>
FINRA Fixed Income Data Center - Manual Bond Lookup <br>
US Treasury Daily Par Yield Curve - Automated Benchmark Rates <br>
## Requirements
pip install requests pandas 
## Limitations
Manual bond entry/lookup <br>
Rudimentary, rule-based heuristic credit "read"
