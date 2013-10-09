rotmg-apidoc
============

A list of methods supported by the RotMG API.



BASE URL
===
http://realmofthemadgod.appspot.com



/account/register
===
POST request

`guid` random letters or numbers

`newGUID` account email

`ignore` random number

`newPassword` account password

`isAgeVerified` value: 1


/account/setName
===
POST request

`guid` account email

`ignore` random number

`password` account password

`name` character name


/account/changePassword
===
POST request

`guid` account email

`ignore` random number

`password` account password

`newPassword` new account password


References
===
http://www.mpgh.net/forum/720-realm-mad-god-tutorials-source-code/717144-how-make-mule-really-fast.html#post8604346

http://www.mpgh.net/forum/720-realm-mad-god-tutorials-source-code/742157-change-email-via-http-just-like-account-creation.html#post8841898

http://www.mpgh.net/forum/720-realm-mad-god-tutorials-source-code/659194-multithreaded-mass-mule-password-changer-written-perl.html#post8045682
