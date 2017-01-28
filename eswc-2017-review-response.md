

Dear Sarven,

Thank you for your submission to ESWC 2017. The ESWC 2017
review response period will be between now and Sunday 5th February 2017, midnight Hawaii time.

During this time, you will have access to the current state of
your reviews and have the opportunity to submit a response of
up to 1000 words. Please keep in mind the following during this
process:

* The response must focus on any factual errors in the reviews
and any questions posed by the reviewers. It must not provide
new research results or reformulate the presentation. Try to be
as concise and to the point as possible.

* The review response period is an opportunity to react to the
reviews, but not a requirement to do so. Thus, if you feel the
reviews are accurate and the reviewers have not asked any
questions, then you do not have to respond.

* The reviews are as submitted by the PC members, without any
coordination between them. Thus, there may be inconsistencies.
Furthermore, these are not the final versions of the reviews.
The reviews can later be updated to take into account the
discussions at the program committee meeting, and we may find
it necessary to solicit other outside reviews after the review
response period.

* The program committee will read your responses carefully and
take this information into account during the discussions. On
the other hand, the program committee will not directly respond
to your responses, either before the program committee meeting
or in the final versions of the reviews.

* Your response will be seen by all PC members who have access
to the discussion of your paper, so please try to be polite and
constructive.

The reviews on your paper are attached to this letter. To
submit your response you should log on the EasyChair Web page
for ESWC 2017 and select your submission on the menu.

----------------------- REVIEW 1 ---------------------
PAPER: 29
TITLE: Linked Data Notifications
AUTHORS: Sarven Capadisli, Amy Guy, Christoph Lange, Sören Auer and Tim Berners-Lee

Overall evaluation: 2

----------- Overall evaluation -----------
The article presents the Linked Data Notifications (LDN) protocol, a candidate W3C recommendation, and how it relates to similar notification protocols. Starting with requirements based on Linked Data design principles and the need for re-decentralisation of the Web the article makes a structured comparison of notification mechanisms today and discusses the various implementations of LDN.

This is an architecture type of article in which the requirements and design considerations (section 3) are the base on which the rest of the contribution is built; naturally, some of those requirements are based on opinion but this is exactly the kind of topic to present at ESWC to foster fruitful discussion. For example, the requirement for reusability could be seen as a potential risk for privacy; what is the benefit of reusable notifications to balance that risk? Who would benefit the most from this principle (users, application developers, other) and in what way? A similar discussion could be made for R3 (persistence and retrievability).

It would help if those requirements were discussed a little more in the paper and if they could be placed more clearly in the wider framework/paradigm of Web re-decentralisation (including stakeholders) to give a sense of ‘completeness’ when it comes to notification protocols.

One final point is that certain references (e.g. [3] do not seem to be cited in the text).

----------------------- REVIEW 2 ---------------------
PAPER: 29
TITLE: Linked Data Notifications
AUTHORS: Sarven Capadisli, Amy Guy, Christoph Lange, Sören Auer and Tim Berners-Lee

Overall evaluation: 3

----------- Overall evaluation -----------
LDNs provide an important mechanism for the current effort (as described in the paper) to re-decentralise the web. The paper is well written. It describes the motivation for LDNs, gives examples and compares LDNs to related efforts.

I have only minor comments:

1) one may add in section 2 "related work" a mention of atomPub https://tools.ietf.org/html/draft-snell-atompub-notification-01 , and add this also to table 2 "comparison of notification mechanisms"

2) for the standardisation process of LDNs this may not be crucial, but one may want to examine benchmarks for notification processing. This could help to evaluate different LDNs applications in terms of their performance. This criterion may become critical during broad adoption,  with billions of notifications generated every day.

----------------------- REVIEW 3 ---------------------
PAPER: 29
TITLE: Linked Data Notifications
AUTHORS: Sarven Capadisli, Amy Guy, Christoph Lange, Sören Auer and Tim Berners-Lee

Overall evaluation: 2

----------- Overall evaluation -----------
This paper presents a communication protocol for Linked Data Notifications, reusable messages on the Web that follow the Linked Data principles.

The paper is generally well written and easy to follow. The authors motivate their work well and provide a detailed description of the protocol and its implementations.

