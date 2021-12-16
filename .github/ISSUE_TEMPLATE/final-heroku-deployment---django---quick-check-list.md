---
name: Final Heroku Deployment - Django - quick check list
about: Describe this issue template's purpose here.
title: ''
labels: documentation
assignees: dkitley1975

---

[ ] Ensure requirements.txt is up todate:  run pip3 freeze --local > requirements.txt
 
Settings.py 
[ ] Debug to False
[ ] X_FRAME_OPTIONS = 'SAMEORIGIN'   #(this is for the somernote editor)

In Heroku config Vars
[ ] Remove the DISABLE_COLLECTSTATIC  key
