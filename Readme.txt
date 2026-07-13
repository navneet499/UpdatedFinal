git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/navneet499/UpdatedFinal.git
git push -u origin main


devops pipeline sequence
1. agent
2. Install
3. Restore
4. Build
5. Publish
6. Artifact....drop(Zipfile)
all six steps is said to be continous integration

Deployment-
a. Service connection...AzureResourcegroup...AzureWebapp...Deploy(Zipfile)
DotnetCoreService..NavneetWebApp
NavneetUpdatedConnection