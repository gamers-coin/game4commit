Game4commit FAQ
===============

What is Game4commit?
--------------------
Game4commit is a website where people raise funds for any kind of project.

Anyone can start collecting funds in a few clicks. You just have to explain what you're going to do with the funds and why people can trust you.

People can easily donate to the projects they want to support by sending cryptocurrencies. The fundraiser can then distribute the funds to the people who make the project happen.


How is it different than other crowdfunding sites?
--------------------------------------------------
On Game4commit the fundraiser is not expected to do the actual work. His job is to collect funds and distribute them to the people who work on the project. He may for example reward commits on an open source project or pay a lobbyist.


Why?
----
The goal is give the initiative to the people, and not only to those who are able to achieve projects.

For example imagine you want a feature in an open source software but the developers don't care about it and you can't implement it yourself. You can start a project on Game4commit to make it happen. If you get enough funds you can pay someone to implement the feature. There are many freelance developers and companies who will be happy to do that for you.

Or imagine you favorite band has given up. You can raise funds to pay them to work on a new album.


Why give control to a fundraiser and not directly to the people?
----------------------------------------------------------------

Giving direct control to multiple persons is a complex task with no ideal solution. For example are decisions made at the majority? Is there a quorum? Can people vote for multiple choices? Are votes proportional to the amount you gave?

And there is a big risk. For example if all decisions are made proportional to the amount given, then someone can easily take over the funds by sending more than everybody else. He can then send the whole funds to himself.

So we decided all these choices will be made by the fundraiser. He can start a project where he decides everything as a benevolent dictator, but he can also create more democratic projects where important decisions will be taken at the majority among choices he selects.

The fundraiser will also have the responsibility of deciding what can and cannot be changed. For example the main goal of the project is not likely to change. Even if you give a small amount and have an insignificant weight in the decisions you can rest assured that your money will still be used for the same goal. Someone who gave 90% of the funds won't be able to change that.


Why use Game4commit and not send funds directly to the fundraiser?
------------------------------------------------------------------

Game4commit provides tools to the donors and the fundraisers.

The donors can browse the fundraiser history: what projects he managed, how he distributed funds, what comments he received, etc. The fundraisers are forced to distribute the funds through Game4commit so that anyone can see the details. For example if the fundraiser decided to send money to a GitHub account, then the GitHub account name will be displayed, not only the payment address.

The fundraisers have tools to easily distribute money. They can for example send funds to an email address. Game4commit will take charge of getting payment information from the owner of this email address. They can also send funds to a GitHub users or to the author of a particular commit. More options will be added later (sending to a Reddit user, to a forum member, etc.).

We also provide tools to identify donors. When they donate they can provide a address. This address can be used whenever Game4commit, the fundraiser or anyone wants to identify a donor. Anyone able to sign with this address will be considered the sender of the associated money. This can be used to return the funds, to organize votes, to send rewards, etc.


Can I trust the fundraisers?
----------------------------

Not blindly. You should do some researches before you give money.

For example the fact a project has a lot of donations is not an indication that many people trust the fundraiser. He may have sent the money himself.

Game4commit provides some tools to help you check the fundraiser. We keep track of all the projects he managed and all the funds he distributed. You can browse that and see how he managed previous projects. Anyone can comment the projects, distributions and users so if he did something wrong then there are good chances he received bad comments.

The fundraiser should also explain in the project description why you can trust him. If he doesn't do that you should be skeptical. Then you'll have to evaluate what he says. It's particularly important to check the identity of the fundraiser. He should provide proofs he really is who he claims to be.

But an important point is that the fundraisers will actually compete on trust. Since anyone can raise funds a big part of the difference will be made on trustworthiness.

Some other skills may be important too. For example the project may require some technical skills to evaluate the work made by others. You should ensure the fundraiser has these abilities.

Refund
------
When you make a donation you explicitly give to the fundraiser the full control of the money you send. He may have committed himself to refund the donations under certain circumstances but you still need to evaluate whether you can trust him on that.

When you donate Game4commit asks you for a return address. This address will be used if the fundraiser wants to send funds back to you. It may also be used for other things where you need to prove you are the sender (a vote, a reward, etc.). All the donation addresses will be displayed publicly so you should use a newly generated address without history. And you must keep the associated private key in a safe place.

Does it work?
-------------

Game4commit is still young but yes. Some projects were successfully managed.

