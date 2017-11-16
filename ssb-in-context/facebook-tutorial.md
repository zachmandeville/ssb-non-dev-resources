## Centralization vs. Decentralization: Facebook Example

# Introduction

A core aspect of Scuttlebutt is that we are decentralized, meaning we don't rely on any central
server. This aspect is deeply important to our community, as we believe decentralized systems will
help bring a more optimistic and equal future.  This aspect also makes Scuttlebutt markedly
different from the internet, as most sites and services there are centralized.

This centralized design is not obvious.  Web developers want their sites to be simple and
accessible, so the technical processes that power them are hidden in the background. But the
technical side has a profound affect on what is and is not possible online, as well as the level of
influence these sites have upon your general life. 

To better understand what makes Scuttlebutt different, it's good to know how exactly a centralized
system works.  So let's take a look at how something simple, like sending a personal message, works
with a centralized model.  Specifically, let's take a look at how it'd work on Facebook.  And to be
even more specific, let's say it’s a message to your grandma.

A quick note: There's an absurd amount that happens behind the scenes when you do anything online,
more than I could cover in a 10 minute read.  This article is meant to explain the fundamental
essence of a centralized site, and so some complexities are simplified into their basic conceptual
model. It’s sorta like how the phrase "It’s raining outside" should not be considered a definitive
description of weather, but still gets a necessary point across.   

And so, let’s get to the point!


**How to Send a Facebook Message to your Grandma: a Step-by-Step Guide**

**The Setup:** It's a Thursday afternoon, and you realize you haven't talked to your grandma in
a while. You know your grandma's bookclub meets on Wednesdays, and so you come up with the
(incredible) idea of sending her the message: "Hey Grandma, how are you!  How was book club
yesterday?"

**You open up your computer and head to *www.facebook.com**

-At this moment, the first key technical process occurs.  Which is that your computer requests some
information from the server that holds Facebook.  The words 'facebook.com' are an address for where,
within the vast network of the internet, this server broadcasts itself, but the server is actually
a physical _thing_ living somewhere in the real world.  Since Facebook (the site) is huge , it's
server must be huge too-- rows upon stacks upon rows of simultaneously running computers, all housed
in a giant warehouse situated in the middle of nowhere so Facebook can save on real estate costs.
This warehouse will likely be near some natural body of water, like a river. The server is
receiving, storing, and sending everyone’s messages at once, which causes it to get get _hot_. By
diverting water from the river, Facebook has a natural, inexpensive coolant, a grand version of the
icepack you place beneath your computer when you want to watch a movie and use photoshop at the same
time.

When you access Facebook on the browser, your computer sends a request to this idyllic riverside
monolith, which responds by showing you the data on its server it would like you to see. In this
case, it's the homepage.  Because the internet is awesome and powerful, this transaction happens
near instantaneously.  But what's important to remember is that your computer is _viewing_ the data
that makes up the site, but it is not holding it.  All of it is still living  on the distant server.
It's like when you video chat with someone: you can see their nice face and messy room, but their
face and room are not alive inside your computer.  When you go onto their site, Facebook lets you
view your photos, friends, memories, and posts, without you holding any of them yourself.

**You log into your FB account**

The server holds all the data about Facebook; not just your Facebook, the entirety of the site from
back when it was `thefacebook`.  To make managing their data easier, FB will optimize how it's
stored, how it's organized, and how the server should access it. But this efficiency is designed to
help computers and servers, and so the information that makes up facebook, when viewed as just data
on a hard drive, would likely make very little sense to you. There would not be a folder called
"You!" that held all your stuff, and placed neatly beside folders called "Your Friend!" and "Your
Grandma!". Instead, the entire site is a folded up, byzantine jumble of efficiency. -

