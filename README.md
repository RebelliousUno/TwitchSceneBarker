Twitch Chat widget to bark on scene changes

Set up

Generate an OAUTH token https://twitchapps.com/tmi/ if you don't already have one

Update this OAUTH token completely into the props.js file
Update the props.js file with your username (all lowercase)
Update the props.js file with your channel (usually # followed by your username)
Update the props.js file with the thing you want to say at the scene transition.

Add barkerWidget in OBS this as a CLR browser source(not a global source)

When you change to this scene with this widget on the page will connect to the twitch IRC as your user and bark the appropriate phrase
