## Guidelines проекта "Прожито"
<div align="right">
  <img src="https://github.com/prozhito/project/blob/main/apps/center/public/logo/prozhito_logo_ru.svg" width="156">
  <span>&nbsp;</span>
  <img src="https://github.com/prozhito/project/blob/main/apps/center/public/logo/eusp_logo_ru.svg" width="102">
</div>

- [Commits](./commits.md)
- [Repository](./repository.md)
- [Types](./types.md)

## Utils
### Installation:
```
git clone git@github.com:prozhito/utils.git
cd utils
nvm install 21
npm install
```
### Coworking process:
1. `git pull`
2. `git checkout -b feat/feature_name`
3. Make changes.
4. `git add .`
5. `git commit -m "feat: feature name"`
6. `git push`
7. Create pull request.
8. Ask for review.
9. After approval squash merge and delete branch.
10. `git checkout main`
11. `git branch -D feat/feature_name`
12. Repeat from 1-st step for a new feature.
