# rebort

rebort is a chat bot built on the [Hubot][hubot] framework. 

This README is intended to help get you started. Definitely update and improve
to talk about your own instance, how to use and deploy, what functionality is
available, etc!

## Supported commands

[Qq]{1}ueue calls did (.*) receive (.*)
How many queue calls did Michael call queue receive last month

Qq]{1}ueue calls that (.*) missed (.*)$/
How many queue calls that Michael call queue missed last month

[Qq]{1}ueue calls that (.*) answered (.*)$/
How many queue calls that Michael call queue answered last month

[Ll]{1}ist queues (.*)$
List queues last month

[Oo]{1}verview for (.*)$/
Show me queue overview for last month

[Ll]{1}ength range for (.*)$
Show me length range for last month

How many times did (.*) call (.*) at (.*)$/
How many times did Allen Test call 13345214412 at last month


# Start Hubot

HUBOT_GLIP_APP_KEY={appkey} HUBOT_GLIP_APP_SECRET={secret} HUBOT_GLIP_USERNAME={username} HUBOT_GLIP_PASSWORD={psd} HUBOT_GLIP_SERVER={glip server} ./bin/hubot -a glip -n Rebot
