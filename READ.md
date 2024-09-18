echo "# my-project-hpk2t5i1kzfq2nbqhjnd7pjkbu8hxw9rtbpquk54eti31" >> README.md
git init 
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/VintageViiews/my-project-hpk2t5i1kzfq2nbqhjnd7pjkbu8hxw9rtbpquk54eti31.git
curl -sS https://webi.sh/gh | sh
gh auth login
git push -u origin main
