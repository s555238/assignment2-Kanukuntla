# assignment2-Kanukuntla
# Sumanth Reddy Kanukuntla
###### Birla Science Museum -Hyderabad
B. M. Birla Science Museum is an Indian science museum located in Hyderabad, India. Constructed by civil engineer P. A. Singaravelu, it comprises a **planetarium, museum, science centre, art gallery as well as a dinosaurium**. The museum itself was the second phase of the science centre when it opened in 1990.The centre also houses India's first private Space Museum. **The museum is a unique facility which is dedicated to history of the space program of India**.The space museum was inaugurated in July 2019 and was curated by Pranav Sharma.

- - -
# directions from airport to musem
Rajiv Gandhi International airport
1. Head east on Airport Approach Road toward Cargo Rotary
2. At Cargo Rotary, take the 3rd exit and stay on Airport Approach Road
3. 	Keep right at the fork pass by Hotel Dsr International
4. Continue straight pass by Yes Bawarchi Multi Cuisine Restauranr
5. Continue straight onto NH 44
6. Turn left onto Nagarguda - Shamshabad Rd/Rallaguda Rd
7. Turn right pass by Sri Ganesh Hardware (on the left in 300 m)
8. Keep right to continue on NH 44
9. Keep right to stay on NH 44 pass by the lake
10. Turn right after St Nirankari Satsang Bhawan
11. Turn left onto Naubat Pahad Ln

- Birla Mandir
- LB Stadium
- Secretariat
- Shahi Masjid
- Tank Bund

[AboutMefile](AboutMe.md)

- - -
# Cities Table
Four Indian Cities I would recommed to see.
| City Name | Places to Visit | Visiting hours of the locations |
| --- | --- | --- |
| Hyderabad |  Charminar | 1 Hours |
| Chennai | Mahabalipuram | 2 Hours |
| Kerala | Munnar | 5 hours |
| Banglore | Banglore Place | 4 Hours |

- - -
# Motivational Quotes
>  " life is like moving bicycle .To keep balance, you must keep moving" *-Albert Einstein*

> "Don't find fault, find a remedy" *-Henry Ford*

- - - 
# stack over flow 
> To get my last tweet in PHP I use this code :
[Getting last tweet with PHP](https://stackoverflow.com/questions/6416815/getting-last-tweet-with-php)

```
<?php

function getTwitterStatus($userid){
$url = "https://api.twitter.com/1/statuses/user_timeline/$userid.xml?count=1&include_rts=1callback=?";

$xml = simplexml_load_file($url) or die("could not connect");

       foreach($xml->status as $status){
       $text = $status->text;
       }
       echo $text;
 }

// USAGE
getTwitterStatus("chriscoyier");
```
[Get Latest Twitter Status](https://css-tricks.com/snippets/php/get-latest-twitter-status/)
