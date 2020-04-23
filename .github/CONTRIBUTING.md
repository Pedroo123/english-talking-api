
# Submitting an issue

- Please search for similar issues before opening a new one;
- Use a clear and descriptive title;
- Include as much information as possible by filling out the provided issue
  template;

## Creating an issue

1. On GitHub, navigate to the main page of the repository.

2. Under your repository name, click  Issues.  
  ![issue](https://help.github.com/assets/images/help/repository/repo-tabs-issues.png)
  
3. Click New issue.  

4. Type a title and description for your issue.  
  ![description](https://help.github.com/assets/images/help/issues/sample_issue.png)
  
5. When you're finished, click Submit new issue.

# Submitting a Pull Request 

- All pull requests should be to the develop branch.
- Every pull request should have associated issue(s) on our [issue tracker](https://github.com/barbosamaatheus/english-talking-api/issues).
  - choose an issue to solve or create your own;
  - don't forget to assign the issue to yourself as someone else can choose the same issue simultaneously.
- New functionality codes and bug fixes must be sent with their respective integration and/or unit tests
<img align="right" width="300" src="https://github.com/firstcontributions/first-contributions/raw/master/assets/fork.png" alt="fork this repository" />

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.  
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://github.com/firstcontributions/first-contributions/raw/master/assets/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://github.com/firstcontributions/first-contributions/raw/master/assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:
```
git clone https://github.com/this-is-you/english-talking-api.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd english-talking-api
```

Now create a branch using the `git checkout` command:

```
git checkout -b <add-your-new-branch-name>
```
The branch name must follow the following pattern `label/#Issue_ID
For example:
```
git checkout -b enhancement/#1
```
or
```
git checkout -b bug/#2
```

## Make necessary changes and commit those changes

Now open the project in a text editor and make necessary changes. Don't forget to save the changed files.

<img align="right" width="450" src="https://github.com/firstcontributions/first-contributions/raw/master/assets/git-status.png" alt="git status" />


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add .
```

Now commit those changes using the `git commit` command:
```
git commit -m "<type>(<context>): <subject>"
```
`<type>` Must be one of:
- **chore**: A change that neither fix a bug nor adds a feature;
- **ci**: A CI change;
- **docs**: A documentation change or fix;
- **feat**: A new feature;
- **fix**: A bug fix;
- **test**: A test-related change.

`<context>` is your _issue_id_.

`<subject>` is a message describing the change:
- Must be capitalized;
- Must be limited to 50 characters or less;
- Must omit any trailing punctuation.

Example of a commit message:

`feat(#1): Commit message style guide for Git`

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://github.com/firstcontributions/first-contributions/raw/master/assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://github.com/firstcontributions/first-contributions/raw/master/assets/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats!  You just completed the standard _fork -> clone -> edit -> PR_ workflow that you'll encounter often as a contributor!

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out [the list of projects in the web app](https://firstcontributions.github.io/#project-list).

:star: **Don't forget to donate a star, like, follow and contribute in any way.**