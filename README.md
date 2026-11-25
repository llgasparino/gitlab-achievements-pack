<div align="center">

[![English](https://img.shields.io/badge/lang-English-blue.svg)](./README.md)
[![Português](https://img.shields.io/badge/lang-Português-green.svg)](./README.pt-BR.md)

</div>

# 🦊 GitLab Achievements Pack

A collection of custom, lighthearted badges to gamify your daily engineering, QA, DevOps, and onboarding workflow on **GitLab** (including the **Free Self-Managed** tier).

The goal is simple: turn classic day-to-day engineering moments—from accidentally committing a `.env` file to saving a Friday deploy or taking down a test database during a load test—into fun milestones for learning, recognition, and team decompression.

---

## 🏆 Achievements Catalog

> All descriptions below fit within GitLab's **200-character limit**, and all `.webp` badge files in `/badges` are already compressed to **under 200 KB** (ready for direct upload).
> 
| Badge | Title | Description (≤ 200 chars) |
| :---: | :--- | :--- |
| <img src="./badges/01-enviou-a-env.webp" width="72" /> | **Committed the .env** | Awarded for the quick fix and hands-on lesson after removing a `.env` file from the repository, updating `.gitignore`, and securing credentials. |
| <img src="./badges/02-arqueologo-de-git.webp" width="72" /> | **Git Archaeologist** | Awarded to the explorer who opened, analyzed, or resolved conflicts in legacy code untouched for over two years. |
| <img src="./badges/03-sexta-sem-medo.webp" width="72" /> | **Fearless Friday** | Awarded to anyone brave enough to open a Merge Request or deploy after 5 PM on a Friday and keep everything running smoothly through the weekend. |
| <img src="./badges/04-lgtm.webp" width="72" /> | **LGTM** | Awarded to the speedy reviewer who approved a Merge Request with hundreds of changed lines in record time, showing full trust in a teammate's delivery. |
| <img src="./badges/05-cirurgiao-de-conflitos.webp" width="72" /> | **Conflict Surgeon** | Awarded to the specialist who resolved a complex merge conflict with surgical precision, keeping everything working and the build green on the first try. |
| <img src="./badges/06-commit-poetico.webp" width="72" /> | **Poetic Commit** | Awarded to the author of an inspired commit history (*"tweaks"*, *"now it works"*, *"final fix"*, *"really final fix"*) until the pipeline finally passed. |
| <img src="./badges/07-primeiro-merge.webp" width="72" /> | **First Merge** | Awarded to the developer who got their very first Merge Request approved and merged into `main` cleanly with zero rollbacks needed. |
| <img src="./badges/08-domador-de-yaml.webp" width="72" /> | **YAML Tamer** | Awarded to the indentation master who survived the invisible spaces of `.gitlab-ci.yml` and got the pipeline running with zero syntax errors. |
| <img src="./badges/09-cacador-de-logs.webp" width="72" /> | **Log Hunter** | Awarded to the technical detective who tracked down the root cause of a bug directly in pipeline or app logs before an incident ticket was even opened. |
| <img src="./badges/10-oomkilled-survivor.webp" width="72" /> | **OOMKilled Survivor** | Awarded to the container explorer who discovered a pod or job's RAM limit the hard way and tuned the resource requests and limits successfully. |
| <img src="./badges/11-cache-limpo.webp" width="72" /> | **Clean Cache** | Awarded to the mystery solver who fixed a seemingly impossible bug simply by clearing stale pipeline, browser, or CDN cache. |
| <img src="./badges/12-guardiao-do-pipeline.webp" width="72" /> | **Pipeline Guardian** | Awarded to the CI/CD sentinel who quickly spotted a broken build, alerted the team, and delivered the fix to turn everything green again. |
| <img src="./badges/13-funciona-na-minha-maquina.webp" width="72" /> | **Works on My Machine** | Awarded to the developer whose code ran 100% flawlessly locally, sparking a deep dive into configuration differences across `localhost`, QA, and prod. |
| <img src="./badges/14-documentador-oficial.webp" width="72" /> | **Official Documenter** | Awarded to the team hero who saved future teammates by updating and organizing an outdated `README.md` right after conquering project setup. |
| <img src="./badges/15-pato-de-borracha.webp" width="72" /> | **Rubber Duck** | Awarded to the practitioner of classic *Rubber Duck Debugging*: explained a technical issue to a teammate and figured out the fix mid-sentence. |
| <img src="./badges/16-coruja-do-deploy.webp" width="72" /> | **Deploy Night Owl** | Awarded to the late-night guardian who watched over an after-hours release until the very last second, ensuring all services came up healthy. |
| <img src="./badges/17-mestre-do-rebase.webp" width="72" /> | **Rebase Master** | Awarded to the Git virtuoso who cleaned up commit history with an interactive `git rebase` without losing a single commit or re-cloning the repo. |
| <img src="./badges/18-faxineiro-de-codigo.webp" width="72" /> | **Code Janitor** | Awarded to the repository minimalist who opened a Merge Request purely to delete dead code, leaving the project lighter and easier to maintain. |
| <img src="./badges/19-bisturi-de-hotfix.webp" width="72" /> | **Hotfix Scalpel** | Awarded to the crisis responder who fixed a critical production bug with a surgical diff of just a few lines and zero side effects. |
| <img src="./badges/20-sem-console-log.webp" width="72" /> | **Zero console.log** | Awarded to the detail-oriented developer who scrubbed all temporary debug logs before opening a Merge Request, delivering spotless code for review. |
| <img src="./badges/21-salva-vidas-de-onboarding.webp" width="72" /> | **Onboarding Lifeguard** | Awarded to the supportive mentor who helped a new teammate set up their local environment and run the full project without a hitch. |
| <img src="./badges/22-workaholic.webp" width="72" /> | **Workaholic** | Awarded to the productivity machine who surpassed 100 contributions in a single day, painting their GitLab contribution graph deep dark green. |
| <img src="./badges/23-investigador-profissional.webp" width="72" /> | **Pro Investigator** | Awarded to the sharp-eyed QA specialist who caught a sneaky bug hidden in the most unlikely user flow long before it ever reached production. |
| <img src="./badges/24-stress-test-supremo.webp" width="72" /> | **Supreme Stress Test** | Awarded to whoever took load testing seriously enough to find the exact breaking point of a database in practice, yielding valuable scaling lessons. |
| <img src="./badges/25-select-sem-where.webp" width="72" /> | **SELECT Without WHERE** | Awarded to the data explorer who ran a heavier-than-expected query in a test environment and learned firsthand the true value of a good index. |
| <img src="./badges/26-guardiao-da-regressao.webp" width="72" /> | **Regression Guardian** | Awarded to the quality sentinel who caught and blocked an old bug trying to sneak back inside a new release before reaching production. |

---

## 🚀 How to Use on GitLab (Including Self-Managed Free)

### 1. Manual Setup via UI
1. Open your **Group** in GitLab (Achievements are configured at the group level).
2. Go to **Settings > General** and expand the **Achievements** section (or visit `https://your-gitlab.com/groups/YOUR-GROUP/-/achievements`).
3. Click **New achievement**, upload the badge image from `/badges`, enter the title, and paste the matching description.

### 2. Automated Awarding via GraphQL API
Even on the **Free Self-Managed** tier, you can automate awarding achievements using a **Personal Access Token** (with `api` scope from a group Maintainer/Owner) and the `achievementsAward` mutation:

```bash
curl --request POST \
  --header "PRIVATE-TOKEN: $GITLAB_TOKEN" \
  --header "Content-Type: application/json" \
  --data '{
    "query": "mutation { achievementsAward(input: { achievementId: \"gid://gitlab/Achievements::Achievement/1\", userId: \"gid://gitlab/User/42\" }) { userAchievement { id } errors } }"
  }' \
  "[https://your-gitlab.com/api/graphql](https://your-gitlab.com/api/graphql)"
```
## 🤝 Contributing

Have a classic engineering, QA, database, or infrastructure achievement idea? Feel free to open an Issue or submit a Pull Request!