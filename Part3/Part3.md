# Part 3

## Imagine you are working at a game studio, and they want you to help with installing Git.

### Write instructions on installing git on a windows system. Making sure to include

1. Go to this link (https://git-scm.com/download/win)
2. Click on "64-bit Git for Windows Setup" to download the latest version of the 64-bit windows installer
3. Open the installer
4. Follow installer instructions
5. Once installer is complete, click finish

Remember that the current version of git requires Windows 7 or later. The last version to support Windows Vista was v2.37.1, and the last to support Windows XP was v2.

If you have further problems installing git enquire for support at your companies IT desk.

### Do research on some principles/techniques of industry standard best practices creating and working with repositories and branches in Git. 

#### List the most important principles/techniques for creating and working with repositories
* Create a README file for everey repo
* Forking is for open-source projects, branching is for regular/internal collaborators
* Ensure commits have meaningful names and descriptions
* Never reset a public commit
* Dont clump unrelated code into a single commit

#### List the most important principles/techniques for creating and working with branches
* Never work directly off of main branch
* Only merge to main off of a staging branch
* Favour branching over forking when possible
* Ensure each developer and/or feature has its own branch

### List the steps in a Git workflow that the team should follow when working on projects.
<ol>
	<li> Create a staging branch off of main</li>
	<li> Create other branches for each individual feature</li>
	<li> Only work directly into the branch assigned to your particular feature</li>
	<li> Commit changes at regular intervals and/or when a major section or task is completed</li>
	<li> When ready, merge your branch into the staging branch</li>
	<li> Use the staging branch to ensure there are no conflicts or compatibility problems between merging branches</li>
	<li> Once Changes have been verified in the staging branch, merge staging into main</li>
	<li> Repeat from line 2.</li>
</ol>
<li> NOTE: Main branch is only for content that is complete and ready for release. DO NOT merge to main from any branch other than staging.

## Link to Part 2
[Part 2](../Part2/Part2.md)