# Vision Browser

![converted_image_variation](https://github.com/mrdavtan/Vision_Browse/assets/21132073/4b4eba70-3d26-47a9-aa85-07a6a9b34329)

## Notes

This is a tool which allows you to navigate the web from a chat window, by taking screenshots and sending them to GPT4Vision using the OpenAI API.

The idea was to use this as an additional search tool when webscraping isn't successful. I added a websocket client to connect it to another LLM/bot.

This is a fork from https://github.com/unconv/gpt4v-browsing Props to unconventional-coding for this cool project!

What I've added:
   -improved chat navigation/link selection.\
   -added a websocket chat feature to use with other projects.\
   -removed the python implementations.\
   -works best w open browser/non-headless mode.\
   -chat history saved in chatlog, to be used for context later

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

![Screenshot from 2024-04-09 02-47-50](https://github.com/mrdavtan/Vision_Browse/assets/21132073/1be781cb-3daf-4c79-970c-f327b43cdc27)

![Screenshot from 2024-04-09 01-51-02](https://github.com/mrdavtan/Vision_Browse/assets/21132073/6e0bab71-7243-4cc8-8eb9-f1f1bb008d15)
