# Decisions

A decision log: what you chose and why, in your own words.
P1 uses a file with this name and five questions; this one has one.
Answer it in two or three sentences after the live page is verified, then commit and push it.

## How you know it works

What check did you run on the live page, and what would have made that check fail?
A check that could not have failed is not a check.

I ran '❯ In work/03/lab, poll `gh api repos/cnash03/03-git-verify-deploy/pages/builds/latest --jq .status` every 15 seconds until it says built,
  then fetch the live URL and confirm the sentence I put in index.html is present. Paste the exact command output, do not summarize." in claude code.
This would have failed if I did not have gh installed or if I was not logged in.