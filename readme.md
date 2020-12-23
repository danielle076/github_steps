### Stappen voor nog niet bestaande files naar GitHub
1. git init
2. git status
3. .gitignore aanmaken /.idea
4. git rm -r –cached.idea
5. git add .
6. git status
7. git commit -m "comment about changes”
8. git remote add “link repository GitHub”
9. git push origin master

### Files staan al op GitHub, stappen voor aanpassingen
1. git status
2. git add .
3. git status 
4. git commit -m "comment about changes”
5. git push origin master

### Files staan al op GitHub, stappen voor aanpassingen
1. Clone een GitHub project naar jouw computer
2. Maak een GitHub repository aan

Terminal WebStorm/IntelliJ
3. git remote remove origin
4. git remote add “link repository GitHub”
5. git push origin master
6. git checkout -b feature/naam


7. Maak aanpassingen aan de file

Terminal WebStorm/IntelliJ
8. git status
9. git add .
10. check of alles groen is
11. git commit -m "comment about changes”
12. git push origin feature/naam


13. Via GitHub maak je een Pull Request (PR) en dan compare & pull request