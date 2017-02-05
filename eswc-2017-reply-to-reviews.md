This document is a reply to eswc-2017-review-response.md

The information here will be made available at
http://csarven.ca/linked-data-notifications


## Review 1

>the requirement for reusability could be seen as a potential risk for privacy;
what is the benefit of reusable notifications to balance that risk? Who would
benefit the most from this principle (users, application developers, other) and
in what way?

Once fetched by a 3rd-party, any piece of information could potentially be
subject to privacy. This is whether the notifications are ephemeral or
persistent. In R4-C, we briefly touch on various authentication methods which
could be used alongside LDN with the idea that notifications are not necessarily
public but only visible or reusable by intended parties. The receivers decide
(based on their use case) which consumers (based on any criteria) can reuse.
They achieve this by setting authentication and authorization settings on the
notifications.

>It would help if those requirements were discussed a little more in the paper
>and if they could be placed more clearly in the wider framework/paradigm of Web
>re-decentralisation (including stakeholders) to give a sense of ‘completeness’
>when it comes to notification protocols.

We've updated the article to make the role of authn/authz more clear.

>One final point is that certain references (e.g. [3] do not seem to be cited in
>the text).

Fixed reference [3].


## Review 2


## Review 3


## Review 4
