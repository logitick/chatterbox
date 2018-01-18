
```
...
 Chatter.on("channel_name", (request, channel) -> {
    request.get('wat');
    channel.all().except(request.getSender()).send("what");
    channel.
  });
...
```