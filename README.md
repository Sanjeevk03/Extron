# Extron
Discord chatbot that can code chat generate images and text

# Prequisites
OpenAI and DiscordBot Token in these lines 
```
openai.api_key = "OPENAI_API_KEY" #type API key here
client.run("BOT_SECRET_TOKEN_HERE") #type bot token here
```

Then enjoy your discord bot!!!!

#features

 **!image:**

The !image command generates an image based on the given prompt

 **!chat:**

The !chat command generates a response based on a prompt. It will split up the generated response into parts that are sent to discord channel in order to increase engagement.

 **!code:**

!code command is the same as the chat command except it sends a response in a code block. This makes copying text and code easy as doing so with the !chat command will result in too many time stamps and structuring issues.

 **!creative:**

The !creative command is the same as the !chat command except it uses a temperature of 1 instead of 0.5.

 **!cc:**

The !cc command combines the functionality of the !creative and !code commands.

**!help**

The !help command lists all the commands in brief


# Faults

As you may know AI can sometimes make mistakes. Its just that you have given a very complex task or a task that cannot be done.
If its stuck at generating try to resend the command or changing the command a bit
