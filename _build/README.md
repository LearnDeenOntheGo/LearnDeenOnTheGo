# How this copy was made (Web project)

Free static copy of learndeenonthego.com (WordPress), address https://learndeenonthego.github.io/LearnDeenOnTheGo/. Hidden from search (noindex, canonical = the real site) until the name is moved here.

`smallsite.sh` mirrors the site; then `HIDDEN=1 python3 -I wpstatic.py mirror OUT learndeenonthego.com https://learndeenonthego.github.io/LearnDeenOnTheGo/ posts.json pages.json` (on move day drop HIDDEN=1 and use https://learndeenonthego.com/ as the address). Check with linkcheck.py and shoot.js.
