Feeding The Mouth That Bites: Subsidies and Secessionist Demands In Catalonia, An Experimental Method
=====================================================================================================

Dan Gamarnik

October 23, 2017

Perspectives on Computational Analysis

### Introduction

Less attention has been paid to secessionist movements in the civil
conflict literature, especially on what causes secessionist demands.
This is especially pertinent in the case of Catalonia which had a
contested referendum for independence in 2017. Specifically, I want to
ask: do changes in subsidies create secessionist demands? To test this
within Spanish Catalonia, I will use a Twitter bot, and responses to it,
in order to gauge the effect of changed perceptions of funding on
secessionist sentiment.

### Research design

#### Text analysis of social media

As categorized by [Salganik
(2017)](http://www.bitbybitbook.com/en/observing-behavior/designs/forecasting/),
this study would be considered a causal use of big data (as opposed to
predictive models) because it seeks to explain why something is
occurring and not just predict it. I plan on web scraping the users of
[Twitter](https://twitter.com/) and specifically look at their posts (or
in this case tweets). It will only observe users that are geo-located in
Catalonia.

Like a longitudinal study, this will follow the same users over time.
Using machine learning techniques, I will then code whether a specific
post is pro-independence/secession or not. With machine learning, it
will be able to recognize things like ambiguous wording, satire, and
bots which can skew normal attempts at coding. Finally, based on this
coding, I will test whether pro-secessionist demands have increased
among these users in relation to their local funding. This approach has
numerous advantages in comparison to other non-big data designs.

#### Experiment

For the experiment, I will be using a twitter bot that looks for users
who are geocoded in Catalonia and that post pro-secessionist statements
(based on the first part of the design). The bot will resemble either a
pro or anti-independence student with a realistic seeming profile
picture and twitter biography. The bot will post a reply to a
pro-secessionist user as the treatment effect. It will also use a
randomization method to separate users who are closely communicating,
that is, out of a dyad of users with a lot of replies to each other, it
will only send the reply to one of those users so it is less obvious
that it is a bot. Specifically, the message will be in Catalan, saying:

"Have you heard the rumors? Madrid will finally improve funding for
Catalonia!"

This will only be said once per user to prevent the user easily
realizing that it is a bot. Likewise, there will be a control group of
pro-secession users who will not receive the reply. These "no-message"
users will be used as a baseline for comparison. In essence, the bot's
treatment will induce a positive idea about improved funding and this
will be compared to baseline users. The hypothesis is that perceptions
of improved funding will decrease secessionist tweets. The temporal
effect of this treatment will also be measured; that is, how long, if at
all, the user reduced their pro-secessionist posts: it will observe one
day, one week, one month and four months since the treatment occurred to
see if it still has significant effect compared to the controls.
Finally, it will observe whether the users are anonymous.

This will be like the paper by [Munger
(2017)](https://link-springer-com.proxy.uchicago.edu/article/10.1007%2Fs11109-016-9373-5)
who created a bot to shame those posting racist messages on twitter. In
this case however, it will push a message of improved funding to see if
that reduces the secession sentiment. Likewise, this will control for
heterogeneous effects among the sender: there will be a pro and
anti-independence bot and the effects of both can be compared to see if
the effect still occurs from a user of the opposing ideology. This
similar to how the Munger study included both a black and white bot to
control for the effect of who sent the message.

This design is almost entirely digitally-enhanced compared to a typical
experiment. All the participants are only those who post online, they
will be randomized based on who they talk to online, their treatment is
by a bot resembling another online user and finally, their results are
measured by the differences between secessionist posting frequency.
Likewise, because of this digitized design, the costs are drastically
reduced. As mentioned by [Salganik
(2017)](http://www.bitbybitbook.com/en/running-experiments/exp-advice/zero-variable-cost/),
this kind of design should have virtually no variable cost, especially
compared to paid services like M-Turk experiments.

### Assessment

#### Heterogeneity

One issue that comes with analyzing the efficacy of this project are how
well it measures heterogeneous effects. That is, how will it will be
able to control for differences in the participants? Since there are
many kinds of people who are affected by the study, there will be
different effects not captured by the aggregate result. Here the design
is somewhat mixed in how much it is able to capture. For one, a positive
of this design is that it is able to capture the effect of
anti-secessionists pushing the message. Given the effects of groupthink,
especially for a political cause, it will be able to tell if the user is
influenced by someone they would view as an ideological opponent (who
might be sending the message for nefarious ends such as spreading rumors
to placate secessionists). Finally, it could also capture whether a user
is anonymous to adjust for whether they might be more or less
susceptible to social pressure.

However, there are many effects this design cannot capture. Because it
is based almost entirely online there is no way to verify the
demographics of the users, this can include their political views
(pro-secessionist Catalan parties represent the entire political
spectrum). However, other factors like their demographics and income
already assumed to skew wealthier given the population I am observing.
In sum, because of the things it can and cannot capture, the ability to
measure heterogeneity is somewhat mixed.

#### Causal mechanisms

An aspect where this design shines is in its ability to capture the
causal mechanisms. Since independenece is often framed in moral and
abstract terms, the ability to measure something less intuitive (like
perceptions of local funding) as a mediator for how that person feels
about secession gives a lot of insight into the cause of secessionist
claims. While this might indicate more practical and economic concerns
for Catalans, it can also imply normative ones as well. The theory
posits that secession attempts happen because a minority region lacks
fiscal benefits (that is, it pays more in taxes than it receives in
subsidies). As a salient identity group, this is seen as an affront and,
until it is corrected, leads many to want to form a separate country. In
summary, the ability to measure a change in perception and changes in
behaviors gives very good insight into the causal mechanisms of this
study.

#### Internal vs External validity

Finally, one aspect which needs to evaluated is how this study handles
the difference between internal vs external validity. Here we can think
of internal validity as how well controlled the design is to only
observe the topic of interest (funding perceptions and secessionist
sentiment) while external validity is how generalizable the experiment
is to a larger population.

Because of the focus on the current events in Catalonia, this study
prioritizes the latter over the former, gaining a lot of external
validity over internal. Under normal circumstances, people who are
politically engaged (especially on an issue in conflict with the Spanish
state) might be hesistant to say their true intentions to researchers.
Since this project does not announce it is a study to the participants,
this measures how people respond without the problem of the Hawthorne
effect, or people changing their behavior because they know they are
being observed. Likewise, since it observes people based on their
posting behavior in real-life (as opposed to a lab simulation) the
responses are highly genuine in a way they would not be in lab
conditions.

Of course, the downside is that it is likely not very internally valid
because the design cannot control for people's decisions the way it
might in a lab. Peoples' responses, while genuine, can come from all
sorts of influences that are highly heterogeneous and personal to them.
That is, people are likely by themselves on their computers or phones
and highly influenced by what is happening to them in the moment and
this can be radically different even if the responses are similar (or
vice versa). Without full lab controls such as time limits on how long
they can take to respond, it is unclear how internally valid the
conditions are. Likewise, even with randomization to decrease the
possibility of being discovered to be a bot, there are issues of
contagion such as if the "rumor" by the bots becomes viral and trends on
Twitter.

However, the benefits seem to outweigh the costs. First, If the lack of
internal validity was so radically defeating, then it is unlikely that
any significant results would be found. Given the prospect of
generalized findings, and ones which are controlled for opposing
ideology, peer contagion and anonymity, then the benefits of doing a
highly generalizable study outweigh fears of internal problems. Second,
given the sensitive political nature and possible contamination by the
Hawthorne effect, it is important to prioritize external over internal
validity. In sum, given the topic of interest, while this study makes
some large trade-offs, they are ultimately in the service of the
question.
