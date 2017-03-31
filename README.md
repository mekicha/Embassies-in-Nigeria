# Embassies-in-Nigeria

## About
--------
This is a json formatted document containing all the embassies in Nigeria, their addresses and contact details.
The original data for this comes from the guys at [hotels.ng](https://hotels.ng/travel/list-embassies-nigeria/) 
who did the good job of putting the list together. So, all the credits go to them for that. And it is fair that they
should take all the blame too for any misinformation :). Just kidding!

The document has been validated using the json validator at [code beautify](http://codebeautify.org/jsonvalidator).

## What use is it?
------------------
Not much in practical terms, if you ask me. But I put it together because I hope it can be a good resource for teaching, for
instance.
I can imagine it will be a good source of data for teaching data manipulation in a no-sql database like Mongodb, or even objects
and arrays in general. Especially with things having to do with searching.
A few sample questions I can think of:
1. Find all the embassies that are located in more than one city.
2. Find all the embassies in Abuja that are in Maitama, or Asokoro.
3. Find embassies that do not have websites listed. This is particularly interesting because armed with that information,
an ambitious web developer can give them a call and pitch the idea of creating one for them:)
4. etc

Another practical application would be to use put all the embassies on a map, and visually show how close they are to each other, using
the google maps api or some similar api. Now, I hope to add a script that does this sometime later.

## Improvements/Suggestions
-------------------------
The first improvement I would like to make to the document as it is would be to make the phones and fax field array fields. At the moment,
they are comma separated string fields for those having more than one number.

Any other suggestions/improvements are welcome. Feel free to send a PR if there's something I have missed.

Thanks again to the hotels.ng guys!



