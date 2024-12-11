# css-fundamentals-lab

(1)
git add .
git commit -m "init project"
git push

(2)
git checkout -b "feature/main"
git add index.html
git commit -m "create main page"

(3)
git checkout -b "feature/css"
git add css/styles.css
git commit -m "add basic CSS selectors"

(4)
git add css/styles.css
git commit -m "add box model styles"

(5)
git add css/styles.css
git commit -m "add flexbox layouts"

(6)
git checkout main
git merge feature/main
git merge feature/css
git push origin main
