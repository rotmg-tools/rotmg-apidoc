rotmg-apidoc
============

rotmg api documentation



BASE URI
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


account/changePassword
===
POST request

`guid` account email

`ignore` random number

`password` account password

`newPassword` new account password
