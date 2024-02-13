Expected rendering
![image](https://github.com/KidElectric/r_notebook_tests/assets/14025598/64b8b25f-cb60-466d-a32a-9f17643d4586)

How it looks on nbviewer:
https://nbviewer.org/github/KidElectric/r_notebook_tests/blob/main/example.ipynb

What I now see on github:
![image](https://github.com/KidElectric/r_notebook_tests/assets/14025598/ae3f4043-f624-4ede-ae74-71b9483800db)

# Pages
~~~
~/envs/r_seurat/bin/jupyter nbconvert example.ipynb --to html --output example.html
git checkout --orphan gh-pages
~~~
switch to that branch and push
now atleast this exists:
https://kidelectric.github.io/r_notebook_tests/example.html
