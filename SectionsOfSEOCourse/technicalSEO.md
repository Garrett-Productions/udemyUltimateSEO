Technical SEO 

HTTP vs HTTPS

With the 's', it is protected, literally meaning secure

Https using SSL for encryption
- if data is trafficed with https, the message or content will be created

Your Hosting company can grant this with you


~~~~~~~~Setting up a Google Search Console.~~~~~~~~
* We'll crash course google search console, but it needs to be added to bluehiost and provide a txt record
- go into advanced dns and add a record and a txt record as per request from google search console
* You can verify after a day


~~~~~~~~~There are 2 different versions of Google Analytics 
1. Universal Analytics(GA3)
2. Google Analytics(GA4)

Universal uses traffic for data, how many hits did your website get?
- session based model

GA4 uses a model based on events and paramenters
- event based model

GA4 was created 10/2020
GA4 is still being fully updated 

~~~~~~~~~~GA4 SETUP~~~~~~~~~~

I must setup on wordpress backend, because I already setup GA4 account accessibility, but now I need to install the plugin on the wordpress end. I can now go into my analytics account, select my data stream, and select 'tag' and add all that tutrial code

OK I have added the striung to my DNS settings gonna come back tomorrow at 3PM to click verify

Installed plugin Site Kit
- Google adds a verification token to your site's HTML code.
- Turn on metrics in your dashboard
- Set up Search Console
- Setup Google Analytics
*Site Kit


XML SiteMap
- Wordpress - admin, Yoast SEO, Settings, Site Features,API's, XML SiteMaps
- Go over to google search console and Copy and Paste your XML sitemap URL to 'sitemaps' on search console sidebar as 'Add a new Sitemap'
- google can now crawl this site

Duplicate Content
- google can experience troubles w querying duplicate content.
- there is a tool to find: siteliner.com
SITELINER.COM
- Score under 15% of duplicate content is what we pay attention to
- there is a tab for dup content which will show all URL's w matching content

What is a 404 page?
- error, page not found
- result in a poor UI
- wasted link juice, if you had conencted users, this is bad 
- you can find your 404 pages under 'coverage' on the tab on 'Google Search Console'


301 Redirect
- redirects user to new location of same page 
- when you want to combine 2 pages together
- this provides consolidation of authority and causes better content

Setting up a 301 redirect
- site:https://mauishoresdiveshop.com/ *dive*
- open both pages simaltaneously
- once the plugin is setup, go to it, make sure 301 is selected copy and paste the url that you want to redirect, not the /, 
- next copy the url to where you want it to redirect to


Keyword Canibalization
- two pages competing for same keyword, resulting in google doesnt know which to rank
1. either redirect one to the other, or just deoptimize

Steps
- finding KW's on SEMrush, making a spreadsheet, we just need search volume and position, and URL
- we are looking for multiple occurences of same keywords

Ex) same KW, but google returns 2 differnt links on same page
* to deoptimize, remove your KW from titles, etc

* THIS IS ONLY AN ISSUE IF 2 PAGES ARE COMPETING FOR A SPOT ON THE 1ST PAGE OF GOOGLE'S SEARCH RESULTs

Schema Mark Up
- rich snippets and titles 
1. Schemas tell search engines what your data means, not just what it says
2. Uses unique Semantic vocab in microdata format
3. Schema.org
4. Invented for users 

Markup Types
- articles, eventsd, products, episodes 

ADDING A SCHEMA ON WP
- Schema – All In One Schema Rich Snippets

With this plugin you can add a schema piece directly to a page, by selecting the page and configuring a rich snippet and adding right there

We just added an article schema to our wordpress website

~~~ now its deprecated, use this, use the Rich Results Test
Tool: https://search.google.com/test/rich-results