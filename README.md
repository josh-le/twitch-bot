# twitch bot
wow this was a doozie, the twitch documentation for creating a twitch bot is not great, so this took quite a while
# usage
you need to create a twitch application, get the oauth token using the `authentication-node-sample`, get the USER ID of your twitch account, and the USER ID of the twitch account that you would like the bot to respond from(which can just be your own twitch account).

none of which are straight forward. i wrote a [blog post](https://josh-le.github.io/portfolio/blog/making-a-twitch-bot-blog) with a quick tutorial so you don't have to scavenge like i did.
# todo
- make it turn on when the stream start with EventSub
- figure out how to trim message length based on name of front app
- llm in chat?
