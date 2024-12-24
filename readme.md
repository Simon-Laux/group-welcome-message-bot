# Welcome bot

Welcomes new group members with a predefined message.
To not spam users it only sends the message to the group once and uses resend message to send it again once new members join.

Set welcome message by creating `welcome.txt` with the text for the welcome message.

Run it with:
```
BOT_NAME="Welcome Bot" CHATMAIL_QR=dcaccount:https://nine.testrun.org/new deno task start
```

Note that `deno compile` doesn't work yet.