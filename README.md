```bash
rm -rf .git
git init
git config --local user.name "admin"
git config --local user.email "admin"
git add .
git commit -m "first commit"


git remote remove origin
git remote add origin git@github.com:gptinfo/app.git
git push -u origin main
```

```
https://gptinfo.github.io/app/privacy.html
```