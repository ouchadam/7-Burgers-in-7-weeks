7 Burgers in 7 Weeks
======

###Guide 

- Buy a burger
- Take a picture of the burger
- Eat the burger
- Review the burger
- Make a burger PR to `burgerplacename/`
- Repeat until 7 of your burger conquests have been merged 


###Contributing

####Set up

 - Create a folder (if it doesn't exist already) named with the name of the burger place `burgerplacename/`
 - Create a Markdown file named like: `yourname_burgername.md`
 - Use that file to write your review.

####File format

 - The file should follow the next format: 
 
 ``` 
 Title/Burger name
 -----------------
 
 Link to burger or burger place
 
 
 ##Review
 
  - Bullet points
  - With highlights or downers
  
  
 ##Verdict
  
  Score & optional short sentence as a summary
  
  
 ##Pictures
 
  - [Add your burger pics](path_to_pictura)
  - [Might have more than one](path_to_pictura)
  
  
 ---
 
 "metadata": {
   "ubi": "burger://yourname@burgerplace:burgername/year/month/day"
 }
```


####Pictures

 Pictures should be added inside the folder `burgerplacename/` and it the name should follow something similar to this:
 
 `yourname_placename_burgername_picnumber.format`


####Metadata
 
 The metadata has a field `"ubi"` which stands for `Universal burger identifier` and it is defined as follows:
 
 `burger://yourname@burgerplace:burgername/year/month/day`
