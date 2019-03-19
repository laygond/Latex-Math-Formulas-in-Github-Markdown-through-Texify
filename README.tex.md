# Latex Math Formulas in Markdown through Texify 
Just install this https://github.com/apps/texify save your file with extension *.tex.md and that's it!!

## Explanation
For example take the following code block and place it in between. 

\mathbf{x} = \\begin{bmatrix} x_1\\ x_2\\ \\vdots\\ x_n \\end{bmatrix}

it will become this next time you git push:
$\mathbf{x} = \begin{bmatrix}
                x_1\\
                x_2\\
                \vdots\\
                x_n
\end{bmatrix}$

**NOTE:** I noticed that the next time you git push you will be prompted to git pull to save locally those images that were created by the app in the folder tex.

**TIP:** If something goes wrong delete the tex folder locally and then `git push -f` to force the push and evade the git pull. Then go back to git pull / git push convention.  

# More Examples:
```
||\mathbf{x}||_2 = \sqrt{x_1^2 + x_2^2 +...+ x_n^2}
```
$||\mathbf{x}||_2 = \sqrt{x_1^2 + x_2^2 +...+ x_n^2}$

```
||\mathbf{x}||_2^2 = \displaystyle\sum_{i=1}^n x_i^2 =\mathbf{x}^T \cdot \mathbf{x}
```
$||\mathbf{x}||_2^2 = \displaystyle\sum_{i=1}^n x_i^2 =\mathbf{x}^T \cdot \mathbf{x}$

The sum of squares of `\mathbf{x}` is denoted by `||\mathbf{x}||_2^2`

The sum of squares of $\mathbf{x}$ is denoted by $||\mathbf{x}||_2^2$
