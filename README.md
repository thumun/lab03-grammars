# lab03-grammars
Let's practice using grammars! For this lab, please pull up the L-system node in Houdini.

## 1. Wheat grammar puzzle
Look at these iterations (n = 1, 2, 3) of a one-rule grammar. Using the built in symbols in Houdini, design a grammar that produces this output. Take a screenshot of your rules.\
<img width="200" alt="square1" src="https://user-images.githubusercontent.com/1758825/193949661-a3a0e1f7-7d68-4b9e-8384-d9991e1e9fd2.png">
<img width="200" alt="square2" src="https://user-images.githubusercontent.com/1758825/193949853-cf2306b3-3537-4c24-91b5-0a3083bc87c0.png">
<img width="200" alt="square3" src="https://user-images.githubusercontent.com/1758825/193949859-5e432b4b-f18d-48b5-a9e9-8d7dba255955.png">

Rules:
<p>
  <img src="https://github.com/thumun/lab03-grammars/blob/main/Screenshot%202024-09-30%20135454.png?raw=true" />
</p>

## 2. Square grammar puzzle
How about this one? Take a screenshot of your rules.\
<img width="200" alt="square1" src="https://user-images.githubusercontent.com/1758825/193949895-87cdfb43-da7c-4867-ab1b-107e1ba9d2a7.png">
<img width="200" alt="square2" src="https://user-images.githubusercontent.com/1758825/193949904-a9cdfe0f-319e-4ca8-9935-dd338217a7cf.png">
<img width="200" alt="square3" src="https://user-images.githubusercontent.com/1758825/193949910-928e5993-ce26-4681-80f8-ffeb54be4dcf.png">

Rules:
<p>
  <img src="https://github.com/thumun/lab03-grammars/blob/main/Screenshot%202024-09-30%20114240.png?raw=true" />
</p>

## 3. Custom plant

Fern! 
<p> 
(This was a bit simple) 

<code> Axiom: F, Angle 45 </code>

This draws the F rule. 

<code> Rule1: F=G[C1-F][C1+F]G[C2-F][C2+F]G[C3-F][C3+F]GF </code>

This rule creates the stem and the branching out part of the fern. I decided to make 3 branches-if there were more I ran out of memory : ( (And it adds some colors based on what level is drawn!) 

<code> Rule2: G=GG </code>

This rule extends the 'G' portions by a factor of two - thus creating some degree of separation.

Iteration 1: 
<img src="https://github.com/thumun/lab03-grammars/blob/main/fern1.png?raw=true" /> 

Iteration 3: 
<img src="https://github.com/thumun/lab03-grammars/blob/main/fern3.png?raw=true" /> 

Iteration 5: 
<img src="https://github.com/thumun/lab03-grammars/blob/main/fern5.png?raw=true" /> 

</p>

Japanese Woodblock Print Inspired Trees 
<p> 

<code> Axiom: FX, Angle 30 </code>

This draws the F rule and then the X on top. 

<code> Rule1: F=FF-[-FF-FF+FF+F]+F-[-FFF]F+ </code>

This rule creates two branches: one that's more crooked and one that's a straight line. It also extends the trunk.

<code> Rule2: X=FF-[-F]+[+F] </code>

This rule creates a Y-like shape on top of the ending of the previous rule. This spaces out the branches of the tree more and creates a more abstract/random effect. (Which makes the tree look more natural and it has a similar shape as you would see in wood block prints : ) 

Iteration 1: 
<img src="https://github.com/thumun/lab03-grammars/blob/main/wood1.png?raw=true" /> 

Iteration 3: 
<img src="https://github.com/thumun/lab03-grammars/blob/main/wood3.png?raw=true" /> 

Iteration 5: 
<img src="https://github.com/thumun/lab03-grammars/blob/main/wood5.png?raw=true" /> 

</p>

## Submission
- Create a pull request against this repository
- In your readme, list your solutions and format your README nicely
- Profit
