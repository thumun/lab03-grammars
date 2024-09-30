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
Choose a plant in the world. Working off a reference, design a grammar that mimics the structure of that plant. Unlike our simple puzzles, please use multiple rules for greater complexity. Think carefully about the structure of your grammar! EXPLAIN the structure of your plant in the README. What are the components? What do each of the rules do? Be sure to also include images of a few iterations of your output plant. 

<p>
  Kelp (at iter: 4)
  
  <img src=""/>

Axiom is FX. So, F is done first; then, the X rule happens on top. 


Rule 1: It starts by drawing a forward line, then the angle is shifted by 10, and the state is saved. Inside the brackets, the angle is shifted, and a line is drawn; then, the angle is shifted again, and a line is drawn. The angle is shifted in the opposite direction, and a line is drawn (this happens twice). Then we go back to the old state and shift the angle in the negative direction, then draw once more, and then the angle is shifted with the state being saved. Inside the saved state, the angle is shifted once and drawn twice (so it looks longer). Finally, we go back to the old state, draw a line, and add a rotation to the end of it. 

will adjust above for readability

Since all the angle shifts and new line drawings only happen on the right side, the little kelp forest is aligned towards the right (similar to real-life kelp forests- or at least similar to my image reference). 

Rule 2: This just draws two lines going up. So, in iteration one, the top looks taller. 

In all honesty, I got this by messing around and trying stuff out. The second rule is rather simple here since I wanted larger stems—like how kelp forests look. The actual 'leaves' are constructed with rule 1.

  <img src=""/>
</p>


<p>
  Pine Branch (at iter: 4)
  
  <img src=""/>

Since my first plant had a pretty simple Rule 2, I tried to go for a more complicated one and ended up with a pine needle-looking thing. 

Axiom is FX. So, F is done first; then, the X rule happens on top. 


Rule 1: I used the previous Rule 1 as a base and added different angle shifts so the plant branches off in both the left and right directions. (As seen in iter 1) 

Rule 2: will add

I got this by messing around and trying stuff out, in all honesty. The second rule is rather simple here since I wanted larger stems - like how kelp forests look. And the actual 'leaves' are constructed with rule 1.

  <img src=""/>
</p>

## Submission
- Create a pull request against this repository
- In your readme, list your solutions and format your README nicely
- Profit
