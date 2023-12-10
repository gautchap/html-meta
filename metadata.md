## Basic HTML Meta Tags

```html
<meta charset="UTF-8" />
<link rel="icon" href="favicon.ico" />
<meta name="keywords" content="your, tags" />
<meta name="description" content="150-230 caracs" />
<meta name="distribution" content="Global,Local,IU" />
<meta name="subject" content="your website's subject" />
<meta name="language" content="ES" />
<meta name="robots" content="index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1" />
<meta name="revisit-after" content="7 days" />
<meta name="theme-color" content="#319197, currentColor" media="(prefers-color-scheme: light)" />
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
<meta http-equiv="Content-Security-Policy" content="default-src https:" />
<meta name="copyright" content="company name" />
<meta name="revised" content="Sunday, July 18th, 2010, 5:15 pm" />
<meta name="abstract" content="" />
<meta name="topic" content="" />
<meta name="summary" content="" />
<meta name="author" content="name, email@hotmail.com" />
<meta name="designer" content="" />
<meta name="reply-to" content="email@hotmail.com" />
<meta name="owner" content="" />
<meta name="url" content="http://www.websiteaddrress.com" />
<meta name="identifier-URL" content="http://www.websiteaddress.com" />
<meta name="directory" content="submission" />
<meta name='pagename' content='jQuery Tools, Tutorials and Resources - O'Reilly Media'>
<meta name="category" content="" />
<meta name="coverage" content="Worldwide" />
<meta name="rating" content="General" />
<meta name="subtitle" content="This is my subtitle" />
<meta name="target" content="all" />
<meta name="HandheldFriendly" content="True" />
<meta name="MobileOptimized" content="320" />
<meta name="date" content="Sep. 27, 2010" />
<meta name="search_date" content="2010-09-27" />
<meta name="DC.title" content="Unstoppable Robot Ninja" />
<meta name="ResourceLoaderDynamicStyles" content="" />
<meta name="medium" content="blog" />
<meta name="syndication-source" content="http://example.com/2008/12/24/free-brand-monitoring-tools/" />
<meta name="original-source" content="http://example.com/2008/12/24/free-brand-monitoring-tools/" />
<meta name="verify-v1" content="dV1r/ZJJdDEI++fKJ6iDEl6o+TMNtSu0kv18ONeqM0I=" />
<meta name="y_key" content="1e39c508e0d87750" />
<meta name="pageKey" content="guest-home" />
<meta itemprop="name" content="jQTouch" />
```

## OpenGraph Meta Tags

```html
<meta property="og:title" content="The Rock" />
<meta property="og:type" content="movie" />
<meta property="og:url" content="http://example.com/tt0117500/" />
<meta property="og:image" content="http://example.com/rock.jpg" />
<meta property="og:site_name" content="IMDb" />
<meta property="og:description" content="A group of U.S. Marines, under command of..." />

<meta property="og:determiner" content="the" />
<meta property="og:locale" content="en_GB" />
<meta property="og:locale:alternate" content="fr_FR" />
<meta property="og:locale:alternate" content="es_ES" />

<meta property="fb:admins" content="987654321" />
<meta property="og:type" content="game.achievement" />

<meta property="og:video" content="http://example.com/awesome.swf" />
<meta property="og:video:height" content="640" />
<meta property="og:video:width" content="385" />
<meta property="og:video:type" content="application/x-shockwave-flash" />
<meta property="og:video" content="http://example.com/html5.mp4" />
<meta property="og:video:type" content="video/mp4" />
<meta property="og:video" content="http://example.com/fallback.vid" />
<meta property="og:video:type" content="text/html" />

<meta property="og:audio" content="http://example.com/amazing.mp3" />
<meta property="og:audio:title" content="Amazing Song" />
<meta property="og:audio:artist" content="Amazing Band" />
<meta property="og:audio:album" content="Amazing Album" />
<meta property="og:audio:type" content="application/mp3" />
```

## Create Custom Meta Tags

Use custom meta tags to store data that you need in Javascript, instead of hard-coding that data into your Javascript. I store my Google Analytics code in meta tags. Here's some examples:

```html
<meta name="googlebot" content="all" />
<meta name="googlebot-news" content="all" />
<meta name="google-analytics" content="1-AHFKALJ" />
<meta name="disqus" content="abcdefg" />
<meta name="uservoice" content="asdfasdf" />
<meta name="mixpanel" content="asdfasdf" />
```

