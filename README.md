# [Duke Cosmology Group website](https://cosmology.phy.duke.edu/)

This is the source of the collaboratively maintained website of the Duke Cosmology group.

## Editing the website

Anyone part of the [DukeCosmology GitHub organization](https://github.com/DukeCosmolog) may edit the website.
If you are not part of the organization, ask an owner (any of the faculty members) to invite you to the organization first.

### Familiarizing with Git workflows
All edits must be done via pull requests (PRs) to the `main` branch of this repository.
Edits may be made directly on GitHub or from a local editor.
If editing locally, follow the steps below:

```
git clone https://github.com/DukeCosmology/duke-cosmology-group.git
cd duke-cosmology-website
git checkout -b <your-branch-name>
# make your edits as needed (see instructions in the next section)
git add .
git commit -m "Add <your name> to the website"
git push -u origin <your-branch-name>
```

Then, create a PR from your branch to the `main` branch of this repository.

If editing on GitHub, click on the pencil icon on the top right of the file you want to edit.
Make your edits and then click on "Commit changes" at the upper right of the page.
Then, add a more useful commit message and click on "Propose changes".

Once the PR is created, it checks if the website builds successfully with your changes.
Once all the checks have passed, you may click the "Merge pull request" button to merge your changes into the `main` branch.
You may also request a review from any of the owners (any of the faculty members) before merging (recommended for first time contributors).

If you are new to Git, we recommend you to read the [GitHub guide](https://guides.github.com/activities/hello-world/) and the [GitHub flow](https://guides.github.com/introduction/flow/).


### Adding yourself to the website
1. Create a folder under `content/authors/` with your name as the folder name.
2. Under your folder, add your display picture (optionally) as `avatar.jpg`.
3. Copy the `_index.md` file from any `content/authors/arun`folder and edit it to add your details.
Because this is a group website, add your narrative in third person i.e., addressing yourself with your pronouns instead of "I" or "me".
4. **Most important**: The `user_groups` section must include one (and exactly one) of the following groups: `Faculty`, `Researchers`, `Graduate Students`, `Undergraduates`, `Visitors`, `Alumni` to appear on the website.
