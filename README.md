Download Link: https://assignmentchef.com/product/solved-cuny605-assignment1
<br>
You can think of vectors representing many dimensions of related information. For instance, Netflix might store all the ratings a user gives to movies in a vector. This is clearly a vector of very large dimensions (in the millions) and very sparse as the user might have rated only a few movies. Similarly, Amazon might store the items purchased by a user in a vector, with each slot or dimension representing a unique product and the value of the slot, the number of such items the user bought. One task that is frequently done in these settings is to find similarities between users. And, we can use dot-product between vectors to do just that. As you know, the dot-product is proportional to the length of two vectors and to the angle between them. In fact, the dot-product between two vectors, normalized by their lengths is called as the cosine distance and is frequently used in recommendation engines.

<ul>

 <li>Calculate the dot product <em>v </em>where <em>u </em>= [0<em>.</em>5;0<em>.</em>5] and <em>v </em>= [3;−4]</li>

 <li>What are the lengths of <em>u </em>and <em>v</em>? Please note that the mathematical notion of the length of a vector is not the same as a computer science definition.</li>

 <li>What is the linear combination: 3<em>u </em>− 2<em>v</em>?</li>

 <li>What is the angle between <em>u </em>and <em>v</em></li>

</ul>

You can use R-markdown to submit your responses to this problem set. If you decide to do it in paper, then please either scan it or take a picture using a smartphone and attach that picture. Please make sure that the picture is legible before submitting.

<ol start="2">

 <li>Problem set 2</li>

</ol>

Set up a system of equations with 3 variables and 3 constraints and solve for x. Please write a function in R that will take two variables (matrix A &amp; constraint vector b) and solve using elimination. Your function should produce the right answer for the system of equations for any 3-variable, 3-equation system. You don’t have to worry about degenerate cases and can safely assume that the function will only be tested with a system of equations that has a solution. Please note that you do have to worry about zero pivots, though. Please note that you should not use the built-in function <strong>solve </strong>to solve this system or use matrix inverses. The approach that you should employ is to construct an Upper Triangular Matrix and then back-substitute to get the solution. Alternatively, you can augment the matrix A with vector b and jointly apply the Gauss Jordan elimination procedure.

1

<h1>2                                    IS 605 FUNDAMENTALS OF COMPUTATIONAL MATHEMATICS – FALL 2014</h1>

Please test it with the system below and it should produce a solution <em>x </em>= [−1<em>.</em>55<em>,</em>−0<em>.</em>32<em>,</em>0<em>.</em>95]

(1)

Please send your code (as an R-markdown file, named using your first initial, last name, assignment, problem set. For instance, if I submit the code for this assignment, it will be called <strong>GIyengar Assign1.Rmd</strong>