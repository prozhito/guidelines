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
4. `npm run format`
5. `npm run lint`
6. `git add .`
7. `git commit -m "feat: feature name"`
8. `git push`
9. Create pull request.
10. Ask for review.
11. After approval squash merge and delete branch.
12. `git checkout main`
13. `git branch -D feat/feature_name`
14. Repeat from 1-st step for a new feature.

### Deployment:
[Actions](https://github.com/prozhito/utils/actions) > Prozhito utils live/test > Run workflow
