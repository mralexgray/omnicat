# Omnicat

Ever find you have to look at a repository on GitHub you know the name of but not the owner? You go to [github.com](https://github.com) or you may already have a search keyword for GitHub in your browser, you enter the name of the repository, wait a few seconds and then try to identify the repository you're looking for in the search results.

This can be easier and quicker. Install this chrome extension and start typing `gh<tab>` in Omnibox (the location bar). Anything you type after this will be autocompleted to GitHub repositories by owner and/or name. The repositories are ordered by the number of watchers and you can even see their descriptions right on the spot. Choose the one you're looking for and you'll be on the page of the repository in no time.

Much quicker and easier, isn't it? Now go and contribute to open source!

# Development

The extension is written in JavaScript for Google Chrome. You won't need
anything except for the browser for development.

Support codes are written in CoffeeScript with Node.js. You will need to
install [coffee-script](https://github.com/jashkenas/coffee-script) and
[jake](https://github.com/mde/node-jake) globally:

```
npm install -g coffee-script jake
```

Every other dependencies are already included under `node_modules/`.

Oh, an you'll also need [CouchDB](http://couchdb.apache.org/) if you want
to poke around the views and repo documents.

# Note on Patches/Pull Requests

* Fork the project.
* Make your feature addition or bug fix.
* Test it thoroughly. (I haven't found a way to write tests for the
  extension yet.)
* Commit.
* Send me a pull request. Bonus points for topic branches.

# License

Copyright © 2011 László Bácsi. See LICENSE for details.