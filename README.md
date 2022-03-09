# Template
```html

<head>
  <meta charset="utf-8">

  <!-- BASIC SEO SUPPORT -->
  <!-- Mobile Support -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <!-- Author of HTML document -->
  <meta name="author" content="the author of this document">
  <!-- description within 80 characeters -->
  <meta name="description" content="description with main keywrod">
  <!-- keywords, subkeywords, detailed keywords within 160 characters. Separated by `,` without empty space between keywords -->
  <meta name="keywords" content="keyword1,keyword2,keyword3"/>
  <!-- Title of your page. Include main keyword. Recommended length: 70 characters -->
  <title>Title of your page that contains main keyword</title>

  <!-- SOCIAL MEDIA SUPPORT -->
  <!-- title you want it to appear when people are sharing your link on social media -->
  <meta property="og:title" content="What you want it to appear">
  <!-- description you want it to appear when people are sharing your link on social media -->
  <meta property="og:description" content="What you want it to appear">
  <!-- type of content you are providing -->
  <meta property="og:type" content="website">
  <!-- image you want it to appear when people are sharing your link on social media -->
  <meta property="og:image" content="http://www.mysite.com/myimage.jpg">
  <!-- website url -->
  <meta property="og:url" content="http://www.mysite.com">
  <!-- the name of website you want to put. -->
  <meta property="og:site_name" content="Hot Programmer's residence">

  <!-- IF YOU HAVE MOBILE APPLICATION-->
  <meta property="al:ios:url" content="applinks://docs">
  <meta property="al:ios:app_store_id" content="12345">
  <meta property="al:ios:app_name" content="App Name">
  <meta property="al:android:url" content="applinks://docs">
  <meta property="al:android:app_name" content="App Name">
  <meta property="al:android:package" content="org.applinks">
  <meta property="al:web:url" content="https://apppower.com">

  <!-- IF YOU HAVE MULTIPLE PAGES -->
  <link rel="canoncial" href="https://www.mysite.com">
</head>
```
## **Expert Tips**

- Do not make images that can be written as text on the site => The site needs a lot of text so that the search robot can understand the characteristics of the site.
- Don't move links with JavaScript. location.href is not used.
- Avoid making multiple sites by copying a site.
- Make sure the title and description of each page are different.
- Create a site optimized for mobile.
- When there is a separate site such as m.sample.com optimized for mobile, be sure to add canonical.

## **Why does canonicalization matter?**

[Duplicate content](https://moz.com/learn/seo/duplicate-content) is a complicated subject, but when search engines crawl many URLs with identical (or very similar) content, it can cause a number of SEO problems. First, if search crawlers have to wade through too much duplicate content, they may miss some of your unique content. Second, large-scale duplication may dilute your ranking ability. Finally, even if your content does rank, search engines may pick the wrong URL as the "original." Using canonicalization helps you control your duplicate content.

## **The problem with URLs**

You might be thinking "Why would anyone duplicate a page?" and wrongly assume that canonicalization isn’t something you have to worry about. The problem is that we, as humans, tend to think of a page as a concept, such as your homepage. For search engines, though, every unique URL is a separate page. For example, search crawlers might be able to reach your homepage in all of the following ways:

- [http://www.example.com](http://www.example.com/)
- [https://www.example.com](https://www.example.com/)
- [http://example.com](http://example.com/)
- [http://example.com](http://example.com/)/index.php
- [http://example.com](http://example.com/)/index.php?r...

To a human, all of these URLs represent a single page. To a search crawler, though, every single one of these URLs is a unique "page." Even in this limited example, we can see there are five copies of the homepage in play. In reality, though, this is just a small sample of the variations you might encounter.

Modern content management systems (CMS) and dynamic, code-driven websites exacerbate the problem even more. Many sites automatically add tags, allow multiple paths (and URLs) to the same content, and add URL parameters for searches, sorts, currency options, etc. You may have thousands of duplicate URLs on your site and not even realize it.