## Twitter Meta Tags

```html
<meta name="twitter:card" content="summary, summary_large_image, app, player cards" />
<meta name="twitter:site" content="@nytimesbits || http://monsite.com" />
<meta name="twitter:site:id" content="id compte twitter" />
<meta name="twitter:creator" content="@arobase" />
<meta name="twitter:creator" content="id compte twitter" />
<meta name="twitter:description" content="200 caracs max" />
<meta name="twitter:title" content="70 caracs max" />
<meta name="twitter:image" content="URL, 5MB in size JPG, PNG, WEBP" />
<meta name="twitter:image:src" content="URL, 5MB in size JPG, PNG, WEBP" />
<meta name="twitter:image:alt" content="image desc 420 caracs max" />

<meta name="twitter:player" content="URL https iframe player" />
<meta name="twitter:player:width" content="width player" />
<meta name="twitter:player:width" content="height player" />
<meta name="twitter:player:stream" content="URL to raw video or audio stream" />
<meta name="twitter:app:name:iphone" content="Name of your iPhone app" />
<meta name="twitter:app:id:iphone" content="Your app ID in the iTunes App Store (Note: NOT your bundle ID)" />
<meta
    name="twitter:app:url:iphone"
    content="Your app’s custom URL scheme (you must include ”://” after your scheme name)"
/>
<meta name="twitter:app:name:ipad" content="Name of your iPad optimized app" />
<meta name="twitter:app:id:ipad" content="Your app ID in the iTunes App Store" />
<meta name="twitter:app:url:ipad" content="Your app’s custom URL scheme" />
<meta name="twitter:app:name:googleplay" content="Name of your Android app" />
<meta name="twitter:app:id:googleplay" content="Your app ID in the Google Play Store" />
<meta name="twitter:app:url:googleplay" content="Your app’s custom URL scheme" />
```

## Company/Service Meta Tags

#### ClaimID

```html
<meta name="microid" content="mailto+http:sha1:e6058ed7fca4a1921cq91d7f1f3b8736cd3cc1g7" />
<meta name="readability-verification" content="E7aEHvVQpWc8VHDqKvaB2Z58hek2EAv2HuLuegv7" />
<meta name="google-site-verification" content="4SMIedO1X4IkYrYuhEC2VuovdQM36Xxb0btUjElqQyg" />
<meta name="ICBM" content="40.746990, -73.980537" />
<meta name="generator" content="WordPress 3.3.1" />
<meta
    name="norton-safeweb-site-verification"
    content="tz8iotmk-pkhui406y41y5bfmfxdwmaa4a-yc0hm6r0fga7s6j0j27qmgqkmc7oovihzghbzhbdjk-uiyrz438nxsjdbj3fggwgl8oq2nf4ko8gi7j4z7t78kegbidl4"
/>
```

#### Apple Meta Tags

```html
<meta name="apple-mobile-web-app-title" content="My App" />
<!-- New in iOS6 -->
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-touch-fullscreen" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="black" />
<meta name="format-detection" content="telephone=no" />

<link href="/apple-touch-icon.png" rel="apple-touch-icon" type="image/png" />
<link href="touch-icon-ipad.png" rel="apple-touch-icon" sizes="72x72" />
<link href="touch-icon-iphone4.png" rel="apple-touch-icon" sizes="114x114" />
<link href="/startup.png" rel="apple-touch-startup-image" />

<link href="http://example.com/images/touch-icon-iphone4.png" sizes="114x114" rel="apple-touch-icon-precomposed" />
<link href="http://example.com/images/touch-icon-ipad.png" sizes="72x72" rel="apple-touch-icon-precomposed" />
<link href="http://example.com/images/apple-touch-icon-57x57.png" sizes="57x57" rel="apple-touch-icon-precomposed" />
```

#### Internet Explorer Meta Tags

