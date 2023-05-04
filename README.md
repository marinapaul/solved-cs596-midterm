Download Link: https://assignmentchef.com/product/solved-cs596-midterm
<br>
<strong>Problem 1: </strong>Let V denote the space of all polynomials <em>p</em>(<em>x</em>) of order <em>up to </em>some fixed integer value <em>n</em>.

<ol>

 <li>a) Show that V is a vector space. Specify the addition and multiplication. b) Is V finite dimensional? If yes what is its dimension? c) Define a straightforward basis. d) Define at least three linear subspaces of V.</li>

 <li>e) If <em>p</em>(<em>x</em>) = <em>p</em><sub>0 </sub>+ <em>p</em><sub>1</sub><em>x </em>+ <em>p</em><sub>2</sub><em>x</em><sup>2 </sup>+ ··· + <em>p<sub>n</sub>x<sup>n </sup></em>there is a one-to-one correspondence between <em>p</em>(<em>x</em>) and the vector [<em>p</em><sub>0 </sub><em>p</em><sub>1 </sub>··<em>p<sub>n</sub></em>]<sup>| </sup>of its coefficients. Using this correspondence define an inner product for V and then use it to define a norm for polynomials of order up to <em>n</em>.</li>

</ol>

<strong>Problem 2: </strong>If <em>Q </em>is a real <em>symmetric </em>matrix of dimensions <em>k </em>× <em>k</em>, with eigenvalues <em>ρ</em><sub>1 </sub>≥ <em>ρ</em><sub>2 </sub>≥ ··· ≥ <em>ρ<sub>k</sub></em>, which are real, then we recall that we have <em>already proved </em>that for any <em>real </em>vector <em>X </em>we have

<em>.</em>

<ol>

 <li>a) Using the special eigen-decomposition of real symmetric matrices, extend the previous inequalities to <em>complex </em>vectors <em>X </em>as follows</li>

</ol>

<em>,</em>

where <em>X</em><sup>∗ </sup>denotes the conjugate of <em>X</em>. b) If <em>A </em>is a square matrix of dimensions <em>k </em>× <em>k </em>with real elements, denote with <em>λ</em><sub>1</sub><em>,…,λ<sub>k </sub></em>its eigenvalues that may be complex numbers (and the corresponding eigenvectors complex vectors) and with <em>σ</em><sub>1 </sub>≥ <em>σ</em><sub>2 </sub>≥ ··· ≥ <em>σ<sub>k </sub></em>its singular values which are real and nonnegative. Using question a) show that all eigenvalues <em>λ<sub>i </sub></em>satisfy

<em>σ</em><sub>1 </sub>≥ |<em>λ<sub>i</sub></em>| ≥ <em>σ<sub>k</sub>.</em>

<em>Hint: The σ<sub>i</sub></em><sup>2 </sup><em>are the eigenvalues of the symmetric matrix A</em><sup>|</sup><em>A</em>.

<strong>Problem 3: </strong>A square matrix <em>P </em>is called a <em>projection </em>if <em>P</em><sup>2 </sup>= <em>P</em>. a) Show that the eigenvalues of <em>P </em>are either 0 or 1. b) Show that if <em>P </em>is a projection so is <em>I </em>− <em>P </em>where <em>I </em>the identity matrix. c) If <em>P </em>is also symmetric <em>P</em><sup>| </sup>= <em>P </em>then <em>P </em>is called an <em>orthogonal projection</em>. Prove that for an orthogonal projection <em>P </em>and any vector <em>X </em>we have that <em>X </em>− <em>PX </em>and <em>PX </em>are orthogonal. d) If the two matrices <em>A,B </em>have the same dimensions <em>m </em>× <em>n </em>then show that <em>P </em>= <em>A</em>(<em>B</em><sup>|</sup><em>A</em>)<sup>−1</sup><em>B</em><sup>| </sup>is a projection matrix. What is the condition on the dimensions <em>m,n </em>and on the product <em>B</em><sup>|</sup><em>A </em>for this <em>P </em>to be well defined ? When is this matrix an orthogonal projection? e) If <em>b </em>is a fixed vector of length <em>m </em>and <sup>ˆ</sup><em>b </em>some arbitrary vector, we are interested in minimizing the square distance min<sub>ˆ<em>b </em></sub>k<em>b</em>−<sup>ˆ</sup><em>b</em>k<sup>2 </sup>where k·k is the Euclidean norm. To avoid the trivial solution we constrain

<sup>ˆ</sup><em>b </em>to satisfy <sup>ˆ</sup><em>b </em>= <em>AX </em>where <em>A </em>is a matrix of dimensions <em>m </em>× <em>n </em>with <em>m &gt; n </em>and <em>X </em>an arbitrary vector of length <em>n</em>. Show that the optimum <sup>ˆ</sup><em>b </em>is the orthogonal projection of <em>b </em>with some proper projection matrix which <em>you must identify</em>.

<strong>Problem 4: </strong>As discussed in the class, the space of all random variables constitutes a vector space. We can also define an inner product (also mentioned in class) between two random variables <em>x,y </em>using the expectation of the product

<em>&lt;x,y&gt;</em>= E[<em>xy</em>]<em>.</em>

Consider now the random variables <em>x,z,w</em>. We are interested in linear combinations of the form ˆ<em>x </em>= <em>az </em>+ <em>bw </em>where <em>a,b </em>are real deterministic quantities. a) By using the orthogonality principle find the ˆ<em>x</em><sub>∗ </sub>(equivalently the optimum coefficients <em>a</em><sub>∗</sub><em>,b</em><sub>∗</sub>) that is closest to <em>x </em>in the sense of the norm induced by the inner product. b) Compute the optimum (minimum) distance and its optimum approximation ˆ<em>x</em><sub>∗ </sub>in terms of E[<em>xz</em>]<em>,</em>E[<em>xw</em>]<em>,</em>E[<em>z</em><sup>2</sup>]<em>,</em>E[<em>zw</em>]<em>,</em>E[<em>w</em><sup>2</sup>].<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/635.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/635.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>