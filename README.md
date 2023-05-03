Download Link: https://assignmentchef.com/product/solved-cs2261-homewor4-game
<br>
<strong>Purpose:</strong>​ To build a complex game in Mode 4 to further your understanding of: double buffering, palettes in Mode 4, text, DMA, and images in Mode 4.

<strong>Instructions: </strong>

For this homework, you will create a complex game in Mode 4. The complexity expectation is the same as the last homework assignment, but this time, images are required. ​<strong>You may NOT extend a game you already made for a previous assignment; you MUST create something new. Outside of helper files (myLib.c, myLib.h, font.c, font.h, etc.), you also may not extend a previous lab to fit the requirements of this homework.</strong>

You are free to choose one of the examples we provide, but you are also free to create your own original game (​<em>if you choose this option, please speak with a TA firs</em>​t so that we can ensure it is on the expected difficulty level).

&nbsp;

&nbsp;

<strong>Requirements: </strong>

Your ​<em>game</em>​ must have the following:
<ul>
 	<li>At least ​<strong>one struct </strong></li>
 	<li>At least​<strong> one array </strong></li>
 	<li><strong>Pooling </strong></li>
 	<li>Meaningful​<strong> text </strong>
<ul>
 	<li>It needs to be relevant to the game</li>
</ul>
</li>
 	<li><strong>Non-static</strong>​ ​<strong>text </strong>
<ul>
 	<li>This means the text changes while you are looking at it (erased then redrawn)</li>
</ul>
</li>
</ul>
■ E.g. score that visibly updates during the game
<ul>
 	<li>A ​<strong>state machine</strong>​ with the following states: Start, Pause, Game, Win/lose
<ul>
 	<li>You can have a Win state, a Lose state, or both</li>
</ul>
</li>
 	<li><strong>DMA used correctly for fillScreen4(), drawRect4(), drawImage4(), and drawFullscreenImage4() </strong></li>
 	<li><strong>At least one non-fullscreen image </strong></li>
 	<li><strong>At least one fullscreen image </strong></li>
 	<li>At least five moving objects</li>
 	<li>At least three buttons used for input</li>
 	<li>Collision that matters (i.e. ​<em>something</em>​ must happen whenever two different objects hit each other)</li>
 	<li>A​<strong>txt</strong>​ file
<ul>
 	<li>An instruction manual (of sorts) that tells a player how to play your game <strong> Only a minimal amount of flicker </strong></li>
</ul>
</li>
</ul>
&nbsp;

Your ​<em>code</em>​ must have the following:
<ul>
 	<li><strong>Be entirely written in Mode 4 </strong>
<ul>
 	<li>Having the Mode 3 functions alongside the others in myLib.c is fine, as long as you ​<strong>never</strong>​ call them.</li>
</ul>
</li>
 	<li><strong>Multiple .c </strong>​files (more than just main.c and myLib.c)</li>
 	<li>At least​<strong> two .h files </strong></li>
 	<li>Good organization (see tips below)</li>
 	<li>Meaningful comments</li>
</ul>
<strong>Examples of games at the complexity level we expect:</strong>
<ul>
 	<li>Tanks</li>
 	<li>Space invaders (at least 3 rows of 5 blocks/aliens)</li>
 	<li>Simple flash games (ex. <a href="http://www.ferryhalim.com/orisinal/">http://www.ferryhalim.com/orisinal</a><u>​ </u><a href="http://www.ferryhalim.com/orisinal/">/</a><a href="http://www.ferryhalim.com/orisinal/">)</a><u>​</u></li>
 	<li>Simple Neopets games (<a href="http://www.neopets.com/games/">http://www.neopets.com/games</a><u>​ </u><a href="http://www.neopets.com/games/">/</a><a href="http://www.neopets.com/games/">)</a><u>​</u></li>
 	<li>Old Atari games, like Asteroids (<a href="http://www.freeasteroids.org/">http://www.freeasteroids.or</a><u>​ </u><a href="http://www.freeasteroids.org/">g</a>)​</li>
</ul>
&nbsp;

&nbsp;

<strong>Tips:</strong>
<ul>
 	<li><strong>Start early</strong>. Never underestimate how long it takes to make a game!​</li>
 	<li><strong>Start from scratch. Do not copy your last game’s code and change it</strong>.​</li>
 	<li>Do not draw text every frame. Text takes a while to draw, so only update it when it needs to be updated (ex: only redraw score when it has changed from the previous frame).</li>
 	<li>When splitting code between multiple files, put code that will be useful in multiple games in myLib.c, and code specific to this game in main.c or other files. Those other files should be specific to a concept (collision, etc.).</li>
 	<li>Organize your code into functions specific to what that code does. <strong>Your main</strong>​ <strong> method should not be very long.</strong>
<ul>
 	<li>Having update() and draw() functions that you call in main() is helpful.</li>
</ul>
</li>
</ul>
○ Make sure the order takes into account waiting for vblank at the correct times to minimize flicker.
<ul>
 	<li>Build upon the myLib.c and myLib.h files from previous assignments. Feel free to reach out to the TAs if you have any questions!</li>
</ul>