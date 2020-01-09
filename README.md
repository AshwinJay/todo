# "Marker" tab with the ability to make a To-do list
A simple marker tab for people who keep many tabs and windows open in their browser but want to know where things are. It has a bonus feature of being able make quick to-do lists. Notes can also have links using the Markdown syntax.

# What is a marker tab?
If you have many tabs open but would like to place a dummy tab with a custom message to help you stay organized, then this is what you need! Of course there are fancy browser plugins but this is plain HTML + JavaScript + CSS and it does not need access to any of your open tabs.

![Sample](sample.png)

# Cobbled together from
 * [Max Sandelin's To-do](https://github.com/themaxsandelin/todo)
 * StackOverflow snippets

# Usage
Download (or clone) this repo and open `<somewhere-on-disk>/todo/index.html` in your browser. Customize the tab by providing a name like `<somewhere-on-disk>/todo/index.html?name=⚑ News`. If you make notes, it will stay in your local browser storage and survive restarts.

You can go one step further and create a custom search engine if your browser supports it. For example on Chrome you could [create a custom search engine](https://www.ghacks.net/2018/03/30/custom-search-engines-in-google-chrome/) to `index.html?name=⚑ %s` and add a keyword like `tab`. You can then open a new marker tab by just typing `tab Blah` in the adderess bar and it will magically open this page for you.

Add to-do list items. They can also be links if they are written like this `[Refer SO](http://stackoverflow.com/foo-bar)`. 

# License
[MIT](LICENSE.md)
