

# Forking and Cloning Labs from Github

### Forking from Github

Forking is a feature of github that creates a copy of a repository on your account. When you solve a lab, you'll be coding the solution not on the deployed copy of the lab that everyone has access too, but rather, on your copy, your fork.

#### How to Fork

1. Click on the Fork Button

![Clicking on Fork](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/1-how-to-fork.png)

2. Fork it to your personal github account.

![Forking](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/2-how-to-fork.png)

3. Make sure you are on your fork of the lab.

![Your Fork](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/3-how-to-fork.png)

### Cloning from Github

Cloning means bringing down a copy of a git repository from a remote source (like Github). It is creating another copy of a repository on your computer and allowing your local copy to communicate and update the copy on github.

#### How to Clone

1. Copy your Clone URL, it should start with https://

![Your Fork Clone URL](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/1-how-to-clone.png)

2. From your terminal, from your home directory (you can `cd ~` to quickly jump there), type in: `git clone` and then paste the clone address you copied in step 1.

![git clone](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/2-how-to-clone.png)

3. Enter in your github credentials.

![github authentication](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/3-how-to-clone.png)

_Note: If you have 2-factor-authentication on github turned on this won't work. Turn it off from your [settings](https://github.com/settings/security)_

4. Your clone should now exist in a new directory named after the lab.

![All good](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/4-how-to-clone.png)

5. cd into the lab directory so you can get to work!

![All good](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/5-how-to-clone.png)


### Posting Your Work on Github

After you've completed a lab post your work onto github with the following steps.

1. Stage your changes for commit with

`git add .`

2. And confirm that the file is staged for commit with `git status`

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/3-solving-the-lab.png)

3. Commit the file.

`git commit -am "My first commit"`

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/5-solving-the-lab.png)

4. Push your work up to your fork on github.

`git push`

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/6-solving-the-lab.png)

5. Go to github and confirm the push.

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/7-solving-the-lab.png)

### Opening a Pull Request

1. Click on the branch comparison icon from the repository home.

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/1-opening-pull-request.png)

2. Click Create Pull Request

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/2-opening-pull-request.png)

3. Confirm the Create Pull Request

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/3-opening-the-pull-request.png)








<a href='https://learn.co/lessons/hs-github-fork-clone-public' data-visibility='hidden'>View this lesson on Learn.co</a>
