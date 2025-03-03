
# How to transfer 1 repo from organisation to my own profile 

1. Go to original repo and click on "code" -> copy HTTPS link
2. Open VS code and type >git clone in command palette
3. Save local
4. Open terminal
```bash
git remote remove origin
```
5. Add the new repo at Github
6. Open terminal
```bash
git remote add origin https://NEW HTTPS LINK.git
```
```bash
git branch -M main
```
```bash
git push -u origin main
```


