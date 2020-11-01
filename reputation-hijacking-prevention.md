# Reputation Hijacking Prevention for Web Search

Author: Dave Mackey (@davidshq)
Version: 0.0.1 11/1/2020

## Introduction
One of the primary challenges facing mediators of web content is the concerted attempts by various actors to manipulate the mediator's systems to their own advantage. The intensity and sophistication of these attacks only increase as the popularity of the mediator grows.

Various systems have been implemented to mitigate these attacks with varying levels of success. The current focus on major social media networks such as Facebook and Twitter shows the inherent difficulties involved in such systems and their as yet limited effectiveness.

In this document we will briefly address how we believe a trust network along with industry standard methods of mitigation can provide a significantly improved result for web search (and perhaps for other areas such as social networks).

## What Are Actors Attempting to Accomplish?
In order to mitigate an attack it is helpful to understand what the attacker is attempting to accomplish. In the case of mediator manipulation there are several common purposes:

### Financial Reward
Perhaps the most common inspiration for misbehavior is the pursuit of economic advantage. By manipulating the content a mediator offers and thus what is presented to it's viewers an actor can increase attention to its own products, services, or other methods of financial gain.

### Entertainment
Some actors are simply looking for a challenge, to get a laugh, to boost their reputation. They can manipulate the mediator to present humorous content or demonstrate the actor's technical skill.

### Political
Perhaps the most difficult to control are political attacks, often involving dissemination of disinformation. The end goal is to manipulate public opinion in favor of a political entity / nation / position. The difficulty in comparison to the other common purposes are:

1. Resources - Especially if a nation-state is involved, the resources can be nearly limitless. This is especially in contrast to those acting from an entertainment motive.
1. Motivation - Actors attempting to derive financial benefit require a fairly straight path from manipulation to reward. Each level of indirection (e.g. content that is not directly deriving financial reward but indirectly points towards the means of reward) increases the costs of the manipulation, eventually outweighing the potential reward. In contrast, a nation-state can shade content with disinformation which will net public opinion manipulation without levels of indirection.

## Traditional Methods of Mitigation

### Identity Verification
Most web services use a form of identity verification to ensure that users are operating within intended scope and to prevent manipulation of their services.

At a basic level this often includes requiring an email address or phone number for account creation. When tied with a validation method this ensures that the individual providing the email address or phone number actually has ownership (or at least access to) the presented account.

The protection provided by this methodology is minimal. Nothing prevents users from utilizing multiple email accounts, phone numbers, etc. and automated methods can be utilized to create new accounts quite rapidly.

More advanced verification can occur through the use of other less common, potentially more personal and rare identifiers. This includes financial accounts (e.g. credit cards), personal documents (passport, driver's license), etc.

Assuming one is able to verify that these rarer identifiers are authentic and that they are not being used across multiple accounts this can significantly improve the trustworthiness of user accounts.

However, this method is only as secure as the rarity and privateness of its identifiers. Should credit card information, personal documents, etc. be compromised and become available to actors (as has happened frequently with hacks of large corporations) the value of these identities is significantly reduced.

At this time many providers are using multiple methods of identification to validate an individual's identity. This is helpful but not fool-proof.

### Cost
One of the ways actors are able to compromise the integrity of web services is raw power. The ready availability of free email addresses, phone numbers, etc. makes the cost to create false accounts immaterial.

One of the more popular ways, especially in the blockchain ecosystem, to mitigate these attacks is to increease the economic cost of each transaction. If this were applied to email addresses, for example, one might charge $0.0001 per email sent, this would be a relatively nominal fee for most average users but significant enough to become an obstacle to malicious actors who by nature are operating at very high volumes.

The difficulty with this approach is finding the balance between frustrating malicious actors and interfering with legitimate user's behavior.

### Behavior Analysis
A third popular method is the use of automated analysis to determine problematic clusters of behavior and to take action to stop such behavior instantaneously.

For example, if a piece of content is being promoted on a mediator service the service might analyze:

1. Quality of Content - Used standard measurements the quality of writing, the likelihood of truthfulness, etc. can be derived to some extent.
1. Quality of Accounts - Whether the accounts promoting the content have shown legitimate value for the network in the past or whether they are accounts with no or little reputation.
1. Method of Spread - Whether the way in which the content is spreading is similar to that found for other historically similar/valid content.

## The Trust Network
One of the core components of our proposed web search engine is a trust network.

[Details to follow]