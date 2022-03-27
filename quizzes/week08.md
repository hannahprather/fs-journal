# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The package. json file is the heart of any Node project. It records important metadata about a project which is required before publishing to NPM, and also defines functional attributes of a project that npm uses to install dependencies, run scripts, and identify the entry point to our package.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
the beginning. you need to launch npm i when you strt your project so your back end will work.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
nmp i
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
params
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can view logs with the Heroku CLI, the dashboard, your logging add-on, or in your log drain
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
clone it down fron git, make your changes and commit, set remote, pust heroku master to deploy your updates. 
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
allows teams to develop and deploy software. But to effectively manage projects with multiple developers and releases, you need a branching strategy. This organizes your branches and development resources, so you can finish things in a timely manner
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
after automated checks have completed successfully, but before the code merges to the repository's mainline branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merging
```