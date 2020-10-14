----------

## Compound Conditional Syntax

A compound conditional is a conditional (an if statement) that has more than one boolean expression. You need to use the `and` or the `or` keywords to link these boolean expressions together. You can use the `not` keyword, but only in combination with `and` or `or`.

```python
if True and True:
    print("True")
```

[Code Visualizer](open_tutor code/selection/compound-conditional-syntax.py)
{try it}(python3 code/selection/compound-conditional-syntax.py 1)

|||challenge
## What happens if you:
* Have an if statement that says `if True or False:`?
* Have an if statement that says `if not True or False:`?
* Have an if statement that says `if True not False:`?
* Have an if statement that says `if 5 < 10 and 5 > 0:`?

|||

[Code Visualizer](open_tutor code/selection/compound-conditional-syntax.py)
{try it}(python3 code/selection/compound-conditional-syntax.py 2)

<details>
  <summary><strong>Compound Less Than or Greater Than</strong></summary>
  This is Python specific syntax, but it is possible to combine a compound conditional to look like something from a math class. Imagine you have a variable <code>a</code> with the value of <code>5</code>. You can rewrite <code>a < 10 and a > 0</code> to be <code>0 < a < 10</code>.
  </details>

{Check It!|assessment}(multiple-choice-2216399909)

