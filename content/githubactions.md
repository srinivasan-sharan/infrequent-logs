Title: my first ci/cd pipeline
Date: 2026-07-31 13:20
Category: tech revelations
Slug: my-super-post
Authors: sharan
Summary: bro yaps about how ci/cd is cool


the site is up! (until i break it again)

so i set the blog up (locally) and it works, wohooo! i then learnt that i could host this (smiles deviously).
this is when i remembered my classes from engineering, where i was taught KISS
we shall now kiss via github actions

setting it up was pretty simple, make sure you point to the right site on you publishconf.py file and then just add a workflow (call it pelican.yaml cuz best practices is the best), you then just add a cheeky setting on github to use pages and you are DONE!

wohoooo, simple right? WRONG, my stupid brain was editing the local conf for a solid 20 mins, wondering why the css doesn't load, i then asked my fav debugging friend, sir claude jr. and surprise surprise, i am the stupid one. fixed the issue, fixed the blog. we have prod up, with close to 0 down time for 0 users.

such an elaborate setup, and what is the outcome? true joy and material for this very blog

-- kiss(ing the floor with a severe lack of skills)