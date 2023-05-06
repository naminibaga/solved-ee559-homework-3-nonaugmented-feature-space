Download Link: https://assignmentchef.com/product/solved-ee559-homework-3-nonaugmented-feature-space
<br>
<ol>

 <li>In discussion we derived an expression for the signed distance <em>d</em> between an arbitrary point <em><u>x</u></em> (or <em><sub> </sub><u>p</u></em>) and a hyperplane H given by <em><sub> </sub></em><em><sup>g</sup></em>(<em><u><sup>x</sup></u></em>)= <em><sup>w</sup></em><sub>0 </sub>+ <em><u>w</u></em><em><sup>T </sup><u>x </u></em>= 0 , all in <em>nonaugmented</em> feature space.  This question explores this topic further.

  <ul>

   <li>Prove that the weight vector <em><u>w</u></em> is normal to H.</li>

  </ul></li>

</ol>

<strong>Hint:</strong>  For any two points <em> <u>x</u></em><sub>1</sub>and <em><u>x</u></em><sub>2</sub> on H, what is <em><sub> </sub>g</em>(<em><u>x</u></em><sub>1</sub>)− <em>g</em>(<em><u>x</u></em><sub>2</sub>)?  How can you interpret the vector <em> </em>(<em><u>x</u></em><sub>1</sub>− <em><u>x</u></em><sub>2</sub>) ?

<ul>

 <li>Show that the vector <em><u>w</u></em> points to the positive side of H.  (Positive side of H means the <em> d </em>&gt; 0)</li>

</ul>

<strong>Hint:</strong>  What sign does the distance <em>d</em> from H to <em> <u>x </u></em><sup>=</sup>(<em><u>x</u></em><sub>1</sub>+ <em>a<u>w</u></em>) have, in which <em><sub> </sub><u>x</u></em><sub>1</sub> is a point on H?

<ul>

 <li>Derive, or state and justify, an expression for the signed distance <em>r</em> between an arbitrary point <em><u>x</u></em><sup>(</sup><sup>+</sup><sup>)</sup> and a hyperplane <em><sub> </sub>g</em>(<em><u>x</u></em><sup>(</sup><sup>+</sup><sup>)</sup>)= <em><u>w</u></em><sup>(</sup><sup>+</sup><sup>)<em>T </em></sup><em><u>x</u></em><sup>(</sup><sup>+</sup><sup>) </sup>= 0 in <em>augmented</em> feature space.  Set up the sign of your distance so that <em><sub> </sub></em><em><u>w</u></em> points to the positive-distance side of H.</li>

 <li>In <em>weight</em> space, using augmented quantities, derive an expression for the signed distance between an arbitrary point <em><u>w</u></em><sup>(</sup><sup>+</sup><sup>)</sup> and a hyperplane <em><sub> </sub>g</em>(<em><u>x</u></em><sup>(</sup><sup>+</sup><sup>)</sup>)= <em><u>w</u></em><sup>(</sup><sup>+</sup><sup>)<em>T </em></sup><em><u>x</u></em><sup>(</sup><sup>+</sup><sup>) </sup>= 0 , in</li>

</ul>

which the vector <em><sub> </sub></em><em><u><sup>x</sup></u></em><sup>(</sup><sup>+)</sup> defines the positive side of the hyperplane.




<ol start="2">

 <li>For a 2-class learning problem with one feature, you are given four training data points (in augmented space):</li>

</ol>

<em><u>x</u></em><sub>1</sub>(<sup>1</sup><sup>) </sup>=(1,−3); <em><u>x</u></em><sub>2</sub>(<sup>1</sup><sup>) </sup>=(1,−5); <em><u>x</u></em><sub>3</sub>(<sup>2</sup><sup>) </sup>=(1,1); <em><u>x</u></em><sub>4</sub>(<sup>2</sup><sup>) </sup>=(1,−1)

<ul>

 <li>Plot the data points in 2D feature space. Draw a linear decision boundary <strong>H</strong> that correctly classifies them, showing which side is positive.</li>

 <li>Plot the reflected data points in 2D feature space. Draw the same decision boundary; does it still classify them correctly?</li>

 <li>Plot the reflected data points, as lines in 2D weight space, showing the positive side of each. Show the solution region.</li>

 <li>Also, plot the weight vector <em><u>w</u></em> of <strong>H</strong> from part (a) as a point in weight space.  Is <em><sub> </sub></em><em><u>w</u></em> in the solution region?</li>

</ul>




<ol start="3">

 <li>(a) Let <em>p</em>(<em><u>x</u></em>) be a scalar function of a <em>D</em>-dimensional vector <em><sub> </sub></em><em><u>x </u></em>,  and <em><sub> </sub></em><em><sup>f </sup></em>( <em><sup>p</sup></em>) be a scalar function of <em>p</em>.  Prove that:</li>

 <li>1 of 2</li>

</ol>

<em>  </em>⎣         ⎦

<em>i.e.</em>, prove that the chain rule applies in this way.  [<strong>Hint:</strong>  you can show it for the <em>i</em><sup>th</sup> component of the gradient vector, for any <em>i</em>.  It can be done in a couple lines.]

<ul>

 <li>Use relation (18) of DHS A.2.4 to find ∇<em><u><sub>x</sub></u></em>(<em><u>x</u><sup>T </sup><u>x</u></em>).</li>

</ul>

<em><sub> </sub></em>

<ul>

 <li>Prove your result of ∇<em><u><sub>x</sub></u></em>(<em><u>x</u><sup>T </sup><u>x</u></em>) in part (b) by, instead, writing out the components.</li>

</ul>

⎡( <em>T </em>)3⎤

<ul>

 <li>Use (a) and (b) to find ∇<em><u><sub>x</sub></u></em>⎢ <em><u>x x </u></em>⎥ in terms of <em><u>x </u></em>.</li>

</ul>

<em>      </em>⎣            ⎦




<ol start="4">

 <li>(a) Use relations above to find  <em> </em>∇<em><u><sub>w </sub>w </u></em><sub>2</sub> .  Express your answer in terms of <em><sub> </sub><u>w </u></em><sub>2</sub> where</li>

</ol>

possible.  <strong>Hint:</strong>   let <em><sub> </sub>p </em>= <em><u>w</u><sup>T</sup><u>w</u></em>;  what is <em><sub> </sub></em><em>f</em> ?

(b)                Find:  <em> </em>∇<em><u><sub>w </sub></u>Mw</em>− <em>b </em><sub>2</sub>.  Express your result in simplest form.  <strong>Hint:</strong>  first choose <em>p</em>

(remember it must be a scalar).




<ol start="5">

 <li><strong>[Extra credit]</strong> For <em> C </em>&gt; 2 , show that total linear separability implies linear separability, and show that linear separability doesn’t necessarily imply total linear separability.  For the latter, a counterexample will suffice.</li>

</ol>





