---
layout: post
title: The Financial Conduct Authority (FCA) broke its Google Search
excerpt: Google has 42,400 FCA webpages that dont lead to what consumers are looking for.
image: https://learn.getgrav.org/user/pages/11.troubleshooting/01.page-not-found/error-404.png
published: false
---

The Financial Conduct Authority (FCA) has a [Register of Authorised Firms and Authorised Persons][1]. Consumers can check the firm they are working with is Authorised and Regulated. The "Financial Services Register" has been running for years. Except it has just received a [redesign][2]. During the redesign, it broke itself by forgetting the basic rules of migrating a website.

When you search [Adam Hosker Financial Conduct Authority][3] the top result on Google is the FCA. In 2019 that was perfect anyone doing due-diligence on me can find my entry on the FCA Register. 

![Adam Hosker Financial COnduct Authority](https://hosker.info/images/3-adam-hosker-fca.png "Adam Hosker Financial COnduct Authority")

It currently does not work.

The Google result takes you to the FCA homepage. Instead of the entry about me. The Financial Conduct Authority (FCA) redesign broke its own Google results. It's not just me, Google has 42,400 FCA webpages that dont lead to what consumers are looking for. Links to Authorised Persons and Authorised Firms.

![42k Bad Links](https://hosker.info/images/3-42k-broken-fca-results.png "42k Bad Links")

Which for a service designed to assist in consumer due diligence, is not great.

The issue arises because, during the redesign, they have changed the website address.
* **Before**: [https://register.fca.org.uk/ShPo_IndividualDetailsPage?id=003b000000LVvtAAAT](https://register.fca.org.uk/ShPo_IndividualDetailsPage?id=003b000000LVvtAAAT)
* **After**:  [https://register.fca.org.uk/s/individual?id=003b000000LVvtAAAT](https://register.fca.org.uk/s/individual?id=003b000000LVvtAAAT) 


You will notice it's more or less the same website address, it's even the same reference. The only change is in this part of the URL:
* **Before**: ShPo_IndividualDetailsPage?id=
* **After**: /s/individual?id=

It's a two-minute job for an FCA Webmaster to fix. A [simple redirect][5] from the old addresses to the new. This fix will make the links in Google work correctly again. Google also outlines that it is [Best Practice][4] so they can pass on the Google Link Authority (FCA stays on top of searches)

It's been three weeks since the redesign. Google is probably catching on and removing the webpages. It's no big issue, a small mistake in the [£20.1 million project][6]. The thing about redirects is that it is a basic rule of website migration.

![Website Migration Checklist](https://hosker.info/images/3-migration-checklist.png "Website Migration Checklist")

## One other thing

If a web developer at FCA does read this. On the homepage design, the use of full-width coloured background boxes is to denote a change of content. You dont use them to break the content from the header. Like with this design, when a form is by itself separated from its title. It's a personal opinion, but it is a terrible UI. 

[1]: https://register.fca.org.uk/s/ "Financial Services Register"
[2]: https://www.mortgagesolutions.co.uk/news/2020/07/27/fca-updates-financial-services-register/ "FCA updates financial services register"
[3]: https://www.google.com/search?q=%E2%80%9CAdam+Hosker%E2%80%9D+%E2%80%9CFinancial+Conduct+Authority "Google: Adam Hosker Financial Conduct Authority"
[4]: https://support.google.com/webmasters/answer/6033049?hl=en "Google Site Url Changes"
[5]: https://wpscholar.com/blog/simple-redirects-with-htaccess/ "Simple Webpage Redirects"
[6]: https://citywire.co.uk/wealth-manager/news/fca-readies-8-7m-industry-bill-for-new-financial-register/a1135424 "FCA readies £8.7m industry bill for new financial register"
