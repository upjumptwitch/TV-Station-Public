# TV-Station-Public
TV station application with Twitch.TV integration

<h4>To enable twitch connectivity follow the following steps before starting the program</h4>
<ol>
  <li>open up Twitch_auth.html in a web browser</li>
  <li>click the link</li>
  <li>copy the access token from the url after logging in to twitch and giving access<br>it will look something like this<br><code>https://id.twitch.tv/oauth2/authorize#access_token=<code>AccessTokenHere</code>&scope=chat%3Aread+chat%3Aedit&token_type=bearer</code><br>this is a password, do not share.</li>
  <li>open auth.txt<br>replace data with your nick name, user name, and room name<br>it will look something like this<br><code>upjump@upjump@upjump@AccessTokenHere@done</code></li>
</ol>
<h4>To disable twitch connectivity delete auth.txt before running the program</h4>
