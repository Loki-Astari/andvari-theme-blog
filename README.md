# andvari-theme-landscape

A very simple Blog theme for Andvari.


## Configuration

In the config.json file you will find the following options.

      {
          "author":       "The Copy Right Owner",
          "title":        "Name Your Site",
          "description":  "Simple Description",
          "menu":         null,
          "sidebar": ["posts", "twitter", "github"],
          "twitter": {
              "user": "Your Twitter User"
          },
          "github": {
              "user": "Your Github User",
              "count": 5
          },
          "commentSite": "disque",
          "disque": {
              "site":     "RegisterYourSite",
              "count":    false
          }
      }

You should probably override these in your blog's config.json file.

        * author:      Put in the copyright message at the bottom of each page.
        * title:       Title of the site displayed in the banner.
        * description: Displayed in the banner just under the title.
        * menu:        An array of items to be displayed in the banner.
        *              Each item has the form {"name": "A name to display", "url": "The page it will go to when pushed"}
        *              If the name is also the name of the directory where the file is placed it will be highlited.
        * sidebar:     An array of know sidebars.
        *              Currently Andvari has no sidebar's but this may change in the future.
        *              This theme supports 3.  posts/twitter/github
        * twitter/github your user information on these sites used by the sidebar.
        * commentSite: The comment site used by blog (set to null if you don't want one).
        *              disque is a comment site you can sign up for an account there.
        * disque:      your user information for the site (so the browser can grab the comments).
