# IGSN Link-checking

1. Frequency of checking links

Sample checking is done by Crossref, but not ideal. Might be helpful for a high-level check.
EZID checks links every month, max. call frequency one call every 5 sec.
Frequency of link checking depends on how URLs are generated (Uwe)
DataCite could implement a policy of members/data centers agreeing to a certain frequency of link checks (Jennifer)
HEAD checks would be preferred (Uwe), GET if HEAD doesn’t return a 200 status
Handle URL should be stored in MDS, not only Handle server

2. Criteria for a broken link

What status codes are ok? 
In the big picture we want to know what is on the page, not just the status.
Change handle URL if it is a permanent redirect (Uwe)
Check content_type (should be text/html).

3. Re-checking broken links

Once a broken link is found, continue checking more frequently to determine that something is consistently down (Greg)
Potentially escalate your strategy once a broken link is found (Martin)

4. Reporting of broken links

Report links on member-specific page. Downloadable CSV files. Report by email would be nice (Michael).
Should broken link information be public or private? Might be preferable to keep information private if there are issues to sort out first.
