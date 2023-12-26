# submodule_test

Standard submodule test.

echo "# submodule_test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git submodule add https://github.com/watarium/cocoon_drop.git cocoon
git push -u origin main
