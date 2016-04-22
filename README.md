# tweet-this

![tweet-this allows you to easily create tweetable links out of any text on a webpage. This is based on [InlineTweet.js](http://ireade.github.io/inlinetweetjs/). All credits goes to [Ire Aderinokun] (https://github.com/ireade). I only twerked (not tweek) a few codes.]



## How to Use


#### 1 - Include Script

[Download the file from here](https://raw.githubusercontent.com/ireade/inlinetweetjs/gh-pages/src/inline-tweet.min.js) and include it in your webpage.

```html
<script src="path/to/inline-tweet.min.js"></script>
```


#### 2 - Wrap Text

Wrap the tweetable text in a container element of your choice (`span` recommended) with the data attribute, `data-inline-tweet`


```html
<span data-inline-tweet>Lorem Khaled Ipsum is a major key to success</span>
```


#### 3 - Additional Options

You can add more data attributes to cutomise the tweeted output -

- `data-inline-tweet-via` — Add a twitter username (without the @) to append to the tweet
- `data-inline-tweet-tags` - Add hashtags to the tweet (comma-separated, no spaces)
- `data-inline-tweet-url` — Tweet a URL different to the current page url

```html
<span data-inline-tweet       
	  data-inline-tweet-via="ireaderinokun"   
	  data-inline-tweet-tags="webdesign,webdev,js,yolo"    
	  data-inline-tweet-url="bitsofco.de">   
	Lorem Khaled Ipsum is a major key to success 
</span>
```
