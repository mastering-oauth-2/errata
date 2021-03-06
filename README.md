## Overview

This is the official errata for the book [*Mastering OAuth 2.0*](https://www.packtpub.com/application-development/mastering-oauth-2).

[<img src="https://www.packtpub.com/sites/default/files/5407OS_3653_Mastering%20Oauth%202.0.jpg" width="200" />](https://www.packtpub.com/application-development/mastering-oauth-2)


**Available at:**
* [Amazon.com](http://www.amazon.com/gp/product/B013T7MQNE/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B013T7MQNE&linkCode=as2&tag=charleon-20&linkId=CBTUPI5NOKI7Y6VD)
* [PacktPub.com](https://www.packtpub.com/application-development/mastering-oauth-2)

## Errata

The following is the list of errors and corrections for the book as reported by the readers:

1. Incorrect URL-encoded redirect URI
  * Location:
    * Chapter 5, Get an Access Token with the Client-Side Flow &rarr; A closer look at the implicit grant flow &rarr; Authorization request &rarr; In our application
    * Located on page 59 in print and PDF versions, and page 164 in ePub version
  * Description:
    * The URL-encoded redirect URI specified is missing a forward slash
  * Error and correction:
    * Redirect URI value is `http%3A%2F%wmiig.com%2Fcallback.html` but should be `http%3A%2F%2F%wmiig.com%2Fcallback.html`
  * Reported by:
    * John Ray Thomas ([@johnraythomas](https://github.com/johnraythomas))
