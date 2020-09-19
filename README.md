# JS30CSS-JS-Clock
Tutorial #2 from Wes Bos JavaScript 30


# JS30 CSS-JS-CLOCK
Excorcise 02 in WesBos' JavaScript30 tutorials. 

The exorcise itself was fairly simple, I appreciated Wes' attempt to have us instantly implement the code that ws just demonstrated via the seccondsHand and attempte to create the minuteHand and hourHands JS code on our own. 

In this tutorial I learned how to manipulate the Date() method, and strengthened my use of JS to add/remove CSS classes as needed. It took me about 30minutes to get rid of the ugly rewind/reset of the secondHand every time it hit a new minute via an if/else statement as hinted at by Wes.
<Code>
 if (seconds == 0) {
    secondHand.classList.add('noTransition') //removes the transition effect so that the second hand transitions smoothly instead of resets & rewinds. 
 } else {
    secondHand.classList.remove('noTransition')
 }
</code>

As mentioned in my JS30 exorcise 01, I had recently come across the process of using JS to alter CSS classes when applying for a position that had me re-create a site. 
<br><a href="https://github.com/NikRowe/NickGameSite-MaterializeCSS"> Git Here </a> and <a href="https://nickalodeongamesite.netlify.app/"> Demo Here </a> if interested.<br>
Which I absolutely love, this to me is a simple form of the "wizardry" of JS. 
