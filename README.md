# ⚔️CodingKnights

[![Netlify Status](https://api.netlify.com/api/v1/badges/19c1e4cd-9522-4dd7-add0-b809e96a703c/deploy-status)](https://app.netlify.com/sites/codingknights/deploys)


### About the Theme

This is a Hugo site which uses the customized [hugo-paper](https://github.com/nanxiaobei/hugo-paper) theme. The customized files can be found under `themes/hugo-paper-ammended/`. 

From the `config.toml` file,

```
theme = ["hugo-paper-edited", "hugo-paper"]
```

There is a **theme inheritance** algorithm that looks at the array above and create a new theme with theme on the left being loaded first and being the most important and merging the themes on the right into it. Hence, I copied the files I wanted to amend into a new folder called `hugo-paper-amended` and made all the changes to the theme there. The rest of the theme is then loaded from `hugo-paper` theme.

## Important Commands

* Create a new post

        hugo new posts/what-are-ldap-directory-services.md

* Run the Hugo server

        hugo server
        hugo server -D                 // To build the drafts as well