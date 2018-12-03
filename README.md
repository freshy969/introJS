# introJS

A simple jQuery function which provide a tutorial kind of functionality for your web application.
It will extend your web application's capabilities and allow you to minimize the training part for your application.

# USAGE :::::::
<ul><li> Step 1: Include the introJS in your application's head/body/footer as per your framework structure. <br><pre><code>&#x3C;script src=&#x22;intro.js&#x22;&#x3E;&#x3C;/script&#x3E;</code></pre></li>
 <li>Step 2: Provide classes for your elements for which introduction is required.<br><i>Example - </i><br>
 <pre><code> &#x3C;div class=&#x22;section1&#x22;&#x3E;Section 1&#x3C;/div&#x3E;
 &#x3C;div class=&#x22;section2&#x22;&#x3E;Section 2&#x3C;/div&#x3E;
 &#x3C;div class=&#x22;section3&#x22;&#x3E;Section 3&#x3C;/div&#x3E;</code></pre></li>
 <li> Step 2: Call JS function `initiateIntro(arrOfJson,nextBtnClassName,closeBtnClassName,enableScroll)` on document load.<br>
 <i>Explaining -</i><br>
   <ol><li>There are 4 parameters for the function, as below ::</li>
   <li><i>arrOfJson - </i> You need to provide a string of json array.<br> Example::<br>
    <pre><code>&#x27;[{&#x22;class&#x22;:&#x22;section1&#x22;,&#x22;msg&#x22;:&#x22;section-1-text&#x22;},{&#x22;class&#x22;:&#x22;section2&#x22;,&#x22;msg&#x22;:&#x22;section-2-text&#x22;},{&#x22;class&#x22;:&#x22;section3&#x22;,&#x22;msg&#x22;:&#x22;section-3-text&#x22;}]&#x27;
    </code></pre>
   </li>
   <li><i>nextBtnClassName - </i> This param is used to change the CSS of the next button using your predefined class/classes. If not applicable; pass an empty string as param.</li>
   <li><i>closeBtnClassName - </i> This param is used to change the CSS of the close/done button using your predefined class/classes. If not applicable; pass an empty string as param.</li>
   <li><i>enableScroll - </i> Binary param(true/false); when an element to be introduced is off the screen/introduction area it will scroll the page until the element is visible.</li>
 </ol>
 </li>
 <li>
  Step 3: After executing the function, you will see an introduction pane. Easy Right :)
 </li>
</ul>