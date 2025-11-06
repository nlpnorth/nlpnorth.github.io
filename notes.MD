# Notes for website maintenance
I'll put some minor things in here in order to make it easier for people to see when something weird changed.


## Custom Viewbox in Bluesky Icon
I changed the viewbox from `viewBox="0 0 640 640"` to `viewBox="96 96 448 448"`in order to get rid of the padding.
Otherwise, the logo will be smaller than the one from twitter. I have an LLM-generated explonation for the numbers.
Basically, nothing is drawn outside of a box from 96 to 544, which is a WxL of 448. 
Just note that when you add an icon from fontawesome with padding, that may need adjustment as well if it's smaller 
