# Flutter to GitHub Pages Deployment TODO

## Completed Steps:
- [x] 1. Run `flutter pub get` to install dependencies
- [x] 2. Build web app: `flutter build web --release --base-href '/BUS-IT/'`
- [x] 3. Git init: `git init`, `git add .`, `git commit -m 'Initial Flutter commit'`
- [x] 4. Setup remote: `git branch -M main`, `git remote add origin https://github.com/MONISHC21/BUS-IT.git`, `git push -u origin main`

## Completed Steps:
- [x] 5. Create docs: `mkdir docs`, copy `build\web\*` to `docs\`

## Completed Steps:
- [x] 6. Deploy commit: `git add .`, `git commit -m 'Deploy Flutter web app to /docs folder for GitHub Pages'`, `git push`

## Pending Steps:
- [ ] 7. Manual: User enable GitHub Pages: Repo Settings > Pages > Source: Deploy from branch 'main', folder '/docs' > Save

**Live after: https://monishc21.github.io/BUS-IT/**

**Live URL after step 7: https://MONISHC21.github.io/BUS-IT/**

**Notes:** Windows commands used. Repo overwrite OK per approval.