Strong points:
==============
- The requirements for the protocol are well established.
- The protocol itself is well formalised and described.
- Existence of a number of implementations, both standalone ones and the ones developed previously to the LDN.
- Protocol flexibility and the compatibility with the Linked Data Platform.
- The work is quite relevant.

Weak points:
============
- The lack of a real evaluation. Section 6, although titled "Analysis and Evaluation", is actually a comprehensive analysis and discussion of various aspects of the presented work. Section 6.1 is the closest to the evaluation of the work, however the level of details in this section is not satisfactory in that regard. The authors could maybe extend this section with an in depth analysis of the differences between their work and other system that are mentioned, and a discussion on why these differences are important and how LDN provides improvements over them. 


Other comments:
==============

In the abstract, the authors state: "This permits end users more freedom to switch between the online tools they use, as well as generating greater value when notifications from different sources can be used in combination." Maybe it would be interesting if the authors could mention a few use cases of this added value in a separate section as a strong point for the motivation of the work.

In my opinion, the definition of notification is quite broad and not very clear ("A notification is a retrievable resource which returns RDF"). Is my URI a notification? A URI of an ontology class?
Further explanation perhaps clarifies a bit, but the whole context should be clear in the first sentence.

The interaction steps between consumer and receiver (Section 4.2) might be a bit confusing to the reader. Does step (3) always follow step (2), e.g., the consumer first asks for the listing of notifications and then choses one to retrieve, or it is possible to have only one of the two steps before step (4), e.g., the consumer decides whether it is interested in the listing, or individual notification, or perhaps both.
Also, in my opinion comparing to Section 4.1, the steps in Section 4.2 are described with less detail and rigour.

In Section 5 the authors state: "We note that any LDP implementation is a conforming LDN receiver; we refer here to the ones we have tested". Maybe the authors could mention the reasons why other LDP implementations are not tested, or how they have chosen the implementations that are tested.

The figures in Section 5 are not very readable in the printed version. I understand that the online version of the article reads better, but the authors should maybe consider improving the representations in printed form.

The conclusions section presents only a summary of the paper. But what are the conclusions? Are there any limitations of the presented work and if so which ones? Is there any future work planned?

Not all figures and tables are referenced in the text, I would suggest the authors to include these references.

Reference [3] is not referenced in the text.

In my opinion, the references section could be improved. For example, conference and workshop abbreviations could be extended, exact workshops mentioned (e.g., in [9]). Furthermore, links are omitted in the printed version of the paper which makes the section strange and it is not clear what is the type of the work that is referenced (e.g., conference, technical report, web article, technical specification)

----------------------- REVIEW 4 ---------------------
PAPER: 29
TITLE: Linked Data Notifications
AUTHORS: Sarven Capadisli, Amy Guy, Christoph Lange, Sören Auer and Tim Berners-Lee

Overall evaluation: 1

----------- Overall evaluation -----------
The paper is well written  and mostly understandable, though it might be a good idea to rephrase some of the explanation in the section on Requirements and Design Considerations, specifically R4-B, which is confusing and not easy to understand. 

I would also like more clarity on the following:

1. Performance metrics to measure how well the protocol performs in practice.
2. The most interesting part of the protocol is the (re)use of the received notification by the consumers. The paper should include explicit justification with concrete examples on why an application (consumer) would want to use an outdated notification exposed by some receiver. Most obvious examples are blog posts etc, but that seems to be the only obvious use case. It is also worth thinking about how a service like stack overflow can be re-purposed using LDN and what would be the benefits.

It is also easy to see why a formal semantics for the protocol would make sense. Apart from getting implementations to conform to a test suite, it is worth getting them to conform to a formal semantics specification. This is something that the authors should 
make a part of their future work.

I also see the evaluation as being quite limited, as there is no user-driven evaluation result that have been reported. While it is still early days for the protocol, without a clear idea of what it means for the consumers and how much it contributes to improving the overall data integration for a specific use-case or domain, it is hard to see the utility of implementing this as part of a larger system.

------------------------------------------------------

Many Thanks!
The ESWC 2017 PC Chairs and Track Chairs.
