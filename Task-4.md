# TASK 4. Repository with at least three meaningful commits.

# create the repo
mkdir HTML-CSS && cd HTML-CSS
git init
git branch -M main

# commit 1
echo "# HTML-CSS" > README.md
git add README.md
git commit -m "docs: add README with project overview"

# commit 2
cp -r /C:\Users\LENOVO\OneDrive\Desktop\CODING\ASSIGNMENTS .
git add 01-*.md 02-*.md 03-*.md 04-*.md 05-*.md
git commit -m "docs: add setup & git assignments (1-5)"

# commit 3
git add 06-*.html 07-*.html 08-*.html 09-*.html 10-*.html
git commit -m "feat: add HTML basics assignments (6-10)"