Facebook creates _the illusion_ of order through the metaphor of a user account.  User accounts give
filtered views into the data, so you only see things relevant to you. To ensure your unique view
cannot be seen by other users,  they let you assign your username a password, so your partitioned
view is specific to a login (or at least to whomever knows your login). This information about
usernames and passwords _also_ lives on Facebook's server, in its own database.  This is why you may
have your _classic_ nickname that everyone knows you by, but when you try to choose that as
a username, Facebook tells you it's already taken.  The server had scanned the database of all
Facebook names to see if the one you asked for already exists in some row.  Since it does, it asks
if you'd prefer to use "ClassicNicknameEveryoneKnowsMeBy2". If you choose that, it'll then add your
new nickname as a new row to the database. 

The essential point  is that your personal, protected Facebook account is a metaphor, designed to
give you a feeling of security and a personalized, filtered view into your data.  These accounts
protect your view from being seen by other users, and protect Facebook's private company data from
being seen by you.  User accounts are effective metaphors, and provide a great user experience, but
do not reflect how your data is being physically held and processed.  In reality, the server is
holding your memories, friends and photos in a big cyber stew of everyone’s friends, memories and
photos.  From this view, things like “private messages” or “closed groups” don’t really mean
anything. This is because the structure and rules of your data is designed for Facebook's servers,
and not for you.   

**You open a Private Message Window, add your Grandma as the recipient, and write her your message.**

When you click the send button on your private message, it doesn't actually send it to yourgrandma.
Instead, it sends it to Facebook's server with a request for them to please give your Grandma access
to it.  Facebook stores your message in their database, and then decides whether or not they pass it
along. 

Giving Facebook this responsibility has some benefits.  For example: if your grandmother blocked
you, for some reason, then Facebook would not send your message.  Or, if you weren't friends with
your Grandma yet, then Facebook wouldn't send it directly to her, instead placing it in her 'other'
inbox so she doesn’t get too much non-friend spam. In most cases, they'll send your message as you
asked and do it so quickly you don't realize this exchange took place, but on a technical level, the
delivery of your private message is a decision Facebook gets to make, and you don't have any say in
the matter.
	      
There's quite a lot that happens when you add your message to Facebook’s server, besides it being
eventually sent to your grandma.  This is a partial summary of some of the decisions and processes
that take place. 

First, a package is sent from your computer to Facebook's server, where it will now reside. This
package says:
    - I would like to send a message to my grandma.
    - I want this message to be private.
    - here are the contents: "Hi! Grandma, how was book club yesterday?"

Facebook parses the entirety of the message, the context of it withinyour relationship to your
grandma, and the conclusions it can draw from the exchange.  Then it uses all these things to make
some money.

This isn't necessarily evil.  Facebook _needs_ to make money to keep its server running, as that’s
what keeps the site online. Since all of Facebook.com lives on this, it gets expensive: There's the
price of the warehouse, the cost of the actual physical devices holding the information, the staff
maintaining this hardware, the staff continually working on the software to keep it technically
updated and secure, and the staff handling the upkeep of the space itself.  There’s also all the
people working in some way for Facebook(the company), and they need to get paid too. 

Facebook chose advertising, essentially, as their business model.  They sell ad space, like many
sites do.  What makes Facebook powerful, though, is that they can offer targeted ad space--in other
words, they give advertisers the ability to reach the right people with the right things at the
right time.  Facebook does this by accumulating as much data as possible from you and your social
connections, from which they build a highly specific customer profile of you.  They can then sell
the ad space of your specific partition to the companies that want to target your profile.  This
helps the companies make sure their marketing budget is bringing in the highest return on
investment.

Since all Facebook activity is stored within a central server, Facebook is able to make some
stunning connections and conclusions from the data available to them — connections you may not see. 

