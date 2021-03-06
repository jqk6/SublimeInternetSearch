# SublimeInternetSearch

A Sublime Text 3 plugin for easily search through the Internet.

[Google CSE API](https://developers.google.com/custom-search/docs/overview) provides 100 search queries per day for free, so by default it uses [DuckDuckGo](https://duckduckgo.com/) search engine and you [can change it](#installation-configuration) to the Google engine.

## Installation & configuration

Download [Package Control](https://sublime.wbond.net/installation) and use the Package Control: Install Package command from the command palette. Using Package Control ensures `Internet Search` will stay up to date automatically.

### Using Google CSE API 

If you want to use Google CSE as main search engine instead of DuckDuckGo you must register 
your own [developer key](https://developers.google.com/custom-search/v1/getting_started#auth) and specify it at configuration file (Packages/User/SublimeInternetSearch.sublime-settings):

```
{
    "google_cse": {
        "developer_key": "{yourAPIKey}", 
        // SublimeInternetSearch public Google Custom Search Engine identifier
        "engine_id": "003214559008085120238:jvdgt7ubdja"
    }
}
```

## Using It

I'm so lazy to describe how it works, so just see an example:

![Screenshot](screenshot.png?raw=true "Screenshot")

## License

This plugin is under the MIT license. See the complete license [here](LICENSE).
