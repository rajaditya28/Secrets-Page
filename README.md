# Secrets-Page

https://fathomless-savannah-88442.herokuapp.com/

Secret Pages is built for people to be themselves and share anything they’re thinking and feeling with their friends without judgment. We did this by eliminating profile photos and names and by putting the emphasis entirely on the words and images being shared. This way, people are free to express themselves without holding back.

This site is highly secure and has a total of 6 levels of authentication and security starting from manual username and password method wherein we used bcrypt initially to hash and salt passwords before storing them in the database. Later on, we switched from bcrypt to PassportJS for authentication purposes and to provide users with more security of their passwords.

Finally, we have also used OAuth for sign-ins and signups using google account itself rather than manually entering the username and password.