We initially started as a [tip4commit](http://tip4commit.com/) clone where GitHub commits were automatically rewarded 1% of the balance. We moved recently to the more generic system described here.

Examples of successful projects:
* [Game4commit](http://game4commit.gamers-coin.org/projects/8) itself
* [Gamerscoin Website](http://game4commit.gamers-coin.org/projects/17)
* [Gamerscoin Steam Tip Bot](http://game4commit.gamers-coin.org/projects/21)

Currency
--------

For now the only supported currency is [Gamerscoin](http://gamers-coin.org).
Gamerscoin is the 1st Free Open Source Revolutionary Digital Gaming Currency sent through the internet.
Gamerscoin focus on Video games,Esport and Digital Gaming Goods.
Created by Gamers Controlled by Gamers. A new currency made by gamers for Gamers and GameDevs are you prepared ?


How can I raise funds?
----------------------

Click on the <%= link_to '"Create a project"', new_project_path %> button. You'll have to fill a detailed description. Here are some recommendations:

* State the main goal of your game4commit project, and decide what can and cannot be changed for the project. The main goal cannot be changed.
* Provide your identity and convince donators why they should trust you.
* Decide and state if you will be a benevolent dictator (more efficient), or create a more democratic project (finer control for stakeholders).
* Describe your techical skills and other relevant qualifications if they are needed to evaluate the work made by others.
* State policy of tipping for potential developers. Use other projects as templates or references.

The project will be visible on Game4commit but it will not be particularly highlighted. You will have to communicate about it, that's part of your job.


Can fundraisers get paid for their work?
----------------------------------------

Yes. A fundraisers can send money to himself for his raising and distributing jobs. He can also reward himself to do actual work. That's up to him.

Fundraisers should explain in the project description whether they intend to pay themselves and how much.


How can I get paid to do the actual work?
-----------------------------------------

Check the policies of the projects. Fundraiser can chose to raise bounty or a specific percentage of the donated funds for specific tasks or assign a percentage of the fund for commits in case of a development. If unclear ask the fundraiser. Disputes should be resolved between the developer and the fundraiser.
We automatically parse github for new commits.
Project Admin Decide the tip amounts.
--------------------
![](http://i.imgur.com/ISHzHRJ.png)

Auto Payout Sample :
--------------------
![](http://i.imgur.com/OFuiTIV.png)


How do I Push my Commits?
-------------------------
Getting write access to the "Master" of a project involves that the project maintainer provides access to you in Github. This type of access would only be given to people trusted by the maintainer. If you already have write access to the project, just push your commits to the default branch of the project as usual. Otherwise, you'll have to fork the project (i.e. Start your own project based on the supported project), make some changes and create a pull request to propose your changes. If your pull request is accepted (Merged), you'll receive one tip per commit. If the changes are simple enough, you can do them in your browser by editing the files on GitHub. Otherwise, you'll have to use Git to clone your fork, make some changes, commit them and push the commits to GitHub. You can find a lot of information about that on GitHub help and on the web.


Make Sure You Read the Project Charter & Tipping Policies Before Starting
-------------------------------------------------------------------------
Project maintainers can refuse your commits for several reasons. It is important to read the "Charter" of the project on its GitHub page, which usually provides guidance on which commits and under what rules they would be accepted. For example, there are very strict rules for contributing to the official Gamerscoin project. A good way to ensure the maintainer is willing to merge your changes is to first create an issue explaining what you're going to do and ask if they would merge a pull request. Wait for an answer before starting. 

How do I donate to a project I like?
------------------------------------
Browse the project list and click on the "Donate" button. You will be asked for a personal address that will be used if Game4commit or the fundraiser ever needs to identify you. Then Game4commit will give you an address to which you just have to send Gamecoins. 99% of your donation will be available to the fundraiser. 1% will be kept to host Game4commit and pay the transaction fees.

You can also donate without providing an address. But the fundraiser won't be able to return you the funds if he ever wants to. And if the fundraiser organizes a vote or send rewards, you won't be able to participate.
![](http://i.imgur.com/wapUvKy.png)

What's going to happen next?
----------------------------
There are many features planed. Their achievement depends on the willingness of donors, fundraisers and developers.

### Multi-signature
The most important imminent change is the introduction of multi-signature donation addresses:

When you donate, your money will be sent to a multi-signature address:
* 1 key will be owned by Game4commit,
* 1 key will be owned by the fundraiser and
* 1 key will be owned by yourself (if you want to).

And 2 keys will be required to use the funds.

To distribute coins the fundraiser will use the website and fill some forms. The website will generate a transaction and ask the fundraiser to provide a signature for it. Then the website will sign the transaction too and propagate it.

So if the website is hacked the funds can't be stolen. And the fundraiser cannot spend the funds outside the website. 

Also if a fundraiser is clearly misbehaving the website and the supporter can decide to return the funds. If the website itself is misbehaving (a very bad policy change, abandoned, hacked...) the fundraiser and the supporter can decide to move the funds elsewhere.

### Decentralization
Game4commit can probably run completely decentralized, maybe on its own blockchain, maybe as a [Gameshares](http://gameshares.net/) implementation. But this will require a lot of thoughts. For now we focus on more practical things, but decentralization is certainly an ultimate goal.

Multi-signature will already be a big step toward decentralization.

### Other
We will also improve the various tools provided by the website:
* add new recipients the fundraisers can distribute funds to: all the people involved in a GitHub issue, another Game4commit project, a Reddit user, etc.
* project categorization, tags, sorting, filtering, etc.
* browsing the history of projects (description changes, distribution changes, etc). The data are already there but just not displayed.
* etc.

We may also add some kind of discussion boards, unless the community thinks this is better kept externalized.


What measures have been taken to secure the funds on Game4commit?
-----------------------------------------------------------------
The project funds are isolated in different accounts in the wallet, so if someone ever finds a way to distribute more funds than the project balance, Gamecoin will not take the funds from another project and will refuse the transaction. Projects with a high balance have a part of its funds moved to cold storage. The website runs in an isolated virtual server running only this service. There's an <%= link_to "audit page", audit_path %> that shows the status of all project accounts.

When multisignatures are implemented Game4commit will not have direct the control over the funds (see above).

