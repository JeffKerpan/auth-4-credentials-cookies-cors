# Credentials, Cookies, and CORS Quiz.
## Coookieee! Om Nom Nom!

### Instructions
With your partner, in words both of you will understand 6 months from now, answer the following questions.

> How would you best summarize credentials when it comes to auth?

Allows a user to keep being logged in when going back and forth between pages.
EX: Online Banking, going back and forth between accounts and pages.

> Describe how cookies are exchanged between client and server.  Make sure you touch on the technical implementation of cookies.

Cookies are stored on the client side temporarily.  The server sends an
authorization allowing the cookie to be used.

> From the perspective of a developer, name some basic strengths of using cookies and some weaknesses.

STRENGHTS:
- small
- secure
- can control how long access period is

WEAKNESES:
- session hijacking
- can be disabled
- user can delete them

> What is the difference between a session cookie and a persistant cookie?

Session cookies are deleted when the browser is closed.
Persistant cookies only expire at a specific date or after a specific length of
time.

> What is your opinion of the same-origin policy?  Support your opinion with some evidence.

Same origin policy is good for security since it places limits on data
accessibility. An example of this would be an attempted attacked by a malicious
site on a a users bank account. If the user is logged in to the bank account and
has the browser open to the malicious page, same origin policy prevents the
malware from accessing the bank account information.

Same-origin policy is good for security reasons since limiting where the user
prevents them from accessing unauthorized pages.

EX: Having a browser open with your bank account and a malicious site open on
the same browser.

> Based on what you know, how would you explain CORS?

CORS works within the same origin policy framework by providing keys which allow
one site to access data through another site. Same origin policy prevents this
interaction without special credentialing.
