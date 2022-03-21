# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

| Input                  | Output              |
| -----                  | ------              |
|  Brad, Slagle, 2       | {firstName: Brad    |
|                        |  lastName: Slagle   | 
|                        |   age: 2  }         | 
|                        |                     |
|  Tiffany, Warren, 3    | {firstName: Tiffany |
|                        |  lastName: Warren   | 
|                        |  age: 3 }           |
|                        |                     |
| Kyle, Coberly, 4       | {firstName: Kyle    |
|                        |  lastName: Coberly  |
|                        |  age: 4 }           | 
|                        |                     | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This function creates an object called person that has information for firstName, lastName and age and stores the information in threturns the person object when called.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
**