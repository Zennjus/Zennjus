echo "# Zennjus" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Zennjus/Zennjus.git
git push -u origin main
echo "<!DOCTYPE html><html><head><title>Zennjus Recharge</title></head><body><h1>Welcome to Zennjus Recharge</h1></body></html>" > index.html
git add index.html
git commit -m "Added index.html"
git push origin main
