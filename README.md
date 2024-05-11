# Setup
1. Download repo and `cd` into it
2. `pip install -r requirements.txt` (this assumes you have Python and PIP installed already)
3. create a file called `.secrets` and make sure it looks like the example below. Replace `XXX` with your [Linear API key](https://linear.app/brightmetrics/settings/api).
```conf
[DEFAULT]
API_KEY=XXX
```
4. Then run the notebook via `jupyter notebook CustomSprintMetrics.ipynb`
