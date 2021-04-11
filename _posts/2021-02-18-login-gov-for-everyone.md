---
title: "Login.gov for Everyone!"
author: Bill Hunt
type: post
date: 2021-02-18-T23:48:24-0500
permalink: /blog/2021/02/18/login-gov-for-everyone/
layout: post
excerpt: GSA's Login.gov identity service is now available to city and state governments!  This is literally the biggest and most important govtech news to come out in the last five years!

---

A little over two years ago, I was walking out of the New Executive Office Building by the White House. I immediately ran into [Robin Carnahan](https://twitter.com/RobinCarnahan), who said to me, "Bill, we should be able to provide Login to cities and states." (If you haven't met Robin, let me just make it clear for the narrative here that she's super-smart and anything she says you should just agree with immediately because she knows what she's talking about.) As soon as I got back to my desk at the Office of Management and Budget (OMB), I started sending out emails to figure out why the General Services Administration (GSA) was preventing this excellent service from being used by smaller governments.

For those of you who don't know about this hidden gem, [Login.gov](https://login.gov/) is a GSA solution to help solve the difficult problem of verifying that a person is who they say they are to receive a government benefit, as well as a solution for logging into government websites.  It was created through the combined efforts of USDS and 18F - the two most prominent digital service teams in all of government - and is in use by many Federal agencies today. Today it provides access to government services for over **27 million people**!

Today, [GSA has announced](https://www.gsa.gov/blog/2021/02/18/logingov-to-provide-authentication-and-identity-proofing-services-to-a-limited-number-of-federally-funded-state-and-local-government-programs) that Login.gov is available for use by local and state governments!  (To be clear, I had effectively nothing to do with the actual permission being granted here - sending stern emails had little effect. The victory today belongs entirely to the wonderful, amazing, fantastic team at Login and the bureaucrats who were willing to push to make it happen.)

There are, however, still a few restrictions for city and state use. To be eligible, the government agencies must be using Login for a "federally funded program." This is an arbitrary addition by GSA that, in my opinion, misinterprets the original intent of the legal authority - but I'm not a lawyer and am no longer responsible for these sorts of policy decisions. I am hopeful that this restriction will be removed in the future and this incredible service will be open to all who want it!

Moreover, as [I've written in the past](/blog/2020/12/18/federal-policy-recs/#4-solve-identity-once-and-for-all), it is my hope that OMB will **mandate** the use of Login for all Federal agencies. This is [already mandated by law](https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title6-section1523&num=0&edition=prelim), but OMB is not enforcing the requirement. The most expensive part of the tool is the identity verification step - however, once an identity has been proven, it does not need to be re-proven if the customer wants to use any other service that is using Login. This means that as more organizations sign up for Login, the cost to each decreases. By allowing Federal agencies to maintain their own independent login systems, the costs remain high. Moreover, this presents customers with an inferior experience, as they must sign up for a new account for each website or application.

It's also important to note that most identity verification behind the scenes is using data sources that the government controls and gives to private companies, who then sell the government back its own data in the verification process at a very high premium. Eventually, it would be smarter to allow agencies to exchange the necessary information themselves, cutting out the middleperson, which would decrease the cost to _almost nothing._ (Congress, of course, could speed this along too with the right legislation.)

I've heard that the Login team has also been working on a pilot to allow customers to prove their identity in-person at a government facility, which has shown to improve the success rates of the verification process. The Department of Veterans Affairs (VA) uses such a process to help Veterans walk through the process of setting up their online accounts right in the lobby of many VA health clinics. The US Postal Service also performed a similar pilot several years ago, where anyone could stop by a post office and have them review their documents, or even let their postal carrier perform the review when they drop off the day's mail, allowing them to reach almost every single person in the country!

Detractors still complain about the cost of Login.gov, and consider that a reason to not require it, even though the cost would be reduced if it _was mandated_. Even so, _if_ the Federal government agrees that this is the tool that agencies should be using, then it should be treated like a Public Good - like a library or park. To that end, Congress could pass appropriations dedicated to funding this critical program, for instance as part of [President Biden's proposal for TTS Funding](https://www.whitehouse.gov/briefing-room/legislation/2021/01/20/president-biden-announces-american-rescue-plan/).

However, I would caution agencies from implementing identity requirements **beyond what is absolutely necessary**! The [Digital Identity Guidelines from the National Institute for Standards and Technology (NIST)](https://www.nist.gov/itl/tig/projects/special-publication-800-63) are the baseline that most Federal agencies use; in my personal opinion, they set too high a bar. The government must provide critical services to at-risk and economically disadvantaged groups, and by setting requirements that individuals in these groups cannot meet agencies are not serving people equitably. For instance, the the VA serves Veterans that may be homeless, may not have a credit card, may be partially or fully blind, may have trouble remembering or recalling information, may not have fingerprints, and so on.  Since the standard methods of identity verification and authentication may present an impossible barrier for the very people the VA serves, it is in the best interest of these people to not implement NIST's high standards as written. (And I told NIST the same thing.)

If you’re a city or state government interested in a world-class identity solution, I'd recommend reaching out to GSA about Login.gov! Even if you don't meet the requirement mentioned above, it's definitely worthwhile to getting in touch with GSA anyway - as we've learned, policies change every day.