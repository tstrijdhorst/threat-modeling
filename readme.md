Making security decisions is hard. There are often plenty of unknowns and scary emotions, yet you have to make an efficient and rational decision about real world problems.
Defining explicit threat scenarios can help you think about these problems in a systematic way.

_Note: This is a flow of working with a specific threat scenario. If you are looking for ways to threat model an entire system (i.e identifying sets of threat scenarios) there are other systems for that. You can start [here](https://owasp.org/www-community/Application_Threat_Modeling)_

Key Points to take home:

* Security is based on risk assessment. Risk is a combination of `the chance that something happens` multiplied by `the impact when something happens`.
* There is no such thing as perfect security, which means you cannot safeguard yourself against every threat. Accept this.
* Resources are limited, security responses have costs, choose wisely.

# Modeling a threat scenario

## General outline

* [Identify the treat](#Identify-the-threat)
* [Identify a potential response](#Identify-a-potential-response)
* [Determine effectiveness](#Determine-effectiveness)
* [Cost/Benefit ratio](#costbenefit-ratio)
* [If necessary rinse & repeat](#rinse--repeat)

_Note: to any of the questions below you can always answer __unknown__. However, what does it tell you that this is unknown?_  
_Note: accepting the risk (i.e do nothing) is also a valid response and will necessarily be the answer to many threats._

## Identify the threat

To get a good idea of the threat, you can use these questions to evaluate:

* What is the vulnerability?
* Who is the threat actor, i.e who is going to exploit this and what is their motivation?
* What is the damage if the vulnerability is exploited? (impact)
* How easy is it to launch an attack? (chance of it happening)

## Identify a potential response

Is the risk of the described scenario acceptable? If so __do nothing__.

If not, how can you make sure the above described scenario doesn't happen?

* Describe the response with enough detail to have a clear idea of how it works (if this is not possible, take a mental note of that and describe all the available details).

## Determine effectiveness

* Does the response counter the threat completely (i.e chance of it happening is reduced to 0)? If not, reidentify the threat from a perspective where the response is in place. Is this level of risk acceptable?

## Cost/Benefit ratio

Security almost always has costs, if not directly monetary then it will most probably make the user experience harder, in terms of time consumption or cognitive load.

* How much monetary resources do we have to invest directly into this response?
* How does the response affect user experience and other non-monetary resources?

* How do these costs measure up against the risk of the threat?

## Rinse & Repeat

If you feel the cost/benefit ratio of your chosen response is not favorable, try to identify and analyse a different response.

