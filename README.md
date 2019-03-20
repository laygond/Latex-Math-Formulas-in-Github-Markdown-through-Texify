# Latex Math Formulas in Markdown through Texify 
Just install this https://github.com/apps/texify save your file with extension *.tex.md and that's it!!

## Explanation
For example take the following code block and place it in between **\$**. 
```
y_i& \approx \beta_0 + \beta_1 x_{i1} + .. + \beta_N x_{iN}
```
it will become this next time you git push:
<img src="/tex/d35243df38441b543a6da16df1f2f46f.svg?invert_in_darkmode&sanitize=true" align=middle width=207.07912004999997pt height=22.831056599999986pt/>

**NOTE:** I noticed that the next time you git push you will be prompted to git pull to save locally those images that were created by the app in the folder tex.

**TIP:** If something goes wrong delete the tex folder locally and then `git push -f` to force the push and evade the git pull. Then go back to git pull / git push convention.  

# More Examples:
```
||\mathbf{x}||_2 = \sqrt{x_1^2 + x_2^2 +...+ x_n^2}
```
<img src="/tex/59c927018141d66e182ddf8afebf26f7.svg?invert_in_darkmode&sanitize=true" align=middle width=199.82646584999998pt height=29.899755600000006pt/>

```
||\mathbf{x}||_2^2 = \displaystyle\sum_{i=1}^n x_i^2 =\mathbf{x}^T \cdot \mathbf{x}
```
<img src="/tex/39dff840fdbb7e37d2ff6935fd797547.svg?invert_in_darkmode&sanitize=true" align=middle width=164.88698655pt height=51.0047109pt/>

The sum of squares of `\mathbf{x}` is denoted by `||\mathbf{x}||_2^2`

The sum of squares of <img src="/tex/b0ea07dc5c00127344a1cad40467b8de.svg?invert_in_darkmode&sanitize=true" align=middle width=9.97711604999999pt height=14.611878600000017pt/> is denoted by <img src="/tex/a550d0130762075f3d4377778db5e35f.svg?invert_in_darkmode&sanitize=true" align=middle width=34.79455814999999pt height=26.76175259999998pt/>
