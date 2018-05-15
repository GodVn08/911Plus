# 911Plus
A plugin that allows /911 and /panic be posted in a Discord channel via a webhook.

PLEASE NOTE: TTS is enabled by default, so an automated voice will read out message to anyone focused on the discord channel these messages will be getting posted on

# Setup
1. Set up your webhook by going to your Discord server, and going into "Server Settings"
2. On the left panel, select "Webhooks" then "Create Webhook"
3. Name it and give it a picture you see fit, then select a channel the 911 calls and panic button information will be posted to (Highly suggested you make a channel specifically for dispatchers to see it in)
4. Now copy the "Webhook URL", and paste it into it's proper place in server.lua
5. Now place the 911plus resource in your resources folder and be sure to start the resource in your server.cfg!

# Usage
For civilians:
Do "/911 [information about a call here]" and dispatch will be alerted!

For officers:
Do "/panic [current location]" and dispatch will be alerted!
