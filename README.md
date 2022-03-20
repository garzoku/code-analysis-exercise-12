# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (currentColor){
  if (currentColor === "green"){
    nextColor = "yellow"
  } else if (currentColor === "yellow"){
    nextColor = 'red'
  } else if (currentColor === "red"){
    nextColor = 'green'
  }

  return nextColor
}
```

| Input | Output |
| ----- | ------ |
| green | yellow | 
|yellow |  red   | 
| red   | green  | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>1). The function accepts a string value which should be entered as the name of a color.<br>
2). If the currentColor is equal to "green", the value of "yellow" is assigned to nextColor.<br>
3). Else if means that this block of code will only execute if the first if statement returned false. So, if currentColor was not green, and it is equal to yellow, nextColor is assigned the value of "red".<br>
4). Else if the currentColor was not green, nor yellow, but is equal to "red", then the value of "green" is assigned to nextColor.<br>
SUMMARY: This program controls the flow of logic for a traffic light. If the light is green, and about to turn red, it turns yellow first.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
