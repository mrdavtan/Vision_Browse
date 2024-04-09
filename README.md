# AI Vision Browser


## Notes

This is a fork from https://github.com/unconv/gpt4v-browsing

It allows you to browse the web from a chat session in the terminal by taking screenshots via GPT4Vision using the OpenAI API.

Updates:
-improved chat navigation/link selection.
-added a websocket chat feature to use with other projects.
-removed the python implementations
-works best w open browser/non-headless mode

## JavaScript version

The JavaScript version (`vision_browse.js`) is able to not only open a URL directly, but it can also click on links on pages.

```shell
$ npm install
$ node vision_browse.js
```

```shell
$ npm install
$ pip install -r requirements.txt
$ python3 vision_crawl.py
```

## Examples

![Screenshot from 2024-04-09 01-50-44](https://github.com/mrdavtan/Vision_Browse/assets/21132073/b5065028-ba02-4c60-8ea9-ad8d36a37c5f)

![Screenshot from 2024-04-09 01-51-02](https://github.com/mrdavtan/Vision_Browse/assets/21132073/6e0bab71-7243-4cc8-8eb9-f1f1bb008d15)
