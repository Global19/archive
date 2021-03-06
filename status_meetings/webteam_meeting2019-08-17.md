# 2019-08-17 NumPy Web Team Meeting

**Present:** Ralf, Inessa, Joe, Shekhar 


# Agenda

1. Outline major project milestones.
2. Decide on project management tool.
3. Define project organization.
4. Decide on website generator.
5. Discuss deployment strategies.
6. Explore further translation options. 



# Minutes
Introductions.


### Major project milestones

NumPy turns 25 next year - opportunity for some messaging around it?

1. Deploy new numpy.org (5-10 page, English only)
2. Change Sphinx theme in line with numpy.org Hugo theme
3. Add translations (one language first - Chinese (Zieje))
4. Add more content / showcases

### Project management tool
GitHub Projects
github.com/numpy/numpy.org/projects/1


### Project organization

Graphic designer: color scheme hex values + logo touch up
(Ralf)

Rendering PRs on Surge (or similar) (Shekhar)

Content for the first version: About Us, Donate, etc. - put .md files on HackMD for now (Ralf/Inessa)

Get first site up (Joe)

Crowdin-Hugo (Shekhar)

Notes: 
- all images preferably in .svg
- fonts to consider: fonts.google.com/specimen/Ubuntu

### Website generator
**Hugo** is selected.
Themes to consider:
themes.gohugo.io/theme/hugo-fresh/
themes.gohugo.io//theme/agency (no longer maintained)



### Deployment strategies

First instance, keep deploying to GitHub Pages, with CloudFlare in front (already set up). Then evaluate bandwidth needs.

GitHub Actions has CI/CD in beta. It would be a good option for our project, no need for extra permissions and API tokens.


### Translations

Crowdin - let's try it once we have a small site up. Should be doable with GitHub.


## Notes 
<!-- Other important details discussed during the meeting can be entered here. -->
