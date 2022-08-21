# OverView
This is My Portofolio Source.

URL: https://myportfolio-84b54.web.app/

# Used template
https://templatemo.com/tm-464-ultra-profile#google_vignette

# Implementation steps
## prerequisite
have nodejs installed

## steps
1. Create Repository (Local, Remote)
4. Create Firebase Project
5. Firebase Hosting
```
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy --only hosting
// ※選択肢(Y/n)はEnterを押下。
```

6. Move HTML Template to Public Folder
7. ReDeploy
```
firebase deploy --only hosting
```