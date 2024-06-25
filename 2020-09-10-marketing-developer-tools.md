---
date: 2020-09-10
author: jw
title: "A few thoughts on PMMing dev tools"
description: "After a few minutes scrolling through StackShare, I was inspired to write down a few tips for all the PMMs out there slinging dev tools. Here is how to make your product standout, how to get a few early adopters, and a few insights into the dev tools space."
categories: [work]
tags: [Product Marketing]
---
![Emerald](img/dcstreet-site-art.png "DC Street Art")
<span class="heroart">A bit of DC street art by, various artists | <a href="../about#whats-with-the-random-art">What's with the random art?</a></span>

This week I spent a few minutes scrolling through StackShare checking out new tools which were recently listed. The list seemed endless, a night and day contrast from when I wrote the listings for Codenvy and Eclipse Che in early 2013. The dev tooling space has exploded in recent years and for someone who focuses on dev tools, it’s an exciting time. 

Most dev tools are created to improve the workflows of developers and make it easier to build great software. If you keep tabs on the developer ecosystem reports and surveys, you know that most of the market is dominated by a handful of editors, git, CI/CD, build and runtime solutions, frameworks, extensions, and plugins. While I was scrolling through StackShare I couldn’t help but ask a few questions, 1/ If most developers use the same stack, why is the dev tools space expanding at its current rate? 2/ How do you cut through all of the clutter and avoid the pitfall of ambiguity in your product messaging? 3/ How do you build awareness of your solution with developers?

<h3>What’s driving the expansion and growth of dev tools?</h3>

The obvious reason is supply and demand. As the developer population expands investing into tools that once seemed like an edge case solution can be justified. The second obvious reason is that software has made its way into places that we never would have expected ten years ago (think smart-locks or most of the other smart-home devices) that leverage new languages and frameworks. In theory every time a new language is created another syntax highlighting plugin is released. In fact, just this week I downloaded an IDE that was specific to the software that powers a robot that I’m building with my son, it runs on a simplified version of C++.

I would argue that the not so obvious reason for this expansion is open source …

If you look at a popular project like Kubernetes there is an entire ecosystem of developer tools that have sprung up around the project. It’s incredibly overwhelming, and that’s not even factoring in the tools that have been built around vendor offerings like OpenShift,  EKS, AKS, GKS … the list goes on forever. Open Source projects create this foundation that can be used as a springboard for niche solutions and a level of standardization for the enterprise. 

This is one of the reasons why dev tool positioning is repetitive at best, and ambiguous at worst. <b>When your tools are built on the same underlying technology, it’s easy for product marketers to fall into the trap of over-adopting the identity of the upstream project.</b> I can’t tell you how many times I’ve looked over the site of a new CI/CD solution just to scratch my head and wonder why they didn’t just call it “Jenkins with a different logo”. Vendors, project leads, and committers invest tons of time and resources into these offerings just to have the features that set them apart completely disregarded in their product marketing materials. 

I’ve found that the key to product positioning often begins by working from extreme simplification and brutal honesty towards differentiation. This is really key for product marketers, instead of starting at “a cloud-native IDE for AI/ML” start at “another python IDE built on Eclipse Theia that runs in the cloud and can be customized with plugins”. This forces you to think about the ‘but’ which is what should be the focal point of your product marketing. 

In this case, “BUT, unlike VS Code, our IDE is embedded into our platform, has peer-programming, and has OBS-mode that auto blurs sensitive data so you can live-stream all your work directly onto Twitch”.  From this point you can easily see the theme that begins to stand out, this IDE has a social focus and is specific to a platform. Your positioning will now change from “A-IDE, a cloud-native workspace for platform.io” to “A-IDE, social coding for platform.io”. This positioning is much more compelling and identifies with the audience that you are targeting. Note, that I didn’t add anything about AI/ML or cloud-native, this is because we’re assuming that the type of development is implied by the platform you are building on. We’re hyper-focused on the aspects that matter, everything else can be called out later.

<h3>You built it and positioned it, why don’t they use it?</h3>

Going back to the original questions that sparked this post, in an ecosystem that is so crowded, how do you build awareness of your tool? This is not a simple question to answer, in fact it’s probably the one thing that every marketer (no matter the industry) thinks about daily … I know I do. Luckily, there are a few things that you can do to help your chances of getting noticed, which is the first step. To keep things simple, let’s continue to use the example above of A-IDE. We have a defined product with a defined set of users (this is fairly easy for our example since they have to use platform.io for AI/ML development and be interested in live-streaming on Twitch). 

If you’re not technical, think of a dev tool like any other tool and ask yourself what you would care about if you had to go to a hardware shop to buy one. If you’re like me, you want the most optimal tool for the job. Things like price, color, name, and brand don’t matter, all I care about is if it will get the job done in a way where I exert as little effort as possible. Developers are the same way I would even argue that they are way more obsessed with this than you are about buying a hammer. Being driven by laziness isn’t frowned upon by developers, after all they created the copy/paste button. This is your first stop for building awareness, your goal should be to make sure that developers know that your tool makes it easier and faster to accomplish their desired outcome. 

As product marketers, we tend to focus on technical problems. For A-IDE, the integration with platform.io might eliminate a complex self-service integration that is notorious for security vulnerabilities. This improvement should be quantified and should be surfaced early in your marketing materials. But, the real benefit for developers is that they can live-code without worry and forget the pain of scrubbing their videos of sensitive information. Too many products focus on easing the burden of configuration, however, that burden doesn’t persist when once they’ve completed it. Compare this to editing videos on a daily or weekly basis, and you have a compelling reason to try your product.

This is where product marketing for developer tools becomes really fun. Developers tend to seek guidance from their community when making a decision about a tool, so as long as it’s true, you have a good chance of building awareness quickly. I’ve found that companies that share really good tools with developer communities on Reddit, Twitter, HN, etc. can often times see their solutions take off overnight. 

I hope that this post provides you with a few things to think about next time you are planning on bringing a tool to market. If you have questions, hit me up on twitter.
