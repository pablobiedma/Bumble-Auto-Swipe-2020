# Tinder-Auto-Swipe-2020
javascript simple script for saving time and swiping RIGHT all the time 

If you want this to work: 

#Go to the script.js file and copy it
#Go to Tinder.com
#Right click->inspect->console
#Paste the script.js file and hit enter, in the console
#Enjoy your date and stay safe




shortcut: 

x = setInterval(
  function(){
   var elem = document.getElementsByClassName("recsGamepad__button--like");
   elem[0].click()
  },200)
