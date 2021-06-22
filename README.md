# CodeXplore Portfolio Website

- Portfolio Website of CodeXplore Founder - Quan Nguyen
- [Live Demo](https://codexplorerepo.github.io/)

### Technology:

- Font: Poppins
- Next.js, React.js, HTML, JS, SASS
- Icon: https://iconscout.com/unicons/explore/line

### Commands

#### Development Commands:

| Usage         | Command             |
| ------------- | ------------------- |
| Start Dev Env | `npm run dev`       |
| Pre-Deploy    | `npm run predeploy` |
| Deploy        | `npm run deploy`    |

#### Deployment:

- In `package.json`, please add below:

```json
"homepage": "https://codexplorerepo.github.io/"

#In script:
"predeploy": "npm run build",
"deploy": "gh-pages -d out"
```

- Once `npm run predeploy` > `npm run deploy`:
  - `git add .` > `commit` > `push`
- In `Settings`, Github Pages, chọn branchs Gh-Pages
