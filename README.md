﻿Git assignment 2
Steps:

1. mkdir Git-2
2. cd Git-2
3. git init
4. echo "Git assignment 2" > README.md
5. git add README.md
6. git commit -m "Add readme file"
7. git branch -M main
8. git remote add Fatin https://github.com/Newt20/Git-assignment-2.git
9. git push -u Fatin main
10.git checkout -b feature-1
11.echo "Feature 1 content" > feature1.txt
12.git add feature1.txt
13.git commit -m "Add feature 1 in feature-1 branch"
14.git push -u Fatin feature-1
15.git checkout main
16.git checkout -b feature-2
17.echo "Feature 2 content" > feature2.txt
18.git add feature2.txt
19.git commit -m "Add feature 2 in feature-2 branch"
20.git push -u Fatin feature-2
21.git checkout feature-1
22.git fetch Fatin
23.git rebase Fatin/main
24.git push Fatin feature-1
25.git checkout feature-2
26.git fetch Fatin
27.git rebase Fatin/main
28.git push Fatin feature-2
29.git checkout main
30.git branch -d feature-1
31.git branch -d feature-2
32.git push Fatin --delete feature-1
33.git push Fatin --delete feature-2
34.git branch -a
