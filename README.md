# dsacks

Semi-anonymous communication keys

# Use cases

## Site registration
* generate random email (the random part is later called 'tag')
  * e.g. B07TVG9964@dsacks.cc
* all the communication to that email is forwarded to user's email
* user is able to send email from that random address
* tag is associated with the site where it was used
  * if, for example, user gets spam or promotions addressed to that tag, she can identify the source
* User's own email is never disclosed

## Drop messages
* a generated tag can be accessed online, e.g. http://dsacks.cc/B07TVG9964
  * each tag will have a permission, whether it's visible to public
  * tag can contain a user-defined message
* other users can send and receive messages on that tag

# Vocabulary
||Term|Definition|
|---|---|---|
||Tag|Unique 10-character identifier|
||DSACKS|Digital Semi-Anonymous Communication KeyS|

# Architecture
Back-end: Django, Django REST Framework
Fron-end> Vue.js, Element UI
