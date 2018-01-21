This app utilizes WebGL globe and the Twitter API to plot and live stream tweets regarding the US 2016 presidential election. This divisive election has resulted in many vulgar tweets that target the four candidates (Trump, Clinton, Stein, Johnson). This app utilizes  tweets with geodata that meet certain tracking criteria that include terms from both of the following lists:

1) trump,clinton,stein,johnson

2) shit,fuck,damn,bitch,crap,piss,dick,darn,cock,pussy,asshole,fag,bastard,slut,douche



This filtering results in tweets being displayed that feature crude language towards the candidates, exposing the political polarization and hostility this election has caused.

References
- [Twitter API statuses/filter stream](https://dev.twitter.com/streaming/reference/post/statuses/filter)
- [Twitter REST API Rate Limiting](https://dev.twitter.com/rest/public/rate-limiting)
- [AngularJS](https://angularjs.org/)
- [PubNub AngularJS SDK](https://github.com/pubnub/pubnub-angular)
- [Three.js](http://threejs.org/)
- 15 most popular Facebook swear words (http://www.slate.com/blogs/lexicon_valley/2013/09/11/top_swear_words_most_popular_curse_words_on_facebook.html)
- WebGL globe of live tweets https://github.com/twitterdev/twitter-stream-globe

package.json was deleted because of security vulnerabilities
