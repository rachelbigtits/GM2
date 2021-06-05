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

Change `GitHubMail` and `GitHubName` environment variable as your own.

```text
GitHubMail :- Your github email address
GitHubName :- Your github username
```

![image](https://user-images.githubusercontent.com/77688759/120901023-e4ea1d00-c655-11eb-8fa9-ccb7429b64df.png)


## Tip:-
If workflow stopped working or if you want to re-run the workflow, first make sure that workflow is stopped. You can stop the workflow in "actions" tab.
Now to start the workflow, goto looper.txt and remove the last letter/digit i.e if its 12345 then remove the last letter/digit to make it 1234 and commit the file.

And That's it.

Thanks to [©ElytrA8](https://github.com/ElytrA8) for the base of the workflow.
