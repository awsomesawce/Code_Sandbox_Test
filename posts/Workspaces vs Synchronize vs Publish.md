# StackEdit's Many Options for Publishing MD docs

With [StackEdit](https://stackedit.io), one can publish their notes/posts/writings in many different ways.  
The first way is to initiate a *workspace*.  

## Workspaces
This option is good if you want to work with a specific destination of your files, for example publishing to a Jekyll blog hosted on a GitHub repository, or even to a specific folder in a repository.
StackEdit doesn't require you to add a workspace.  By default, it stores your notes in browser storage, so it's all local unless you set up a workspace.
You can set up a workspace 5 different ways:
* **GoogleDrive** - *by default will store in your appdata folder*
* **CouchDB**
* **GitHub** - links your workspace to a repository/branch/folder of your choice
* **GitLab** - much of the same

Any number of workspaces can be created.  For example you can have multiple GoogleDrive workspaces.  The first one will by default just lead to your invisible **AppData** folder, but you can create a GoogleDrive workspace to sync with a specific folder if you want.
I currently have **4** workspaces.  Why so many?  Mostly because I'm testing out it's functionality.  My main one is attached to GoogleDrive, and the next 3 are attached to a GitHub repo.
## My goal
You see, my goal was to link my StackEdit to a GitHub repository and have StackEdit push and pull my posts to a Jekyll blog, and that way I could create new posts using StackEdit's cool interface to compose!
It turns out there are many ways I could have done so.
Right now I have a workspace that's linked to my `/posts` folder on the `gh-pages` branch in my primary GitHub repo, so no matter where I create/upload my posts they will always be synced with that StackEdit workspace.
## Other sync options
Now let me explain the other syncronization options in StackEdit.
In addition to **workspaces**, you can synchronize *individual* writings/posts/notes in the cloud using many different services.  They are:
* **Dropbox**
* **GitHub**
* **A GitHub Gist**
*  **Google Drive**

>When you *synchronize* a file, you can do so from any workspace.  *Files from one workspace won't be accessible from another workspace unless you navigate to that workspace*.  
The point is, I could have just used the *synchronize* option instead.  I didn't have to create an entire new **workspace** in order to work with my GitHub files.  The downside to this is if files are added using another method, they won't be synced to your StackEdit unless you use the *workspace* option.

## The Publish option
**StackEdit** also has a *publish* option.  This acts like an *export* to the web, as opposed to synchronization.  This means if you change the post using a different method, those changes won't be reflected back to StackEdit's interface.  This option has a wider list of destinations your file can be published to.  Be aware that I'm still experimenting with this feature.
* Publish to **Blogger**
* Publish to **Blogger Page**
* Publish to **Dropbox**
* Publish to **Gist**
* Publish to **GitHub**
* Publish to **Google Drive**
* Publish to **GitLab**
* Wordpress
* Zendesk

Just like the other options, you can add as many accounts from those services as you'd like.
I find this feature to be useful if you want to use StackEdit to compose a Blogger or Wordpress blog post.  But if you're collaborating with other people, I'd stick to Synchronize unless you're sure you won't have to edit it again.

### Keeping track of sync destinations
If you choose to sync or publish your writing to multiple destinations, **StackEdit** makes it really easy for you to keep track of those destinations.  







> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJkaXNjdXNzaW9ucyI6eyJzWk4xbVprcThxa1BYaklWIjp7In
N0YXJ0IjoxNDg3LCJlbmQiOjE1NDEsInRleHQiOiJJdCB0dXJu
cyBvdXQgdGhlcmUgYXJlIG1hbnkgd2F5cyBJIGNvdWxkIGhhdm
UgZG9uZSBzby4ifX0sImNvbW1lbnRzIjp7IklHNUdOYU5UYUpH
WGhIcjYiOnsiZGlzY3Vzc2lvbklkIjoic1pOMW1aa3E4cWtQWG
pJViIsInN1YiI6ImdoOjY5NjczNjQwIiwidGV4dCI6ImNvdWxk
IGJlIGRlbGV0ZWQiLCJjcmVhdGVkIjoxNTk5MjU4NDU5OTY0fX
0sImhpc3RvcnkiOls1ODAzNDczNDddfQ==
-->