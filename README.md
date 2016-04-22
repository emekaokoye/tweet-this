# tweet-this

tweet-this allows you to define a set of words, terms or sentences to be tweeted in a container on a webpage. This is based on [InlineTweet.js](http://ireade.github.io/inlinetweetjs/). All credits goes to [Ire Aderinokun] (https://github.com/ireade). I only twerked (not tweek) a few codes.



## How to Use


#### 1 - Include Script

[Download the javascript file from here](https://github.com/emekaokoye/tweet-this/blob/master/src/tweet-this.js) and include it in your webpage. Place it at the bottom part of your webpage just before the closing `body` tag.

```html
<script src="path/to/tweet-this.js"></script>
```


#### 2 - Wrap Text

Wrap an action text for your tweet in a container element of your choice (`span` recommended) with the data attribute, `data-inline-tweet`


```html
<span data-inline-tweet>Share on twitter</span>
```


#### 3 - Options

You can add data attributes to customise the tweeted output -

- `data-inline-tweet-msg` — Add the tweetable text or tweet
- `data-inline-tweet-via` — Add a twitter username (without the @) to append to the tweet
- `data-inline-tweet-tags` - Add hashtags to the tweet (comma-separated, no spaces)
- `data-inline-tweet-url` — Tweet a URL different to the current page url

```html
<span data-inline-tweet       
	  data-inline-tweet-msg="Any ecommerce organization not embracing semantic search has itself to blame"   
	  data-inline-tweet-via="EmekaOkoye"   
	  data-inline-tweet-tags="SemanticWeb,SemanticSearch,LinkedData"    
	  data-inline-tweet-url="cymantiks.com">   
	Tweet this 
</span>
```
