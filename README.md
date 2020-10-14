# Auto-Swipe-2020

javascript simple script for saving time and swiping RIGHT all the time on TINDER or BUMBLE

If you want this to work: 

#Go to the script.js file and copy it
#Go to Tinder.com or Bumble.com
#Right click->inspect->console
#Paste the script.js file and hit enter, in the console
#Enjoy your date and stay safe




shortcut: 

var numba = 1;
var doshit = function(){
    document.querySelector('[aria-label="Like"]').click();
    console.log(numba);
    numba++;
    setTimeout(doshit, 100);
};
setTimeout(doshit, 100);