```html
<meta name="mssmarttagspreventparsing" content="true" />
<meta name="msapplication-starturl" content="http://example.com/about/" />
<meta name="msapplication-window" content="width=800;height=600" />
<meta name="msapplication-navbutton-color" content="red" />
<meta name="application-name" content="Rey Bango Front-end Developer" />
<meta name='msapplication-tooltip' content='Launch Rey Bango's Blog'>
<meta name="msapplication-task" content="name=About;action-uri=/about/;icon-uri=/images/about.ico" />
<meta
    name="msapplication-task"
    content="name=The Big List;action-uri=/the-big-list-of-javascript-css-and-html-development-tools-libraries-projects-and-books/;icon-uri=/images/list_links.ico"
/>
<meta name="msapplication-task" content="name=jQuery Posts;action-uri=/category/jquery/;icon-uri=/images/jquery.ico" />
<meta
    name="msapplication-task"
    content="name=Start Developing;action-uri=/category/javascript/;icon-uri=/images/script.ico"
/>
<meta name="msvalidate.01" content="6E3AD52DC176461A3C81DD6E98003BC9" />
```

#### Google Meta Tags

```html
<meta name="news_keywords" content="World Cup, Brazil 2014, Spain vs Netherlands, soccer, football" />
```

#### TweetMeme Meta Tags

```html
<meta name="tweetmeme-title" content="Retweet Button Explained" />
```

#### Blog Catalog Meta Tags

```html
<meta name="blogcatalog" />
```

#### Rails Meta Tags

```html
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="/bZVwvomkAnwAI1Qd37lFeewvpOIiackk9121fFwWwc=" />
```

## HTML Link Tags

```html
<link rel="alternate" type="application/rss+xml" title="RSS" href="http://example.com/martini" />
<link rel="alternate" type="application/atom+xml" title="Atom 0.3" href="https://example.com/feed.atom" />
<link rel="shortcut icon" type="image/ico" href="/favicon.ico" />
<link rel="fluid-icon" type="image/png" href="/fluid-icon.png" />
<link rel="me" type="text/html" href="http://example.comprofiles/thenextweb" />
<link rel="shortlink" href="http://example.com/?p=353" />
<link rel="archives" title="May 2003" href="http://example.com/2003/05/" />
<link rel="index" title="DeWitt Clinton" href="http://example.com" />
<link rel="start" title="Pattern Recognition 1" href="http://example.com/photos/pattern_recognition_1_about/" />
<link rel="bookmark" title="Styleguide" href="http://example.com/about/styleguide/" />
<link rel="search" href="/search.xml" type="application/opensearchdescription+xml" title="Viatropos" />

<link rel="self" type="application/atom+xml" href="http://example.com/atomFeed.php?page=3" />
<link rel="first" href="http://example.com/atomFeed.php" />
<link rel="next" href="http://example.com/atomFeed.php?page=4" />
<link rel="previous" href="http://example.com/atomFeed.php?page=2" />
<link rel="last" href="http://example.com/atomFeed.php?page=147" />

<link rel="canonical" href="http://example.com/2010/06/9-things-to-do-before-entering-social-media.html" />
<link rel="preconnect" href="http://example.com/" />
<link rel="dns-prefetch" href="http://example.com/" />
<link rel="EditURI" type="application/rsd+xml" title="RSD" href="http://example.com/xmlrpc.php?rsd" />
<link rel="pingback" href="http://example.com/xmlrpc.php" />
<link
    rel="stylesheet"
    media="only screen and (max-device-width: 480px)"
    href="http://example.com/style/iphone.css"
    type="text/css"
/>
<link rel="wlwmanifest" href="http://www.example.com/wp-includes/wlwmanifest.xml" type="application/wlwmanifest+xml" />
```

<link rel='help' title='FAQ' href='/faq'>
<link rel='logo' type='image/svg' href='http://example.com/press/logo/foursquare-logo.svg'>
<link rel='P3Pv1' href='/w3c/p3p.xml'>
<link rel='publisher' href='http://example.com/115081025762845243709/'>
<link rel='image_src' href='http://example.com/7b29fe/images/icon-facebook.gif' type='image/jpeg'>

<link rel='author' href='humans.txt' type='text/plain'>
<link href='http://example.com/2009/01/08/how-to-snap-up-that-twitter-username-youve-always-wanted/' rel='original-source'>
<link rel='profile' title='example' href='http://example.com/profile/specs/'>
<link rel='profile' href='http://example.com/xfn/11'>
<link rel='chrome-webstore-item' href='https://chrome.google.com/webstore/detail/noojglkidnpfjbincgijbaiedldjfbhh'>
