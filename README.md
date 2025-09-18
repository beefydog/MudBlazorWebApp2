This is a stock example of a bug in .Net9 rendering when going from a server side rendered page to a client side rendered page (OR this is a bug in MudBlazor - not sure).
A brief flash of an ugly white page (which could be overridden in css) when moving from either the Login or the Register page to the Weather, Counter or Home pages.
To test, run the application and click the login button. Now click the Weather, Counter or Home button from the NavMenu: You will see a brief flash of white and an exploding icon!
I've tried for many hours to mitigate this (and have never seen it before), but with no luck (Claude, ChatGPT, DeepSeek AIs are of no help - their solutions do nothing to mitigate the problem).