For example,  they quickly parse your message and conclude that the specific user account you chose
as the message recipient is your grandma, which puts her in a generational demographic.  They also
know you submitted the message on a Thursday, but asked about a book club that happened yesterday.
So they know your grandma has a regular book club on Wednesdays.  Next, they look at all your
grandma's other private messages, and find several from someone named Victor who always messages her
"Sorry, i'm going to be late! Should I bring anything?" at 12:30 pm on Wednesday.  They find several
other friends writing "what a great time!" around 4 pm.  So they conclude that the book club is
likely happening from 1 to 3 and that Victor is a member.  In addition, they have a small
personality sketch of Victor.  

As they have all of Victor's other data, they can read through any of his private or public
messages. They find a private message from December asking how he likes his new iPhone. They also
find a public message from him exclaiming "So much to do, and not enough time!" further solidifying
his customer profile.  

All of this culminates next Wednesday morning, when an advertisement for Audible.com is placed on
Victor's Facebook feed.  Facebook knows he'll be going to a book club, is always pressed for time,
has an iPhone, and would probably be susceptible to signing up for some audio books.  They could
even use data they're pulling from other sites they maintain a presence on (usually through a like
or share button).  For example, they could see Victor bought a specific mystery thriller from Amazon
that your grandma also bought, determine it's a _mystery_ book club the two of them are in, and
adjust the book featured in the Audible advertisement so it’s even more persuasive. 

In this way, a message you sent to your grandma is used to adjust and target the ads for someone you
may have never met.  This also helps explain the eerie phenomenon where you are talking in-person
about some upcoming trip that you've never talked about online, and the next day see an add for that
destination on your facebook feed.  This could happen because Facebook has bugged your phone and is
listening in on your conversations, or it’s because your friends are talking about you on Facebook
and not telling you. The truth to this paranoia is known only by Facebook.

With all of the social connections and content you've shared on their network, Facebook has compiled
highly detailed dossier on who you are. This dossier is useful to sell you things, but they found
that the dossier itself can be sold to interested parties.  Often, these parties aren't doing any
marketing at all.

One known party is law enforcement.  Security companies have built software intended to help police
find criminals before they've even committed a crime. They do this by pulling in as much data from
social networks as possible, comparing the conversations and activities of the larger population
against people who have been arrested for crimes, and through this determine what sort of social
traits criminals share.

What this means is that your inquiry about your grandma's bookclub might fit a trait for people
arrested for drug possession, and so when you submit your message you are privately tagged with the
labels "grandchild" and "likely drug offender"   Or, you may already be on the list of likely drug
offender, and so your question to your grandma is added to the list of traits these potential
criminals may share.  Or the opposite could be true, and your broader Facebook activity put you into
a "law-abider" category.  In this case, your activity helps flesh out the "law abider" profile and
by extension the "likely criminal" profile. These profiles are then fed into a computer program that
tells your local police to go knock on someone's door and "check in", because that person didn't
write to their grandma this Thursday, and that seems "suspicious".

While this example seems absurd, it is just this sort of small connection/large conclusion that is
the heart of "big data" analysis. Big Data is powered by a near-mystic belief that, by grabbing as
much data as possible and sorting it in as many ways as possible, compelling patterns will emerge
and these patterns can predict behaviors and futures.  

All of this data, the targeted adspace, the endless dossiers on who you are — these are worth a lot
of money to a broad set of people.  And through selling the data that you generate, Facebook keeps
their servers online, letting them log valuable information on you plus everything else they want to
do.  It is how their service stays  both free and incredibly profitable.

**Your Grandma receives the message**

Now thoroughly vetted, Facebook has the responsibility to send your message to your grandma.  But
they may choose a couple different routes, which--since it's on their servers--they have the right
to do.  

If your grandma is on Facebook often, they may decide to show it to her the next time she logs in,
but they'll do so after some random amount of time, to make logging on feel more appealing.

It's exciting when you have a new notification. It gives you a quick dopamine thrill like seeing
a package in front of your door. Facebook knows this, and knows that this makes their service
addicting, so they try to accentuate this rush as much as possible. So your grandma might sign on
and see nothing in the notification bar for nearly a second, before a bright red '1' appears. Since
she's on the site often, she'll naturally learn that there is this delay, but since it's random she
won't be able to predict how long the delay will be.   And so the act of logging on and waiting for
a notification will become a thrilling game of chance, similar to a slot machine.  

