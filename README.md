<div style="width:100%; text-align:center;">
    <a href="https://twitter.com/maartenballiauw" style="display: inline-block; margin: auto;">
      <img src="https://raw.githubusercontent.com/maartenba/maartenba/master/images/template/twitter.png" alt="Twitter @maartenballiauw" width="49%" />
    </a>
    <a href="https://blog.maartenballiauw.be/" style="display: inline-block; margin: auto;">
      <img src="https://raw.githubusercontent.com/maartenba/maartenba/master/images/template/blog.png" alt="Blog" width="49%" />
    </a>
</div>

<hr/>

### Hi there 👋

My name is Maarten Balliauw ([@maartenballiauw](https://twitter.com/maartenballiauw/) on Twitter).

> Maarten Balliauw loves building web and cloud apps. His main interests are in .NET web technologies, C#, Microsoft Azure and application performance. He is Developer Advocate at JetBrains, and formerly founded [MyGet](https://www.myget.org). He's an ASP Insider and former Microsoft MVP. Maarten is a frequent speaker at various national and international events and organizes [Azure User Group](https://www.azug.be) events in Belgium. In his free time, he brews his own beer. Maarten's blog can be found at [https://blog.maartenballiauw.be](https://blog.maartenballiauw.be).

#### 📙 Blog Posts
<!--START_SECTION:feed-->
##### [A sustainable NuGet marketplace will have to compete with the NuGet gallery](https:&#x2F;&#x2F;blog.maartenballiauw.be&#x2F;post&#x2F;2020&#x2F;06&#x2F;18&#x2F;a-sustainable-nuget-marketplace-will-have-to-compete-with-the-nuget-gallery.html) 
*Yesterday, Aaron Stannard posted some awesome news for the .NET community:
the introduction of Sdkbin. Sdkbin is targeted at solving
the OSS sustainability problem by automating the majority of the sales, fulfillment, licensing, and accounting
needed to sell libraries, frameworks, and support plans. It’s (roughly speaking) an App Store, delivered as a
NuGet feed.

This seems like a great idea, and most of all, a needed idea.



     On This Page

  Why open source sustainability matters
  How to sustain open source?    
      Open source foundations &#x2F; .NET Foundation
      Sponsorship
    
  
  Another solution: a NuGet marketplace    
      For producers: legal services
      For producers: business services
      For producers and consumers: flexible licensing and purchasing options
      For producers: where does the money go?
      Intermezzo: “App Stores” live and die by their policies
      For third parties: can they sell value added services?
      For producers and consumers: reporting
      For producers and consumers: a solid platform
    
  
  A marketplace has two sides - getting traction    
      Getting consumers on board
      Getting the component vendors on board
      Getting open source projects on board
    
  
  Compete head-on with the NuGet.org gallery    
      NuGet.org is too good to switch away from
      Competition will come anyway
    
  
  Conclusion


  


In this post, I wanted to contribute some of my own thoughts in this area, and end with a section about
why Sdkbin (or any solution in this space) will have to compete head-on with NuGet.org.

Let’s start with some thoughts on open source sustainability, because that is where this story starts…

Why open source sustainability matters

For a while now, and if I come to think of it, ever since .NET was released, we’ve been struggling with open source projects.
Not with creating them - there are many, many, awesome projects out there in various areas and of various sizes.
We struggle with sustaining them.

Often, open source starts from a personal need of one or more developers, who then solve that need for themselves.
It will be useful for others, so let’s publish a NuGet package and open source all code, take issues and contributions, and all that.

This is where sustainability comes in. How can core contributors sustain their interest in keeping the project going,
promoting it and getting others to use it, responding to bug reports, and all other things involved? What’s their incentive for working
for free? This often starts with trying to build name and reputation, but that wears off. Their interest may fade over time.

Wanted!10x rockstar developer 🔥Responsibilities include:* Merging PRs immediately* Making new features on demand* Fixing bugs right nowCompensation:* Stars* +1&#39;s* Threats, general and specific* Public shamingApply at OSS Inc today&amp;mdash; Ryan Chenkie (@ryanchenkie) November 28, 2018


How can open source contributors involve and interest others? How can they prevent burning out? Things happen, where the
project is no longer being maintained. Their users are disappointed and have to replace project A with project B.

Users expect project A to always work. They adopted it, spent time integrating it in their solutions. They expect the
authors to always be there to tackle questions and issues. And that is understandable. These users are often
companies, who look at continuity. Who expect continuity, for good reasons, as this open source project helps
them run their business processes.

How to sustain open source?

There is zero guarantee that an open source project will be there forever, and that the core contributors will
always be there. This raises some questions and concerns:


  How can we ensure core contributors remain interested?
  How do we prevent them from burning out working on things they no longer care about?
  How can we make sure if their interest fades, the project is maintained?
  Is this hindering more adoption of open source, because companies may pick “company-backed projects” over random folks pushing code to GitHub?


Let’s look at how we can answer these…

Open source foundations &#x2F; .NET Foundation

One attempt to fix some bullets from that list is in open source foundations, like .NET Foundation.
From their FAQ:


  We help projects stay focused on producing high-quality software without the legal and administrative
distractions and overhead so they can focus on helping contributors and writing code.


Great! If we all move our projects under the .NET Foundation, our company-users can be reasonably sure
there is a good license in place, and projects get some help with certificates, legal, administration and so on.

Essentially, these foundations try to solve adoption of open source by other companies, and in some aspect
provide a means of picking up a project when core contributors left. There have not been such cases as far
as I know, so this may even turn out not to be the case.

Bottom line: does this solve the core question? How can we ensure core contributors remain interested?

Sponsorship

In an earlier post, Aaron described that creating sustainable open source projects will have to be done by treating them like proper businesses.
He makes the point that an open source project has to be treated as a business. Contributors and consumers
come as a package deal. Commercial licenses help support the project, and help build trust with users.
Adding support packages on top helps support the project, and builds trust with users.

This is where many projects think sponsorship comes in. Many open source contributors today have
a Patreon link, or have enabled GitHub Sponsors.

Let’s look at the sponsors page of a friend of mine, Tom Kerkhove.
He’s a great person, and has spent countless hours on building out and maintaining Promitor,
used widely by folks pushing Prometheus metrics into Azure Monitor.

Tom has a sponsor button, which tells me that I can sponsor him for
$5, 0, up to $500 per month. There’s also a progress bar at the top, that tells me he’s 30% on his way to
$50&#x2F;month. That’s a whopping 5 per month on the way to becoming a business!

You may not be using this project, but I know many are. How many are sponsoring Tom for his efforts? Very few.
Now, I know Tom has Walmart labs as a big user, and I learned they contribute
at least some of their time towards his project, but that was arranged on the side. Not through a GitHub
sponsors button.

Sponsorships are not going to cut it. I honestly hope they do, but I don’t think they will be the way to
incentivize and encourage open source contributors, and make their projects sustainable.

So what can solve the sustainability issue?

Another solution: a NuGet marketplace

Looking at foundations and sponsorships, there are a few things that make these solutions suboptimal for producers
and consumers.

Producers will have to make consumers aware that there are paid options. They have to direct them to the sponsor button,
and can say the open source foundation lawyers approve of the license.

As a consumer, you have to be aware of these options, and actively search for them. They are not “in your face”
in our IDE, where we consume most open source through the NuGet client. Which means consumers often have no idea
there is a sponsor button.

This is where https:&#x2F;&#x2F;sdkbin.com, and https:&#x2F;&#x2F;bytepack.io, and others come in. In fact, our community has been
dreaming this up for a long, long time.

Some recent calls for this:

An idea.A managed NuGet[org] alternative for selling your NuGet packages.A web interface for discovering paid-for packages. After purchase, they are made available (forever) in a private feed.Subscriptions and payment are managed by the platform.&amp;mdash; Paul Knopf (@pauldotknopf) October 1, 2019


We basically need to transform our NuGet, Npm, VSCode plugin marketplace whatever into AppStore. If dual licensing is not supported out of the box it will never become mainstream solution for sustaining OSS https:&#x2F;&#x2F;t.co&#x2F;oRllcH0qYA&amp;mdash; Krzysztof Cieślak @ #BlackLivesMatter (@k_cieslak) January 28, 2020


I know when I was building MyGet with Xavier,
we dreamt up something like a NuGet marketplace as well. Will have to check but I think I still have nugetmarketplace.com
somewhere…

The above is scientific proof a NuGet marketplace is needed!
Let’s look at what a NuGet marketplace should help with.

For producers: legal services

Open source projects can still be open source, but sell additional services. These could be:


  Dual-licensed open source
  Paid add-on packages
  Support services
  Consulting services


Dual-licensing will require a set of templates that projects can work with.
If the project uses Apache-2, MIT, GPL, or other open source licenses, what will a commercial dual-license
look like?

Paid add-on packages may be open or closed source, but they will still need a license. A NuGet marketplace
will require templates and guidance.

As Aaron mentioned when I showed him a preview of this blog post:


  There must be standard commercial licenses - because the people buying them will also need to trust that
those license agreements won’t come back to haunt them down the road.
One of the big incentives for adopting OSS right now is the fact that most licenses are permissive
  
    a hurdle we’re going to have to overcome is making less permissive, proprietary licenses more palatable.
  


Support services and consulting services are harder. How will a NuGet marketplace assist with these?
Contract templates and guidance, again, may be of help here.

The legal aspect will be a bit like what the open source foundations offer:
help with protecting producers and consumers.

There is one additional aspect a NuGet marketplace will have to help with: establishing rules and preventing
their abuse. What if I have an MIT-licensed project, and someone sells it with a dual license on this
marketplace?

It will be perfectly legal and valid for someone to sell your MIT licence code. You expressly permitted that.&amp;mdash; Damian Hickey (@randompunter) June 17, 2020


Morally, this is “not done”, but legally, this may happen. The marketplace will have to prevent this and have
rules and guidance on how to go about this. We want sustainability!

Another similarity with open source foundations is in the legality of purchasing packages.
A NuGet marketplace will have to make sure consumers who purchase here can trust their purchase is legal
and they can use the package without issue, now and in the future.

Others are GDPR (as a consumer, is my personal data safe?), and probably some more. Feel free to add them
in the comments and I will update the post.

For producers: business services

Before we can sell packages, what’s the legal status of an open source project? Is it a company? A non-profit?

A NuGet marketplace will probably be the legal entity where consumers purchase packages from.
Much like how Fastspring acts as a reseller (“Merchant of Record”), a NuGet marketplace will have to
do this as well.

A NuGet marketplace will have to act as a Merchant of Record, for several reasons:


  Consumers purchase from one legal entity, with one contract.
  Consumers can have e.g. a subscription that includes paid-for open source from multiple vendors, without dealing with all of them separately.
  Consumers will be in several locations - the marketplace will have to accomodate for Value Added Tax (VAT), the EU VAT MOSS, and all that.


If we want to make the step to sustainable open source, a NuGet marketplace will have to help
projects in doing so. Not simply by having a downloadable binary with a paywall, but by helping them out
with being a business.

For producers and consumers: flexible licensing and purchasing options

A NuGet marketplace will need to support various purchasing options. Some examples:


  Trial versions (30 days of usage)
  Subscriptions (containing one or multiple packages)
  Licenses with # seats, ideally also where enterprises can manage who can consume packages
  Perpetual licenses
  Licenses that are valid for major versions of a package only, etc.


And as a consumer, can we pay by credit card only? Can we raise a purchase order and have NET90 payment terms?
Not for a $49 purchase, probably, but a marketplace that is out to help open source sustainability will have
to accommodate the bigger customers with lengthier processes, and take that out of the open source maintaner’s hands.

For producers: where does the money go?

Since many open source projects don’t have a legal entity, where do funds go? As Khalid Abuhakmeh mentioned:

I think the stickier topic is how are funds appropriated to contributors. At some point these projects grow passed their creators.&amp;mdash; Khalid (@buhakmeh) June 17, 2020


When there are 4 core contributors, who gets the proceeds? This is one a NuGet marketplace could solve
by requiring all core contributors to link their account, and get an even portion of proceeds. But maybe a
marketplace should not try to solve this, because this will be different for each project. Let them figure
it out among themselves.

There will have to be guidance at least, around how to do this and how to resolve disputes. Issues over this
topic may erode sustainability and the trust consumers will put in the marketplace, so it is one to take into
account somehow.

Intermezzo: “App Stores” live and die by their policies

In the legal part, I used the example of an MIT-licensed package being sold by a third-party. In the previous
section, we touched on curation and making sure there is at least guidance and policies around conflicts.

Guidance and policies will be super important for a NuGet marketplace. A NuGet marketplace has to help producers
and consumers here, and make it crystal clear what may happen with edge cases.

Something like @DHH’s story would be bad for an emerging NuGet marketplace:

Wow. I&#39;m literally stunned. Apple just doubled down on their rejection of HEY&#39;s ability to provide bug fixes and new features, unless we submit to their outrageous demand of 15-30% of our revenue. Even worse: We&#39;re told that unless we comply, they&#39;ll REMOVE THE APP.&amp;mdash; DHH (@dhh) June 16, 2020


Policies matter, and enforcing them properly is equally important.

Another aspect is in curating what is made available on a NuGet marketplace. Is every package allowed? Or is there
a vetting process to filter out low quality or infringements? Or should there be a barrier of entry, such as an
onboarding fee for producers to be able to start publishing on a NuGet marketplace?

We all know how the Windows 8 Store went down… There was a race to the bottom, where everyone was encouraged
to publish low quality, inexpensive apps into the store to “hit the right number of apps”.
Turns out app quality mattered after all, and even today with the Windows 10 Store, that perception of
quality is not where it could have been.

In short, a NuGet marketplace will have to think about vetting and curation, and where it applies.

For third parties: can they sell value added services?

Having open source producers commercialize on a NuGet marketplace is one thing, but there can be more.
If this NuGet marketplace goes beyond just packages and licenses, others can sell value added services.

An interesting case that I could see popping up: if I&#39;m an expert at a package, could I sell support for that package that specifies it can&#39;t guarantee code changes? I think there&#39;s a market for that and I could see myself applying as a vendor for that sort of thing...&amp;mdash; Sean Killeen (@sjkilleen) June 17, 2020


While not a key component of this NuGet marketplace, it may be a good incentive for consumers to flock here
and find those services.

For producers and consumers: reporting

As a producer, I will want to know who is using packages. How many downloads are there? What’s the revenue our project is making?

As a consumer, I want to know who I’m purchasing from. I want invoices, reports on who of my staff are using which licenses, …

For producers and consumers: a solid platform

This NuGet marketplace will start off as a novel concept and will have to win hearts with producers and consumers.
Over time, it will have to build and maintain trust. As first impressions matter, it will have to be built
as a solid platform, from a technical point of view, UX point of view, and the aformentioned legal and business
services. A Minimum Viable Product (MVP) approach may help in building this solid platform with laser focus.

Speaking from experience building out MyGet in the past, this NuGet marketplace
will get hammered by users. NuGet attempts to retrieve every package installed from every configured feed,
so expect to serve up a lot of 404 not found responses. These, too, will require a solid platform.

A solid platform also means ease of use, and ease of discovery. One thing that could help here is providing
credential providers for Visual Studio and JetBrains Rider.
By extension, maybe also for the .NET command line tools. These will prompt the user to authenticate, and are an in-IDE
experience where payment detail updates and all that can be arranged. Discovery is key, and bringing
part of what this NuGet marketplace will offer in its web application into the IDE may help.

A marketplace has two sides - getting traction

Marketplaces have two sides, producers and consumers. If a NuGet marketplace comes about, it will have
to accommodate both, and probably subsidize one side for a while until traction takes over.

So how can this NuGet marketplace get traction? There are a few things that can be considered.

Getting consumers on board

The marketplace will need consumers, and folks with credit cards and purchase orders. What’s their incentive to look
at this solution? I think the answer is in all of the topics above, where ease of use, legal and purchasing,
single point of contact come to mind. Making it easy for consumers to budget their spend, wihout having to revisit
this for every package or license they decide to purchase.

Getting support from IDE vendors may help as well, helping awareness. Ultimately, convincing consumers
will require producers. So how will this NuGet marketplace get producers?

Getting the component vendors on board

There are commercial component vendors out there - think Telerik, DevExpress, and many more.

A large number of companies are using these components, and getting them on a NuGet marketplace will
help in convincing folks to configure a NuGet marketplace feed and start consuming packages.

These component vendors usually already have their own feed and are distributing components as packages,
so this is going to be mostly about convincing them to publish here as well.

These component vendors usually already have their own storefront, purchase agreement, license agreement, and so on.
How will that integrate with this NuGet marketplace?

Regardless of these issues, if consumers can get their components through a NuGet marketplace, at least
a portion will start using it because ease of use, one point of contact&#x2F;sales, and all that.

Getting open source projects on board

This NuGet marketplace will help in making open source sustainable, so it will need open source producers to
provide their packages here. I think many will do so, but there’s an issue that comes to mind…

How will consumers find this NuGet marketplace, and thus, these producers?

If there are no consumers, we’re back at the Gitub sponsor button and sustaining Tom with 5&#x2F;month. That won’t work.

So how to go about this?

Compete head-on with the NuGet.org gallery

As we have seen so far, there are many, many considerations for building out a NuGet marketplace that thrives,
and makes open source thrive. This means it will need producers and consumers. We’ve seen there are ways to
grow both sides of the marketplace, but there’s one that I have omitted up until now.

A NuGet marketplace will have to compete with the NuGet.org gallery.

Right now, there is one preconfigured feed on every .NET developer’s machine: NuGet.org. That’s a huge advantage
in the current world, but not for this NuGet marketplace. People have to configure its feed in their environment.
What’s the incentive to do that?

NuGet.org is too good to switch away from

The only incentive as a consumer I see, is being forced to start using a NuGet marketplace.
And that can only be done when NuGet.org becomes less valuable. If all of the open source packages I use,
whether free or paid, are on this NuGet marketplace, I will configure the feed to consume them. If NuGet.org keeps
giving me Automapper, Autofac, IdentityServer and all that, why should I bother with this NuGet marketplace as a consumer?

A NuGet marketplace will have to provide free open source packages as well. Much like in the JVM world folks
are using both Maven Central and JCenter
for their projects, instead of just one central gallery. In the .NET world, we will have to move to a future
of multiple authoritative package registries, instead of just one.

Edit: Dave Glick posted a great analogy on Twitter, comparing this argument with video games and consoles.
A NuGet marketplace will need some good exclusives, and make sure some of the popular ones that were previously
available on NuGet.org will now be available only on this marketplace.

Ah gotcha, so competition isn’t so much about replicating functionality as it is a driver for adoption by creating packages exclusivity on the alternative, which drives&#x2F;forces use - and without which the marketplace wouldn’t thrive. Not unlike the console wars and exclusive games&amp;mdash; Dave Glick 😷 (@daveaglick) June 18, 2020


Competition will come anyway

Microsoft is in the money-making business, and that’s good. They also own NuGet.org,
npm, and GitHub. If a NuGet marketplace is executed well
and proves there is value, the above platforms will come with their own marketplace. This is a given,
it will happen.

Having a competitor in the NuGet marketplace space means we’re going back to fragmentation, and moving away
from the single point of contact&#x2F;sales, open source and dual-licensed open source being in a central place,
and all that. What this will mean for the ecosystem, I can’t tell. But since it will happen anyway, I would
like to see the first NuGet marketplace to compete head-on, and aggressively become the place where open source
sustainability thrives.

The alternative is not competing head-on, which will mean we end up in a fragmented world, where the NuGet
marketplace itself as a business may not be sustainable, and ultimately, hurt producer and consumer trust
in sustainable .NET open source.

Edit: this is by no means meant to be a kick in the gut. It will happen, which can be fine,
but having fragmentation in such marketplaces would hurt the mission of supporting OSS sustainability.
A NuGet marketplace will have to go big to drive that mission home.

Conclusion

If all of these criteria (and probably more) are met, a NuGet marketplace can be a huge step towards
open source sustainability. A solid, trustworthy platform for consumers and producers, solving legal
and business issues.

As Aaron concluded, there are a lot of things to consider:

This was one of the things the discussion yesterday made clear to me.20% of the costs of this venture &#x3D; actually delivering packages to customers40% of the cost &#x3D; dealing with accounting &#x2F; tax &#x2F; payments40% of the cost &#x3D; having to train &#x2F; educate the market to transition&amp;mdash; Aaron Stannard (@Aaronontheweb) June 17, 2020


I have no idea yet what Sdkbin will look like, and whether all of the above will be accounted for.
What I do know is that his and Petabridge’s drive and passion for .NET open source are a guarantee that this project will
be delivered, in one form or another. Especially given their track record in making Akka.NET a sustainable open source
project by making it a business.

Whoever builds it out, whether Aaron and Petabridge or other parties, they will have to compete with the NuGet
gallery from day one. Doing so will matter more for sustainability of a NuGet marketplace as a whole,
than supporting 50 different subscription schemes. Trust and sustainability of the marketplace are key in this
story.

Thanks, Aaron, for being the one who started building this out.*
##### [Run Azurite in Docker with Rider and keep Azure Storage data local to a solution](https:&#x2F;&#x2F;blog.maartenballiauw.be&#x2F;post&#x2F;2020&#x2F;06&#x2F;08&#x2F;run-azurite-in-docker-with-rider-and-keep-azure-storage-data-local-to-a-solution.html) 
*In this blog post, we’ll see how we can use Azurite, an open source Azure Storage API compatible server (emulator), in Docker, and how to run it from JetBrains Rider. We can use Azurite in Docker to keep Azure Storage data local to a solution, and, for example, have different blobs and queues for different Azure Functions projects.

Why use Azurite over Azure Storage Emulator?

Ever since I started playing with Azure back in 2008, I’ve been using the Azure Storage Emulator to have a local storage emulator to develop with. It provides a local environment for testing applications that use Azure blob and&#x2F;or queues.

I felt it was time to retire the Azure Storage Emulator in favor of its successor: Azurite. There are various reasons for this:


  Azurite supports newer storage API’s.
  It can run as a Docker container.
  By setting its volume path to something relative to the solution we’re working on, we can keep blobs and queues around. Different solution? Different path! The blobs and queues related to that solution in Azurite.


Setting up Azurite

We can run Azurite using Docker, by running the following command:

docker run -p 10000:10000 -p 10001:10001 mcr.microsoft.com&#x2F;azure-storage&#x2F;azurite


This will fetch and run the mcr.microsoft.com&#x2F;azure-storage&#x2F;azurite image, exposing ports 10000 (blob) and 10001 (queue).

Inside the Docker container, Azurite uses the &#x2F;data folder to store blobs and queue messages. This means that we can map &#x2F;data to a folder on our host machine. When working on different projects and solution, this is great! For every solution, we can map a different path, and preserve the blobs and queues related to that solution in Azurite.

Setting up an Azurite run configuration in Rider

In Rider, we can create a new Run Configuration (Run | Edit Configurations), of the type Docker Image, and enter the image ID as mcr.microsoft.com&#x2F;azure-storage&#x2F;azurite. Optionally, we can name the container (I picked azurite here).

We’ll also have to specify the port bindings (port 10000 and 10001).

Since we want to preserve the Azurite data locally with our solution, we can create a bind mount as well. In the below screenshot, you can see I mapped D:\Projects\Git\NuGetTypeSearch\.idea\azurite to &#x2F;data in the container.



Note: The D:\Projects\Git\NuGetTypeSearch\.idea\azurite path was added into .gitignore to make sure blobs&#x2F;queue messages are not committed to Git.

Once this run configuration is created, we can select and run it. This can be done from the toolbar, but I personally prefer using the Ctrl+Alt+Shift+R keyboard shortcut, where it’s possible to immediately select the run configuration to execute (Enter) or debug (Shift, then Enter).



Once running, we can see the Azurite container’s output from the Services tool window, but usually we will not need that one.

Want to start running an Azure Functions host next? We can use the respective run configuration for that. And when we switch to another solution, we can stop the current container and start it anew in the other solution, with its own data.

Enjoy!*
##### [Referencing a Specific Assembly from a NuGet Package](https:&#x2F;&#x2F;blog.maartenballiauw.be&#x2F;post&#x2F;2020&#x2F;04&#x2F;22&#x2F;referencing-specific-assembly-nuget-package.html) 
*In this post, I’ll describe a little trick I used while building a Rider plugin for XAML Styler, which is referencing a specific assembly from a NuGet package.

Let’s start with some background on why I needed this, followed by how to reference a specific assembly from a NuGet package. If you don’t care about the background, feel free to skip the first section.

Background

Another nerd snipe… A friend of mine asked me how hard it would be to build a Rider plugin for XAML Styler, so I got to work. The plugin will add an intention to the IDE, which will let you reformat XAML documents in a project or solution using XAML Styler.

This is the idea (recorded with the plugin that is in the works):



Getting the plugin project setup correctly is relatively straightforward, thanks to a Rider and ReSharper plugin template.

Interesting to note is that right now, even though Rider is powered by .NET Core on macOS and Linux, plugins that run in the ReSharper-powered backend (architecture), have to target .NET Framework 4.6.1.

The formatting itself can be done using the XamlStyler.Core assembly. It’s a netstandard2.0 assembly, which is also part of the XamlStyler.Console package.

Hooking up the plugin, which targets .NET Framework 4.6.1, and the XamlStyler.Core assembly, which targets netstandard2.0, should be easy, as .NET 4.6.1 supports .NET Standard 2.0.

The problem for me as a plugin writer, is that there is no XamlStyler.Core NuGet package. There is XamlStyler.Console, which contains the assembly, but the XamlStyler.Console package targets netcoreapp3.1. When adding a package reference to it, you’ll be greeted with the following message on build:

Plugin.csproj : error NU1202: Package XamlStyler.Console 3.2003.9 is not compatible with net461 (.NETFramework,Version&#x3D;v4.6.1).
Package XamlStyler.Console 3.2003.9 supports: netcoreapp3.1 (.NETCoreApp,Version&#x3D;v3.1) &#x2F; any [Plugin.sln]
Plugin.csproj : error NU1212: Invalid project-package combination for XamlStyler.Console 3.2003.9. DotnetToolReference project style can only contain references of the DotnetTool type  [Plugin.sln]
  Restore failed in 572,8 ms for Plugin.csproj.


Note that XamlStyler.Console is also a “tools package” (for command line use), so we can’t reference it directly. However, let’s ignore that fact for now.

Looking at the package using NuGet Package Explorer, we can see the XamlStyler.Core assembly is there, and it has the correct target framework.



Can we reference just that assembly? Turns out we can!

How to Reference a Specific Assembly from a NuGet Package

There’s an interesting section in the NuGet documentation on PackageReference:


  Sometimes it is desirable to reference files in a package from an MSBuild target. In packages.config based projects, the packages are installed in a folder relative to the project file. However in PackageReference, the packages are consumed from the global-packages folder, which can vary from machine to machine.

  To bridge that gap, NuGet introduced a property that points to the location from which the package will be consumed.


In other words, if we add the GeneratePathProperty&#x3D;&quot;true&quot; attribute to the PackageReference element in our .csproj file, we can then access the path to that package reference using a $(PkgPackage_Id) variable (where Package_Id is the package id, where dots are replaced with underscores).

Additionally, we can tweak what has to happen with our pakage on restore. We can control the asset behaviour, and essentially tell NuGet to restore the package, but not reference it at all. Adding these attributes to our PackageReference element will do just that: ensure the package is downloaded, and not referenced:

IncludeAssets&#x3D;&quot;None&quot; ExcludeAssets&#x3D;&quot;All&quot; PrivateAssets&#x3D;&quot;None&quot;


Almost there We now have the path to our NuGet package on disk, and we’re not adding any package references. An assembly reference is the final thing to add into the mix, adding a reference to just the XamlStyler.Core assembly:

&lt;Reference Include&#x3D;&quot;XamlStyler.Core, Version&#x3D;1.0.0.0, Culture&#x3D;neutral, PublicKeyToken&#x3D;0b11ff60a8153268&quot;&gt;
    &lt;HintPath&gt;$(PkgXamlStyler_Console)\tools\netcoreapp3.1\any\XamlStyler.Core.dll&lt;&#x2F;HintPath&gt;
&lt;&#x2F;Reference&gt;


By setting the assembly hint path to $(PkgXamlStyler_Console), followed by the path in to our assembly file in the NuGet package, we can reference the assembly directly!

For those who landed here and want a full snippet that can be added to a .csproj file: here you go!

&lt;ItemGroup&gt;
    &lt;!--
        XAML Styler Console package targets netcoreapp3.x - we can&#39;t reference it, but we can download it :-)
        GeneratePathProperty will make the path to the package available in $(PkgXamlStyler_Console), and we can then add an assembly reference...
        https:&#x2F;&#x2F;docs.microsoft.com&#x2F;en-us&#x2F;nuget&#x2F;consume-packages&#x2F;package-references-in-project-files#generatepathproperty
    --&gt;
    &lt;PackageReference Include&#x3D;&quot;XamlStyler.Console&quot; Version&#x3D;&quot;3.2003.9&quot; IncludeAssets&#x3D;&quot;None&quot; ExcludeAssets&#x3D;&quot;All&quot; PrivateAssets&#x3D;&quot;None&quot; GeneratePathProperty&#x3D;&quot;true&quot; &#x2F;&gt;
&lt;&#x2F;ItemGroup&gt;

&lt;ItemGroup&gt;
    &lt;Reference Include&#x3D;&quot;XamlStyler.Core, Version&#x3D;1.0.0.0, Culture&#x3D;neutral, PublicKeyToken&#x3D;0b11ff60a8153268&quot;&gt;
        &lt;HintPath&gt;$(PkgXamlStyler_Console)\tools\netcoreapp3.1\any\XamlStyler.Core.dll&lt;&#x2F;HintPath&gt;
    &lt;&#x2F;Reference&gt;
&lt;&#x2F;ItemGroup&gt;


Use it with caution, as this trick probably sits on the edge of what is proper NuGet usage, but in case you ever need to reference an assembly from a NuGet package directly, ignoring other assemblies, this is a solution that works well.

Another one you may look into is Paket, which has several options for referencing packages, assemblies, and files from GitHub.

Stay safe!*
##### [Building an ASP.NET Core Tag Helper to Show&#x2F;Hide UI Elements based on Authorization](https:&#x2F;&#x2F;blog.maartenballiauw.be&#x2F;post&#x2F;2020&#x2F;04&#x2F;14&#x2F;building-an-aspnet-core-tag-helper-to-show-hide-ui-elements-based-on-authorization.html) 
*In this post, let’s see how we can create an ASP.NET Core Tag Helper to show or hide UI elements based on authorization policies. But before we do so, let’s start with a quick introduction outlining why you may want to do this.

Introduction

The web front-end of SpeakerTravel, a side project that helps simplify travel booking for speakers at conferences and events, is built using ASP.NET MVC and Razor Pages. As it goes with many applications, there is going to be some point where you need authentication, and equally important, authorization.

Thanks to policy-based authorization, expressing authorization requirements becomes more flexible. In SpeakerTravel, there are several main resources (Event, Traveller, BookingRequest), and I’ve created the necessary authorization handlers and requirements to make it possible to write requirements such as a BookingRequestApprovalRequirement, which would check whether the current user can approve a booking request for a traveller in an event. These requirements can then be added to auhorization policies, and ultimately protect a Razor page (or MVC controller) using an [Authorize(Policy &#x3D; &quot;CanApproveBookingRequest&quot;)] attribute.

Sometimes you may want to show or hide a UI element in a page or view, based on the current user’s identity and privileges. The authorization docs have some examples on how to do this, which essentially boil down to:


  Injecting an IAuthorizationService into your views:
    @using Microsoft.AspNetCore.Authorization
@inject IAuthorizationService AuthorizationService
    
  
  Writing an if statement to check authorization:
    if ((await AuthorizationService.AuthorizeAsync(User, Model, &quot;CanApproveBookingRequest&quot;)).Succeeded)
{
 &lt;a class&#x3D;&quot;btn btn-success&quot; role&#x3D;&quot;button&quot;
     asp-action&#x3D;&quot;Approve&quot; asp-route-id&#x3D;&quot;Model.Id&quot;&gt;Approve booking&lt;&#x2F;a&gt;
}
    
  


That is perfectly fine, but having all of those nice tag helpers for other things made me question putting if-statements in views. Instead, I wanted to make this look like the following:

&lt;a class&#x3D;&quot;btn btn-success&quot; role&#x3D;&quot;button&quot;
    asp-action&#x3D;&quot;Approve&quot;
    asp-route-id&#x3D;&quot;Model.Id&quot;
    asp-authpolicy&#x3D;&quot;CanApproveBookingRequest&quot;&gt;Approve booking&lt;&#x2F;a&gt;


Some will prefer the if-statement over this tag helper, as it is more visual. I was in that camp, yet after building this tag helper I can’t say I miss those ifs in view code. By all means, use what works for you.

Creating a Tag Helper for View-Based Authorization

To create a tag helper, we will need to write a class that implements TagHelper. We will also need to annotate it with a HtmlTargetElement attribute, to specify which type of HTML tag we want our tag helper to be available for. Let’s start with the rough outline of our tag helper!

1. Implement TagHelper and Specify the HtmlTargetElementAttribute

Here’s the rough outline of our tag helper (no implementation yet):

[HtmlTargetElement(&quot;*&quot;, Attributes &#x3D; &quot;asp-authpolicy,asp-route-id&quot;)]
public class ResourcePolicyAuthorizationTagHelper : TagHelper
{
    private readonly IHttpContextAccessor _httpContextAccessor;
    private readonly IAuthorizationService _authorizationService;

    public ResourcePolicyAuthorizationTagHelper(
        IHttpContextAccessor httpContextAccessor,
        IAuthorizationService authorizationService)
    {
        _httpContextAccessor &#x3D; httpContextAccessor;
        _authorizationService &#x3D; authorizationService;
    }

    [HtmlAttributeName(&quot;asp-authpolicy&quot;)]
    public string PolicyName { get; set; }

    [HtmlAttributeName(&quot;asp-route-id&quot;)]
    public string ResourceId { get; set; }

    public override async Task ProcessAsync(TagHelperContext context, TagHelperOutput output)
    {
        &#x2F;&#x2F; ...
    }
}


We’ll apply our tag helper to any HTML element, as long as it has an asp-authpolicy attribute (which policy to check against) and an asp-route-id attribute (what’s the id of the resource to verify against) specified. Hence: [HtmlTargetElement(&quot;*&quot;, Attributes &#x3D; &quot;asp-authpolicy,asp-route-id&quot;)].

When our helper executes, we will need to access the current HTTP context (via IHttpContextAccessor, don’t forget to register it using services.AddHttpContextAccessor();). We will also make use of the IAuthorizationService that is available, to validate the authorization policy. We’ll expect them in the constructor - ASP.NET Core’s dependency injection will provide them to our tag helper.

There’s also a PolicyName property, annotated with [HtmlAttributeName(&quot;asp-authpolicy&quot;)]. This property, thanks to the annotation, will be populated with the attribute value we specify in our view. We want the policy name available, and this is how to do that. The same applies to the ResourceId property.

What is very cool is that the properties that map to a tag helper HTML attribute, both ReSharper and Rider will show where that property is used in Razor!



2. Implement the ProcessAsync method

The “business logic” of our tag helper will be in the ProcessAsync method. In here, we will do the following things:


  Do whatever the TagHelper base class has to do.
  If there is a current HTTP context, call AuthorizeAsync on the authorization service, passing in the resource id and the policy name.
  If that succeeds, do nothing. If not, hide the current tag.


In code, this looks like the following:

public override async Task ProcessAsync(TagHelperContext context, TagHelperOutput output)
{
    await base.ProcessAsync(context, output);

    var httpContext &#x3D; _httpContextAccessor.HttpContext;
    if (httpContext !&#x3D; null)
    {
       if (!(await _authorizationService.AuthorizeAsync(
           httpContext.User, new ResourceDescriptor(ResourceId), PolicyName)).Succeeded)
        {
            output.SuppressOutput();
        }
    }
}


Some notes and thoughts:


  If no HTTP context is available, theoretically the entire view will not work. This situation should never happen, but in case it happens, I don’t care too much about the element still being visible. The Razor page&#x2F;controller action still has an [Authorize(...)] attribute checking the authorization policy, so that’s fine. If not, suppress the output for that edge case (?) as well.
  My authorization handlers and policies work off a ResourceDescriptor class that, in reality, holds both the resource type and id. Your situation may be different, so this tag handler and how it calls into the authorization service will probably look different in your situation.


Also, suppressing the HTML tag’s output is not the only thing you can do. Let’s say that instead of hiding the HTML element, we want to strip its href attribute so it still renders, but no longer has a link. That’s perfectly possible!

if (output.Attributes.TryGetAttribute(&quot;href&quot;, out var tagHelperAttribute))
{
    output.Attributes.Remove(tagHelperAttribute);
}


Our tag helper could add a “disabled” CSS class, or change the appearance of the element. For example, the full implementation in SpeakerTravel has an asp-onfailpolicy attribute which I can set to RemoveLink or Hide.

3. Register the Tag Helper in ViewImports

Before we can use our tag helper in any view, we’ll have to register it in the _ViewImports.cshtml file. This can be done by either registering the specific tag helper, or registering any tag helper in a given namespace. I went with the latter, where Caribou is the namespace for my tag helper:

@addTagHelper *, Caribou


4. Using our Tag Helper

After compiling the project, we can now use our tag helper!

&lt;a class&#x3D;&quot;btn btn-success&quot; role&#x3D;&quot;button&quot;
    asp-action&#x3D;&quot;Approve&quot;
    asp-route-id&#x3D;&quot;Model.Id&quot;
    asp-authpolicy&#x3D;&quot;CanApproveBookingRequest&quot;&gt;Approve booking&lt;&#x2F;a&gt;


If the Model.Id matches the CanApproveBookingRequest policy, our hyperlink will be rendered. If not, no HTML is emitted, and our button will not be visible.

When you are using ReSharper or Rider, try Ctrl+click-ing on the asp- attributes - it will show you which tag helper uses that specific attribute.



Enjoy!*
##### [Streaming a Community Event on YouTube Using StreamYard](https:&#x2F;&#x2F;blog.maartenballiauw.be&#x2F;post&#x2F;2020&#x2F;04&#x2F;08&#x2F;streaming-a-community-event-on-youtube-using-streamyard.html) 
*Last week, I wrote a blog post a book about Streaming a Community Event on YouTube - Sharing the Technologies and Learnings from Virtual Azure Community Day. I ended that post with an appendix of things I’ve looked into but have no experience with.

That… changed! Our Azure User Group held its first virtual session yesterday. The social aspect of hanging out with a group of peers was definitely amiss, but the streaming went well! This ime, we streamed on YouTube, with the help of StreamYard. I’ll write some observations and thoughts that build on the previous blog post.

What is StreamYard?

StreamYard (affiliate link that gets you 0 in credit) &#x2F; StreamYard (non-affiliate link) is, in broad strokes, what Google Hangouts on Air once was. It lets you join a virtual meeting with up to 10 people, the meeting owner can pick whose webcam or screen is being broadcast, and stream to one or multiple RTMP services like YouTube, Facebook, Twitch, and others.

Check them out! They have a free version (one stream &amp; their logo is being shown on screen), and a US $20 per month version to lift those restrictions.

If you do at least one stream per month, for which you would normally run that Azure VM from my previous post, their paid plan is priced correctly. Streaming costs resources, and US $20 for infrastructure &amp; tooling is not bad at all!

Anyway, enough with the intro - let’s talk shop!

Event&#x2F;Meetup Setup and First Steps

A few days before our event&#x2F;meetup, we created an event directly from the StreamYard dashboard. We linked it to YouTube and Facebook, added a title &amp; description, and then scheduled it for yesterday.



In the next step, you can customize this for separate targets if you are streaming to multiple services.

Right before you enter your broadcast studio, you’ll have to enter your name and pick the microphone and webcam to use. This is the real benefit of StreamYard to me: no setup with Skype, NDI sources, configuration. Open the browser, pick microphone &amp; webcam, and go.



Once in the studio, you can start setting up the look-and-feel of your stream. The paid version of StreamYard lets you add backgrounds, overlays, banners, … Here’s me, preparing a stream of this blog post!



Once all that is done, you can invite guests. Guest speakers can join the studio by opening one link, not having to install any tools on their system. Open browser, paste link, go.

I’ll not go into too much detail here, as branding etc. is something you’ll have to set up yourself, but jus o give you an idea about the first steps.

Streaming Experience

Let’s talk about the streaming experience itself. For our user group, we typically have one or two hosts who thank our sponsors, introduce the speakers &amp; help everyone feel comfortable. There are also two sessions per meetup, so we replicated that with two online sessions (and three speakers).

15 Minutes Before Stream Start

At 15 minutes before stream start, we had speakers join the broadcast studio. Be aware that in order to hear everyone, you’ll need to add everyone to the active scene. There’s a private chat window you can use to communicate in writing, but if you want voice before going live, add everyone to the scene.

We used this time to try screen sharing, and a bit of general chit chat to ease presenter nerves.

Start the Stream!

At some point, you can go live. If you Start Broadcast in StreamYard, broadcast will also start on YouTube &amp; other targets you may have set up.

We went live with everyone on screen, to make attendees feel comfortable &amp; see all faces.



We then introduced the first speaker, and removed everyone else from the scene.

This is what the broadcast studio looked like during the first session:



Things to note:


  The screen you see in the StreamYard studio is what is being broadcast. No production mode like OBS Studio where you can stage the scene and then push it live.
  Grayed-out participants at the bottom are not visible, but also not audible. If you have a host &amp; a speaker, or two speakers at once, make sure to make them all visible in order to also make them audible.
  Just below the scene that is being broadcast, there are a couple of scenes to choose from. Pick webcam view of one speaker, multiple speakers, speaker &amp; screen, etc.


During the sessions, we switched scenes every once in a while, putting emphasis on the speaker, their screen, or both.

Between the two sessions, we had a break. We put up a still slide, and removed everyone from the scene. This is good &amp; bad! We could clearly show attendees we were switching speakers, but speakers could not communicate in voice because that would mean putting them on the scene &amp; broadcasting the switch.

For future live streams, we may keep talking during the session switch and not make it a real “break”. Yes, attendees may want a quick break, but those who stay around have a still image for a while.

Questions and Comments

One thing StreamYard does really well, is aggregating questions &amp; comments. We were streaming on YouTube and Facebook, and their UI showed questions, comments, and remarks from all channels. We could even show them on screen, to engage both audience &amp; speaker!

I turn on the TV and apparently we have a new channel #AZUGTV complete with its year 2000 sms chatbox. pic.twitter.com&#x2F;rdU1sw2pmY&amp;mdash; Jordi Borghers (@JordiBorghers) April 7, 2020


Like with the OBS Streaming, we found that seeding the conversation a bit helps with interactivity. If you’re ever joining a live stream, use the chat, as it’s the only connection speakers have with the audience other than their own image in the reflection of their webcam!

Conclusion

A lot of the conclusions from that previous post hold true with StreamYard as well. So I’ll focus on the good &amp; bad of our experience yesterday.

In no particular order…

StreamYard is super easy to use! Have speakers join with their browser, and go live. No need for a beefy cloud machine to run OBS Studio, just open your browser &amp; be done.

Go live and stream delays are something to be aware of. There is a ~10 second delay between speaking and your voice being heard on YouTube. If you ask people and expect a response in chat, be wary of this delay (and a potential typing delay). There is also a lag between starting the stream in StreamYard, and when it is actually live on YouTube. This can catch you out if you start speaking too soon after going live in StreamYard. Wait 5 seconds after going live before you start speaking, and be aware that stopping the stream also has a bit of a delay. Don’t go swearing immediately after ending the stream, there is a chance it will still be live.

Scene customization is a bit limited compared to OBS Studio, but I personally don’t think this is a big issue. Unless every streamer uses StreamYard &amp; the same scenes, it all looks interesting enough if you add a custom background &amp; brand color.

Screen sharing resolution could be better. If there’s one thing I hope StreamYard is focusing on (apart from scaling in these times, I would guess), it’s the screen sharing resolution. The stream is 720p, which means 1280x720 pixels. Many applications we use as developers are either unusable or butt ugly in those dimensions.

We went up to 1366x768 for one of the demo’s, which is a bit more comfortable to work in, and still legible enough in the broadcast. However, it looks just a bit too blurry for my liking, especially compared with last week’s VACD stream at 1080p.

The resolution &amp; encoding is fine for slides, but for screen sharing demo’s it could be better. It’s workable, but I hope this gets some attention.

We would use StreamYard again! Despite the screen resolution issue, we’d use it again. The ease-of-use for both hosts &amp; speakers is great! OBS Studio and that custom setup are much more customizable, but as a user group our goal is to share knowledge &amp; experiences, and StreamYard is a great tool to do that.*
<!--END_SECTION:feed-->

#### ❓ Quick bits

* **Name:** Maarten Balliauw
* **Age:** `DateTime.UtcNow.Year - 1983`
* **Gender:** male
* **Occupation:**
	* Frequent [speaker at various events](https://blog.maartenballiauw.be/talks-presentations.html) worldwide
	* Developer Advocate at [JetBrains](https://www.jetbrains.com/)
	* Founder and owner of [SpeakerTravel](https://www.speaker.travel/)
	* Former founder and owner of [MyGet](https://www.myget.org/)
* **Location:** [Antwerp](https://en.wikipedia.org/wiki/Antwerp/), [Belgium](https://en.wikipedia.org/wiki/Belgium)
* **Favourite beer:** [Westmalle Tripel](https://www.trappistwestmalle.be/en/page/tripel.aspx), [Rochefort 10](https://en.wikipedia.org/wiki/Brasserie_de_Rochefort), [La Chouffe (Achouffe)](https://en.wikipedia.org/wiki/Brasserie_d%27Achouffe)
* **Quote:** "A developer is a machine that converts coffee into code"

#### 💻 Open Source

I try to contribute to various open source projects, when time allows. Here are some examples:

* [Azure Toolkit for JetBrains Rider](https://github.com/JetBrains/azure-tools-for-intellij)
* [GoogleAnalyticsTracker](https://github.com/maartenba/GoogleAnalyticsTracker)
* [CamoDotNet](https://github.com/maartenba/CamoDotNet)
* ... and more!

Feel free to reach out to me on Twitter: [@maartenballiauw](https://twitter.com/maartenballiauw/)
