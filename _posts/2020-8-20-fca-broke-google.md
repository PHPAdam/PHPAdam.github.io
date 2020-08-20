---
layout: post
title: The Financial Conduct Authority (FCA) broke its Google Search
excerpt: Google has 42,400 FCA webpages that dont lead to what consumers are looking for.
image: https://hosker.info/images/3-masthead.png
published: true
---

The Financial Conduct Authority (FCA) has a [Register of Authorised Firms and Authorised Persons][1]. Consumers can check the firm they are working with is Authorised and Regulated. The "Financial Services Register" has been running for years. Except this month it received a [redesign][2]. During the redesign, it broke due to forgetting the basic rules of migrating a website.

When you search [Adam Hosker Financial Conduct Authority][3] the top result on Google is the FCA. In 2019 that was perfect anyone doing due-diligence on me can find my entry on the FCA Register. It's simular results if you search for a Authorised company's name.

> ![Adam Hosker Financial COnduct Authority](https://hosker.info/images/3-adam-hosker-fca.png "Adam Hosker Financial COnduct Authority")

It currently does not work.

The Google result takes you to the FCA homepage. Instead of the entry about me (or my firm). The Financial Conduct Authority (FCA) redesign broke its own Google results. It's not just me, Google has 42,400 FCA webpages that dont lead to what consumers are looking for. It's been three weeks since the redesign. Google is probably catching on and removing the links to Authorised Persons and Authorised Firms.

Which for a service designed to assist in consumer due diligence, is not great.

> ![42k Bad Links](https://hosker.info/images/3-42k-broken-fca-results.png "42k Bad Links")

The issue arises because, during the redesign, they have changed the website address.
* **Before**: [https://register.fca.org.uk/ShPo_IndividualDetailsPage?id=003b000000LVvtAAAT](https://register.fca.org.uk/ShPo_IndividualDetailsPage?id=003b000000LVvtAAAT)
* **After**:  [https://register.fca.org.uk/s/individual?id=003b000000LVvtAAAT](https://register.fca.org.uk/s/individual?id=003b000000LVvtAAAT) 


You will notice it's more or less the same website address, it's even the same reference. The only change is in this part of the URL:
* **Before**: ShPo_IndividualDetailsPage?id=
* **After**: /s/individual?id=

It's a two-minute job for an FCA Webmaster to fix. A [simple redirect][5] from the old addresses to the new. This fix will make the links in Google work correctly again. Google also outlines that it is [Best Practice][4] so they can pass on the Google Link Authority. Enabling the FCA to stay on top of searches.

It's no big issue, a small mistake in a grand [£20.1 million project][6]. The thing about redirects is that it is a basic rule of website migration.

> ![Website Migration Checklist](https://hosker.info/images/3-migration-checklist.png "Website Migration Checklist")

# Not the only SEO Mishap
For A website to enable Google to find all its webpages has a [robots.txt][7]. This links to what is called a "Sitemap", which is a list of all the webpages on the website. One small problem is the [FCA's sitemap][8] does not work and also leads to the homepage.

Not only, are authorised firms and persons being removed from Google (due to no redirects). There is no Sitemap telling Google where to find the new pages. So the only way it can find a firm now is via internal links on the FCA's website. A difficult task, its behind a FCA Search system. The webpages are becoming increasingly difficult for a Google Search bot to find.

> ![Bad FCA Sitemap](https://hosker.info/images/3-sitemap.png "Bad FCA Sitemap")

## One other thing

If a web developer at FCA does read this. On the homepage design, the use of full-width coloured background boxes is to denote a change of content on a page. Not to separate a form from its descriptive title. It's a personal opinion, but it is terrible UI.

## Adam, what are you on about?
It's in the title 'I write about the most boring niche stuff'. You learned a few things here for your own websites. If your web developer changes the website structure, use redirects to retain its Google influence and Discoverability. Do you have a robots.txt? Does it have a working sitemap indexing every webpage of your website? Dont follow the FCA lead and get that up and running.

## Adam, Why does this even matter?
Consumer Due-Diligence. The FCA has stated itself that it is battling against fake directories. It needs good Search Engine Optimisation (SEO) and these are basic mistakes that do not foresee a great outcome from the new directory.

[1]: https://register.fca.org.uk/s/ "Financial Services Register"
[2]: https://www.mortgagesolutions.co.uk/news/2020/07/27/fca-updates-financial-services-register/ "FCA updates financial services register"
[3]: https://www.google.com/search?q=%E2%80%9CAdam+Hosker%E2%80%9D+%E2%80%9CFinancial+Conduct+Authority "Google: Adam Hosker Financial Conduct Authority"
[4]: https://support.google.com/webmasters/answer/6033049?hl=en "Google Site Url Changes"
[5]: https://wpscholar.com/blog/simple-redirects-with-htaccess/ "Simple Webpage Redirects"
[6]: https://citywire.co.uk/wealth-manager/news/fca-readies-8-7m-industry-bill-for-new-financial-register/a1135424 "FCA readies £8.7m industry bill for new financial register"
[7]: https://register.fca.org.uk/robots.txt
[8]: https://register.fca.org.uk/robots.txt
