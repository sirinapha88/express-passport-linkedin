# express-passport-linkedin

Objectives
There are two main goals for this lesson: to get familiar with Passport, and to hone your documentation interaction abilities. Note "documentation interaction" - not "reading documentation". Documentation is rarely a step-by-step tutorial. Instead, it's an active process of knowing what to look for, seeking it out, pattern matching and only pulling in the few lines necessary to satisfy the errors you are getting.

By the end of this lesson, you should be able to:

Describe and explain OAuth and it's role in web authentication (content)
Carefully read error messages generated from framework code and reason through possible causes based on current knowledge of Express
Use targeted searches in documentation to answer specific questions or inform hypothesis
use CMD+F on web pages
Keep track of where you were on notecards, so you can maintain your place even when you have to solve smaller problems
You do not need to memorize every step in this document. Using framework code is all about combining what you know with your critical thinking skills and targeted documentation searches. Most of this lesson is about non-cognitive behaviors.

OAuth (content)
The basic OAuth2 web flow is:



Some guiding questions are:

How does Google / Facebook / LinkedIn etc... communicate with your local web app during development? Isn't that private (aka not published on the internet)??
What part of your existing authentication / authorization flows does this replace?
Why would you want to authenticate with Google / Facebook instead of storing the emails / passwords yourself?
Resources:

https://developer.linkedin.com/docs/oauth2
https://github.com/auth0/passport-linkedin-oauth2
http://passportjs.org/docs
http://passportjs.org/docs/configure#configure
https://apigee.com/console/linkedin
http://docs.mongodb.org/manual/reference/method/db.collection.update/#db.collection.update

Heroku App link
https://serene-badlands-4447.herokuapp.com/
