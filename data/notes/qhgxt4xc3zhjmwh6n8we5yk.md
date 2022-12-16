While this site doesn't have a built in editor like Media Wiki style sites such as fandom, it doesn't mean you can't edit the pages!

# Editing Existing Pages
At the bottom of every page you should see a link that says *Edit page on Github* Clicking on this will open the Github code editor allowing you to edit pages with ease!

Seen below is how a page might appear.
![](/assets/images/2022-12-09-09-55-11.png)

At the very top you can see the Front Matter. **DO NOT EDIT THIS!** You can start editing immediately below it! There is an exception, the `title:` field may be edited to modify how a title is displayed on the page.

After you finish editing, Scroll down to commit your changes. making sure to select "Create a **new branch** for this commit to start a pull request."

Make sure to give your changes a title, and a short description of what you changed.
![](/assets/images/2022-12-09-09-58-34.png)

# Creating New Pages.
To create a new page, its not as simple as pressing "New Page" unfortunately.

First open the [Github Repository](https://github.com/LividJava/fourleafwiki), and navigate to the **Notes** folder.
![](/assets/images/2022-12-09-10-01-25.png)

Then from here select **Create New File**
![](/assets/images/2022-12-09-10-02-28.png)

And to categorize the notes. Dendron uses a delimited naming convention, where each successive period indicates a deeper hierarchy.

For Example. If we wanted to create a page for Lupe under the Characters category. we would name it the following:

`characters.guadalupejara`

Don't worry about Adding front matter like shown in the previous section! It will be added after someone with Dendron installed syncs their local repository with the Github repository.