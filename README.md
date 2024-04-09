# Vision Browser

![converted_image](https://github.com/mrdavtan/Vision_Browse/assets/21132073/f4049048-7c77-4ee5-8a82-50aed8886749)

## Notes

This is a fork from https://github.com/unconv/gpt4v-browsing Props to unconventional-coding for this cool project!

It allows you to browse the web from a chat session in the terminal by taking screenshots via GPT4Vision using the OpenAI API.

I wanted to use this as an additional search tool to be used by another llm with websockets.

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
