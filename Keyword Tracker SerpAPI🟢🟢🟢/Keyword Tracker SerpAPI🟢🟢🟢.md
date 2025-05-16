# Keyword Tracker SerpAPI🟢🟢🟢

This workflow acts a keyword tracking app by checking if your domain ranks top 100 for a given keyword

It runs on a schedule and collects all the pages that we are ranking top 100 on SERP via the serp API

Setup

1. Set up your trigger to run this on a schedule
2. Map the path for `set site + keyword` and pass your keyword and url or interest
3. Make an API call to serp API with the given keyword to get top 100 items. Set your API key on this node to pass to the nodes dynamically
4. Make a copy of this google sheet (https://docs.google.com/spreadsheets/d/12Lcol-nL_ETIDI3-IOXh8i0TO4YnxZ---0QQFYQZ410/edit?gid=732537994#gid=732537994)and map your endpoint to the `upload rank` node
5. Run the workflow to generate a list of the keywords you are ranking for