If she isn't on the site much, then Facebook may use your message to try to get her back.  They've
already read its contents, and know that you're her grandchild, and assume that messages from family
are great leverage for converting someone back into a user.  They also likely have her email and
phone number on file, as they asked for both when she signed up.  So they will send her an email
with a brief message like "your grandchild wants to talk to you" with a link to get directly into
facebook.  If that doesn't work, they may send a text message with something more  direct like
"click this to log into facebook right away."  In either case, the link they provide will have
a reference token to your message, so if she does log on they'll know that _you_ are the reason why.
They will then subtly alter her newsfeed so that your posts show up more often, since you’ve talked
recently and she must be interested in how you are doing.

Since user data is their main source of income, they need their users on their site as much as
possible.  Even if your grandma wants to take a social media break, it is in Facebook's best
interest to win her back as quickly as possible, and get her addicted as completely as possible.
Your message acts as that addicting hook. In a way, this helps you too, since them selling the fact
that you can influence your grandma helps keep their servers online, and the servers are required
for you to send the message at all.

**Messages are Read and everyone's happy**

In centralized systems, the company and it's servers acts as the intermediary for all activity.
There is no way for you to send a message directly to your grandma on facebook.  By design, Facebook
has to intercept, store, and send the message for you.

In this example scenario your grandma receives the message, Victor signs up for Audible, the cops
have a potential new arrest, and everyone is happy.  But there are a couple ways this could have
gone wrong, due to it being a centralized model.

For one, the server that holds your message could have gone down.  Since it’s a physical object, the
reason could be as simple as the device getting unplugged.  Since the data centers holding the
servers are so huge, they need to be placed in strategic geographic areas, which makes the system
far more fragile than we realize.  There have been incidents where, for example, a farmer
accidentally plows right through a remote server cable in their field, and the farmer accidentally
causes a large portion of the internet to go down for hours.  There have been other cases where an
employee in charge of maintaining the server forgets some crucial step, and causes a software mishap
that shuts down another part of the internet.  These scenarios don't happen often, but are
a necessary risk within centralized systems.

Alternately, Facebook may find their income model doesn't work and they go out of business.  Since
they own the servers, and the data you've placed within them, if they go out of business, then your
messages disappear with them.  Most likely, Facebook would tell you they're shutting down, and offer
a way for you to export all your photos, stories, and memories.  This is a nicety though, and one
that they do not have to offer.  They may not get the chance to do this nicety, either.  For
example, two news sites (DNAinfo and TheGothamist) were recently shut down without notice by their
owner because he disagreed with the staff wanting to unionize.  In this case, he pulled them offline
so quickly that no professional contributor was able to retrieve the work they had published.
Resumes and portfolios were full of dead links and lack of proof, because of the learned assumption
to rely on a “data cloud”, which is another metaphor intended to hide servers from your view.
Fortunately, the personal data you store on Facebook is worth a lot of money, and Mark Zuckerberg
has promised that he is very nice, so it isn’t likely that they’ll remove your photos anytime soon.

However, Facebook may also determine that you are not a good fit for their site and block your
access to it.  Since access to your account is a metaphor they created, they can easily and legally
do this.  In that case, your old information would still live and be sold on the server, but be
inaccessible by you. In extreme cases, a government may decide that Facebook (or its servers) must
be shut down, due to some profound shift in power.  In that case, policy-abiding users would have
little say.

**Conclusion**

A centralized system like Facebook offers you a way to stay in touch with friends and loved ones. As
you can see, the way you do so is pretty simple, though with a few unexpected steps. A decentralized
model lets you send messages and stay in touch too, but without the need for a central server, and
all the hidden costs and companies that requires.  




