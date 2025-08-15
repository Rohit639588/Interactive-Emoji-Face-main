Interactive-Emoji-Face
Ek fun interactive web app jisme emoji ka face tumhare mouse ke movement ke saath react karta hai. Jab tum cursor move karte ho, emoji ke eyeballs uske saath move karte hain.

Features
Eyeball Movement: Emoji ke eyeballs tumhare cursor ko follow karte hain. Smooth animations aur responsive design. Simple aur maintainable code with TailwindCSS aur JavaScript.

Technologies Used
HTML CSS: TailwindCSS + custom styles JavaScript: Eyeball movement ka logic

Key Logic: Eyeball Movement
const fractionX = ((clientX / innerWidth) * 2 - 1) * maxDistance; const fractionY = ((clientY / innerHeight) * 2 - 1) * maxDistance;

1) Mouse Position Track Karna:
clientX aur clientY tumhare cursor ki exact position ko define karte hain, jo mousemove event se milti hain.

2) Normalization:
clientX / innerWidth aur clientY / innerHeight se cursor ki position ko normalize karte hain (0 se 1 ke beech). Fir, (value * 2 - 1) se mouse position ko -1 se 1 ke range mein map karte hain.

3) Scaling the Movement:
maxDistance se eyeball ki movement ko control karte hain. Example, agar maxDistance = 15px, to eyeball 15px tak move karegi.
4) Apply to Eyeballs:
Ye calculated values (fractionX aur fractionY) transform: translate() se eyeballs ki position ko change karte hain.


Features:

Dynamic emoji expressions

Smooth animations for eyes and mouth

Fully responsive design

Easy to customize


Technologies Used:

HTML5

CSS3 (animations & styling)

JavaScript (event handling & DOM manipulation)


This project is perfect for learning basic web animations, DOM events, and interactive UI elements.
