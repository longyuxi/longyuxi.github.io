---
layout: post
title: A GroupMe link extractor
subtitle: No more scrolling through the sea of chat history just to find invitation links
gh-repo: longyuxi/groupme_links_finder
gh-badge: [star, fork, follow]
tags: [afternoon project]
comments: true
---

# GroupMe Link Extractor
Made in an afternoon in the first month during my first semester at Duke, this is a script that finds invitation links to other GroupMe groups by browsing through the chat history of a designated group and matching every message against a regular expression. Outputs a table containing the:
1. Inferred Title (if the message is a directly pasted GroupMe invitation that starts with "You're invited to my new group ...")
2. Invitation link matched by RegEx
3. Time at which message was sent
4. Original sender (so you can DM him/her if the link fails to work)


Click on "star" to see its GitHub repo. Detailed description in there.

### A screenshot of the result
![End result demo](/assets/img/groupy-result.png)