# Ohio 5 GitHub / Git Tutorial

Pre:
	* What it is - distributed version control system, social code sharing, project management platform.
	* How it works - MAGIC. But actually it tracks line-by-line changes to sets of files as well as who made them, when they were made, and other relevant metadata.
	* Why you might want to do it - professional portfolio, hosting, open source community

1. Sign up for a GitHub account:

	* Visit github.org and sign up for your own account.
	* Avoid capital letters, numbers, punctuation if possible. You might still be able to use them, but why play with fate like that?
	* Pick a name that is good for a professional audience
	* It's hard (but impossible) to change your name, so put some thought into it.

2. Set up team pages.
	* Break into teams
	* Make a GitHub Organization with a name that reflects your team. You can change it later if you want, but you'll need to change your repository name as well.
	* One person will need to make the GitHub organization, and this person will then have to add the other team members as contributors.
	* Make it something professional - your domain name will draw upon this.

3. Make a project repository
	* Click the new repository button.
	* The name your repository will be different dependent on your organization name: username + github.io.
	Ie. for an organization called awesomeohio your repository would be awesomeohio.github.io. 
	* Check the box to initialize your project with a readme.
	* Make your repository public.
	Repositories consist of all the files and folders pertaining to a particular project, but they also contain all of the information that the project's team needs to work together. So a Git repository stores all changes made by anyone ever, allows 

3. GitHub Issues page.
	Useful for tracking a project's history and managing its future.
	* Make an issue
	* Assign that issue to a team member.
	* Make the text of it "Make an index.html page."

4. Make an index.html page
	* One member should add a file called "index.html"
	* You should add the html skeleton here to the file - http://htmlshell.com/ 
	* Give a commit message at the bottom that says "closes #1".
	* Notice how your issue is closed - commit messages are linked to the issue tracker.

5. GitHub pages
	* Visit yourorganization.github.io in the browser
	* You should have a little thing there based on the HTML skeleton
	* Explain how GitHub pages works

6. Adding code
	* Can continue to do this in the browser, but it's a little irritating.
	* After all, how do you know no one else is editing your code at the same time?

7. Working from the command line. (might be saved for later)
	* First copy/clone
	* Now you have your own version.
	* Workflow:
		* git pull
		* git add . or git add filename
		* git commit -m 'a message describing what i did'
		* git push
	* With this workflow you all have the materials working on your own computer at all times.