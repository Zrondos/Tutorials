# How to connect XCode with Github

## Let's connect XCode to our Github.
1. Launch XCode. Click XCode in the top left corner, > Preferences.
2. Click Accounts, then the "plus sign" in the bottom left corner.
3. Select Github. Enter your credentials. 
Great! You're connected!

## Let's create our project that we will push to Github.

1. Launch XCode. Click File > New > Project. 
2. For this example, we will use a Single View App. Make sure it is selected, then click Next.
3. Give your project a name. Let's use HelloWorld. Fill in Organization Name and Organization Identifier. I just used my own name for both.
4. Make sure language is set to Swift and User Interface is set to Storyboard. Click Next.
5. Find the location you want to save your project. Click New Folder, title the folder with your project name, click on the folder.
6. Makre sure the to check the box marked "Create Git Repository on my Mac.
7. Click the "Create" button.

### You've now created a project!

8. Open up any file, and add a comment. Save the file.
9. We can make a commit now. Click Source Control, on the top tool bar. Click commit.
10. On the left hand panel, you should see the file you modified, with an M next to it. Click on that file. You can see the new version of the file on the left, and the old version on the right. 
11. Also note, right below the open file, you will see the current branch you are working on. This should say master.
12. Type your commit comment, in the white box. For example, "Added comment that says..." Click Commit 1 file.
13. Let's check our commit. On the left hand panel, click the "source control" botton. This is the circle with arrow pointing out, to the right of the folder button.
14. Click branches, then master. You can see two commits. The initial commit when the repository was created, and the commit with the added comment.

### Getting your project onto Github
15. Create a new GitHub repository online. Name it anything you would like. 
**DO NOT INITIALIZE THE README.MD FILE. XCODE WILL NOT LET YOU PUSH!**
16. On the next page, copy the Git URL. If you do not see this, click on the "Code" Tab, then the "Clone or Download" button. Copy that link.
17. On XCode, click the "Source Control" button on the left hand pannel.
18. Right click on the "Remote" folder, then click "Add an Existing Remote"
19. Copy and paste the link from Github into the "Location" field.

### Let's push our local repository to Github.
20. Click "Source Control" on the top Tool Bar. Click "Push". On the pop-up, note that the drop down has the location of your remote branch. Click "Push".
21. Refresh the page on Github and *VOILÀ*. You're project is now on Github.

Happy Coding!
