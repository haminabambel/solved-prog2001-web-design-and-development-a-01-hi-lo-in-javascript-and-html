Download Link: https://assignmentchef.com/product/solved-prog2001-web-design-and-development-a-01-hi-lo-in-javascript-and-html
<br>
<h1>OVERVIEW</h1>

You will write an application as part of an HTML file that will play a typical <strong><em><u>Hi-Lo</u></em></strong> game, where the player guesses values in a specific range until the correct number is found.

This is an individual assignment and must be completed on your own.

<h1>OBJECTIVES</h1>

This assignment supports the following course objectives:

<ul>

 <li>To practice writing HTML and JavaScript functions</li>

 <li>To use some of the events supported by the Document Object Model</li>

 <li>Become familiar with client-side validation and feedback techniques</li>

</ul>

<h1>EVALUATION</h1>

<ul>

 <li>Please refer to the assignment weighting in the <em>Instructional Plan</em> for the course as well as the assignment’s Rubric in the course shell.</li>

</ul>

<h1>PREPARATION</h1>

Review Module-01 and Module-02 lesson content and also the Module-02 code samples – they will help you in this assignment.




<h1>REQUIREMENTS <em> </em></h1>

<ol>

 <li>The entire application must be written in <strong><u>one HTML page</u></strong> using only JavaScript and HTML.</li>

 <li>Call this web page <strong>html</strong></li>

 <li>Do not use any <u>external</u> CSS styling. This assignment is not about creating and using CSS.  But if you do want to experiment with styles, define the style in the &lt;HEAD&gt; element or use in-line styles</li>

 <li>When the page initially loads, the application should present a user prompt asking for the player’s name. This prompt should be accompanied by a text box.

  <ol>

   <li>The player’s name is mandatory and therefore cannot be blank – it can contain any non-blank characters.</li>

   <li>An informative error message will be displayed for the user if they attempt to enter a blank name.</li>

  </ol></li>

 <li>After the name is entered, the application shall hide the name prompt and will show a prompt to the user (using the user’s name) to enter the <em>maximum guess</em> number

  <ol>

   <li>The application will only allow the user to enter an integer number and will ensure the value greater than 1. (the only real limit is the limit of an integer)</li>

   <li>If any input other than this is given, then an informative error message must be presented</li>

  </ol></li>

 <li>Your Hi-Lo application must create a <em>random integer</em> between 1 and the <em>maximum guess</em> number</li>

 <li>At this point in the application, the <em>maximum guess</em> number prompt should be hidden as you enter the main runtime (<em>guessing</em>) UI of the application.</li>

 <li>The following must be components of the main <em>runtime</em> UI:

  <ol>

   <li>A prompt asking the user (by name) to guess a number. This prompt must consist of a textbox to allow the user to enter a new guess at the random number.  [NOTE: <u>Do not use</u> the JavaScript prompt() function]</li>

   <li>A button to submit the guess labeled as “<strong>Make this Guess</strong>”</li>

   <li>A message that informs the user about their allowable guessing range

    <ol start="10">

     <li>For example, let’s say the user enters 10 as their maximum number – your initial message would read “Your allowable guessing range is any value between 1 and 10.”</li>

     <li>If the random number your code generated was 7 and the user guesses 5, then after submitting their guess the message would change to “Your allowable guessing range is any value between 6 and 10”</li>

    </ol></li>

  </ol></li>

</ol>

<ul>

 <li>This message must be present in the resultant HTML – do not use the</li>

</ul>

JavaScript alert() function or any other pop-up messaging scheme

<ol>

 <li>If the user happens to enter a <u>number</u> outside of the allowable range – your logic needs to inform them of this and also simply restate your allowable guessing range message

  <ol>

   <li>For example, let’s say the allowable guessing range is between 6 and 10 and the user enters the value 44 or -10 … since they are number values, it’s allowed – tell them it is outside of the allowable range and simply remind them of the guessing range</li>

  </ol></li>

 <li>During the game, if the user enters anything but a number, I expect your Hi-Lo game to remind the user that they need to enter a number – so display some kind of error message to that effect as well as the allowable guessing range message</li>

 <li>When the user’s guess is correct, change the background colour of the page, hide the (main) guessing portion of the UI and show a message on the screen saying “You Win!! You guessed the number!!”

  <ol>

   <li>There should be no remnants of the main <em>guessing</em> prompt and/or messages</li>

   <li>At this point, show a “Play Again” button and reset your page to do it again</li>

  </ol></li>

</ol>

<ul>

 <li>Only this time you don’t need to prompt the user for their name – but you should prompt them for a new <em>maximum number</em>.</li>

</ul>

<ol start="9">

 <li>Make sure that all data entered is validated for proper data type and in some cases proper data ranges/values

  <ol>

   <li>Remember that the objective of the code is to create a workable Hi-Lo game</li>

   <li>Also remember that giving the user timely feedback is a mandated usability factor</li>

  </ol></li>

 <li>The application should also only ever have one user prompt visible on the screen at a time</li>

 <li>Make sure to comment your solution appropriately – HTML header comment, JavaScript function comment blocks as well as inline comments</li>

 <li>Ensure that your Hi-Lo application runs properly and consistently within the Internet Explorer (v11) and Chrome browsers.</li>

</ol>




<h1>FILE NAMING REQUIREMENTS</h1>

As mentioned above in the Requirements, the solution for this assignment must be developed and delivered in <u>one (1) HTML page</u>.  Ensure that you name this HTML file “<strong>a01.html</strong>”.

<h1>SUBMISSION REQUIREMENTS</h1>

When submitting your single HTML page to the drop-box, <strong>please ZIP it up first</strong>.  If you submit your HTML file (unzipped) to the drop-box, eConestoga may edit/adjust/alter your HTML source.  Upload your ZIP’d solution to the appropriate drop-box by the deadline.