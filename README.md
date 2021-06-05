# Ghost Mirror Multi Job Workflow
Join [@ghost_mirror](https://t.me/ghost_mirror)

You can use [this repos](https://github.com/ghostmirrorlab/mirror-bot-repos) as a template
First setup everything then push to your main private Repository

## Prerequisite
Fork this Repo,
Setup secrets in settings --> Secrets

```text
GH_TOKEN :- Your github personal access token, from https://github.com/settings/tokens
MIRROR_REPOSLUG_1 :- Your 1st Secret Repository, as in "<username>/<reponame>"
MIRROR_REPOSLUG_2 :- Your 2nd Secret Repository, as in "<username>/<reponame>"
```
After that done, it should look like this
![image](https://user-images.githubusercontent.com/77688759/120899676-88cfca80-c64e-11eb-9aef-b76c94f21227.png)

Then edit .github/workflows/mirror-bot.yml

Change `GitHubMail`, `GitHubName`, `Repo-1-Branch` and `Repo-2-Branch` environment variable as your own

![image](https://user-images.githubusercontent.com/77688759/120899828-40fd7300-c64f-11eb-9e53-f5b167f60eca.png)


And That's it.

[©ElytrA8](https://github.com/ElytrA8)
