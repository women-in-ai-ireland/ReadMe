# Repository Creation/Maintenance Guideline

Please use the naming conventions and other guidelines below:

![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) **Repository Name:** Month-Year-WaiPRACTICE-ProjectName  

---

![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) **Repository Readme Template:**


# Repository Name
Short Project/Repository Description (Not more than 5 lines)

**Project Type** : Objectives/theme of the project - for example - Data Analysis, Machine Learning, Computer Vision, Natural Language Processing | Can containg multiple themes

**Blog Post** : \[blog name](blog link)

**Dataset Source** : \[Data Source Name](Data Source Link)

**Dataset Desc** : Short Data Source description

**Credits** : Credits if any, for example, especially for new/innovative python libraries, if their website calls for it.

---

# GitHub IO Page

The GitHub IO Page is created for you. Please visit the gh-pages branch of this repository to download the resources required. 

Steps:

1. Go to Settings
2. Scroll down to "GitHub Pages" section. Click on "Choose a theme" and in the next page click on "MINIMAL" theme, the fifth in the ribbon. Click on 'Select theme'
3. You will be redirected to an editable view of index.md. The index.md would contain you blog write-up.
4. Commit Changes and go back to your repository. Find a section on the right hand side column called "Environments" and click on it.
5. You'll be redirected to the 'Deployments' page. Click on 'View Deployment' to view your GitHub IO page.
6. Update your logo with the logo available in this repository's gh-pages branch, copy the config file and make appropritae changes.
7. Create a new folder \_layouts and copy the file default.html from this repository and add the following at line 41.

```<h2><a href="">Contributors</a></h2>
<p><strong>Contri Buter</strong> | <a href="https://www.linkedin.com/in/contributer/">LinkedIn</a>|<a href="https://github.com/contributer">GitHub</a></br><p>```
  
8. Commit and refresh. You'd see the Contributors section appear on the left hand column of the GitHub IO Page.


Feel free to experiment with your GitHub IO Page. Contact (Nabanita Roy)[https://www.linkedin.com/in/nabanita-roy/] (nabanita@womeninai.co) for any questions/troubleshooting GitHub IO Pages.
