# 5-Minute Demo Outline

1. Problem (30 sec): Content teams can't manually review 
   every page on the site to know what needs refreshing.

2. Show the queue (1 min): Show the top 10 ranked pages 
   from the model — explain this is the priority list.

3. Walk through one example (1.5 min): Pick one page, 
   explain why it's flagged — stale, still getting visits, 
   but declining.

4. Baseline vs Model (1 min): Show the comparison table — 
   rule-based baseline vs Random Forest, Precision@20 and @50.

5. Limitations honestly (30 sec): This is a proxy label, 
   not proof the page will actually improve if refreshed.

6. Close (30 sec): Recommendation — use this as a review 
   queue, a human still confirms before acting.

# Social Post

Built a content refresh scoring model that ranks pages by 
staleness and declining demand — no manual scanning needed. 
Random Forest hit 0.75 precision@20 vs a rule-based baseline 
on a client-grouped split. Full writeup and code in the repo.

# Employer-Facing Summary

I built a model that helps content teams decide which pages 
need refreshing, instead of manually checking every page. 
It looks at signals like page age, visibility, and traffic 
trends to automatically rank the highest-priority pages. 
This turns a manual review process into a simple queue the 
team can act on.